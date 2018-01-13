<Type Name="ExceptionReceivedEventArgs" FullName="Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs">
  <TypeSignature Language="C#" Value="public sealed class ExceptionReceivedEventArgs : EventArgs" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ExceptionReceivedEventArgs extends System.EventArgs" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ExceptionReceivedEventArgs&#xA;Inherits EventArgs" />
  <TypeSignature Language="F#" Value="type ExceptionReceivedEventArgs = class&#xA;    inherit EventArgs" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.EventArgs</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Stellt Daten für das <see cref="P:Microsoft.Azure.ServiceBus.MessageHandlerOptions.ExceptionReceivedHandler" />-Ereignis bereit.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExceptionReceivedEventArgs (Exception exception, string action, string endpoint, string entityName, string clientId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Exception exception, string action, string endpoint, string entityName, string clientId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs.#ctor(System.Exception,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs : Exception * string * string * string * string -&gt; Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" Usage="new Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs (exception, action, endpoint, entityName, clientId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="exception">Die Ausnahme, der diese Ereignisdaten gehört.</param>
        <param name="action">Die Aktion, die dem Ereignis zugeordnet wird.</param>
        <param name="endpoint">Der Endpunkt verwendet, wenn diese Ausnahme aufgetreten ist.</param>
        <param name="entityName">Der Entity-Pfad verwendet, wenn diese Ausnahme aufgetreten ist.</param>
        <param name="clientId">Die Client-Id kann zum Zuordnen der <see cref="T:Microsoft.Azure.ServiceBus.QueueClient" />, <see cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />, <see cref="T:Microsoft.Azure.ServiceBus.Core.MessageSender" /> oder <see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" />, die die Ausnahme ist aufgetreten.</param>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exception">
      <MemberSignature Language="C#" Value="public Exception Exception { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception Exception" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs.Exception" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Exception As Exception" />
      <MemberSignature Language="F#" Value="member this.Exception : Exception" Usage="Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs.Exception" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft das übergeordnete Element-Klassenausnahme aus, zu dem diese Ereignisdaten gehört.</summary>
        <value>Die Ausnahme, der generiert durch die übergeordnete Klasse, zu der diese Ereignisdaten gehört.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExceptionReceivedContext">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.ServiceBus.ExceptionReceivedContext ExceptionReceivedContext { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.ServiceBus.ExceptionReceivedContext ExceptionReceivedContext" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs.ExceptionReceivedContext" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExceptionReceivedContext As ExceptionReceivedContext" />
      <MemberSignature Language="F#" Value="member this.ExceptionReceivedContext : Microsoft.Azure.ServiceBus.ExceptionReceivedContext" Usage="Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs.ExceptionReceivedContext" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.ExceptionReceivedContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Kontext der Ausnahme (Aktion Namespacenamen und Entität Pfad) ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>