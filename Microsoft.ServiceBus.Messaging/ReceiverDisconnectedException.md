<Type Name="ReceiverDisconnectedException" FullName="Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException">
  <TypeSignature Language="C#" Value="public sealed class ReceiverDisconnectedException : Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit ReceiverDisconnectedException extends Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReceiverDisconnectedException&#xA;Inherits MessagingException" />
  <TypeSignature Language="F#" Value="type ReceiverDisconnectedException = class&#xA;    inherit MessagingException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.MessagingException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Diese Ausnahme wird ausgelöst, wenn zwei oder mehr <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> Objekte, die an die gleiche Event Hubs-Partition mit verschiedenen Epoche Werten verbinden.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReceiverDisconnectedException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException : string -&gt; Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException" Usage="new Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Die Ausnahmemeldung.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException" /> -Klasse mit der angegebenen Ausnahmemeldung.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReceiverDisconnectedException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException : string * Exception -&gt; Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException" Usage="new Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">Die Ausnahmemeldung.</param>
        <param name="innerException">Der Text der inneren Ausnahme.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException" /> -Klasse mit der angegebenen Ausnahmemeldung und der Text der inneren Ausnahme.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>