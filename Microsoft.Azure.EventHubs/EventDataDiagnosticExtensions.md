<Type Name="EventDataDiagnosticExtensions" FullName="Microsoft.Azure.EventHubs.EventDataDiagnosticExtensions">
  <TypeSignature Language="C#" Value="public static class EventDataDiagnosticExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit EventDataDiagnosticExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.EventDataDiagnosticExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module EventDataDiagnosticExtensions" />
  <TypeSignature Language="F#" Value="type EventDataDiagnosticExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Diagnose Erweiterungsmethoden für <see cref="T:Microsoft.Azure.EventHubs.EventData" />.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ExtractActivity">
      <MemberSignature Language="C#" Value="public static System.Diagnostics.Activity ExtractActivity (this Microsoft.Azure.EventHubs.EventData eventData, string activityName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Diagnostics.Activity ExtractActivity(class Microsoft.Azure.EventHubs.EventData eventData, string activityName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventDataDiagnosticExtensions.ExtractActivity(Microsoft.Azure.EventHubs.EventData,System.String)" />
      <MemberSignature Language="F#" Value="static member ExtractActivity : Microsoft.Azure.EventHubs.EventData * string -&gt; System.Diagnostics.Activity" Usage="Microsoft.Azure.EventHubs.EventDataDiagnosticExtensions.ExtractActivity (eventData, activityName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Diagnostics.Activity</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventData" Type="Microsoft.Azure.EventHubs.EventData" RefType="this" />
        <Parameter Name="activityName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventData">To be added.</param>
        <param name="activityName">To be added.</param>
        <summary>
            Erstellt <see cref="T:System.Diagnostics.Activity" /> basierend auf dem Ablaufverfolgung Kontext gespeichert, der <see cref="T:Microsoft.Azure.EventHubs.EventData" /> <param name="eventData">das Ereignis empfangen von EventHub</param><param name="activityName">Optional Aktivitätsname</param><returns>neu <see cref="T:System.Diagnostics.Activity" /> ohne die Ablaufverfolgung Kontext</returns></summary>
        <returns>To be added.</returns>
        <remarks>
            Zum Korrelieren von Telemetriedaten zwischen Producer und Consumer verwendet und dargestellt durch "Diagnose-Id" und 'Korrelation Context'-Eigenschaften im Kontext Tracing <see cref="P:Microsoft.Azure.EventHubs.EventData.Properties" />.
            
            .NET SDK fügt automatisch Kontext beim Senden der Nachricht mit der Service Bus (wenn es sich um eine Diagnose von Ablaufverfolgungssystem aktiviert ist).
            
            <para>"Diagnose-Id" eindeutig Vorgang identifiziert, in die Warteschlange eingereihten das Ereignis </para> <para> Korrelation kontextabhängigen ist durch Kommas getrennte Liste von Schlüssel-Wert-Paaren Zeichenfolge optional Kontext für den Vorgang darstellt.</para>
            
            Wenn kein Kontext für die Ablaufverfolgung in das Ereignis vorhanden ist, gibt diese Methode <see cref="T:System.Diagnostics.Activity" /> ohne übergeordnetes Element.
            
            Zurückgegebene <see cref="T:System.Diagnostics.Activity" /> muss gestartet werden, bevor er verwendet werden kann (siehe folgendes Beispiel)
            </remarks>
        <example>
          <code>
            async Task ProcessAsync(EventData eventData)
            {
               var activity = eventData.ExtractActivity();
               activity.Start();
               Logger.LogInformation($"Event received, Id = {Activity.Current.Id}")
               try 
               {
                  // process event
               }
               catch (Exception ex)
               {
                    Logger.LogError($"Exception {ex}, Id = {Activity.Current.Id}")
               }
               finally 
               {
                    activity.Stop();
                    // Activity is stopped, we no longer have it in Activity.Current
                    Logger.LogInformation($"Event processed, Id = {activity.Id}, Duration = {activity.Duration}")
               }
            }
            </code>
            
            Beachten Sie, die mit jedem Protokoll versehen ist <see cref="P:System.Diagnostics.Activity.Current" />. ID, die in einer beliebigen verwendet werden, kann geschachtelte Methodenaufruf (Synchronisierung oder Async) - <see cref="P:System.Diagnostics.Activity.Current" /> ein ambient-Kontext, die mit asynchronen Methodenaufrufen übertragen wird.
            
            </example>
      </Docs>
    </Member>
  </Members>
</Type>