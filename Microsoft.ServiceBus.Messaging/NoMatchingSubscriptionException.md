<Type Name="NoMatchingSubscriptionException" FullName="Microsoft.ServiceBus.Messaging.NoMatchingSubscriptionException">
  <TypeSignature Language="C#" Value="public sealed class NoMatchingSubscriptionException : Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit NoMatchingSubscriptionException extends Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.NoMatchingSubscriptionException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NoMatchingSubscriptionException&#xA;Inherits MessagingException" />
  <TypeSignature Language="F#" Value="type NoMatchingSubscriptionException = class&#xA;    inherit MessagingException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.MessagingException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="a8f02-101">Die Ausnahme, die ausgelöst wird, wenn Abonnements zugeordnet keine Übereinstimmung geführt hat.</span><span class="sxs-lookup"><span data-stu-id="a8f02-101">The exception that is thrown when subscription matching resulted no match.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NoMatchingSubscriptionException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NoMatchingSubscriptionException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.NoMatchingSubscriptionException : string -&gt; Microsoft.ServiceBus.Messaging.NoMatchingSubscriptionException" Usage="new Microsoft.ServiceBus.Messaging.NoMatchingSubscriptionException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="a8f02-102">Die Fehlermeldung zur Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="a8f02-102">The error message about the exception.</span></span></param>
        <summary><span data-ttu-id="a8f02-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.NoMatchingSubscriptionException" />-Klasse mit einer Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="a8f02-103">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.NoMatchingSubscriptionException" /> class with error message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NoMatchingSubscriptionException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NoMatchingSubscriptionException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.NoMatchingSubscriptionException : string * Exception -&gt; Microsoft.ServiceBus.Messaging.NoMatchingSubscriptionException" Usage="new Microsoft.ServiceBus.Messaging.NoMatchingSubscriptionException (message, innerException)" />
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
        <param name="message"><span data-ttu-id="a8f02-104">Die Fehlermeldung zur Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="a8f02-104">The error message about the exception.</span></span></param>
        <param name="innerException"><span data-ttu-id="a8f02-105">Die innere Ausnahme, die die Ursache der aktuellen Ausnahme ist.</span><span class="sxs-lookup"><span data-stu-id="a8f02-105">The inner exception that is the cause of the current exception.</span></span></param>
        <summary><span data-ttu-id="a8f02-106">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.NoMatchingSubscriptionException" />-Klasse mit einer Fehlermeldung und inneren </span><span class="sxs-lookup"><span data-stu-id="a8f02-106">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.NoMatchingSubscriptionException" /> class with error message and inner exception.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NoMatchingSubscriptionException.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="noMatchingSubscriptionException.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="a8f02-107">Gibt die Zeichenfolgendarstellung der <see cref="T:Microsoft.ServiceBus.Messaging.NoMatchingSubscriptionException" /> zurück.</span><span class="sxs-lookup"><span data-stu-id="a8f02-107">Returns the string representation of the <see cref="T:Microsoft.ServiceBus.Messaging.NoMatchingSubscriptionException" />.</span></span></summary>
        <returns><span data-ttu-id="a8f02-108">Die Zeichenfolgendarstellung des <see cref="T:Microsoft.ServiceBus.Messaging.NoMatchingSubscriptionException" />.</span><span class="sxs-lookup"><span data-stu-id="a8f02-108">The string representation of the <see cref="T:Microsoft.ServiceBus.Messaging.NoMatchingSubscriptionException" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>