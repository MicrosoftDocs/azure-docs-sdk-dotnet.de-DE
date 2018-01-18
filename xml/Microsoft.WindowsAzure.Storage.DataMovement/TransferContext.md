<Type Name="TransferContext" FullName="Microsoft.WindowsAzure.Storage.DataMovement.TransferContext">
  <TypeSignature Language="C#" Value="public abstract class TransferContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit TransferContext extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class TransferContext" />
  <TypeSignature Language="F#" Value="type TransferContext = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
    <AssemblyVersion>0.5.3.0</AssemblyVersion>
    <AssemblyVersion>0.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="82076-101">Stellt den Kontext für die Übertragung dar und bietet zusätzliche Laufzeitinformationen zu dessen Ausführung.</span><span class="sxs-lookup"><span data-stu-id="82076-101">Represents the context for a transfer, and provides additional runtime information about its execution.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TransferContext ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="82076-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="82076-102">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TransferContext (Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint checkpoint);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint checkpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.#ctor(Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (checkpoint As TransferCheckpoint)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.DataMovement.TransferContext : Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint -&gt; Microsoft.WindowsAzure.Storage.DataMovement.TransferContext" Usage="new Microsoft.WindowsAzure.Storage.DataMovement.TransferContext checkpoint" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="checkpoint" Type="Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint" />
      </Parameters>
      <Docs>
        <param name="checkpoint"><span data-ttu-id="82076-103">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint" /> Objekt, das den letzten Prüfpunkt aus der die Übertragung fortgesetzt wird darstellt.</span><span class="sxs-lookup"><span data-stu-id="82076-103">An <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint" /> object representing the last checkpoint from which the transfer continues on.</span></span></param>
        <summary>
            <span data-ttu-id="82076-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="82076-104">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TransferContext (System.IO.Stream journalStream);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream journalStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.#ctor(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (journalStream As Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.DataMovement.TransferContext : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.DataMovement.TransferContext" Usage="new Microsoft.WindowsAzure.Storage.DataMovement.TransferContext journalStream" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="journalStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="journalStream"><span data-ttu-id="82076-105">Der Stream, in dem die Übertragung Journal Infos in geschrieben wird.</span><span class="sxs-lookup"><span data-stu-id="82076-105">The stream into which the transfer journal info will be written into.</span></span> <span data-ttu-id="82076-106">Sie können die Previours fortsetzen Übertragung von seinen Stream Journal angehalten.</span><span class="sxs-lookup"><span data-stu-id="82076-106">It can resume the previours paused transfer from its journal stream.</span></span></param>
        <summary>
            <span data-ttu-id="82076-107">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="82076-107">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestId">
      <MemberSignature Language="C#" Value="public string ClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.ClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRequestId As String" />
      <MemberSignature Language="F#" Value="member this.ClientRequestId : string with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.ClientRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="82076-108">Ruft ab oder legt die Client-Anforderungs-Id.</span><span class="sxs-lookup"><span data-stu-id="82076-108">Gets or sets the client request id.</span></span>
            </summary>
        <value><span data-ttu-id="82076-109">Eine Zeichenfolge, die die Clientanforderungs-Id enthält.</span><span class="sxs-lookup"><span data-stu-id="82076-109">A string containing the client request id.</span></span></value>
        <remarks>
            <span data-ttu-id="82076-110">Durch Festlegen dieser Eigenschaft ändert alle Anforderungen verknüpften Übertragungsvorgang beteiligten enthalten die die HTTP <i>X-ms-Client-Request-Id</i> Header.</span><span class="sxs-lookup"><span data-stu-id="82076-110">Setting this property modifies all the requests involved in the related transfer operation to include the the HTTP <i>x-ms-client-request-id</i> header.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FileFailed">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt; FileFailed;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt; FileFailed" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.FileFailed" />
      <MemberSignature Language="VB.NET" Value="Public Event FileFailed As EventHandler(Of TransferEventArgs) " />
      <MemberSignature Language="F#" Value="member this.FileFailed : EventHandler&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt; " Usage="member this.FileFailed : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="82076-111">Das Ereignis ausgelöst, wenn für eine Übertragung von Dateien ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="82076-111">The event triggered when a file transfer is failed.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileSkipped">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt; FileSkipped;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt; FileSkipped" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.FileSkipped" />
      <MemberSignature Language="VB.NET" Value="Public Event FileSkipped As EventHandler(Of TransferEventArgs) " />
      <MemberSignature Language="F#" Value="member this.FileSkipped : EventHandler&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt; " Usage="member this.FileSkipped : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="82076-112">Das Ereignis ausgelöst, wenn eine Übertragung von Dateien übersprungen wird.</span><span class="sxs-lookup"><span data-stu-id="82076-112">The event triggered when a file transfer is skipped.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileTransferred">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt; FileTransferred;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt; FileTransferred" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.FileTransferred" />
      <MemberSignature Language="VB.NET" Value="Public Event FileTransferred As EventHandler(Of TransferEventArgs) " />
      <MemberSignature Language="F#" Value="member this.FileTransferred : EventHandler&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt; " Usage="member this.FileTransferred : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="82076-113">Das Ereignis ausgelöst, wenn eine Dateiübertragung erfolgreich abgeschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="82076-113">The event triggered when a file transfer is completed successfully.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceOverwrite">
      <MemberSignature Language="C#" Value="public static bool ForceOverwrite (object source, object destination);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool ForceOverwrite(object source, object destination) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.ForceOverwrite(System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ForceOverwrite (source As Object, destination As Object) As Boolean" />
      <MemberSignature Language="F#" Value="static member ForceOverwrite : obj * obj -&gt; bool" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.ForceOverwrite (source, destination)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Object" />
        <Parameter Name="destination" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="82076-114">Die Instanz der Datenquelle verwendet, um das Ziel zu überschreiben.</span><span class="sxs-lookup"><span data-stu-id="82076-114">Instance of source used to overwrite the destination.</span></span></param>
        <param name="destination"><span data-ttu-id="82076-115">Die Instanz des Ziels, das überschrieben werden.</span><span class="sxs-lookup"><span data-stu-id="82076-115">Instance of destination to be overwritten.</span></span></param>
        <summary>
            <span data-ttu-id="82076-116">Rückruf, der verwendet wird, um zu erzwingen Überschreiben des Ziels ohne Vorhandensein überprüfen.</span><span class="sxs-lookup"><span data-stu-id="82076-116">Callback used to force overwrite the destination without existence check.</span></span> <span data-ttu-id="82076-117">Kann verwendet werden, wenn nur Ziel Anmeldeinformationen Schreibberechtigung enthält.</span><span class="sxs-lookup"><span data-stu-id="82076-117">It can be used when destination credentials only contains write permission.</span></span>
            </summary>
        <returns><span data-ttu-id="82076-118">True, wenn die Datei überschrieben werden soll. andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="82076-118">True if the file should be overwritten; otherwise false.</span></span></returns>
        <remarks>
            <span data-ttu-id="82076-119">Berechtigung "Lesen" ist im Ziel-Anmeldeinformationen in wird die clientseitige Kopie für die Überwachung des kopieren weiterhin erforderlich.</span><span class="sxs-lookup"><span data-stu-id="82076-119">Read permission is still required in destination credentials in serivce side copy for copy status monitoring.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastCheckpoint">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint LastCheckpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint LastCheckpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.LastCheckpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastCheckpoint As TransferCheckpoint" />
      <MemberSignature Language="F#" Value="member this.LastCheckpoint : Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.LastCheckpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="82076-120">Ruft den letzten Prüfpunkt für die Übertragung ab.</span><span class="sxs-lookup"><span data-stu-id="82076-120">Gets the last checkpoint of the transfer.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogLevel">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.LogLevel LogLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.LogLevel LogLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.LogLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property LogLevel As LogLevel" />
      <MemberSignature Language="F#" Value="member this.LogLevel : Microsoft.WindowsAzure.Storage.LogLevel with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.LogLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.LogLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="82076-121">Ruft ab oder legt den Protokolliergrad für den zugehörigen Übertragungsvorgang verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="82076-121">Gets or sets the logging level to be used for the related transfer operation.</span></span>
            </summary>
        <value><span data-ttu-id="82076-122">Ein Wert vom Typ <see cref="T:Microsoft.WindowsAzure.Storage.LogLevel" /> , welche Ereignisse protokolliert werden, für den zugehörigen Übertragungsvorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="82076-122">A value of type <see cref="T:Microsoft.WindowsAzure.Storage.LogLevel" /> that specifies which events are logged for the related transfer operation.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProgressHandler">
      <MemberSignature Language="C#" Value="public IProgress&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; ProgressHandler { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; ProgressHandler" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.ProgressHandler" />
      <MemberSignature Language="VB.NET" Value="Public Property ProgressHandler As IProgress(Of TransferStatus)" />
      <MemberSignature Language="F#" Value="member this.ProgressHandler : IProgress&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.ProgressHandler" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IProgress&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="82076-123">Ruft ab, oder legt ihn fest vom updatehandler durchgeführt.</span><span class="sxs-lookup"><span data-stu-id="82076-123">Gets or sets the progress update handler.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAttributesCallback">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.DataMovement.SetAttributesCallback SetAttributesCallback { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.DataMovement.SetAttributesCallback SetAttributesCallback" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.SetAttributesCallback" />
      <MemberSignature Language="VB.NET" Value="Public Property SetAttributesCallback As SetAttributesCallback" />
      <MemberSignature Language="F#" Value="member this.SetAttributesCallback : Microsoft.WindowsAzure.Storage.DataMovement.SetAttributesCallback with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.SetAttributesCallback" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.DataMovement.SetAttributesCallback</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="82076-124">Abrufen oder festlegen den Rückruf aufgerufen wird, um die Attribute des Ziels im Arbeitsspeicher festgelegt.</span><span class="sxs-lookup"><span data-stu-id="82076-124">Gets or sets the callback invoked to set destination's attributes in memory.</span></span> <span data-ttu-id="82076-125">Der Attributsatz in dieser Rückruf werden an Azure Storage-Dienst gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="82076-125">The attributes set in this callback will be sent to azure storage service.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShouldOverwriteCallback">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.DataMovement.ShouldOverwriteCallback ShouldOverwriteCallback { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.DataMovement.ShouldOverwriteCallback ShouldOverwriteCallback" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.ShouldOverwriteCallback" />
      <MemberSignature Language="VB.NET" Value="Public Property ShouldOverwriteCallback As ShouldOverwriteCallback" />
      <MemberSignature Language="F#" Value="member this.ShouldOverwriteCallback : Microsoft.WindowsAzure.Storage.DataMovement.ShouldOverwriteCallback with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.ShouldOverwriteCallback" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.DataMovement.ShouldOverwriteCallback</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="82076-126">Abrufen oder festlegen den Rückruf aufgerufen wird, um feststellen, ob ein vorhandenes Ziel überschrieben.</span><span class="sxs-lookup"><span data-stu-id="82076-126">Gets or sets the callback invoked to tell whether to overwrite an existing destination.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>