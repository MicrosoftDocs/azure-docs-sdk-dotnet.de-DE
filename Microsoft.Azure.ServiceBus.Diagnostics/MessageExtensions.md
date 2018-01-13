<Type Name="MessageExtensions" FullName="Microsoft.Azure.ServiceBus.Diagnostics.MessageExtensions">
  <TypeSignature Language="C#" Value="public static class MessageExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit MessageExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Diagnostics.MessageExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module MessageExtensions" />
  <TypeSignature Language="F#" Value="type MessageExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ExtractActivity">
      <MemberSignature Language="C#" Value="public static System.Diagnostics.Activity ExtractActivity (this Microsoft.Azure.ServiceBus.Message message, string activityName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Diagnostics.Activity ExtractActivity(class Microsoft.Azure.ServiceBus.Message message, string activityName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Diagnostics.MessageExtensions.ExtractActivity(Microsoft.Azure.ServiceBus.Message,System.String)" />
      <MemberSignature Language="F#" Value="static member ExtractActivity : Microsoft.Azure.ServiceBus.Message * string -&gt; System.Diagnostics.Activity" Usage="Microsoft.Azure.ServiceBus.Diagnostics.MessageExtensions.ExtractActivity (message, activityName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Diagnostics.Activity</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.Azure.ServiceBus.Message" RefType="this" />
        <Parameter Name="activityName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">To be added.</param>
        <param name="activityName">To be added.</param>
        <summary>
            Erstellt <see cref="T:System.Diagnostics.Activity" /> basierend auf dem Ablaufverfolgung Kontext gespeichert, der <see cref="T:Microsoft.Azure.ServiceBus.Message" /> <param name="activityName">Optional Aktivitätsname</param><returns>neu <see cref="T:System.Diagnostics.Activity" /> mit Ablaufverfolgung Kontext</returns></summary>
        <returns>To be added.</returns>
        <remarks>
            Zum Korrelieren von Telemetriedaten zwischen Producer und Consumer verwendet und dargestellt durch "Diagnose-Id" und 'Korrelation Context'-Eigenschaften im Kontext Tracing <see cref="P:Microsoft.Azure.ServiceBus.Message.UserProperties" />.
            
            .NET SDK fügt automatisch Kontext beim Senden der Nachricht mit der Service Bus (wenn es sich um eine Diagnose von Ablaufverfolgungssystem aktiviert ist).
            
            <para>"Diagnose-Id" eindeutig identifiziert Vorgang in die Warteschlange eingereihten Nachricht </para> <para> Korrelation kontextabhängigen ist durch Kommas getrennte Liste von Sting Schlüssel-Wert-Paaren Represeting optional Kontext für den Vorgang.</para>
            
            Wenn kein Kontext für die Ablaufverfolgung in der Nachricht vorhanden ist, gibt diese Methode <see cref="T:System.Diagnostics.Activity" /> ohne übergeordnetes Element.
            
            Zurückgegebene <see cref="T:System.Diagnostics.Activity" /> muss gestartet werden, bevor er verwendet werden kann (siehe folgendes Beispiel)
            </remarks>
        <example>
          <code>
            async Task ProcessAsync()
            {
               var message = await messageReceiver.ReceiveAsync();
               var activity = message.ExtractActivity();
               activity.Start();
               Logger.LogInformation($"Message received, Id = {Activity.Current.Id}")
               try 
               {
                  // process message
               }
               catch (Exception ex)
               {
                    Logger.LogError($"Exception {ex}, Id = {Activity.Current.Id}")
               }
               finally 
               {
                    activity.Stop();
                    // Activity is stopped, we no longer have it in Activity.Current, let's user activity now
                    Logger.LogInformation($"Message processed, Id = {activity.Id}, Duration = {activity.Duration}")
               }
            }
            </code>
            
            Beachten Sie, die mit jedem Protokoll versehen ist <see cref="P:System.Diagnostics.Activity.Current" />. ID, die in einer beliebigen verwendet werden, kann geschachtelte Methodenaufruf (Synchronisierung oder Async) - <see cref="P:System.Diagnostics.Activity.Current" /> ein ambient-Kontext, die mit asynchronen Methodenaufrufen übertragen wird.
            
            </example>
      </Docs>
    </Member>
  </Members>
</Type>