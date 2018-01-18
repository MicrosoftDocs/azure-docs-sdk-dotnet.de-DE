<Type Name="StorageException" FullName="Microsoft.WindowsAzure.Storage.StorageException">
  <TypeSignature Language="C#" Value="public class StorageException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit StorageException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.StorageException" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type StorageException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="51ce0-101">Stellt eine von der Azure Storage-Dienst ausgelöste Ausnahme dar.</span><span class="sxs-lookup"><span data-stu-id="51ce0-101">Represents an exception thrown by the Azure Storage service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="51ce0-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.StorageException" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="51ce0-102">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.StorageException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.StorageException : string -&gt; Microsoft.WindowsAzure.Storage.StorageException" Usage="new Microsoft.WindowsAzure.Storage.StorageException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="51ce0-103">Die Meldung, in der der Fehler beschrieben wird.</span><span class="sxs-lookup"><span data-stu-id="51ce0-103">The message that describes the error.</span></span></param>
        <summary>
            <span data-ttu-id="51ce0-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.StorageException" />-Klasse mit der angegebenen Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="51ce0-104">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.StorageException" /> class using the specified error message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected StorageException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.StorageException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.WindowsAzure.Storage.StorageException" Usage="new Microsoft.WindowsAzure.Storage.StorageException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info"><span data-ttu-id="51ce0-105">Die <see cref="T:System.Runtime.Serialization.SerializationInfo" /> Objekt mit serialisierten Objektdaten für die ausgelöste Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="51ce0-105">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> object that holds serialized object data for the exception being thrown.</span></span></param>
        <param name="context"><span data-ttu-id="51ce0-106">Der <see cref="T:System.Runtime.Serialization.StreamingContext" />, der die Kontextinformationen über die Quelle oder das Ziel enthält.</span><span class="sxs-lookup"><span data-stu-id="51ce0-106">The <see cref="T:System.Runtime.Serialization.StreamingContext" /> that contains contextual information about the source or destination.</span></span></param>
        <summary>
            <span data-ttu-id="51ce0-107">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.StorageException" />-Klasse mit serialisierten Daten.</span><span class="sxs-lookup"><span data-stu-id="51ce0-107">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.StorageException" /> class with serialized data.</span></span>
            </summary>
        <remarks><span data-ttu-id="51ce0-108">Dieser Konstruktor wird während der Deserialisierung aufgerufen, um das über einen Stream übertragene Ausnahmeobjekt wiederherzustellen.</span><span class="sxs-lookup"><span data-stu-id="51ce0-108">This constructor is called during de-serialization to reconstitute the exception object transmitted over a stream.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.StorageException : string * Exception -&gt; Microsoft.WindowsAzure.Storage.StorageException" Usage="new Microsoft.WindowsAzure.Storage.StorageException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="51ce0-109">Die Fehlermeldung "Ausnahme".</span><span class="sxs-lookup"><span data-stu-id="51ce0-109">The exception error message.</span></span></param>
        <param name="innerException"><span data-ttu-id="51ce0-110">Die innere Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="51ce0-110">The inner exception.</span></span></param>
        <summary>
            <span data-ttu-id="51ce0-111">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.StorageException" /> Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die diese Ausnahme generiert.</span><span class="sxs-lookup"><span data-stu-id="51ce0-111">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.StorageException" /> class with a specified error message and a reference to the inner exception that generated this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageException (Microsoft.WindowsAzure.Storage.RequestResult res, string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.RequestResult res, string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageException.#ctor(Microsoft.WindowsAzure.Storage.RequestResult,System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (res As RequestResult, message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.StorageException : Microsoft.WindowsAzure.Storage.RequestResult * string * Exception -&gt; Microsoft.WindowsAzure.Storage.StorageException" Usage="new Microsoft.WindowsAzure.Storage.StorageException (res, message, inner)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="res" Type="Microsoft.WindowsAzure.Storage.RequestResult" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="res"><span data-ttu-id="51ce0-112">Das Ergebnis der Anforderung.</span><span class="sxs-lookup"><span data-stu-id="51ce0-112">The request result.</span></span></param>
        <param name="message"><span data-ttu-id="51ce0-113">Die Ausnahmemeldung.</span><span class="sxs-lookup"><span data-stu-id="51ce0-113">The exception message.</span></span></param>
        <param name="inner"><span data-ttu-id="51ce0-114">Die innere Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="51ce0-114">The inner exception.</span></span></param>
        <summary>
            <span data-ttu-id="51ce0-115">Initialisiert mit den angegebenen Parametern eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.StorageException" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="51ce0-115">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.StorageException" /> class by using the specified parameters.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetObjectData">
      <MemberSignature Language="C#" Value="public override void GetObjectData (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void GetObjectData(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageException.GetObjectData(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub GetObjectData (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="override this.GetObjectData : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; unit" Usage="storageException.GetObjectData (info, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info"><span data-ttu-id="51ce0-116">Das mit Daten aufzufüllende <see cref="T:System.Runtime.Serialization.SerializationInfo" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="51ce0-116">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> object to populate with data.</span></span></param>
        <param name="context"><span data-ttu-id="51ce0-117">Der Zielkontext für diese Serialisierung.</span><span class="sxs-lookup"><span data-stu-id="51ce0-117">The destination context for this serialization.</span></span></param>
        <summary>
            <span data-ttu-id="51ce0-118">Füllt ein <see cref="T:System.Runtime.Serialization.SerializationInfo" />-Objekt mit den Daten, die zum Serialisieren des Zielobjekts erforderlich sind.</span><span class="sxs-lookup"><span data-stu-id="51ce0-118">Populates a <see cref="T:System.Runtime.Serialization.SerializationInfo" /> object with the data needed to serialize the target object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestInformation">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RequestResult RequestInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.RequestResult RequestInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.StorageException.RequestInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestInformation As RequestResult" />
      <MemberSignature Language="F#" Value="member this.RequestInformation : Microsoft.WindowsAzure.Storage.RequestResult" Usage="Microsoft.WindowsAzure.Storage.StorageException.RequestInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RequestResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="51ce0-119">Ruft die <see cref="T:Microsoft.WindowsAzure.Storage.RequestResult" /> für dieses Objekt <see cref="T:Microsoft.WindowsAzure.Storage.StorageException" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="51ce0-119">Gets the <see cref="T:Microsoft.WindowsAzure.Storage.RequestResult" /> object for this <see cref="T:Microsoft.WindowsAzure.Storage.StorageException" /> object.</span></span>
            </summary>
        <value><span data-ttu-id="51ce0-120">Die <see cref="T:Microsoft.WindowsAzure.Storage.RequestResult" /> für dieses Objekt <see cref="T:Microsoft.WindowsAzure.Storage.StorageException" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="51ce0-120">The <see cref="T:Microsoft.WindowsAzure.Storage.RequestResult" /> object for this <see cref="T:Microsoft.WindowsAzure.Storage.StorageException" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageException.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="storageException.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="51ce0-121">Stellt eine von der Microsoft Azure Storage Client Library ausgelöste Ausnahme dar.</span><span class="sxs-lookup"><span data-stu-id="51ce0-121">Represents an exception thrown by the Microsoft Azure storage client library.</span></span> 
            </summary>
        <returns><span data-ttu-id="51ce0-122">Eine Zeichenfolge, die die Ausnahme darstellt.</span><span class="sxs-lookup"><span data-stu-id="51ce0-122">A string that represents the exception.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TranslateException">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.StorageException TranslateException (Exception ex, Microsoft.WindowsAzure.Storage.RequestResult reqResult);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.StorageException TranslateException(class System.Exception ex, class Microsoft.WindowsAzure.Storage.RequestResult reqResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageException.TranslateException(System.Exception,Microsoft.WindowsAzure.Storage.RequestResult)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TranslateException (ex As Exception, reqResult As RequestResult) As StorageException" />
      <MemberSignature Language="F#" Value="static member TranslateException : Exception * Microsoft.WindowsAzure.Storage.RequestResult -&gt; Microsoft.WindowsAzure.Storage.StorageException" Usage="Microsoft.WindowsAzure.Storage.StorageException.TranslateException (ex, reqResult)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageException</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ex" Type="System.Exception" />
        <Parameter Name="reqResult" Type="Microsoft.WindowsAzure.Storage.RequestResult" />
      </Parameters>
      <Docs>
        <param name="ex"><span data-ttu-id="51ce0-123">Die Ausnahme zu übersetzen.</span><span class="sxs-lookup"><span data-stu-id="51ce0-123">The exception to translate.</span></span></param>
        <param name="reqResult"><span data-ttu-id="51ce0-124">Das Ergebnis der Anforderung.</span><span class="sxs-lookup"><span data-stu-id="51ce0-124">The request result.</span></span></param>
        <summary>
            <span data-ttu-id="51ce0-125">Übersetzt die angegebene Ausnahme in einem <see cref="T:Microsoft.WindowsAzure.Storage.StorageException" />.</span><span class="sxs-lookup"><span data-stu-id="51ce0-125">Translates the specified exception into a <see cref="T:Microsoft.WindowsAzure.Storage.StorageException" />.</span></span>
            </summary>
        <returns><span data-ttu-id="51ce0-126">Die Speicher-Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="51ce0-126">The storage exception.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TranslateException">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.StorageException TranslateException (Exception ex, Microsoft.WindowsAzure.Storage.RequestResult reqResult, Func&lt;System.IO.Stream,Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation&gt; parseError);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.StorageException TranslateException(class System.Exception ex, class Microsoft.WindowsAzure.Storage.RequestResult reqResult, class System.Func`2&lt;class System.IO.Stream, class Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation&gt; parseError) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageException.TranslateException(System.Exception,Microsoft.WindowsAzure.Storage.RequestResult,System.Func{System.IO.Stream,Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TranslateException (ex As Exception, reqResult As RequestResult, parseError As Func(Of Stream, StorageExtendedErrorInformation)) As StorageException" />
      <MemberSignature Language="F#" Value="static member TranslateException : Exception * Microsoft.WindowsAzure.Storage.RequestResult * Func&lt;System.IO.Stream, Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation&gt; -&gt; Microsoft.WindowsAzure.Storage.StorageException" Usage="Microsoft.WindowsAzure.Storage.StorageException.TranslateException (ex, reqResult, parseError)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageException</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ex" Type="System.Exception" />
        <Parameter Name="reqResult" Type="Microsoft.WindowsAzure.Storage.RequestResult" />
        <Parameter Name="parseError" Type="System.Func&lt;System.IO.Stream,Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation&gt;" />
      </Parameters>
      <Docs>
        <param name="ex"><span data-ttu-id="51ce0-127">Die Ausnahme zu übersetzen.</span><span class="sxs-lookup"><span data-stu-id="51ce0-127">The exception to translate.</span></span></param>
        <param name="reqResult"><span data-ttu-id="51ce0-128">Das Ergebnis der Anforderung.</span><span class="sxs-lookup"><span data-stu-id="51ce0-128">The request result.</span></span></param>
        <param name="parseError"><span data-ttu-id="51ce0-129">Der Delegat verwendet, um den Fehler zu analysieren, erweiterte Fehlerinformationen abzurufen.</span><span class="sxs-lookup"><span data-stu-id="51ce0-129">The delegate used to parse the error to get extended error information.</span></span></param>
        <summary>
            <span data-ttu-id="51ce0-130">Übersetzt die angegebene Ausnahme in einem Speicher-Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="51ce0-130">Translates the specified exception into a storage exception.</span></span>
            </summary>
        <returns><span data-ttu-id="51ce0-131">Die Speicher-Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="51ce0-131">The storage exception.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>