<Type Name="SessionLockLostException" FullName="Microsoft.Azure.NotificationHubs.Messaging.SessionLockLostException">
  <TypeSignature Language="C#" Value="public sealed class SessionLockLostException : Microsoft.Azure.NotificationHubs.Messaging.MessagingException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit SessionLockLostException extends Microsoft.Azure.NotificationHubs.Messaging.MessagingException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Messaging.SessionLockLostException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SessionLockLostException&#xA;Inherits MessagingException" />
  <TypeSignature Language="F#" Value="type SessionLockLostException = class&#xA;    inherit MessagingException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.Messaging.MessagingException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="613b1-101">Die Ausnahme, die ausgelöst wird, um die Sitzung zu signalisieren Sperren verloren Fehler. Verschieben bei partitionierten messagingentitäten manchmal Partitionen, um Lastenausgleich für Service Bus-Knoten zu erreichen; Wenn ein Knoten neu gestartet wurde oder der neue Knoten beispielsweise um die Last hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="613b1-101">The exception that is thrown to signal session lock lost errors.In the case of partitioned messaging entities, partitions sometimes move to achieve load balancing across Service Bus nodes; for example, when a node restarts or new nodes are added to share the load.</span></span> <span data-ttu-id="613b1-102">In diesem Fall Sitzungssperren können verloren gehen, aber Nachrichten werden nie unterbrochen.</span><span class="sxs-lookup"><span data-stu-id="613b1-102">When that happens, session locks can be lost, but messages are never lost.</span></span> <span data-ttu-id="613b1-103">Wenn eine Partition wechselt, nachdem die Sitzung gesperrt ist, und klicken Sie dann die Verarbeitung Aufruf Bestätigungs-/Abschließen der Nachricht ein Fehler auftritt, da die Sperre verloren geht.</span><span class="sxs-lookup"><span data-stu-id="613b1-103">If a partition moves after the session is locked, then the acknowledge/complete message processing call fails, because the lock is lost.</span></span> <span data-ttu-id="613b1-104">Allerdings bleibt die Nachricht, und Sie können versuchen, diese erneut gelesen.</span><span class="sxs-lookup"><span data-stu-id="613b1-104">However, the message remains and you can try to read it again.</span></span> <span data-ttu-id="613b1-105">Erhalten Sie daher möglicherweise ein <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.SessionLockLostException" /> Ausnahme, obwohl die Nachricht selbst nicht verloren geht.</span><span class="sxs-lookup"><span data-stu-id="613b1-105">Thus, you may receive a <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.SessionLockLostException" /> exception even though the message itself is not lost.</span></span> <span data-ttu-id="613b1-106">In diesem Fall können Sie die Nachrichtenverarbeitung Vorgang wiederholen.</span><span class="sxs-lookup"><span data-stu-id="613b1-106">In this case, you can retry the message processing operation.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SessionLockLostException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.SessionLockLostException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.SessionLockLostException : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.SessionLockLostException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.SessionLockLostException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="613b1-107">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="613b1-107">The error message that explains the reason for the exception.</span></span></param>
        <summary><span data-ttu-id="613b1-108">Initialisiert eine neue Instanz der Klasse SessionLockLostException mit einer angegebenen Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="613b1-108">Initializes a new instance of the SessionLockLostException class with a specified error message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SessionLockLostException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.SessionLockLostException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.SessionLockLostException : string * Exception -&gt; Microsoft.Azure.NotificationHubs.Messaging.SessionLockLostException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.SessionLockLostException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="613b1-109">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="613b1-109">The error message that explains the reason for the exception.</span></span></param>
        <param name="innerException"><span data-ttu-id="613b1-110">Die Ausnahme, die die Ursache der aktuellen Ausnahme ist.</span><span class="sxs-lookup"><span data-stu-id="613b1-110">The exception that is the cause of the current exception.</span></span></param>
        <summary><span data-ttu-id="613b1-111">Initialisiert eine neue Instanz der Klasse SessionLockLostException mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.</span><span class="sxs-lookup"><span data-stu-id="613b1-111">Initializes a new instance of the SessionLockLostException class  with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>