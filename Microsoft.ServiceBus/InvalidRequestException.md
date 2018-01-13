<Type Name="InvalidRequestException" FullName="Microsoft.ServiceBus.InvalidRequestException">
  <TypeSignature Language="C#" Value="public class InvalidRequestException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit InvalidRequestException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.InvalidRequestException" />
  <TypeSignature Language="VB.NET" Value="Public Class InvalidRequestException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type InvalidRequestException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="937f0-101">Die Ausnahme, die ausgelöst wird, wenn eine ungültige Anforderung auftritt.</span><span class="sxs-lookup"><span data-stu-id="937f0-101">The exception that is thrown when an invalid request occurs.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InvalidRequestException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.InvalidRequestException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="937f0-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.InvalidRequestException" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="937f0-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.InvalidRequestException" /> class.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InvalidRequestException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.InvalidRequestException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.InvalidRequestException : string -&gt; Microsoft.ServiceBus.InvalidRequestException" Usage="new Microsoft.ServiceBus.InvalidRequestException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="937f0-103">Die Meldung, in der der Fehler beschrieben wird.</span><span class="sxs-lookup"><span data-stu-id="937f0-103">The message that describes the error.</span></span></param>
        <summary><span data-ttu-id="937f0-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.InvalidRequestException" />-Klasse unter Verwendung der angegebenen Meldung.</span><span class="sxs-lookup"><span data-stu-id="937f0-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.InvalidRequestException" /> class using the specified message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected InvalidRequestException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.InvalidRequestException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.InvalidRequestException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.ServiceBus.InvalidRequestException" Usage="new Microsoft.ServiceBus.InvalidRequestException (info, context)" />
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
        <param name="info"><span data-ttu-id="937f0-105">Enthält die serialisierten Objektdaten zur ausgelösten Ausnahme an.</span><span class="sxs-lookup"><span data-stu-id="937f0-105">Holds the serialized object data about the exception being thrown.</span></span></param>
        <param name="context"><span data-ttu-id="937f0-106">Enthält Kontextinformationen zur Quelle bzw. zum Ziel.</span><span class="sxs-lookup"><span data-stu-id="937f0-106">Contains contextual information about the source or destination.</span></span></param>
        <summary><span data-ttu-id="937f0-107">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.InvalidRequestException" /> -Klasse mit den angegebenen Informationen und Kontext.</span><span class="sxs-lookup"><span data-stu-id="937f0-107">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.InvalidRequestException" /> class using the specified information and context.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InvalidRequestException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.InvalidRequestException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.InvalidRequestException : string * Exception -&gt; Microsoft.ServiceBus.InvalidRequestException" Usage="new Microsoft.ServiceBus.InvalidRequestException (message, innerException)" />
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
        <param name="message"><span data-ttu-id="937f0-108">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="937f0-108">The error message that explains the reason for the exception.</span></span></param>
        <param name="innerException"><span data-ttu-id="937f0-109">Die Ausnahme, die die Ursache der aktuellen Ausnahme oder Null ist, wenn keine innere Ausnahme angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="937f0-109">The exception that is the cause of the current exception, or null if no inner exception is specified.</span></span></param>
        <summary><span data-ttu-id="937f0-110">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.InvalidRequestException" />-Klasse unter Verwendung der angegebenen Nachricht und der internen Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="937f0-110">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.InvalidRequestException" /> class using the specified message and inner exception.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>