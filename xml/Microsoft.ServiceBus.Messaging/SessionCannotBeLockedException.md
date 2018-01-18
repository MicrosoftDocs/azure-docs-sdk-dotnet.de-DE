<Type Name="SessionCannotBeLockedException" FullName="Microsoft.ServiceBus.Messaging.SessionCannotBeLockedException">
  <TypeSignature Language="C#" Value="public sealed class SessionCannotBeLockedException : Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit SessionCannotBeLockedException extends Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.SessionCannotBeLockedException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SessionCannotBeLockedException&#xA;Inherits MessagingException" />
  <TypeSignature Language="F#" Value="type SessionCannotBeLockedException = class&#xA;    inherit MessagingException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.MessagingException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="4ce37-101">Stellt die Ausnahme, die ausgelöst wird, wenn eine Nachricht die Sperre auf eine Sitzung abrufen kann.</span><span class="sxs-lookup"><span data-stu-id="4ce37-101">Represents the exception that is thrown when a message cannot acquire lock on a session.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SessionCannotBeLockedException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SessionCannotBeLockedException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.SessionCannotBeLockedException : string -&gt; Microsoft.ServiceBus.Messaging.SessionCannotBeLockedException" Usage="new Microsoft.ServiceBus.Messaging.SessionCannotBeLockedException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="4ce37-102">Die Fehlermeldung, die die Ursache der Ausnahme beschreibt.</span><span class="sxs-lookup"><span data-stu-id="4ce37-102">The error message that describes the cause of the exception.</span></span></param>
        <summary><span data-ttu-id="4ce37-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.SessionCannotBeLockedException" />-Klasse mit einer angegebenen Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="4ce37-103">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.SessionCannotBeLockedException" /> class with a specified error message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SessionCannotBeLockedException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SessionCannotBeLockedException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.SessionCannotBeLockedException : string * Exception -&gt; Microsoft.ServiceBus.Messaging.SessionCannotBeLockedException" Usage="new Microsoft.ServiceBus.Messaging.SessionCannotBeLockedException (message, innerException)" />
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
        <param name="message"><span data-ttu-id="4ce37-104">Die Fehlermeldung, die die Ursache der Ausnahme beschreibt.</span><span class="sxs-lookup"><span data-stu-id="4ce37-104">The error message that describes the cause of the exception.</span></span></param>
        <param name="innerException"><span data-ttu-id="4ce37-105">Die innere Ausnahme, die die Ursache der aktuellen Ausnahme ist.</span><span class="sxs-lookup"><span data-stu-id="4ce37-105">The inner exception that is the cause of the current exception.</span></span></param>
        <summary><span data-ttu-id="4ce37-106">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.SessionCannotBeLockedException" /> Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="4ce37-106">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.SessionCannotBeLockedException" /> class with a specified error message and a reference to the inner.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>