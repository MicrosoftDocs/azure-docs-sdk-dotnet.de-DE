<Type Name="MessageNotFoundException" FullName="Microsoft.ServiceBus.Messaging.MessageNotFoundException">
  <TypeSignature Language="C#" Value="public sealed class MessageNotFoundException : Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit MessageNotFoundException extends Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessageNotFoundException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MessageNotFoundException&#xA;Inherits MessagingException" />
  <TypeSignature Language="F#" Value="type MessageNotFoundException = class&#xA;    inherit MessagingException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.MessagingException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="1e6d4-101">Die Ausnahme, die ausgelöst wird, um die Nachricht zu signalisieren nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="1e6d4-101">The exception that is thrown to signal message not found errors.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageNotFoundException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageNotFoundException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.MessageNotFoundException : string -&gt; Microsoft.ServiceBus.Messaging.MessageNotFoundException" Usage="new Microsoft.ServiceBus.Messaging.MessageNotFoundException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="1e6d4-102">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="1e6d4-102">The error message that explains the reason for the exception.</span></span></param>
        <summary><span data-ttu-id="1e6d4-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.MessageNotFoundException" />-Klasse mit einer angegebenen Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="1e6d4-103">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.MessageNotFoundException" /> class with a specified error message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageNotFoundException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageNotFoundException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.MessageNotFoundException : string * Exception -&gt; Microsoft.ServiceBus.Messaging.MessageNotFoundException" Usage="new Microsoft.ServiceBus.Messaging.MessageNotFoundException (message, innerException)" />
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
        <param name="message"><span data-ttu-id="1e6d4-104">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="1e6d4-104">The error message that explains the reason for the exception.</span></span></param>
        <param name="innerException"><span data-ttu-id="1e6d4-105">Die Ausnahme, die die Ursache der aktuellen Ausnahme ist.</span><span class="sxs-lookup"><span data-stu-id="1e6d4-105">The exception that is the cause of the current exception.</span></span></param>
        <summary><span data-ttu-id="1e6d4-106">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.MessageNotFoundException" />-Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.</span><span class="sxs-lookup"><span data-stu-id="1e6d4-106">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.MessageNotFoundException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>