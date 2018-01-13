<Type Name="RetryPolicy" FullName="Microsoft.ServiceBus.RetryPolicy">
  <TypeSignature Language="C#" Value="public abstract class RetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit RetryPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.RetryPolicy" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class RetryPolicy" />
  <TypeSignature Language="F#" Value="type RetryPolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt eine Abstraktion für die Wiederholung Messagingvorgänge dar. Benutzer sollten diese Klasse nicht implementiert, und verwenden stattdessen eine der bereitgestellten Implementierungen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceBus.RetryPolicy Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.RetryPolicy Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RetryPolicy.Clone" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function Clone () As RetryPolicy" />
      <MemberSignature Language="F#" Value="abstract member Clone : unit -&gt; Microsoft.ServiceBus.RetryPolicy" Usage="retryPolicy.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RetryPolicy</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Erstellt eine neue Kopie des aktuellen <see cref="T:Microsoft.ServiceBus.RetryPolicy" /> und Klonen Sie es in eine neue Instanz.</summary>
        <returns>Eine neue Kopie des <see cref="T:Microsoft.ServiceBus.RetryPolicy" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.RetryPolicy Default { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.ServiceBus.RetryPolicy Default" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RetryPolicy.Default" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Default As RetryPolicy" />
      <MemberSignature Language="F#" Value="member this.Default : Microsoft.ServiceBus.RetryPolicy" Usage="Microsoft.ServiceBus.RetryPolicy.Default" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine Instanz von der <see cref="T:Microsoft.ServiceBus.RetryExponential" /> wiederholungsrichtlinie auf, die eine Standardinstallation von exponentiell erhöhen Wiederholungsintervalle für Messagingvorgänge bereitstellt. Jedes Mal, wenn diese Eigenschaft zugegriffen wird, wird eine neue Instanz erstellt.
            </summary>
        <value>Die Standardrichtlinie, die der Richtlinie zugeordnet sind.</value>
        <remarks>Diese Eigenschaft ist die folgende Instanz dadurch auf effektive Weise.
            <code>
               var policy = new RetryExponential(
                                    TimeSpan.Zero,
                                    TimeSpan.FromSeconds(30),
                                    10);                 
            </code>
            
            Es ist wichtig zu beachten, dass die wiederholungsrichtlinie immer berücksichtigt werden sollten die <seealso cref="P:Microsoft.ServiceBus.Messaging.ClientEntity.OperationTimeout" /> damit, wiederholen Sie den Vorgang beendet wird, wenn es sich bei der nächsten Wiederholungsintervall wird das die Vorgang Zeit überschreitet.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRetryableException">
      <MemberSignature Language="C#" Value="protected abstract bool IsRetryableException (Exception lastException);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool IsRetryableException(class System.Exception lastException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RetryPolicy.IsRetryableException(System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function IsRetryableException (lastException As Exception) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsRetryableException : Exception -&gt; bool" Usage="retryPolicy.IsRetryableException lastException" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lastException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="lastException">Die neuesten aufgetretene Ausnahme.</param>
        <summary>Bestimmt, ob es nach der angegebenen Ausnahme erfolgen zulässig ist.</summary>
        <returns>Wenn diese Methode "false" zurückgibt, tritt keine Wiederholung. Andernfalls die <see cref="M:Microsoft.ServiceBus.RetryPolicy.OnShouldRetry(System.TimeSpan,System.Int32,System.TimeSpan@)" /> Methode bestimmt, wann zu wiederholen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NoRetry">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.RetryPolicy NoRetry { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.ServiceBus.RetryPolicy NoRetry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RetryPolicy.NoRetry" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property NoRetry As RetryPolicy" />
      <MemberSignature Language="F#" Value="member this.NoRetry : Microsoft.ServiceBus.RetryPolicy" Usage="Microsoft.ServiceBus.RetryPolicy.NoRetry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine Instanz von der <see cref="P:Microsoft.ServiceBus.RetryPolicy.NoRetry" /> wiederholungsrichtlinie auf, wodurch effektiv Wiederholungen deaktiviert.
            Bei jedem wird Zugriff auf diese Eigenschaft eine neue Instanz zurückgegeben.
            </summary>
        <value>Eine wiederholungsrichtlinie, die keine Wiederholungen ausgeführt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnShouldRetry">
      <MemberSignature Language="C#" Value="protected abstract bool OnShouldRetry (TimeSpan remainingTime, int currentRetryCount, out TimeSpan retryInterval);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool OnShouldRetry(valuetype System.TimeSpan remainingTime, int32 currentRetryCount, [out] valuetype System.TimeSpan&amp; retryInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RetryPolicy.OnShouldRetry(System.TimeSpan,System.Int32,System.TimeSpan@)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnShouldRetry (remainingTime As TimeSpan, currentRetryCount As Integer, ByRef retryInterval As TimeSpan) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member OnShouldRetry : TimeSpan * int *  -&gt; bool" Usage="retryPolicy.OnShouldRetry (remainingTime, currentRetryCount, retryInterval)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="remainingTime" Type="System.TimeSpan" />
        <Parameter Name="currentRetryCount" Type="System.Int32" />
        <Parameter Name="retryInterval" Type="System.TimeSpan&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="remainingTime">Die verbleibende Zeit.</param>
        <param name="currentRetryCount">Die Gesamtanzahl der Wiederholungen.</param>
        <param name="retryInterval">Das Wiederholungsintervall.</param>
        <summary>Berechnet das Wiederholungsintervall für die wiederholungsrichtlinie.</summary>
        <returns>Wenn diese Methode gibt "true" zurück, der Wiederholungsvorgang auftritt, nachdem der Thread für eine bestimmte Zeitspanne gleich in den Leerlauf wechselt <paramref name="retryInterval" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetServerBusyInternal">
      <MemberSignature Language="C#" Value="protected virtual void ResetServerBusyInternal ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void ResetServerBusyInternal() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RetryPolicy.ResetServerBusyInternal" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub ResetServerBusyInternal ()" />
      <MemberSignature Language="F#" Value="abstract member ResetServerBusyInternal : unit -&gt; unit&#xA;override this.ResetServerBusyInternal : unit -&gt; unit" Usage="retryPolicy.ResetServerBusyInternal " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServerBusy">
      <MemberSignature Language="C#" Value="protected void SetServerBusy (string exceptionMessage);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void SetServerBusy(string exceptionMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RetryPolicy.SetServerBusy(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub SetServerBusy (exceptionMessage As String)" />
      <MemberSignature Language="F#" Value="member this.SetServerBusy : string -&gt; unit" Usage="retryPolicy.SetServerBusy exceptionMessage" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exceptionMessage" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="exceptionMessage"></param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServerBusyInternal">
      <MemberSignature Language="C#" Value="protected virtual void SetServerBusyInternal ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void SetServerBusyInternal() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RetryPolicy.SetServerBusyInternal" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub SetServerBusyInternal ()" />
      <MemberSignature Language="F#" Value="abstract member SetServerBusyInternal : unit -&gt; unit&#xA;override this.SetServerBusyInternal : unit -&gt; unit" Usage="retryPolicy.SetServerBusyInternal " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>