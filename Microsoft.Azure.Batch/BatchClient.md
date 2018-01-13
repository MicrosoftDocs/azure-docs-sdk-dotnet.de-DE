<Type Name="BatchClient" FullName="Microsoft.Azure.Batch.BatchClient">
  <TypeSignature Language="C#" Value="public class BatchClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchClient extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.BatchClient" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type BatchClient = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="bf580-101">Der Client für eine Azure Batch-Konto verwendet, um den Batch-Dienst zuzugreifen.</span><span class="sxs-lookup"><span data-stu-id="bf580-101">A client for an Azure Batch account, used to access the Batch service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationOperations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ApplicationOperations ApplicationOperations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ApplicationOperations ApplicationOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchClient.ApplicationOperations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationOperations As ApplicationOperations" />
      <MemberSignature Language="F#" Value="member this.ApplicationOperations : Microsoft.Azure.Batch.ApplicationOperations" Usage="Microsoft.Azure.Batch.BatchClient.ApplicationOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ApplicationOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf580-102">Ruft eine <see cref="P:Microsoft.Azure.Batch.BatchClient.ApplicationOperations" /> für Operationen anwendungsbezogenen auf das zugeordnete Konto.</span><span class="sxs-lookup"><span data-stu-id="bf580-102">Gets an <see cref="P:Microsoft.Azure.Batch.BatchClient.ApplicationOperations" /> for performing application-related operations on the associated account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateOperations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CertificateOperations CertificateOperations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.CertificateOperations CertificateOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchClient.CertificateOperations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CertificateOperations As CertificateOperations" />
      <MemberSignature Language="F#" Value="member this.CertificateOperations : Microsoft.Azure.Batch.CertificateOperations" Usage="Microsoft.Azure.Batch.BatchClient.CertificateOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CertificateOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf580-103">Ruft eine <see cref="P:Microsoft.Azure.Batch.BatchClient.CertificateOperations" /> für Operationen zertifikatbezogene auf das zugeordnete Konto.</span><span class="sxs-lookup"><span data-stu-id="bf580-103">Gets a <see cref="P:Microsoft.Azure.Batch.BatchClient.CertificateOperations" /> for performing certificate-related operations on the associated account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Close">
      <MemberSignature Language="C#" Value="public void Close ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Close() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.Close" />
      <MemberSignature Language="VB.NET" Value="Public Sub Close ()" />
      <MemberSignature Language="F#" Value="member this.Close : unit -&gt; unit" Usage="batchClient.Close " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bf580-104">Schließt die aktuelle Instanz von <see cref="T:Microsoft.Azure.Batch.BatchClient" />.</span><span class="sxs-lookup"><span data-stu-id="bf580-104">Closes the current instance of <see cref="T:Microsoft.Azure.Batch.BatchClient" />.</span></span>  
            <span data-ttu-id="bf580-105">Geschlossen von Instanzen von <see cref="T:Microsoft.Azure.Batch.BatchClient" /> können keine Aufrufe an den Batch-Dienst vorgenommen werden und das Verhalten und die Werte der anderen Methoden oder Eigenschaften sind nicht definiert.</span><span class="sxs-lookup"><span data-stu-id="bf580-105">Closed instances of <see cref="T:Microsoft.Azure.Batch.BatchClient" /> are unable to make calls to the Batch Service and the behavior and values of any other methods or properties are undefined.</span></span> <span data-ttu-id="bf580-106">Diese Einschränkungen gelten auch sofort für alle Objekte, die zu diesem Instantation zurückverfolgen können <see cref="T:Microsoft.Azure.Batch.BatchClient" />.</span><span class="sxs-lookup"><span data-stu-id="bf580-106">These restrictions also apply immediately to any objects that can trace instantation back to this <see cref="T:Microsoft.Azure.Batch.BatchClient" />.</span></span>
            <span data-ttu-id="bf580-107">Diese Methode ist hinsichtlich und beliebig häufig aufgerufen werden kann.</span><span class="sxs-lookup"><span data-stu-id="bf580-107">This method is threadsafe and can be called any number of times.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.CloseAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CloseAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.CloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="batchClient.CloseAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bf580-108">Startet einen asynchronen Vorgang zum Schließen der aktuellen Instanz der <see cref="T:Microsoft.Azure.Batch.BatchClient" />.</span><span class="sxs-lookup"><span data-stu-id="bf580-108">Starts an asynchronous operation to close the current instance of <see cref="T:Microsoft.Azure.Batch.BatchClient" />.</span></span>  
            <span data-ttu-id="bf580-109">Geschlossen von Instanzen von <see cref="T:Microsoft.Azure.Batch.BatchClient" /> können keine Aufrufe an den Batch-Dienst vorgenommen werden und das Verhalten und die Werte der anderen Methoden oder Eigenschaften sind nicht definiert.</span><span class="sxs-lookup"><span data-stu-id="bf580-109">Closed instances of <see cref="T:Microsoft.Azure.Batch.BatchClient" /> are unable to make calls to the Batch Service and the behavior and values of any other methods or properties are undefined.</span></span> <span data-ttu-id="bf580-110">Diese Einschränkungen gelten auch sofort für alle Objekte, die zu diesem Instantation zurückverfolgen können <see cref="T:Microsoft.Azure.Batch.BatchClient" />.</span><span class="sxs-lookup"><span data-stu-id="bf580-110">These restrictions also apply immediately to any objects that can trace instantation back to this <see cref="T:Microsoft.Azure.Batch.BatchClient" />.</span></span>
            <span data-ttu-id="bf580-111">Diese Methode ist hinsichtlich und beliebig häufig aufgerufen werden kann.</span><span class="sxs-lookup"><span data-stu-id="bf580-111">This method is threadsafe and can be called any number of times.</span></span>
            </summary>
        <returns><span data-ttu-id="bf580-112">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="bf580-112">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchClient.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.BatchClient.CustomBehaviors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf580-113">Ruft ab oder legt eine Liste der Verhaltensweisen, die ändern oder Anpassen von Anforderungen an den Batch-Dienst.</span><span class="sxs-lookup"><span data-stu-id="bf580-113">Gets or sets a list of behaviors that modify or customize requests to the Batch service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="bf580-114">Diese Verhaltensweisen werden von untergeordneten Objekten geerbt.</span><span class="sxs-lookup"><span data-stu-id="bf580-114">These behaviors are inherited by child objects.</span></span></para>
          <para><span data-ttu-id="bf580-115">Änderungen werden in der Reihenfolge der Auflistung angewendet.</span><span class="sxs-lookup"><span data-stu-id="bf580-115">Modifications are applied in the order of the collection.</span></span> <span data-ttu-id="bf580-116">Der letzte write Wins.</span><span class="sxs-lookup"><span data-stu-id="bf580-116">The last write wins.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="batchClient.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bf580-117">Aufrufe <see cref="M:Microsoft.Azure.Batch.BatchClient.Close" /> und frei, die nicht verwalteten Ressourcen und optional auch die verwalteten Ressourcen von der <see cref="T:Microsoft.Azure.Batch.BatchClient" />.</span><span class="sxs-lookup"><span data-stu-id="bf580-117">Calls <see cref="M:Microsoft.Azure.Batch.BatchClient.Close" /> and releases the unmanaged resources and disposes of the managed resources used by the <see cref="T:Microsoft.Azure.Batch.BatchClient" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected virtual void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="abstract member Dispose : bool -&gt; unit&#xA;override this.Dispose : bool -&gt; unit" Usage="batchClient.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing"><span data-ttu-id="bf580-118">Gibt an, ob das Objekt wird verworfen oder freigegeben.</span><span class="sxs-lookup"><span data-stu-id="bf580-118">Indicates whether the object is being disposed or finalized.</span></span>  <span data-ttu-id="bf580-119">Bei "true", wird das Objekt freigegeben wird, und verwaltete Ressource freigeben kann.</span><span class="sxs-lookup"><span data-stu-id="bf580-119">If true, the object is being disposed and can dispose managed resource.</span></span>  <span data-ttu-id="bf580-120">Wenn "false" wird das Objekt abgeschlossen wird, und sollten nur nicht verwaltete Ressourcen frei.</span><span class="sxs-lookup"><span data-stu-id="bf580-120">If false, the object is being finalized and should only release unmanaged resources.</span></span></param>
        <summary>
            <span data-ttu-id="bf580-121">Vom nicht verwalteten Ressourcen frei der <see cref="T:Microsoft.Azure.Batch.BatchClient" />, und optional verwaltete Ressourcen frei.</span><span class="sxs-lookup"><span data-stu-id="bf580-121">Releases unmanaged resources used by the <see cref="T:Microsoft.Azure.Batch.BatchClient" />, and optionally disposes of managed resources.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobOperations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobOperations JobOperations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobOperations JobOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchClient.JobOperations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobOperations As JobOperations" />
      <MemberSignature Language="F#" Value="member this.JobOperations : Microsoft.Azure.Batch.JobOperations" Usage="Microsoft.Azure.Batch.BatchClient.JobOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf580-122">Ruft eine <see cref="P:Microsoft.Azure.Batch.BatchClient.JobOperations" /> für Operationen auftragsbezogene auf das zugeordnete Konto.</span><span class="sxs-lookup"><span data-stu-id="bf580-122">Gets a <see cref="P:Microsoft.Azure.Batch.BatchClient.JobOperations" /> for performing job-related operations on the associated account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobScheduleOperations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobScheduleOperations JobScheduleOperations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobScheduleOperations JobScheduleOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchClient.JobScheduleOperations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobScheduleOperations As JobScheduleOperations" />
      <MemberSignature Language="F#" Value="member this.JobScheduleOperations : Microsoft.Azure.Batch.JobScheduleOperations" Usage="Microsoft.Azure.Batch.BatchClient.JobScheduleOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobScheduleOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf580-123">Ruft eine <see cref="P:Microsoft.Azure.Batch.BatchClient.JobScheduleOperations" /> zum Ausführen des Auftrags Zeitplan-bezogenen Vorgänge für das zugeordnete Konto.</span><span class="sxs-lookup"><span data-stu-id="bf580-123">Gets a <see cref="P:Microsoft.Azure.Batch.BatchClient.JobScheduleOperations" /> for performing job schedule-related operations on the associated account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Open">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.BatchClient Open (Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.BatchClient Open(class Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.Open(Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Open (credentials As BatchSharedKeyCredentials) As BatchClient" />
      <MemberSignature Language="F#" Value="static member Open : Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials -&gt; Microsoft.Azure.Batch.BatchClient" Usage="Microsoft.Azure.Batch.BatchClient.Open credentials" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.BatchClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials" />
      </Parameters>
      <Docs>
        <param name="credentials"><span data-ttu-id="bf580-124">Die Anmeldeinformationen für den Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="bf580-124">The Batch account credentials.</span></span></param>
        <summary>
            <span data-ttu-id="bf580-125">Erstellt eine Instanz von <see cref="T:Microsoft.Azure.Batch.BatchClient" />.</span><span class="sxs-lookup"><span data-stu-id="bf580-125">Creates an instance of <see cref="T:Microsoft.Azure.Batch.BatchClient" />.</span></span>
            </summary>
        <returns><span data-ttu-id="bf580-126">Eine Instanz von <see cref="T:Microsoft.Azure.Batch.Protocol.BatchServiceClient" />.</span><span class="sxs-lookup"><span data-stu-id="bf580-126">An instance of <see cref="T:Microsoft.Azure.Batch.Protocol.BatchServiceClient" />.</span></span></returns>
        <remarks>
            <span data-ttu-id="bf580-127">Dies ist ein blockierender Aufruf.</span><span class="sxs-lookup"><span data-stu-id="bf580-127">This is a blocking call.</span></span> <span data-ttu-id="bf580-128">Für eine nicht blockierende entspricht, finden Sie unter<see cref="M:Microsoft.Azure.Batch.BatchClient.OpenAsync(Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials)" /></span><span class="sxs-lookup"><span data-stu-id="bf580-128">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.BatchClient.OpenAsync(Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials)" /></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Open">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.BatchClient Open (Microsoft.Azure.Batch.Auth.BatchTokenCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.BatchClient Open(class Microsoft.Azure.Batch.Auth.BatchTokenCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.Open(Microsoft.Azure.Batch.Auth.BatchTokenCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Open (credentials As BatchTokenCredentials) As BatchClient" />
      <MemberSignature Language="F#" Value="static member Open : Microsoft.Azure.Batch.Auth.BatchTokenCredentials -&gt; Microsoft.Azure.Batch.BatchClient" Usage="Microsoft.Azure.Batch.BatchClient.Open credentials" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.BatchClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.Batch.Auth.BatchTokenCredentials" />
      </Parameters>
      <Docs>
        <param name="credentials"><span data-ttu-id="bf580-129">Die Anmeldeinformationen für den Azure Active Directory-Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="bf580-129">The Azure Active Directory Batch account credentials.</span></span></param>
        <summary>
            <span data-ttu-id="bf580-130">Erstellt eine Instanz von <see cref="T:Microsoft.Azure.Batch.BatchClient" />.</span><span class="sxs-lookup"><span data-stu-id="bf580-130">Creates an instance of <see cref="T:Microsoft.Azure.Batch.BatchClient" />.</span></span>
            </summary>
        <returns><span data-ttu-id="bf580-131">Eine Instanz von <see cref="T:Microsoft.Azure.Batch.Protocol.BatchServiceClient" />.</span><span class="sxs-lookup"><span data-stu-id="bf580-131">An instance of <see cref="T:Microsoft.Azure.Batch.Protocol.BatchServiceClient" />.</span></span></returns>
        <remarks>
            <span data-ttu-id="bf580-132">Dies ist ein blockierender Aufruf.</span><span class="sxs-lookup"><span data-stu-id="bf580-132">This is a blocking call.</span></span> <span data-ttu-id="bf580-133">Für eine nicht blockierende entspricht, finden Sie unter<see cref="M:Microsoft.Azure.Batch.BatchClient.OpenAsync(Microsoft.Azure.Batch.Auth.BatchTokenCredentials)" /></span><span class="sxs-lookup"><span data-stu-id="bf580-133">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.BatchClient.OpenAsync(Microsoft.Azure.Batch.Auth.BatchTokenCredentials)" /></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Open">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.BatchClient Open (Microsoft.Azure.Batch.Protocol.BatchServiceClient restClient);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.BatchClient Open(class Microsoft.Azure.Batch.Protocol.BatchServiceClient restClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.Open(Microsoft.Azure.Batch.Protocol.BatchServiceClient)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Open (restClient As BatchServiceClient) As BatchClient" />
      <MemberSignature Language="F#" Value="static member Open : Microsoft.Azure.Batch.Protocol.BatchServiceClient -&gt; Microsoft.Azure.Batch.BatchClient" Usage="Microsoft.Azure.Batch.BatchClient.Open restClient" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.BatchClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="restClient" Type="Microsoft.Azure.Batch.Protocol.BatchServiceClient" />
      </Parameters>
      <Docs>
        <param name="restClient"><span data-ttu-id="bf580-134">Die Instanz von <see cref="T:Microsoft.Azure.Batch.Protocol.BatchServiceClient" /> für alle Aufrufe an die Batch-Dienst verwendet.</span><span class="sxs-lookup"><span data-stu-id="bf580-134">The instance of <see cref="T:Microsoft.Azure.Batch.Protocol.BatchServiceClient" /> to use for all calls made to the Batch Service.</span></span> <span data-ttu-id="bf580-135">Es wird nicht gelöscht, wenn BatchClient verworfen wird.</span><span class="sxs-lookup"><span data-stu-id="bf580-135">It will not be disposed when BatchClient is disposed.</span></span></param>
        <summary>
            <span data-ttu-id="bf580-136">Blockierenden Aufruf, der eine Instanz erstellt <see cref="T:Microsoft.Azure.Batch.BatchClient" /> verknüpft sind, mit dem angegebenen <see cref="T:Microsoft.Azure.Batch.Protocol.BatchServiceClient" />.</span><span class="sxs-lookup"><span data-stu-id="bf580-136">Blocking call that creates an instance of <see cref="T:Microsoft.Azure.Batch.BatchClient" /> associated with the specified <see cref="T:Microsoft.Azure.Batch.Protocol.BatchServiceClient" />.</span></span>
            </summary>
        <returns><span data-ttu-id="bf580-137">Eine Instanz von <see cref="T:Microsoft.Azure.Batch.Protocol.BatchServiceClient" />.</span><span class="sxs-lookup"><span data-stu-id="bf580-137">An instance of <see cref="T:Microsoft.Azure.Batch.Protocol.BatchServiceClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.BatchClient&gt; OpenAsync (Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.BatchClient&gt; OpenAsync(class Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.OpenAsync(Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OpenAsync (credentials As BatchSharedKeyCredentials) As Task(Of BatchClient)" />
      <MemberSignature Language="F#" Value="static member OpenAsync : Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.BatchClient&gt;" Usage="Microsoft.Azure.Batch.BatchClient.OpenAsync credentials" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.BatchClient&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials" />
      </Parameters>
      <Docs>
        <param name="credentials"><span data-ttu-id="bf580-138">Die Anmeldeinformationen für den Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="bf580-138">The Batch account credentials.</span></span></param>
        <summary>
            <span data-ttu-id="bf580-139">Erstellt eine Instanz des <see cref="T:Microsoft.Azure.Batch.BatchClient" /> den angegebenen Anmeldeinformationen zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="bf580-139">Creates an instance of <see cref="T:Microsoft.Azure.Batch.BatchClient" /> associated with the specified credentials.</span></span>
            </summary>
        <returns><span data-ttu-id="bf580-140">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="bf580-140">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.BatchClient&gt; OpenAsync (Microsoft.Azure.Batch.Auth.BatchTokenCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.BatchClient&gt; OpenAsync(class Microsoft.Azure.Batch.Auth.BatchTokenCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.OpenAsync(Microsoft.Azure.Batch.Auth.BatchTokenCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OpenAsync (credentials As BatchTokenCredentials) As Task(Of BatchClient)" />
      <MemberSignature Language="F#" Value="static member OpenAsync : Microsoft.Azure.Batch.Auth.BatchTokenCredentials -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.BatchClient&gt;" Usage="Microsoft.Azure.Batch.BatchClient.OpenAsync credentials" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.BatchClient&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.Batch.Auth.BatchTokenCredentials" />
      </Parameters>
      <Docs>
        <param name="credentials"><span data-ttu-id="bf580-141">Die Anmeldeinformationen für den Azure Active Directory-Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="bf580-141">The Azure Active Directory Batch account credentials.</span></span></param>
        <summary>
            <span data-ttu-id="bf580-142">Erstellt eine Instanz von <see cref="T:Microsoft.Azure.Batch.BatchClient" />.</span><span class="sxs-lookup"><span data-stu-id="bf580-142">Creates an instance of <see cref="T:Microsoft.Azure.Batch.BatchClient" />.</span></span>
            </summary>
        <returns><span data-ttu-id="bf580-143">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="bf580-143">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.BatchClient&gt; OpenAsync (Microsoft.Azure.Batch.Protocol.BatchServiceClient restClient);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.BatchClient&gt; OpenAsync(class Microsoft.Azure.Batch.Protocol.BatchServiceClient restClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.OpenAsync(Microsoft.Azure.Batch.Protocol.BatchServiceClient)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OpenAsync (restClient As BatchServiceClient) As Task(Of BatchClient)" />
      <MemberSignature Language="F#" Value="static member OpenAsync : Microsoft.Azure.Batch.Protocol.BatchServiceClient -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.BatchClient&gt;" Usage="Microsoft.Azure.Batch.BatchClient.OpenAsync restClient" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.BatchClient&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="restClient" Type="Microsoft.Azure.Batch.Protocol.BatchServiceClient" />
      </Parameters>
      <Docs>
        <param name="restClient"><span data-ttu-id="bf580-144">Die Instanz von <see cref="T:Microsoft.Azure.Batch.Protocol.BatchServiceClient" /> für alle Aufrufe an die Batch-Dienst verwendet.</span><span class="sxs-lookup"><span data-stu-id="bf580-144">The instance of <see cref="T:Microsoft.Azure.Batch.Protocol.BatchServiceClient" /> to use for all calls made to the Batch Service.</span></span> <span data-ttu-id="bf580-145">Es wird nicht gelöscht, wenn BatchClient verworfen wird.</span><span class="sxs-lookup"><span data-stu-id="bf580-145">It will not be disposed when BatchClient is disposed.</span></span></param>
        <summary>
            <span data-ttu-id="bf580-146">Erstellt eine Instanz des <see cref="T:Microsoft.Azure.Batch.BatchClient" /> verknüpft sind, mit dem angegebenen <see cref="T:Microsoft.Azure.Batch.Protocol.BatchServiceClient" />.</span><span class="sxs-lookup"><span data-stu-id="bf580-146">Creates an instance of <see cref="T:Microsoft.Azure.Batch.BatchClient" /> associated with the specified <see cref="T:Microsoft.Azure.Batch.Protocol.BatchServiceClient" />.</span></span>
            </summary>
        <returns><span data-ttu-id="bf580-147">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="bf580-147">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolOperations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.PoolOperations PoolOperations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.PoolOperations PoolOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchClient.PoolOperations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PoolOperations As PoolOperations" />
      <MemberSignature Language="F#" Value="member this.PoolOperations : Microsoft.Azure.Batch.PoolOperations" Usage="Microsoft.Azure.Batch.BatchClient.PoolOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.PoolOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf580-148">Ruft eine <see cref="P:Microsoft.Azure.Batch.BatchClient.PoolOperations" /> für Pool-bezogenen Vorgänge für das zugeordnete Konto ausführen.</span><span class="sxs-lookup"><span data-stu-id="bf580-148">Gets a <see cref="P:Microsoft.Azure.Batch.BatchClient.PoolOperations" /> for performing pool-related operations on the associated account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Utilities">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Utilities Utilities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Utilities Utilities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchClient.Utilities" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Utilities As Utilities" />
      <MemberSignature Language="F#" Value="member this.Utilities : Microsoft.Azure.Batch.Utilities" Usage="Microsoft.Azure.Batch.BatchClient.Utilities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Utilities</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf580-149">Ruft eine <see cref="P:Microsoft.Azure.Batch.BatchClient.Utilities" /> Objekt, das Hilfsmethoden für die Orchestrierung mehrere Batchvorgänge enthält.</span><span class="sxs-lookup"><span data-stu-id="bf580-149">Gets a <see cref="P:Microsoft.Azure.Batch.BatchClient.Utilities" /> object containing utility methods for orchestrating multiple Batch operations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>