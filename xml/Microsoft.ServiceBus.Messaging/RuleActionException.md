<Type Name="RuleActionException" FullName="Microsoft.ServiceBus.Messaging.RuleActionException">
  <TypeSignature Language="C#" Value="public sealed class RuleActionException : Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit RuleActionException extends Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.RuleActionException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RuleActionException&#xA;Inherits MessagingException" />
  <TypeSignature Language="F#" Value="type RuleActionException = class&#xA;    inherit MessagingException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.MessagingException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="b0300-101">Die Ausnahme, die für eine anzeigenden Filter Aktionsfehler ausgelöst, und wird ausgelöst, wenn ein Filter fehl beziehen.</span><span class="sxs-lookup"><span data-stu-id="b0300-101">The exception that is thrown for signaling filter action errors and is thrown when a filter related operation fails.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleActionException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.RuleActionException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.RuleActionException : string -&gt; Microsoft.ServiceBus.Messaging.RuleActionException" Usage="new Microsoft.ServiceBus.Messaging.RuleActionException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="b0300-102">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="b0300-102">The error message that explains the reason for the exception.</span></span></param>
        <summary><span data-ttu-id="b0300-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.RuleActionException" />-Klasse mit der angegebenen Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="b0300-103">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.RuleActionException" /> class with the specified error message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleActionException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.RuleActionException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.RuleActionException : string * Exception -&gt; Microsoft.ServiceBus.Messaging.RuleActionException" Usage="new Microsoft.ServiceBus.Messaging.RuleActionException (message, innerException)" />
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
        <param name="message"><span data-ttu-id="b0300-104">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="b0300-104">The error message that explains the reason for the exception.</span></span></param>
        <param name="innerException"><span data-ttu-id="b0300-105">Die Ausnahme, die die Ursache der aktuellen Ausnahme ist.</span><span class="sxs-lookup"><span data-stu-id="b0300-105">The exception that is the cause of the current exception.</span></span></param>
        <summary><span data-ttu-id="b0300-106">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.RuleActionException" /> Klasse mit der angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.</span><span class="sxs-lookup"><span data-stu-id="b0300-106">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.RuleActionException" /> class with the specified error message and a reference to the inner exception that is the cause of this exception.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>