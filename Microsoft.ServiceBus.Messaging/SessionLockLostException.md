<Type Name="SessionLockLostException" FullName="Microsoft.ServiceBus.Messaging.SessionLockLostException">
  <TypeSignature Language="C#" Value="public sealed class SessionLockLostException : Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit SessionLockLostException extends Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.SessionLockLostException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SessionLockLostException&#xA;Inherits MessagingException" />
  <TypeSignature Language="F#" Value="type SessionLockLostException = class&#xA;    inherit MessagingException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.MessagingException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Die Ausnahme, die ausgelöst wird, um die Sitzung zu signalisieren Sperren verloren Fehler. Verschieben bei partitionierten messagingentitäten manchmal Partitionen, um Lastenausgleich für Service Bus-Knoten zu erreichen; Wenn ein Knoten neu gestartet wurde oder der neue Knoten beispielsweise um die Last hinzugefügt. In diesem Fall Sitzungssperren können verloren gehen, aber Nachrichten werden nie unterbrochen. Wenn eine Partition wechselt, nachdem die Sitzung gesperrt ist, und klicken Sie dann die Verarbeitung Aufruf Bestätigungs-/Abschließen der Nachricht ein Fehler auftritt, da die Sperre verloren geht. Allerdings bleibt die Nachricht, und Sie können versuchen, diese erneut gelesen. Erhalten Sie daher möglicherweise ein <see cref="T:Microsoft.ServiceBus.Messaging.SessionLockLostException" /> Ausnahme, obwohl die Nachricht selbst nicht verloren geht. In diesem Fall können Sie die Nachrichtenverarbeitung Vorgang wiederholen.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SessionLockLostException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SessionLockLostException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.SessionLockLostException : string -&gt; Microsoft.ServiceBus.Messaging.SessionLockLostException" Usage="new Microsoft.ServiceBus.Messaging.SessionLockLostException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</param>
        <summary>Initialisiert eine neue Instanz der Klasse SessionLockLostException mit einer angegebenen Fehlermeldung.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SessionLockLostException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SessionLockLostException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.SessionLockLostException : string * Exception -&gt; Microsoft.ServiceBus.Messaging.SessionLockLostException" Usage="new Microsoft.ServiceBus.Messaging.SessionLockLostException (message, innerException)" />
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
        <param name="message">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</param>
        <param name="innerException">Die Ausnahme, die die Ursache der aktuellen Ausnahme ist.</param>
        <summary>Initialisiert eine neue Instanz der Klasse SessionLockLostException mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>