<Type Name="FabricElementAlreadyExistsException" FullName="System.Fabric.FabricElementAlreadyExistsException">
  <TypeSignature Language="C#" Value="public class FabricElementAlreadyExistsException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit FabricElementAlreadyExistsException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricElementAlreadyExistsException" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricElementAlreadyExistsException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type FabricElementAlreadyExistsException = class&#xA;    inherit FabricException" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.FabricException</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.MaintainabilityRules", "SA1402:FileMayOnlyContainASingleClass", Justification="Exception")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para><span data-ttu-id="62f69-101">Die Ausnahme, die fehlgeschlagen, da das Vorhandensein einer in Konflikt stehenden Entität angibt.</span><span class="sxs-lookup"><span data-stu-id="62f69-101">The exception that indicates failure due to the existence of a conflicting entity.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricElementAlreadyExistsException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricElementAlreadyExistsException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="62f69-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricElementAlreadyExistsException" /> Klasse mit dem Fehlercode <see cref="F:System.Fabric.FabricErrorCode.Unknown" />.</span><span class="sxs-lookup"><span data-stu-id="62f69-102">Initializes a new instance of <see cref="T:System.Fabric.FabricElementAlreadyExistsException" /> class with error code <see cref="F:System.Fabric.FabricErrorCode.Unknown" />.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricElementAlreadyExistsException (System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricElementAlreadyExistsException.#ctor(System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricElementAlreadyExistsException : System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricElementAlreadyExistsException" Usage="new System.Fabric.FabricElementAlreadyExistsException errorCode" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="errorCode">
          <para><span data-ttu-id="62f69-103">Der Fehlercode, der der Ausnahme zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="62f69-103">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="62f69-104">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricElementAlreadyExistsException" /> -Klasse mit einem angegebenen Fehlercode.</span><span class="sxs-lookup"><span data-stu-id="62f69-104">Initializes a new instance of <see cref="T:System.Fabric.FabricElementAlreadyExistsException" /> class with a specified error code.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricElementAlreadyExistsException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricElementAlreadyExistsException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricElementAlreadyExistsException : string -&gt; System.Fabric.FabricElementAlreadyExistsException" Usage="new System.Fabric.FabricElementAlreadyExistsException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">
          <para><span data-ttu-id="62f69-105">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="62f69-105">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="62f69-106">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricElementAlreadyExistsException" /> Klasse mit dem Fehlercode <see cref="F:System.Fabric.FabricErrorCode.Unknown" /> und einer angegebenen Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="62f69-106">Initializes a new instance of <see cref="T:System.Fabric.FabricElementAlreadyExistsException" /> class with error code <see cref="F:System.Fabric.FabricErrorCode.Unknown" /> and a specified error message.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricElementAlreadyExistsException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricElementAlreadyExistsException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricElementAlreadyExistsException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; System.Fabric.FabricElementAlreadyExistsException" Usage="new System.Fabric.FabricElementAlreadyExistsException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">
          <para><span data-ttu-id="62f69-107">Die <see cref="T:System.Runtime.Serialization.SerializationInfo" /> -Objekt mit serialisierten Objektdaten für die ausgelöste Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="62f69-107">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> object that contains serialized object data of the exception being thrown.</span></span></para>
        </param>
        <param name="context">
          <para><span data-ttu-id="62f69-108">Das <see cref="T:System.Runtime.Serialization.StreamingContext" />-Objekt, das die Kontextinformationen für die Quelle oder das Ziel enthält.</span><span class="sxs-lookup"><span data-stu-id="62f69-108">The <see cref="T:System.Runtime.Serialization.StreamingContext" /> object that contains contextual information about the source or destination.</span></span> <span data-ttu-id="62f69-109">Der Kontextparameter ist für die zukünftige Verwendung reserviert und kann null sein.</span><span class="sxs-lookup"><span data-stu-id="62f69-109">The context parameter is reserved for future use and can be null.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="62f69-110">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricElementAlreadyExistsException" /> -Klasse aus den Daten des serialisierten Objekts an, mit einem angegebenen Kontext.</span><span class="sxs-lookup"><span data-stu-id="62f69-110">Initializes a new instance of <see cref="T:System.Fabric.FabricElementAlreadyExistsException" /> class from the serialized object data, with a specified context.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricElementAlreadyExistsException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricElementAlreadyExistsException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricElementAlreadyExistsException : string * Exception -&gt; System.Fabric.FabricElementAlreadyExistsException" Usage="new System.Fabric.FabricElementAlreadyExistsException (message, inner)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">
          <para><span data-ttu-id="62f69-111">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="62f69-111">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="inner">
          <para><span data-ttu-id="62f69-112">Die Ausnahme, die die Ursache der aktuellen Ausnahme oder Null ist, wenn keine innere Ausnahme angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="62f69-112">The exception that is the cause of the current exception or null if no inner exception is specified.</span></span> <span data-ttu-id="62f69-113">Die <see cref="T:System.Exception" /> Klasse erhalten Sie weitere Informationen zur inneren Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="62f69-113">The <see cref="T:System.Exception" /> class provides more details about the inner exception.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="62f69-114">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricElementAlreadyExistsException" /> Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.</span><span class="sxs-lookup"><span data-stu-id="62f69-114">Initializes a new instance of <see cref="T:System.Fabric.FabricElementAlreadyExistsException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricElementAlreadyExistsException (string message, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricElementAlreadyExistsException.#ctor(System.String,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricElementAlreadyExistsException : string * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricElementAlreadyExistsException" Usage="new System.Fabric.FabricElementAlreadyExistsException (message, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="message">
          <para><span data-ttu-id="62f69-115">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="62f69-115">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="errorCode">
          <para><span data-ttu-id="62f69-116">Der Fehlercode, der der Ausnahme zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="62f69-116">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="62f69-117">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricElementAlreadyExistsException" /> -Klasse mit der angegebenen Fehlermeldung und der Fehlercode.</span><span class="sxs-lookup"><span data-stu-id="62f69-117">Initializes a new instance of <see cref="T:System.Fabric.FabricElementAlreadyExistsException" /> class with specified error message and error code.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricElementAlreadyExistsException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricElementAlreadyExistsException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricElementAlreadyExistsException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricElementAlreadyExistsException" Usage="new System.Fabric.FabricElementAlreadyExistsException (info, context, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="info">
          <para><span data-ttu-id="62f69-118">Die <see cref="T:System.Runtime.Serialization.SerializationInfo" /> -Objekt mit serialisierten Objektdaten für die ausgelöste Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="62f69-118">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> object that contains serialized object data of the exception being thrown.</span></span></para>
        </param>
        <param name="context">
          <para><span data-ttu-id="62f69-119">Das <see cref="T:System.Runtime.Serialization.StreamingContext" />-Objekt, das die Kontextinformationen für die Quelle oder das Ziel enthält.</span><span class="sxs-lookup"><span data-stu-id="62f69-119">The <see cref="T:System.Runtime.Serialization.StreamingContext" /> object that contains contextual information about the source or destination.</span></span> <span data-ttu-id="62f69-120">Der Kontextparameter ist für die zukünftige Verwendung reserviert und kann null sein.</span><span class="sxs-lookup"><span data-stu-id="62f69-120">The context parameter is reserved for future use and can be null.</span></span></para>
        </param>
        <param name="errorCode">
          <para><span data-ttu-id="62f69-121">Der Fehlercode, der der Ausnahme zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="62f69-121">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="62f69-122">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricElementAlreadyExistsException" /> -Klasse mit einem angegebenen Fehlercode mit angegebenen Kontext und Fehlercode.</span><span class="sxs-lookup"><span data-stu-id="62f69-122">Initializes a new instance of <see cref="T:System.Fabric.FabricElementAlreadyExistsException" /> class with a specified error code, with specified context and error code.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricElementAlreadyExistsException (string message, Exception inner, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricElementAlreadyExistsException.#ctor(System.String,System.Exception,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricElementAlreadyExistsException : string * Exception * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricElementAlreadyExistsException" Usage="new System.Fabric.FabricElementAlreadyExistsException (message, inner, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="message">
          <para><span data-ttu-id="62f69-123">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="62f69-123">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="inner">
          <para><span data-ttu-id="62f69-124">Die Ausnahme, die die Ursache der aktuellen Ausnahme oder Null ist, wenn keine innere Ausnahme angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="62f69-124">The exception that is the cause of the current exception or null if no inner exception is specified.</span></span> <span data-ttu-id="62f69-125">Die <see cref="T:System.Exception" /> Klasse erhalten Sie weitere Informationen zur inneren Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="62f69-125">The <see cref="T:System.Exception" /> class provides more details about the inner exception.</span></span></para>
        </param>
        <param name="errorCode">
          <para><span data-ttu-id="62f69-126">Der Fehlercode, der der Ausnahme zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="62f69-126">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="62f69-127">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricElementAlreadyExistsException" /> Nachricht Klasse mit einer angegebenen Fehlermeldung, der einen Verweis auf die innere Ausnahme, die die Ursache dieser Ausnahme und eine angegebene Fehlercode ist.</span><span class="sxs-lookup"><span data-stu-id="62f69-127">Initializes a new instance of <see cref="T:System.Fabric.FabricElementAlreadyExistsException" /> class with a specified error message, a reference to the inner exception that is the cause of this exception, and a specified error code.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>