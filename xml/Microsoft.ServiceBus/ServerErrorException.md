<Type Name="ServerErrorException" FullName="Microsoft.ServiceBus.ServerErrorException">
  <TypeSignature Language="C#" Value="public class ServerErrorException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit ServerErrorException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.ServerErrorException" />
  <TypeSignature Language="VB.NET" Value="Public Class ServerErrorException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type ServerErrorException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="576f5-101">Eine Ausnahme, die von Azure Service Bus ausgelöst wird, tritt ein Fehler beim Verarbeiten einer Anforderung.</span><span class="sxs-lookup"><span data-stu-id="576f5-101">An exception that is thrown by the Azure Service Bus when an error occurs while processing a request.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServerErrorException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServerErrorException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="576f5-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.ServerErrorException" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="576f5-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.ServerErrorException" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServerErrorException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServerErrorException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.ServerErrorException : string -&gt; Microsoft.ServiceBus.ServerErrorException" Usage="new Microsoft.ServiceBus.ServerErrorException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="576f5-103">Die Fehlermeldung, die diese Ausnahme beschreibt.</span><span class="sxs-lookup"><span data-stu-id="576f5-103">The error message that describes this exception.</span></span></param>
        <summary><span data-ttu-id="576f5-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.ServerErrorException" />-Klasse mit der angegebenen Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="576f5-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.ServerErrorException" /> class with the specified error message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ServerErrorException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServerErrorException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.ServerErrorException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.ServiceBus.ServerErrorException" Usage="new Microsoft.ServiceBus.ServerErrorException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info"><span data-ttu-id="576f5-105">Enthält die serialisierten Objektdaten zur ausgelösten Ausnahme an.</span><span class="sxs-lookup"><span data-stu-id="576f5-105">Holds the serialized object data about the exception being thrown.</span></span></param>
        <param name="context"><span data-ttu-id="576f5-106">Die Kontextinformationen zur Quelle bzw. zum Ziel.</span><span class="sxs-lookup"><span data-stu-id="576f5-106">The contextual information about the source or destination.</span></span></param>
        <summary><span data-ttu-id="576f5-107">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.ServerErrorException" />-Klasse mit den angegebenen Serialisierungsinformationen und dem angegebenen Streamingkontext.</span><span class="sxs-lookup"><span data-stu-id="576f5-107">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.ServerErrorException" /> class with the specified serialization information and streaming context.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServerErrorException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServerErrorException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.ServerErrorException : string * Exception -&gt; Microsoft.ServiceBus.ServerErrorException" Usage="new Microsoft.ServiceBus.ServerErrorException (message, innerException)" />
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
        <param name="message"><span data-ttu-id="576f5-108">Die Fehlermeldung, die diese Ausnahme beschreibt.</span><span class="sxs-lookup"><span data-stu-id="576f5-108">The error message that describes this exception.</span></span></param>
        <param name="innerException"><span data-ttu-id="576f5-109">Die Ausnahme, die ausgelöst wird, die aktuelle Ausnahme verursacht hat.</span><span class="sxs-lookup"><span data-stu-id="576f5-109">The exception that caused the current exception to be thrown.</span></span></param>
        <summary><span data-ttu-id="576f5-110">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.ServerErrorException" />-Klasse mit der angegebenen Fehlermeldung und der angegebenen internen Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="576f5-110">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.ServerErrorException" /> class with the specified error message and inner exception.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>