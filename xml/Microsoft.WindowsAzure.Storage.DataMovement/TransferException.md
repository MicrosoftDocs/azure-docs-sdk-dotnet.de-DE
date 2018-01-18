<Type Name="TransferException" FullName="Microsoft.WindowsAzure.Storage.DataMovement.TransferException">
  <TypeSignature Language="C#" Value="public class TransferException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit TransferException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" />
  <TypeSignature Language="VB.NET" Value="Public Class TransferException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type TransferException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
    <AssemblyVersion>0.5.3.0</AssemblyVersion>
    <AssemblyVersion>0.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8fe02-101">Basisausnahmeklasse für Blob/FileTransferJobs ausgelöste Ausnahmen.</span><span class="sxs-lookup"><span data-stu-id="8fe02-101">Base exception class for exceptions thrown by Blob/FileTransferJobs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8fe02-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8fe02-102">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferException (Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferException.#ctor(Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As TransferErrorCode)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException : Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode -&gt; Microsoft.WindowsAzure.Storage.DataMovement.TransferException" Usage="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException errorCode" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode" />
      </Parameters>
      <Docs>
        <param name="errorCode"><span data-ttu-id="8fe02-103">Fehlercode zu übertragen.</span><span class="sxs-lookup"><span data-stu-id="8fe02-103">Transfer error code.</span></span></param>
        <summary>
            <span data-ttu-id="8fe02-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8fe02-104">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException : string -&gt; Microsoft.WindowsAzure.Storage.DataMovement.TransferException" Usage="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="8fe02-105">Die Meldung, in der der Fehler beschrieben wird.</span><span class="sxs-lookup"><span data-stu-id="8fe02-105">The message that describes the error.</span></span></param>
        <summary>
            <span data-ttu-id="8fe02-106">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8fe02-106">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferException (Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode errorCode, string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode errorCode, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferException.#ctor(Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As TransferErrorCode, message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException : Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode * string -&gt; Microsoft.WindowsAzure.Storage.DataMovement.TransferException" Usage="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException (errorCode, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="errorCode"><span data-ttu-id="8fe02-107">Fehlercode zu übertragen.</span><span class="sxs-lookup"><span data-stu-id="8fe02-107">Transfer error code.</span></span></param>
        <param name="message"><span data-ttu-id="8fe02-108">Ausnahmemeldung.</span><span class="sxs-lookup"><span data-stu-id="8fe02-108">Exception message.</span></span></param>
        <summary>
            <span data-ttu-id="8fe02-109">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8fe02-109">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TransferException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.WindowsAzure.Storage.DataMovement.TransferException" Usage="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info"><span data-ttu-id="8fe02-110">Die Serialisierungsinformationen.</span><span class="sxs-lookup"><span data-stu-id="8fe02-110">Serialization information.</span></span></param>
        <param name="context"><span data-ttu-id="8fe02-111">Der Streamingkontext.</span><span class="sxs-lookup"><span data-stu-id="8fe02-111">Streaming context.</span></span></param>
        <summary>
            <span data-ttu-id="8fe02-112">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8fe02-112">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferException (string message, Exception ex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception ex) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, ex As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException : string * Exception -&gt; Microsoft.WindowsAzure.Storage.DataMovement.TransferException" Usage="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException (message, ex)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="ex" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="8fe02-113">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="8fe02-113">The error message that explains the reason for the exception.</span></span></param>
        <param name="ex"><span data-ttu-id="8fe02-114">Die Ausnahme, die die Ursache für die aktuelle Ausnahme oder ein null-Verweis ist, wenn keine innere Ausnahme angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="8fe02-114">The exception that is the cause of the current exception, or a null reference if no inner exception is specified.</span></span></param>
        <summary>
            <span data-ttu-id="8fe02-115">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8fe02-115">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferException (Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode errorCode, string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode errorCode, string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferException.#ctor(Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode,System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As TransferErrorCode, message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException : Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode * string * Exception -&gt; Microsoft.WindowsAzure.Storage.DataMovement.TransferException" Usage="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException (errorCode, message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="errorCode"><span data-ttu-id="8fe02-116">Fehlercode zu übertragen.</span><span class="sxs-lookup"><span data-stu-id="8fe02-116">Transfer error code.</span></span></param>
        <param name="message"><span data-ttu-id="8fe02-117">Ausnahmemeldung.</span><span class="sxs-lookup"><span data-stu-id="8fe02-117">Exception message.</span></span></param>
        <param name="innerException"><span data-ttu-id="8fe02-118">Beschreibung der eingeschlossenen Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="8fe02-118">Inner exception.</span></span></param>
        <summary>
            <span data-ttu-id="8fe02-119">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8fe02-119">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode ErrorCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferException.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorCode As TransferErrorCode" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferException.ErrorCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8fe02-120">Ruft den detaillierten Fehlercode ab.</span><span class="sxs-lookup"><span data-stu-id="8fe02-120">Gets the detailed error code.</span></span>
            </summary>
        <value><span data-ttu-id="8fe02-121">Der Fehlercode der Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="8fe02-121">The error code of the exception.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetObjectData">
      <MemberSignature Language="C#" Value="public override void GetObjectData (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void GetObjectData(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferException.GetObjectData(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub GetObjectData (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="override this.GetObjectData : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; unit" Usage="transferException.GetObjectData (info, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info"><span data-ttu-id="8fe02-122">Infoobjekt für die Serialisierung.</span><span class="sxs-lookup"><span data-stu-id="8fe02-122">Serialization info object.</span></span></param>
        <param name="context"><span data-ttu-id="8fe02-123">Der Streamingkontext.</span><span class="sxs-lookup"><span data-stu-id="8fe02-123">Streaming context.</span></span></param>
        <summary>
            <span data-ttu-id="8fe02-124">Serialisiert die Ausnahme an.</span><span class="sxs-lookup"><span data-stu-id="8fe02-124">Serializes the exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>