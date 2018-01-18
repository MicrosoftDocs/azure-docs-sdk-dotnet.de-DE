<Type Name="CloudTable" FullName="Microsoft.Azure.CosmosDB.Table.CloudTable">
  <TypeSignature Language="C#" Value="public class CloudTable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudTable extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.CloudTable" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudTable" />
  <TypeSignature Language="F#" Value="type CloudTable = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2b698-101">Stellt eine Microsoft Azure-Tabelle dar.</span><span class="sxs-lookup"><span data-stu-id="2b698-101">Represents a Microsoft Azure table.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudTable (Uri tableAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri tableAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tableAddress As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.CosmosDB.Table.CloudTable : Uri -&gt; Microsoft.Azure.CosmosDB.Table.CloudTable" Usage="new Microsoft.Azure.CosmosDB.Table.CloudTable tableAddress" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tableAddress" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="tableAddress"><span data-ttu-id="2b698-102">Ein <see cref="T:System.Uri" /> den absoluten URI zur Tabelle angeben.</span><span class="sxs-lookup"><span data-stu-id="2b698-102">A <see cref="T:System.Uri" /> specifying the absolute URI to the table.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2b698-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudTable (Microsoft.Azure.Storage.StorageUri tableAddress, Microsoft.Azure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Storage.StorageUri tableAddress, class Microsoft.Azure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.#ctor(Microsoft.Azure.Storage.StorageUri,Microsoft.Azure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tableAddress As StorageUri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.CosmosDB.Table.CloudTable : Microsoft.Azure.Storage.StorageUri * Microsoft.Azure.Storage.Auth.StorageCredentials -&gt; Microsoft.Azure.CosmosDB.Table.CloudTable" Usage="new Microsoft.Azure.CosmosDB.Table.CloudTable (tableAddress, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tableAddress" Type="Microsoft.Azure.Storage.StorageUri" />
        <Parameter Name="credentials" Type="Microsoft.Azure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="tableAddress"><span data-ttu-id="2b698-104">Ein <see cref="P:Microsoft.Azure.CosmosDB.Table.CloudTable.StorageUri" /> , den absoluten URI der Tabelle auf dem primären und sekundären Speicherorte enthält.</span><span class="sxs-lookup"><span data-stu-id="2b698-104">A <see cref="P:Microsoft.Azure.CosmosDB.Table.CloudTable.StorageUri" /> containing the absolute URI to the table at both the primary and secondary locations.</span></span></param>
        <param name="credentials"><span data-ttu-id="2b698-105">Ein <see cref="T:Microsoft.Azure.Storage.Auth.StorageCredentials" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="2b698-105">A <see cref="T:Microsoft.Azure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-106">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2b698-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudTable (Uri tableAbsoluteUri, Microsoft.Azure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri tableAbsoluteUri, class Microsoft.Azure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.#ctor(System.Uri,Microsoft.Azure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tableAbsoluteUri As Uri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.CosmosDB.Table.CloudTable : Uri * Microsoft.Azure.Storage.Auth.StorageCredentials -&gt; Microsoft.Azure.CosmosDB.Table.CloudTable" Usage="new Microsoft.Azure.CosmosDB.Table.CloudTable (tableAbsoluteUri, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tableAbsoluteUri" Type="System.Uri" />
        <Parameter Name="credentials" Type="Microsoft.Azure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="tableAbsoluteUri"><span data-ttu-id="2b698-107">Ein <see cref="T:System.Uri" /> den absoluten URI zur Tabelle angeben.</span><span class="sxs-lookup"><span data-stu-id="2b698-107">A <see cref="T:System.Uri" /> specifying the absolute URI to the table.</span></span></param>
        <param name="credentials"><span data-ttu-id="2b698-108">Ein <see cref="T:Microsoft.Azure.Storage.Auth.StorageCredentials" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="2b698-108">A <see cref="T:Microsoft.Azure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-109">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2b698-109">Initializes a new instance of the <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreate (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreate(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginCreate(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginCreate (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginCreate : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreate : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginCreate (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="2b698-110">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-110">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-111">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-111">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-112">Startet einen asynchronen Vorgang zum Erstellen einer Tabelle.</span><span class="sxs-lookup"><span data-stu-id="2b698-112">Begins an asynchronous operation to create a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-113">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-113">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreate (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreate(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginCreate(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreate : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreate : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginCreate (requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="2b698-114">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-114">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-115">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-115">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="2b698-116">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-116">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-117">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-117">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-118">Startet einen asynchronen Vorgang zum Erstellen einer Tabelle.</span><span class="sxs-lookup"><span data-stu-id="2b698-118">Begins an asynchronous operation to create a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-119">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-119">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreate (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, Nullable&lt;Microsoft.Azure.CosmosDB.IndexingMode&gt; indexingMode, Nullable&lt;int&gt; throughput, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreate(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.CosmosDB.IndexingMode&gt; indexingMode, valuetype System.Nullable`1&lt;int32&gt; throughput, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginCreate(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Nullable{Microsoft.Azure.CosmosDB.IndexingMode},System.Nullable{System.Int32},System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreate : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * Nullable&lt;Microsoft.Azure.CosmosDB.IndexingMode&gt; * Nullable&lt;int&gt; * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreate : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * Nullable&lt;Microsoft.Azure.CosmosDB.IndexingMode&gt; * Nullable&lt;int&gt; * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginCreate (requestOptions, operationContext, indexingMode, throughput, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="indexingMode" Type="System.Nullable&lt;Microsoft.Azure.CosmosDB.IndexingMode&gt;" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="2b698-120">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-120">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-121">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-121">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="indexingMode"><span data-ttu-id="2b698-122">Geben Sie indizierungsmodus für CosmosDB-Tabelle</span><span class="sxs-lookup"><span data-stu-id="2b698-122">Specify indexing mode for CosmosDB table</span></span></param>
        <param name="throughput"><span data-ttu-id="2b698-123">CosmosDB Tabelle Durchsatz</span><span class="sxs-lookup"><span data-stu-id="2b698-123">CosmosDB table throughput</span></span></param>
        <param name="callback"><span data-ttu-id="2b698-124">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-124">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-125">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-125">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-126">Startet einen asynchronen Vorgang zum Erstellen einer Tabelle.</span><span class="sxs-lookup"><span data-stu-id="2b698-126">Begins an asynchronous operation to create a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-127">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-127">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreate (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, Nullable&lt;int&gt; throughput, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreate(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, valuetype System.Nullable`1&lt;int32&gt; throughput, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginCreate(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.String,System.Nullable{System.Int32},System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreate : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreate : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginCreate (requestOptions, operationContext, serializedIndexingPolicy, throughput, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="serializedIndexingPolicy" Type="System.String" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="2b698-128">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-128">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-129">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-129">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="serializedIndexingPolicy"><span data-ttu-id="2b698-130">CosmosDB Tabelle indizierungsrichtlinie</span><span class="sxs-lookup"><span data-stu-id="2b698-130">CosmosDB table indexing policy</span></span></param>
        <param name="throughput"><span data-ttu-id="2b698-131">CosmosDB Tabelle Durchsatz</span><span class="sxs-lookup"><span data-stu-id="2b698-131">CosmosDB table throughput</span></span></param>
        <param name="callback"><span data-ttu-id="2b698-132">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-132">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-133">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-133">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-134">Startet einen asynchronen Vorgang zum Erstellen einer Tabelle.</span><span class="sxs-lookup"><span data-stu-id="2b698-134">Begins an asynchronous operation to create a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-135">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-135">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreateIfNotExists (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreateIfNotExists(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginCreateIfNotExists(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginCreateIfNotExists (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateIfNotExists : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateIfNotExists : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginCreateIfNotExists (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="2b698-136">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-136">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-137">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-137">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-138">Startet einen asynchronen Vorgang zum Erstellen einer Tabelle, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-138">Begins an asynchronous operation to create a table if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-139">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-139">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="2b698-140">Diese API führt eine Überprüfung auf Vorhandensein und erfordert daher Listenberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="2b698-140">This API performs an existence check and therefore requires list permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreateIfNotExists (Microsoft.Azure.CosmosDB.IndexingMode indexingMode, Nullable&lt;int&gt; throughput, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreateIfNotExists(valuetype Microsoft.Azure.CosmosDB.IndexingMode indexingMode, valuetype System.Nullable`1&lt;int32&gt; throughput, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginCreateIfNotExists(Microsoft.Azure.CosmosDB.IndexingMode,System.Nullable{System.Int32},System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateIfNotExists : Microsoft.Azure.CosmosDB.IndexingMode * Nullable&lt;int&gt; * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateIfNotExists : Microsoft.Azure.CosmosDB.IndexingMode * Nullable&lt;int&gt; * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginCreateIfNotExists (indexingMode, throughput, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="indexingMode" Type="Microsoft.Azure.CosmosDB.IndexingMode" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="indexingMode"><span data-ttu-id="2b698-141">CosmosDB Tabelle indizierungsmodus</span><span class="sxs-lookup"><span data-stu-id="2b698-141">CosmosDB table indexing mode</span></span></param>
        <param name="throughput"><span data-ttu-id="2b698-142">CosmosDB Tabelle Durchsatz</span><span class="sxs-lookup"><span data-stu-id="2b698-142">CosmosDB table throughput</span></span></param>
        <param name="callback"><span data-ttu-id="2b698-143">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-143">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-144">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-144">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-145">Startet einen asynchronen Vorgang zum Erstellen einer Tabelle, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-145">Begins an asynchronous operation to create a table if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-146">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-146">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="2b698-147">Diese API führt eine Überprüfung auf Vorhandensein und erfordert daher Listenberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="2b698-147">This API performs an existence check and therefore requires list permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreateIfNotExists (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreateIfNotExists(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginCreateIfNotExists(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateIfNotExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateIfNotExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginCreateIfNotExists (requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="2b698-148">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-148">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-149">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-149">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="2b698-150">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-150">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-151">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-151">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-152">Startet einen asynchronen Vorgang zum Erstellen einer Tabelle, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-152">Begins an asynchronous operation to create a table if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-153">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-153">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="2b698-154">Diese API führt eine Überprüfung auf Vorhandensein und erfordert daher Listenberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="2b698-154">This API performs an existence check and therefore requires list permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreateIfNotExists (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, Nullable&lt;int&gt; throughput, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreateIfNotExists(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, valuetype System.Nullable`1&lt;int32&gt; throughput, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginCreateIfNotExists(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.String,System.Nullable{System.Int32},System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateIfNotExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateIfNotExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginCreateIfNotExists (requestOptions, operationContext, serializedIndexingPolicy, throughput, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="serializedIndexingPolicy" Type="System.String" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="2b698-155">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-155">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-156">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-156">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="serializedIndexingPolicy"><span data-ttu-id="2b698-157">CosmosDB Tabelle indizierungsrichtlinie</span><span class="sxs-lookup"><span data-stu-id="2b698-157">CosmosDB table indexing policy</span></span></param>
        <param name="throughput"><span data-ttu-id="2b698-158">CosmosDB Tabelle Durchsatz</span><span class="sxs-lookup"><span data-stu-id="2b698-158">CosmosDB table throughput</span></span></param>
        <param name="callback"><span data-ttu-id="2b698-159">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-159">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-160">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-160">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-161">Startet einen asynchronen Vorgang zum Erstellen einer Tabelle, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-161">Begins an asynchronous operation to create a table if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-162">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-162">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="2b698-163">Diese API führt eine Überprüfung auf Vorhandensein und erfordert daher Listenberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="2b698-163">This API performs an existence check and therefore requires list permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginDelete (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginDelete(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginDelete(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDelete (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDelete : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginDelete : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginDelete (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="2b698-164">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-164">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-165">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-165">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-166">Startet einen asynchronen Vorgang zum Löschen einer Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-166">Begins an asynchronous operation to delete a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-167">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-167">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginDelete (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginDelete(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginDelete(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDelete : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginDelete : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginDelete (requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="2b698-168">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-168">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-169">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-169">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="2b698-170">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-170">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-171">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-171">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-172">Startet einen asynchronen Vorgang zum Löschen einer Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-172">Begins an asynchronous operation to delete a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-173">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-173">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginDeleteIfExists (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginDeleteIfExists(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginDeleteIfExists(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDeleteIfExists (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteIfExists : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginDeleteIfExists : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginDeleteIfExists (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="2b698-174">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-174">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-175">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-175">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-176">Startet einen asynchronen Vorgang zum Löschen der Tabelle, sofern vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2b698-176">Begins an asynchronous operation to delete the table if it exists.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-177">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-177">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginDeleteIfExists (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginDeleteIfExists(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginDeleteIfExists(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteIfExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginDeleteIfExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginDeleteIfExists (requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="2b698-178">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-178">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-179">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-179">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="2b698-180">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-180">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-181">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-181">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-182">Startet einen asynchronen Vorgang zum Löschen der Tabelle, sofern vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2b698-182">Begins an asynchronous operation to delete the table if it exists.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-183">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-183">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecute">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecute (Microsoft.Azure.CosmosDB.Table.TableOperation operation, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecute(class Microsoft.Azure.CosmosDB.Table.TableOperation operation, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecute(Microsoft.Azure.CosmosDB.Table.TableOperation,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecute (operation As TableOperation, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecute : Microsoft.Azure.CosmosDB.Table.TableOperation * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecute : Microsoft.Azure.CosmosDB.Table.TableOperation * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecute (operation, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operation" Type="Microsoft.Azure.CosmosDB.Table.TableOperation" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="operation"><span data-ttu-id="2b698-184">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> Objekt, das den auszuführenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-184">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> object that represents the operation to perform.</span></span></param>
        <param name="callback"><span data-ttu-id="2b698-185">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-185">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-186">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-186">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-187">Beginnt die Ausführung eines asynchronen Tabelle-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="2b698-187">Begins execution of an asynchronous table operation.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-188">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-188">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecute">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecute (Microsoft.Azure.CosmosDB.Table.TableOperation operation, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecute(class Microsoft.Azure.CosmosDB.Table.TableOperation operation, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecute(Microsoft.Azure.CosmosDB.Table.TableOperation,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecute : Microsoft.Azure.CosmosDB.Table.TableOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecute : Microsoft.Azure.CosmosDB.Table.TableOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecute (operation, requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operation" Type="Microsoft.Azure.CosmosDB.Table.TableOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="operation"><span data-ttu-id="2b698-189">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> Objekt, das den auszuführenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-189">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> object that represents the operation to perform.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-190">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-190">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-191">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-191">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="2b698-192">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-192">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-193">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-193">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-194">Beginnt die Ausführung eines asynchronen Tabelle-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="2b698-194">Begins execution of an asynchronous table operation.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-195">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-195">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteBatch">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteBatch (Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteBatch(class Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteBatch(Microsoft.Azure.CosmosDB.Table.TableBatchOperation,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecuteBatch (batch As TableBatchOperation, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteBatch : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteBatch : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteBatch (batch, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="batch"><span data-ttu-id="2b698-196">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> Objekt, das die Vorgänge zum Ausführen für die Tabelle darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-196">The <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> object representing the operations to execute on the table.</span></span></param>
        <param name="callback"><span data-ttu-id="2b698-197">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-197">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-198">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-198">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-199">Startet einen asynchronen Vorgang zum Ausführen eines Batches von Vorgängen für eine Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-199">Begins an asynchronous operation to execute a batch of operations on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-200">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-200">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteBatch">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteBatch (Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteBatch(class Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteBatch(Microsoft.Azure.CosmosDB.Table.TableBatchOperation,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteBatch : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteBatch : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteBatch (batch, requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="batch"><span data-ttu-id="2b698-201">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> Objekt, das die Vorgänge zum Ausführen für die Tabelle darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-201">The <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> object representing the operations to execute on the table.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-202">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-202">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-203">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-203">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="2b698-204">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-204">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-205">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-205">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-206">Startet einen asynchronen Vorgang zum Ausführen eines Batches von Vorgängen für eine Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-206">Begins an asynchronous operation to execute a batch of operations on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-207">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-207">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQueryForKeyRotationSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQueryForKeyRotationSegmented (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQueryForKeyRotationSegmented(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQueryForKeyRotationSegmented(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecuteQueryForKeyRotationSegmented (query As TableQuery, token As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQueryForKeyRotationSegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteQueryForKeyRotationSegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteQueryForKeyRotationSegmented (query, token, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="2b698-208">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-208">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-209">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-209">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="callback"><span data-ttu-id="2b698-210">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-210">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-211">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-211">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-212">Beginnt eine asynchrone segmentierte Abfrage für eine Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-212">Begins an asynchronous segmented query on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-213">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-213">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQueryForKeyRotationSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQueryForKeyRotationSegmented (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQueryForKeyRotationSegmented(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQueryForKeyRotationSegmented(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQueryForKeyRotationSegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteQueryForKeyRotationSegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteQueryForKeyRotationSegmented (query, token, requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="2b698-214">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-214">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-215">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-215">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-216">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-216">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-217">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-217">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="2b698-218">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-218">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-219">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-219">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-220">Beginnt eine asynchrone segmentierte Abfrage für eine Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-220">Begins an asynchronous segmented query on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-221">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-221">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQuerySegmented(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecuteQuerySegmented (query As TableQuery, token As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteQuerySegmented (query, token, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="2b698-222">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-222">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-223">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-223">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="callback"><span data-ttu-id="2b698-224">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-224">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-225">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-225">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-226">Beginnt eine asynchrone segmentierte Abfrage für eine Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-226">Begins an asynchronous segmented query on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-227">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-227">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQuerySegmented(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteQuerySegmented (query, token, requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="2b698-228">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-228">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-229">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-229">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-230">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-230">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-231">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-231">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="2b698-232">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-232">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-233">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-233">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-234">Beginnt eine asynchrone segmentierte Abfrage für eine Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-234">Begins an asynchronous segmented query on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-235">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-235">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TElement&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, AsyncCallback callback, object state) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQuerySegmented``1(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecuteQuerySegmented(Of TElement As {ITableEntityNew}) (query As TableQuery(Of TElement), token As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.BeginExecuteQuerySegmented (query, token, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="2b698-236">Der Entitätstyp der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-236">The entity type of the query.</span></span></typeparam>
        <param name="query"><span data-ttu-id="2b698-237">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-237">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-238">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-238">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="callback"><span data-ttu-id="2b698-239">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-239">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-240">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-240">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-241">Startet einen asynchronen Vorgang zum Abfragen einer Tabelle im segmentierten Modus.</span><span class="sxs-lookup"><span data-stu-id="2b698-241">Begins an asynchronous operation to query a table in segmented mode.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-242">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-242">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TElement&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQuerySegmented``1(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.BeginExecuteQuerySegmented (query, token, requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="2b698-243">Der Entitätstyp der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-243">The entity type of the query.</span></span></typeparam>
        <param name="query"><span data-ttu-id="2b698-244">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-244">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-245">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-245">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-246">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-246">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-247">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-247">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="2b698-248">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-248">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-249">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-249">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-250">Startet einen asynchronen Vorgang zum Abfragen einer Tabelle im segmentierten Modus.</span><span class="sxs-lookup"><span data-stu-id="2b698-250">Begins an asynchronous operation to query a table in segmented mode.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-251">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-251">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQuerySegmented``1(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.EntityResolver{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecuteQuerySegmented(Of TResult) (query As TableQuery, resolver As EntityResolver(Of TResult), token As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteQuerySegmented (query, resolver, token, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">To be added.</typeparam>
        <param name="query"><span data-ttu-id="2b698-252">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-252">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="resolver"><span data-ttu-id="2b698-253">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-253">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-254">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-254">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="callback"><span data-ttu-id="2b698-255">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-255">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-256">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-256">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-257">Startet einen asynchronen Vorgang zum Ausführen einer Abfrage segmentierten und Anwenden der angegebenen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> auf das Ergebnis.</span><span class="sxs-lookup"><span data-stu-id="2b698-257">Begins an asynchronous operation to execute a segmented query and apply the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the result.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-258">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-258">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQuerySegmented``1(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.EntityResolver{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteQuerySegmented (query, resolver, token, requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TResult"><span data-ttu-id="2b698-259">Der Typ, in dem <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> projiziert die Ergebnisse der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-259">The type into which the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> will project the query results.</span></span></typeparam>
        <param name="query"><span data-ttu-id="2b698-260">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz unter Angabe der Tabelle Abfragen ausgeführt und die Abfrageparameter verwendet.</span><span class="sxs-lookup"><span data-stu-id="2b698-260">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use.</span></span></param>
        <param name="resolver"><span data-ttu-id="2b698-261">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-261">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-262">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-262">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-263">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-263">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-264">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-264">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="2b698-265">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-265">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-266">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-266">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-267">Startet einen asynchronen Vorgang zum Ausführen einer Abfrage segmentierten und Anwenden der angegebenen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> auf das Ergebnis.</span><span class="sxs-lookup"><span data-stu-id="2b698-267">Begins an asynchronous operation to execute a segmented query and apply the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the result.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-268">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-268">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TElement,TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, AsyncCallback callback, object state) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQuerySegmented``2(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.EntityResolver{``1},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecuteQuerySegmented(Of TElement As {ITableEntityNew}, TResult As {ITableEntityNew}) (query As TableQuery(Of TElement), resolver As EntityResolver(Of TResult), token As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.BeginExecuteQuerySegmented (query, resolver, token, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="2b698-269">Der Entitätstyp der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-269">The entity type of the query.</span></span></typeparam>
        <typeparam name="TResult"><span data-ttu-id="2b698-270">Der Typ, in dem <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> projiziert die Ergebnisse der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-270">The type into which the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> will project the query results.</span></span></typeparam>
        <param name="query"><span data-ttu-id="2b698-271">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-271">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="resolver"><span data-ttu-id="2b698-272">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-272">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-273">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-273">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="callback"><span data-ttu-id="2b698-274">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-274">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-275">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-275">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-276">Startet einen asynchronen Vorgang zum Abfragen einer Tabelle im segmentierten Modus und Anwenden der angegebenen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> mit den Ergebnissen.</span><span class="sxs-lookup"><span data-stu-id="2b698-276">Begins an asynchronous operation to query a table in segmented mode and apply the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the results.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-277">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-277">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TElement,TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQuerySegmented``2(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.EntityResolver{``1},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.BeginExecuteQuerySegmented (query, resolver, token, requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="2b698-278">Der Entitätstyp der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-278">The entity type of the query.</span></span></typeparam>
        <typeparam name="TResult"><span data-ttu-id="2b698-279">Der Typ, in dem <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> projiziert die Ergebnisse der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-279">The type into which the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> will project the query results.</span></span></typeparam>
        <param name="query"><span data-ttu-id="2b698-280">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-280">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="resolver"><span data-ttu-id="2b698-281">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-281">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-282">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-282">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-283">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-283">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-284">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-284">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="2b698-285">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-285">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-286">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-286">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-287">Startet einen asynchronen Vorgang zum Ausführen einer Abfrage im segmentierten Modus und Anwenden der angegebenen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> mit den Ergebnissen.</span><span class="sxs-lookup"><span data-stu-id="2b698-287">Begins an asynchronous operation to execute a query in segmented mode and apply the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the results.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-288">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-288">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExists (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExists(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExists(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExists (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExists : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExists : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExists (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="2b698-289">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-289">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-290">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-290">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-291">Startet einen asynchronen Vorgang, um festzustellen, ob eine Tabelle vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-291">Begins an asynchronous operation to determine whether a table exists.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-292">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-292">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExists (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExists(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExists(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExists (requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="2b698-293">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-293">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-294">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-294">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="2b698-295">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-295">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-296">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-296">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-297">Startet einen asynchronen Vorgang, um festzustellen, ob eine Tabelle vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-297">Begins an asynchronous operation to determine whether a table exists.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-298">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-298">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginGetPermissions (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginGetPermissions(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginGetPermissions(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetPermissions (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetPermissions : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetPermissions : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginGetPermissions (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="2b698-299">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-299">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-300">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-300">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-301">Beginnt eine asynchrone Anforderung an die berechtigungseinstellungen für die Tabelle zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="2b698-301">Begins an asynchronous request to get the permissions settings for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-302">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-302">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginGetPermissions (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginGetPermissions(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginGetPermissions(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetPermissions : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetPermissions : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginGetPermissions (requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="2b698-303">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-303">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-304">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-304">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="2b698-305">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-305">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-306">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-306">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-307">Beginnt eine asynchrone Anforderung an die berechtigungseinstellungen für die Tabelle zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="2b698-307">Begins an asynchronous request to get the permissions settings for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-308">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-308">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginSetPermissions (Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginSetPermissions(class Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginSetPermissions(Microsoft.Azure.CosmosDB.Table.TablePermissions,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginSetPermissions (permissions As TablePermissions, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginSetPermissions : Microsoft.Azure.CosmosDB.Table.TablePermissions * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetPermissions : Microsoft.Azure.CosmosDB.Table.TablePermissions * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginSetPermissions (permissions, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.Azure.CosmosDB.Table.TablePermissions" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="2b698-309">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> Objekt, das die Berechtigungen festgelegt darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-309">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> object that represents the permissions to set.</span></span></param>
        <param name="callback"><span data-ttu-id="2b698-310">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-310">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-311">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-311">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-312">Beginnt eine asynchrone Anforderung zum Festlegen von Berechtigungen für die Tabelle.</span><span class="sxs-lookup"><span data-stu-id="2b698-312">Begins an asynchronous request to set permissions for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-313">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-313">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginSetPermissions (Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginSetPermissions(class Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginSetPermissions(Microsoft.Azure.CosmosDB.Table.TablePermissions,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetPermissions : Microsoft.Azure.CosmosDB.Table.TablePermissions * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetPermissions : Microsoft.Azure.CosmosDB.Table.TablePermissions * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginSetPermissions (permissions, requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.Azure.CosmosDB.Table.TablePermissions" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="2b698-314">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> Objekt, das die Berechtigungen festgelegt darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-314">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> object that represents the permissions to set.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-315">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-315">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-316">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-316">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="2b698-317">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-317">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="2b698-318">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-318">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-319">Beginnt eine asynchrone Anforderung zum Festlegen von Berechtigungen für die Tabelle.</span><span class="sxs-lookup"><span data-stu-id="2b698-319">Begins an asynchronous request to set permissions for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-320">Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-320">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public virtual void Create (Nullable&lt;Microsoft.Azure.CosmosDB.IndexingMode&gt; indexingMode, Nullable&lt;int&gt; throughput = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Create(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.CosmosDB.IndexingMode&gt; indexingMode, valuetype System.Nullable`1&lt;int32&gt; throughput) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.Create(System.Nullable{Microsoft.Azure.CosmosDB.IndexingMode},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Create (indexingMode As Nullable(Of IndexingMode), Optional throughput As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="abstract member Create : Nullable&lt;Microsoft.Azure.CosmosDB.IndexingMode&gt; * Nullable&lt;int&gt; -&gt; unit&#xA;override this.Create : Nullable&lt;Microsoft.Azure.CosmosDB.IndexingMode&gt; * Nullable&lt;int&gt; -&gt; unit" Usage="cloudTable.Create (indexingMode, throughput)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="indexingMode" Type="System.Nullable&lt;Microsoft.Azure.CosmosDB.IndexingMode&gt;" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="indexingMode"><span data-ttu-id="2b698-321">Geben Sie indizierungsmodus für CosmosDB-Tabelle</span><span class="sxs-lookup"><span data-stu-id="2b698-321">Specify indexing mode for CosmosDB table</span></span></param>
        <param name="throughput"><span data-ttu-id="2b698-322">CosmosDB Tabelle Durchsatz</span><span class="sxs-lookup"><span data-stu-id="2b698-322">CosmosDB table throughput</span></span></param>
        <summary>
            <span data-ttu-id="2b698-323">Erstellt eine Tabelle.</span><span class="sxs-lookup"><span data-stu-id="2b698-323">Creates a table.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public virtual void Create (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null, string serializedIndexingPolicy = null, Nullable&lt;int&gt; throughput = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Create(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, valuetype System.Nullable`1&lt;int32&gt; throughput) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.Create(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="F#" Value="abstract member Create : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; -&gt; unit&#xA;override this.Create : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; -&gt; unit" Usage="cloudTable.Create (requestOptions, operationContext, serializedIndexingPolicy, throughput)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="serializedIndexingPolicy" Type="System.String" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="2b698-324">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-324">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-325">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-325">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="serializedIndexingPolicy"><span data-ttu-id="2b698-326">CosmosDB Tabelle indizierungsrichtlinie</span><span class="sxs-lookup"><span data-stu-id="2b698-326">CosmosDB table indexing policy</span></span></param>
        <param name="throughput"><span data-ttu-id="2b698-327">CosmosDB Tabelle Durchsatz</span><span class="sxs-lookup"><span data-stu-id="2b698-327">CosmosDB table throughput</span></span></param>
        <summary>
            <span data-ttu-id="2b698-328">Erstellt eine Tabelle.</span><span class="sxs-lookup"><span data-stu-id="2b698-328">Creates a table.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudTable.CreateAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2b698-329">Initiiert einen asynchronen Vorgang zum Erstellen einer Tabelle.</span><span class="sxs-lookup"><span data-stu-id="2b698-329">Initiates an asynchronous operation to create a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-330">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-330">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.CreateAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="2b698-331">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-331">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-332">Initiiert einen asynchronen Vorgang zum Erstellen einer Tabelle.</span><span class="sxs-lookup"><span data-stu-id="2b698-332">Initiates an asynchronous operation to create a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-333">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-333">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudTable.CreateAsync (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="2b698-334">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-334">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-335">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-335">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-336">Initiiert einen asynchronen Vorgang zum Erstellen einer Tabelle.</span><span class="sxs-lookup"><span data-stu-id="2b698-336">Initiates an asynchronous operation to create a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-337">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-337">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.CreateAsync (requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="2b698-338">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-338">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-339">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-339">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b698-340">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-340">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-341">Initiiert einen asynchronen Vorgang zum Erstellen einer Tabelle.</span><span class="sxs-lookup"><span data-stu-id="2b698-341">Initiates an asynchronous operation to create a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-342">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-342">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (Nullable&lt;int&gt; throughput, Microsoft.Azure.CosmosDB.IndexingMode indexingMode, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(valuetype System.Nullable`1&lt;int32&gt; throughput, valuetype Microsoft.Azure.CosmosDB.IndexingMode indexingMode, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateAsync(System.Nullable{System.Int32},Microsoft.Azure.CosmosDB.IndexingMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Nullable&lt;int&gt; * Microsoft.Azure.CosmosDB.IndexingMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : Nullable&lt;int&gt; * Microsoft.Azure.CosmosDB.IndexingMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.CreateAsync (throughput, indexingMode, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="indexingMode" Type="Microsoft.Azure.CosmosDB.IndexingMode" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="throughput"><span data-ttu-id="2b698-343">CosmosDB Tabelle Durchsatz</span><span class="sxs-lookup"><span data-stu-id="2b698-343">CosmosDB table throughput</span></span></param>
        <param name="indexingMode"><span data-ttu-id="2b698-344">Geben Sie indizierungsmodus für CosmosDB-Tabelle</span><span class="sxs-lookup"><span data-stu-id="2b698-344">Specify indexing mode for CosmosDB table</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b698-345">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-345">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-346">Initiiert einen asynchronen Vorgang zum Erstellen einer Tabelle.</span><span class="sxs-lookup"><span data-stu-id="2b698-346">Initiates an asynchronous operation to create a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-347">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-347">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (Nullable&lt;int&gt; throughput, string serializedindexingPolicy, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(valuetype System.Nullable`1&lt;int32&gt; throughput, string serializedindexingPolicy, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateAsync(System.Nullable{System.Int32},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Nullable&lt;int&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : Nullable&lt;int&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.CreateAsync (throughput, serializedindexingPolicy, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="serializedindexingPolicy" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="throughput"><span data-ttu-id="2b698-348">CosmosDB Tabelle Durchsatz</span><span class="sxs-lookup"><span data-stu-id="2b698-348">CosmosDB table throughput</span></span></param>
        <param name="serializedindexingPolicy"><span data-ttu-id="2b698-349">CosmosDB Tabelle indizierungsrichtlinie</span><span class="sxs-lookup"><span data-stu-id="2b698-349">CosmosDB table indexing policy</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b698-350">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-350">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-351">Initiiert einen asynchronen Vorgang zum Erstellen einer Tabelle.</span><span class="sxs-lookup"><span data-stu-id="2b698-351">Initiates an asynchronous operation to create a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-352">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-352">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, Nullable&lt;int&gt; throughput, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, valuetype System.Nullable`1&lt;int32&gt; throughput, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.CreateAsync (requestOptions, operationContext, serializedIndexingPolicy, throughput, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="serializedIndexingPolicy" Type="System.String" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="2b698-353">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-353">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-354">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-354">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="serializedIndexingPolicy"><span data-ttu-id="2b698-355">CosmosDB Tabelle indizierungsrichtlinie</span><span class="sxs-lookup"><span data-stu-id="2b698-355">CosmosDB table indexing policy</span></span></param>
        <param name="throughput"><span data-ttu-id="2b698-356">CosmosDB Tabelle Durchsatz</span><span class="sxs-lookup"><span data-stu-id="2b698-356">CosmosDB table throughput</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b698-357">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-357">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-358">Initiiert einen asynchronen Vorgang zum Erstellen einer Tabelle.</span><span class="sxs-lookup"><span data-stu-id="2b698-358">Initiates an asynchronous operation to create a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-359">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-359">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual bool CreateIfNotExists (Microsoft.Azure.CosmosDB.IndexingMode indexingMode, Nullable&lt;int&gt; throughput = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool CreateIfNotExists(valuetype Microsoft.Azure.CosmosDB.IndexingMode indexingMode, valuetype System.Nullable`1&lt;int32&gt; throughput) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateIfNotExists(Microsoft.Azure.CosmosDB.IndexingMode,System.Nullable{System.Int32})" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExists : Microsoft.Azure.CosmosDB.IndexingMode * Nullable&lt;int&gt; -&gt; bool&#xA;override this.CreateIfNotExists : Microsoft.Azure.CosmosDB.IndexingMode * Nullable&lt;int&gt; -&gt; bool" Usage="cloudTable.CreateIfNotExists (indexingMode, throughput)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="indexingMode" Type="Microsoft.Azure.CosmosDB.IndexingMode" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="indexingMode"><span data-ttu-id="2b698-360">CosmosDB Tabelle indizierungsmodus</span><span class="sxs-lookup"><span data-stu-id="2b698-360">CosmosDB table indexing mode</span></span></param>
        <param name="throughput"><span data-ttu-id="2b698-361">CosmosDB Tabelle Durchsatz</span><span class="sxs-lookup"><span data-stu-id="2b698-361">CosmosDB table throughput</span></span></param>
        <summary>
            <span data-ttu-id="2b698-362">Erstellt die Tabelle aus, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-362">Creates the table if it does not already exist.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="2b698-363"><c>"true"</c> Wenn Tabelle erstellt; andernfalls wurde, <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-363"><c>true</c> if table was created; otherwise, <c>false</c>.</span></span></returns>
        <remarks><span data-ttu-id="2b698-364">Diese API führt eine Überprüfung auf Vorhandensein und erfordert daher Listenberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="2b698-364">This API performs an existence check and therefore requires list permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual bool CreateIfNotExists (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null, string serializedIndexingPolicy = null, Nullable&lt;int&gt; throughput = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool CreateIfNotExists(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, valuetype System.Nullable`1&lt;int32&gt; throughput) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateIfNotExists(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; -&gt; bool&#xA;override this.CreateIfNotExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; -&gt; bool" Usage="cloudTable.CreateIfNotExists (requestOptions, operationContext, serializedIndexingPolicy, throughput)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="serializedIndexingPolicy" Type="System.String" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="2b698-365">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-365">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-366">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-366">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="serializedIndexingPolicy"><span data-ttu-id="2b698-367">CosmosDB Tabelle indizierungsrichtlinie</span><span class="sxs-lookup"><span data-stu-id="2b698-367">CosmosDB table indexing policy</span></span></param>
        <param name="throughput"><span data-ttu-id="2b698-368">CosmosDB Tabelle Durchsatz</span><span class="sxs-lookup"><span data-stu-id="2b698-368">CosmosDB table throughput</span></span></param>
        <summary>
            <span data-ttu-id="2b698-369">Erstellt die Tabelle aus, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-369">Creates the table if it does not already exist.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="2b698-370"><c>"true"</c> Wenn Tabelle erstellt; andernfalls wurde, <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-370"><c>true</c> if table was created; otherwise, <c>false</c>.</span></span></returns>
        <remarks><span data-ttu-id="2b698-371">Diese API führt eine Überprüfung auf Vorhandensein und erfordert daher Listenberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="2b698-371">This API performs an existence check and therefore requires list permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateIfNotExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateIfNotExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.CreateIfNotExistsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2b698-372">Initiiert einen asynchronen Vorgang zum Erstellen einer Tabelle, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-372">Initiates an asynchronous operation to create a table if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-373">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-373">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="2b698-374">Diese API führt eine Überprüfung auf Vorhandensein und erfordert daher Listenberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="2b698-374">This API performs an existence check and therefore requires list permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateIfNotExistsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.CreateIfNotExistsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="2b698-375">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-375">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-376">Initiiert einen asynchronen Vorgang zum Erstellen einer Tabelle, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-376">Initiates an asynchronous operation to create a table if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-377">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-377">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="2b698-378">Diese API führt eine Überprüfung auf Vorhandensein und erfordert daher Listenberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="2b698-378">This API performs an existence check and therefore requires list permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateIfNotExistsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.CreateIfNotExistsAsync (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="2b698-379">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-379">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-380">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-380">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-381">Initiiert einen asynchronen Vorgang zum Erstellen einer Tabelle, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-381">Initiates an asynchronous operation to create a table if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-382">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-382">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="2b698-383">Diese API führt eine Überprüfung auf Vorhandensein und erfordert daher Listenberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="2b698-383">This API performs an existence check and therefore requires list permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (Microsoft.Azure.CosmosDB.IndexingMode indexingMode, Nullable&lt;int&gt; throughput, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(valuetype Microsoft.Azure.CosmosDB.IndexingMode indexingMode, valuetype System.Nullable`1&lt;int32&gt; throughput, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateIfNotExistsAsync(Microsoft.Azure.CosmosDB.IndexingMode,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : Microsoft.Azure.CosmosDB.IndexingMode * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : Microsoft.Azure.CosmosDB.IndexingMode * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.CreateIfNotExistsAsync (indexingMode, throughput, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="indexingMode" Type="Microsoft.Azure.CosmosDB.IndexingMode" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="indexingMode"><span data-ttu-id="2b698-384">CosmosDB Tabelle indizierungsmodus</span><span class="sxs-lookup"><span data-stu-id="2b698-384">CosmosDB table indexing mode</span></span></param>
        <param name="throughput"><span data-ttu-id="2b698-385">CosmosDB Tabelle Durchsatz</span><span class="sxs-lookup"><span data-stu-id="2b698-385">CosmosDB table throughput</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b698-386">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-386">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-387">Initiiert einen asynchronen Vorgang zum Erstellen einer Tabelle, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-387">Initiates an asynchronous operation to create a table if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-388">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-388">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="2b698-389">Diese API führt eine Überprüfung auf Vorhandensein und erfordert daher Listenberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="2b698-389">This API performs an existence check and therefore requires list permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateIfNotExistsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.CreateIfNotExistsAsync (requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="2b698-390">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-390">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-391">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-391">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b698-392">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-392">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-393">Initiiert einen asynchronen Vorgang zum Erstellen einer Tabelle, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-393">Initiates an asynchronous operation to create a table if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-394">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-394">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="2b698-395">Diese API führt eine Überprüfung auf Vorhandensein und erfordert daher Listenberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="2b698-395">This API performs an existence check and therefore requires list permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, Nullable&lt;int&gt; throughput, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, valuetype System.Nullable`1&lt;int32&gt; throughput, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateIfNotExistsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.CreateIfNotExistsAsync (requestOptions, operationContext, serializedIndexingPolicy, throughput, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="serializedIndexingPolicy" Type="System.String" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="2b698-396">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-396">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-397">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-397">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="serializedIndexingPolicy"><span data-ttu-id="2b698-398">CosmosDB Tabelle indizierungsrichtlinie</span><span class="sxs-lookup"><span data-stu-id="2b698-398">CosmosDB table indexing policy</span></span></param>
        <param name="throughput"><span data-ttu-id="2b698-399">CosmosDB Tabelle Durchsatz</span><span class="sxs-lookup"><span data-stu-id="2b698-399">CosmosDB table throughput</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b698-400">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-400">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-401">Initiiert einen asynchronen Vorgang zum Erstellen einer Tabelle, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-401">Initiates an asynchronous operation to create a table if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-402">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-402">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="2b698-403">Diese API führt eine Überprüfung auf Vorhandensein und erfordert daher Listenberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="2b698-403">This API performs an existence check and therefore requires list permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQuery&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; CreateQuery&lt;TElement&gt; () where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; CreateQuery&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateQuery``1" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateQuery(Of TElement As {ITableEntityNew}) () As TableQuery(Of TElement)" />
      <MemberSignature Language="F#" Value="abstract member CreateQuery : unit -&gt; Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.CreateQuery : unit -&gt; Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.CreateQuery " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="2b698-404">Der Entitätstyp der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-404">The entity type of the query.</span></span></typeparam>
        <summary>
            <span data-ttu-id="2b698-405">Eine Factorymethode, die eine Abfrage erstellt, kann mithilfe von LINQ geändert werden.</span><span class="sxs-lookup"><span data-stu-id="2b698-405">A factory method that creates a query that can be modified using LINQ.</span></span> <span data-ttu-id="2b698-406">Die Abfrage kann ausgeführt werden, anschließend mithilfe einer der Ausführungsmethoden zur <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" />, wie z. B. <see cref="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuery(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />, <see cref="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmented(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />, oder <see cref="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="2b698-406">The query may be subsequently executed using one of the execution methods available for <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" />, such as <see cref="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuery(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />, <see cref="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmented(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />, or <see cref="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-407">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> -Objekt, für den Typ spezialisiert <c>TElement</c>, wiederholt ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="2b698-407">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> object, specialized for type <c>TElement</c>, that may subsequently be executed.</span></span></returns>
        <remarks>
            <span data-ttu-id="2b698-408">Die <see cref="N:Microsoft.Azure.CosmosDB.Table.Queryable" /> Namespace enthält Erweiterungsmethoden für die <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Objekts, einschließlich <see cref="M:WithOptions" />, <see cref="M:WithContext" />, und <see cref="M:AsTableQuery" />.</span><span class="sxs-lookup"><span data-stu-id="2b698-408">The <see cref="N:Microsoft.Azure.CosmosDB.Table.Queryable" /> namespace includes extension methods for the <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> object, including <see cref="M:WithOptions" />, <see cref="M:WithContext" />, and <see cref="M:AsTableQuery" />.</span></span> <span data-ttu-id="2b698-409">Um diese Methoden verwenden, schließen Sie eine <c>mit</c> -Anweisung, verweist der <see cref="N:Microsoft.Azure.CosmosDB.Table.Queryable" /> Namespace.</span><span class="sxs-lookup"><span data-stu-id="2b698-409">To use these methods, include a <c>using</c> statement that references the <see cref="N:Microsoft.Azure.CosmosDB.Table.Queryable" /> namespace.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public virtual void Delete (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Delete(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.Delete(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Delete : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; unit&#xA;override this.Delete : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; unit" Usage="cloudTable.Delete (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="2b698-410">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-410">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-411">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-411">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-412">Löscht eine Tabelle.</span><span class="sxs-lookup"><span data-stu-id="2b698-412">Deletes a table.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.DeleteAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DeleteAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudTable.DeleteAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2b698-413">Initiiert einen asynchronen Vorgang zum Löschen einer Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-413">Initiates an asynchronous operation to delete a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-414">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-414">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.DeleteAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.DeleteAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="2b698-415">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-415">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-416">Initiiert einen asynchronen Vorgang zum Löschen einer Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-416">Initiates an asynchronous operation to delete a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-417">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-417">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.DeleteAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudTable.DeleteAsync (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="2b698-418">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-418">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-419">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-419">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-420">Initiiert einen asynchronen Vorgang zum Löschen einer Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-420">Initiates an asynchronous operation to delete a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-421">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-421">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.DeleteAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.DeleteAsync (requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="2b698-422">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-422">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-423">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-423">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b698-424">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-424">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-425">Initiiert einen asynchronen Vorgang zum Löschen einer Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-425">Initiates an asynchronous operation to delete a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-426">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-426">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual bool DeleteIfExists (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool DeleteIfExists(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.DeleteIfExists(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; bool&#xA;override this.DeleteIfExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; bool" Usage="cloudTable.DeleteIfExists (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="2b698-427">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-427">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-428">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-428">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-429">Löscht die Tabelle aus, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2b698-429">Deletes the table if it exists.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="2b698-430"><c>"true"</c> , wenn die Tabelle gelöscht; andernfalls wurde, <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-430"><c>true</c> if the table was deleted; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.DeleteIfExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DeleteIfExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.DeleteIfExistsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2b698-431">Initiiert einen asynchronen Vorgang zum Löschen der Tabelle, sofern vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2b698-431">Initiates an asynchronous operation to delete the table if it exists.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-432">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-432">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.DeleteIfExistsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.DeleteIfExistsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="2b698-433">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-433">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-434">Initiiert einen asynchronen Vorgang zum Löschen der Tabelle, sofern vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2b698-434">Initiates an asynchronous operation to delete the table if it exists.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-435">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-435">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.DeleteIfExistsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.DeleteIfExistsAsync (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="2b698-436">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-436">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-437">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-437">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-438">Initiiert einen asynchronen Vorgang zum Löschen der Tabelle, sofern vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2b698-438">Initiates an asynchronous operation to delete the table if it exists.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-439">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-439">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.DeleteIfExistsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.DeleteIfExistsAsync (requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="2b698-440">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-440">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-441">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-441">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b698-442">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-442">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-443">Initiiert einen asynchronen Vorgang zum Löschen der Tabelle, sofern vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2b698-443">Initiates an asynchronous operation to delete the table if it exists.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-444">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-444">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndCreate">
      <MemberSignature Language="C#" Value="public virtual void EndCreate (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndCreate(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndCreate(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndCreate (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndCreate : IAsyncResult -&gt; unit&#xA;override this.EndCreate : IAsyncResult -&gt; unit" Usage="cloudTable.EndCreate asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="2b698-445">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-445">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-446">Beendet einen asynchronen Vorgang zum Erstellen einer Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-446">Ends an asynchronous operation to create a table.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual bool EndCreateIfNotExists (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool EndCreateIfNotExists(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndCreateIfNotExists(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndCreateIfNotExists (asyncResult As IAsyncResult) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member EndCreateIfNotExists : IAsyncResult -&gt; bool&#xA;override this.EndCreateIfNotExists : IAsyncResult -&gt; bool" Usage="cloudTable.EndCreateIfNotExists asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="2b698-447">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-447">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-448">Beendet einen asynchronen Vorgang zum Erstellen einer Tabelle, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-448">Ends an asynchronous operation to create a table if it does not already exist.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="2b698-449"><c>"true"</c> Wenn Tabelle erstellt; andernfalls wurde, <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-449"><c>true</c> if table was created; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDelete">
      <MemberSignature Language="C#" Value="public virtual void EndDelete (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndDelete(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndDelete(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndDelete (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndDelete : IAsyncResult -&gt; unit&#xA;override this.EndDelete : IAsyncResult -&gt; unit" Usage="cloudTable.EndDelete asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="2b698-450">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-450">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-451">Beendet einen asynchronen Vorgang zum Löschen einer Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-451">Ends an asynchronous operation to delete a table.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual bool EndDeleteIfExists (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool EndDeleteIfExists(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndDeleteIfExists(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndDeleteIfExists (asyncResult As IAsyncResult) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member EndDeleteIfExists : IAsyncResult -&gt; bool&#xA;override this.EndDeleteIfExists : IAsyncResult -&gt; bool" Usage="cloudTable.EndDeleteIfExists asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="2b698-452">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-452">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-453">Beendet einen asynchronen Vorgang zum Löschen der Tabelle, sofern vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2b698-453">Ends an asynchronous operation to delete the table if it exists.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="2b698-454"><c>"true"</c> , wenn die Tabelle gelöscht; andernfalls wurde, <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-454"><c>true</c> if the table was deleted; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExecute">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableResult EndExecute (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableResult EndExecute(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndExecute(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExecute (asyncResult As IAsyncResult) As TableResult" />
      <MemberSignature Language="F#" Value="abstract member EndExecute : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableResult&#xA;override this.EndExecute : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableResult" Usage="cloudTable.EndExecute asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="2b698-455">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-455">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-456">Beendet die Ausführung einer asynchronen Table-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="2b698-456">Ends execution of an asynchronous table operation.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-457">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> , die das Ergebnis der Ausführung des Vorgangs für die Tabelle enthält.</span><span class="sxs-lookup"><span data-stu-id="2b698-457">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> containing the result executing the operation on the table.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExecuteBatch">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt; EndExecuteBatch (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt; EndExecuteBatch(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndExecuteBatch(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExecuteBatch (asyncResult As IAsyncResult) As IList(Of TableResult)" />
      <MemberSignature Language="F#" Value="abstract member EndExecuteBatch : IAsyncResult -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&#xA;override this.EndExecuteBatch : IAsyncResult -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;" Usage="cloudTable.EndExecuteBatch asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="2b698-458">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-458">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-459">Beendet einen asynchronen Vorgang zum Ausführen eines Batches von Vorgängen für eine Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-459">Ends an asynchronous operation to execute a batch of operations on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-460">Eine aufzählbare Auflistung vom Typ <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> , enthält die Ergebnisse in der Reihenfolge jedes Vorgangs in der <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> für die Tabelle.</span><span class="sxs-lookup"><span data-stu-id="2b698-460">A enumerable collection of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> that contains the results, in order, of each operation in the <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> on the table.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExecuteQueryForKeyRotationSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt; EndExecuteQueryForKeyRotationSegmented (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt; EndExecuteQueryForKeyRotationSegmented(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndExecuteQueryForKeyRotationSegmented(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExecuteQueryForKeyRotationSegmented (asyncResult As IAsyncResult) As TableQuerySegment(Of KeyRotationEntity)" />
      <MemberSignature Language="F#" Value="abstract member EndExecuteQueryForKeyRotationSegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&#xA;override this.EndExecuteQueryForKeyRotationSegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;" Usage="cloudTable.EndExecuteQueryForKeyRotationSegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="2b698-461">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-461">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-462">Beendet eine asynchrone segmentierte Abfrage für eine Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-462">Ends an asynchronous segmented query on a table.</span></span> 
            </summary>
        <returns><span data-ttu-id="2b698-463">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" /> , die die Ergebnisse der Ausführung der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-463">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" /> containing the results of executing the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExecuteQuerySegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt; EndExecuteQuerySegmented (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt; EndExecuteQuerySegmented(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndExecuteQuerySegmented(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExecuteQuerySegmented (asyncResult As IAsyncResult) As TableQuerySegment(Of DynamicTableEntity)" />
      <MemberSignature Language="F#" Value="abstract member EndExecuteQuerySegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&#xA;override this.EndExecuteQuerySegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;" Usage="cloudTable.EndExecuteQuerySegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="2b698-464">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-464">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-465">Beendet eine asynchrone segmentierte Abfrage für eine Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-465">Ends an asynchronous segmented query on a table.</span></span> 
            </summary>
        <returns><span data-ttu-id="2b698-466">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> , die die Ergebnisse der Ausführung der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-466">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> containing the results of executing the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExecuteQuerySegmented&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt; EndExecuteQuerySegmented&lt;TResult&gt; (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt; EndExecuteQuerySegmented&lt;TResult&gt;(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndExecuteQuerySegmented``1(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExecuteQuerySegmented(Of TResult) (asyncResult As IAsyncResult) As TableQuerySegment(Of TResult)" />
      <MemberSignature Language="F#" Value="abstract member EndExecuteQuerySegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&#xA;override this.EndExecuteQuerySegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;" Usage="cloudTable.EndExecuteQuerySegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <typeparam name="TResult"><span data-ttu-id="2b698-467">Der Typ der zurückzugebenden Ergebnisse.</span><span class="sxs-lookup"><span data-stu-id="2b698-467">The type of the results to be returned.</span></span> <span data-ttu-id="2b698-468">Der Entitätstyp angegeben, die in den BEGIN- oder der Ergebnistyp des Konfliktlösers möglich</span><span class="sxs-lookup"><span data-stu-id="2b698-468">Can be the entity type specified in the Begin or the result type of the resolver</span></span></typeparam>
        <param name="asyncResult"><span data-ttu-id="2b698-469">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-469">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-470">Beendet einen asynchronen Vorgang zum Abfragen einer Tabelle im segmentierten Modus.</span><span class="sxs-lookup"><span data-stu-id="2b698-470">Ends an asynchronous operation to query a table in segmented mode.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-471">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , die die Ergebnisse der Ausführung der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-471">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> containing the results of executing the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExecuteQuerySegmented&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt; EndExecuteQuerySegmented&lt;TElement,TResult&gt; (IAsyncResult asyncResult) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt; EndExecuteQuerySegmented&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement, TResult&gt;(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndExecuteQuerySegmented``2(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExecuteQuerySegmented(Of TElement As {ITableEntityNew}, TResult As {ITableEntityNew}) (asyncResult As IAsyncResult) As TableQuerySegment(Of TResult)" />
      <MemberSignature Language="F#" Value="abstract member EndExecuteQuerySegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.EndExecuteQuerySegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.EndExecuteQuerySegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="2b698-472">Der Entitätstyp der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-472">The entity type of the query.</span></span></typeparam>
        <typeparam name="TResult"><span data-ttu-id="2b698-473">Der Typ, in dem <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> projiziert die Ergebnisse der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-473">The type into which the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> will project the query results.</span></span></typeparam>
        <param name="asyncResult"><span data-ttu-id="2b698-474">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-474">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-475">Beendet einen asynchronen Vorgang zum Ausführen einer Abfrage im segmentierten Modus.</span><span class="sxs-lookup"><span data-stu-id="2b698-475">Ends an asynchronous operation to execute a query in segmented mode.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-476">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , enthält die Projektion in den Typ <c>TResult</c> der Ergebnisse der Ausführung der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-476">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> containing the projection into type <c>TResult</c> of the results of executing the query.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExists">
      <MemberSignature Language="C#" Value="public virtual bool EndExists (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool EndExists(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndExists(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExists (asyncResult As IAsyncResult) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member EndExists : IAsyncResult -&gt; bool&#xA;override this.EndExists : IAsyncResult -&gt; bool" Usage="cloudTable.EndExists asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="2b698-477">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-477">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-478">Beendet einen asynchronen Vorgang, um festzustellen, ob eine Tabelle vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-478">Ends an asynchronous operation to determine whether a table exists.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="2b698-479"><c>"true"</c> Wenn Tabelle vorhanden ist; andernfalls <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-479"><c>true</c> if table exists; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TablePermissions EndGetPermissions (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TablePermissions EndGetPermissions(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndGetPermissions(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetPermissions (asyncResult As IAsyncResult) As TablePermissions" />
      <MemberSignature Language="F#" Value="abstract member EndGetPermissions : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TablePermissions&#xA;override this.EndGetPermissions : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TablePermissions" Usage="cloudTable.EndGetPermissions asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TablePermissions</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="2b698-480">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-480">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-481">Das asynchrone Ergebnis der Anforderung zum Abrufen der berechtigungseinstellungen für die Tabelle zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="2b698-481">Returns the asynchronous result of the request to get the permissions settings for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-482">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="2b698-482">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetPermissions">
      <MemberSignature Language="C#" Value="public virtual void EndSetPermissions (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetPermissions(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndSetPermissions(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetPermissions (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetPermissions : IAsyncResult -&gt; unit&#xA;override this.EndSetPermissions : IAsyncResult -&gt; unit" Usage="cloudTable.EndSetPermissions asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="2b698-483">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="2b698-483">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-484">Das asynchrone Ergebnis der Anforderung zum Abrufen der berechtigungseinstellungen für die Tabelle zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="2b698-484">Returns the asynchronous result of the request to get the permissions settings for the table.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Execute">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableResult Execute (Microsoft.Azure.CosmosDB.Table.TableOperation operation, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableResult Execute(class Microsoft.Azure.CosmosDB.Table.TableOperation operation, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.Execute(Microsoft.Azure.CosmosDB.Table.TableOperation,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Execute : Microsoft.Azure.CosmosDB.Table.TableOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableResult&#xA;override this.Execute : Microsoft.Azure.CosmosDB.Table.TableOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableResult" Usage="cloudTable.Execute (operation, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operation" Type="Microsoft.Azure.CosmosDB.Table.TableOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="operation"><span data-ttu-id="2b698-485">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> Objekt, das den auszuführenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-485">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> object that represents the operation to perform.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-486">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-486">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-487">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-487">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-488">Führt einen Vorgang für eine Tabelle.</span><span class="sxs-lookup"><span data-stu-id="2b698-488">Executes an operation on a table.</span></span>  
            </summary>
        <returns><span data-ttu-id="2b698-489">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="2b698-489">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteAsync (Microsoft.Azure.CosmosDB.Table.TableOperation operation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteAsync(class Microsoft.Azure.CosmosDB.Table.TableOperation operation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteAsync(Microsoft.Azure.CosmosDB.Table.TableOperation)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteAsync (operation As TableOperation) As Task(Of TableResult)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteAsync : Microsoft.Azure.CosmosDB.Table.TableOperation -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&#xA;override this.ExecuteAsync : Microsoft.Azure.CosmosDB.Table.TableOperation -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;" Usage="cloudTable.ExecuteAsync operation" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operation" Type="Microsoft.Azure.CosmosDB.Table.TableOperation" />
      </Parameters>
      <Docs>
        <param name="operation"><span data-ttu-id="2b698-490">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> Objekt, das den auszuführenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-490">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> object that represents the operation to perform.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-491">Initiiert einen asynchronen Vorgang, der einen asynchronen Table-Vorgang ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="2b698-491">Initiates an asynchronous operation that executes an asynchronous table operation.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-492">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-492">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteAsync (Microsoft.Azure.CosmosDB.Table.TableOperation operation, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteAsync(class Microsoft.Azure.CosmosDB.Table.TableOperation operation, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteAsync(Microsoft.Azure.CosmosDB.Table.TableOperation,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteAsync : Microsoft.Azure.CosmosDB.Table.TableOperation * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&#xA;override this.ExecuteAsync : Microsoft.Azure.CosmosDB.Table.TableOperation * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;" Usage="cloudTable.ExecuteAsync (operation, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operation" Type="Microsoft.Azure.CosmosDB.Table.TableOperation" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operation"><span data-ttu-id="2b698-493">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> Objekt, das den auszuführenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-493">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> object that represents the operation to perform.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b698-494">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-494">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-495">Initiiert einen asynchronen Vorgang, der einen asynchronen Table-Vorgang ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="2b698-495">Initiates an asynchronous operation that executes an asynchronous table operation.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-496">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-496">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteAsync (Microsoft.Azure.CosmosDB.Table.TableOperation operation, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteAsync(class Microsoft.Azure.CosmosDB.Table.TableOperation operation, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteAsync(Microsoft.Azure.CosmosDB.Table.TableOperation,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteAsync : Microsoft.Azure.CosmosDB.Table.TableOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&#xA;override this.ExecuteAsync : Microsoft.Azure.CosmosDB.Table.TableOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;" Usage="cloudTable.ExecuteAsync (operation, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operation" Type="Microsoft.Azure.CosmosDB.Table.TableOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="operation"><span data-ttu-id="2b698-497">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> Objekt, das den auszuführenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-497">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> object that represents the operation to perform.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-498">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-498">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-499">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-499">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-500">Initiiert einen asynchronen Vorgang, der einen asynchronen Table-Vorgang ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="2b698-500">Initiates an asynchronous operation that executes an asynchronous table operation.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-501">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-501">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteAsync (Microsoft.Azure.CosmosDB.Table.TableOperation operation, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteAsync(class Microsoft.Azure.CosmosDB.Table.TableOperation operation, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteAsync(Microsoft.Azure.CosmosDB.Table.TableOperation,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteAsync : Microsoft.Azure.CosmosDB.Table.TableOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&#xA;override this.ExecuteAsync : Microsoft.Azure.CosmosDB.Table.TableOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;" Usage="cloudTable.ExecuteAsync (operation, requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operation" Type="Microsoft.Azure.CosmosDB.Table.TableOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operation"><span data-ttu-id="2b698-502">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> Objekt, das den auszuführenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-502">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> object that represents the operation to perform.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-503">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-503">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-504">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-504">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b698-505">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-505">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-506">Initiiert einen asynchronen Vorgang, der einen asynchronen Table-Vorgang ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="2b698-506">Initiates an asynchronous operation that executes an asynchronous table operation.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-507">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-507">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteBatch">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteBatch (Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteBatch(class Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteBatch(Microsoft.Azure.CosmosDB.Table.TableBatchOperation,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteBatch : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&#xA;override this.ExecuteBatch : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;" Usage="cloudTable.ExecuteBatch (batch, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="batch"><span data-ttu-id="2b698-508">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> Objekt, das die Vorgänge zum Ausführen für die Tabelle darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-508">The <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> object representing the operations to execute on the table.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-509">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-509">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-510">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-510">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-511">Führt einen Batchvorgang für eine Tabelle als atomarer Vorgang.</span><span class="sxs-lookup"><span data-stu-id="2b698-511">Executes a batch operation on a table as an atomic operation.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-512">Eine aufzählbare Auflistung von <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> Objekte, die die Ergebnisse jedes Vorgangs im nacheinander enthält die <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> für die Tabelle.</span><span class="sxs-lookup"><span data-stu-id="2b698-512">An enumerable collection of <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> objects that contains the results, in order, of each operation in the <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> on the table.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteBatchAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt; ExecuteBatchAsync (Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt; ExecuteBatchAsync(class Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteBatchAsync(Microsoft.Azure.CosmosDB.Table.TableBatchOperation)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteBatchAsync (batch As TableBatchOperation) As Task(Of IList(Of TableResult))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteBatchAsync : Microsoft.Azure.CosmosDB.Table.TableBatchOperation -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;&#xA;override this.ExecuteBatchAsync : Microsoft.Azure.CosmosDB.Table.TableBatchOperation -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;" Usage="cloudTable.ExecuteBatchAsync batch" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />
      </Parameters>
      <Docs>
        <param name="batch"><span data-ttu-id="2b698-513">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> Objekt, das die Vorgänge zum Ausführen für die Tabelle darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-513">The <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> object representing the operations to execute on the table.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-514">Initiiert einen asynchronen Vorgang zum Ausführen eines Batches von Vorgängen für eine Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-514">Initiates an asynchronous operation to execute a batch of operations on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-515">Ein <see cref="T:System.Threading.Tasks.Task`1" /> -Objekt, das eine Liste vom Typ <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-515">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is list of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteBatchAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt; ExecuteBatchAsync (Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt; ExecuteBatchAsync(class Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteBatchAsync(Microsoft.Azure.CosmosDB.Table.TableBatchOperation,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteBatchAsync : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;&#xA;override this.ExecuteBatchAsync : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;" Usage="cloudTable.ExecuteBatchAsync (batch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="batch"><span data-ttu-id="2b698-516">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> Objekt, das die Vorgänge zum Ausführen für die Tabelle darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-516">The <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> object representing the operations to execute on the table.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b698-517">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-517">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-518">Initiiert einen asynchronen Vorgang zum Ausführen eines Batches von Vorgängen für eine Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-518">Initiates an asynchronous operation to execute a batch of operations on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-519">Ein <see cref="T:System.Threading.Tasks.Task`1" /> -Objekt, das eine Liste vom Typ <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-519">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is list of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteBatchAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt; ExecuteBatchAsync (Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt; ExecuteBatchAsync(class Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteBatchAsync(Microsoft.Azure.CosmosDB.Table.TableBatchOperation,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteBatchAsync : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;&#xA;override this.ExecuteBatchAsync : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;" Usage="cloudTable.ExecuteBatchAsync (batch, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="batch"><span data-ttu-id="2b698-520">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> Objekt, das die Vorgänge zum Ausführen für die Tabelle darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-520">The <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> object representing the operations to execute on the table.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-521">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-521">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-522">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-522">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-523">Initiiert einen asynchronen Vorgang zum Ausführen eines Batches von Vorgängen für eine Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-523">Initiates an asynchronous operation to execute a batch of operations on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-524">Ein <see cref="T:System.Threading.Tasks.Task`1" /> -Objekt, das eine Liste vom Typ <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-524">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is list of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteBatchAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt; ExecuteBatchAsync (Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt; ExecuteBatchAsync(class Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteBatchAsync(Microsoft.Azure.CosmosDB.Table.TableBatchOperation,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteBatchAsync : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;&#xA;override this.ExecuteBatchAsync : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;" Usage="cloudTable.ExecuteBatchAsync (batch, requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="batch"><span data-ttu-id="2b698-525">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> Objekt, das die Vorgänge zum Ausführen für die Tabelle darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-525">The <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> object representing the operations to execute on the table.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-526">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-526">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-527">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-527">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b698-528">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-528">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-529">Initiiert einen asynchronen Vorgang zum Ausführen eines Batches von Vorgängen für eine Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-529">Initiates an asynchronous operation to execute a batch of operations on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-530">Ein <see cref="T:System.Threading.Tasks.Task`1" /> -Objekt, das eine Liste vom Typ <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-530">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is list of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuery">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt; ExecuteQuery (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt; ExecuteQuery(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuery(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuery : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&#xA;override this.ExecuteQuery : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;" Usage="cloudTable.ExecuteQuery (query, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="2b698-531">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-531">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-532">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-532">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-533">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-533">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-534">Führt eine Abfrage für eine Tabelle und gibt eine aufzählbare Auflistung von <see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="2b698-534">Executes a query on a table and returns an enumerable collection of <see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> objects.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-535">Eine aufzählbare Auflistung von <see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> Objekten, die von der Abfrage zurückgegebenen Tabellenentitäten darstellen.</span><span class="sxs-lookup"><span data-stu-id="2b698-535">An enumerable collection of <see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> objects, representing table entities returned by the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuery&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;TElement&gt; ExecuteQuery&lt;TElement&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;!!TElement&gt; ExecuteQuery&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuery``1(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuery : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuery : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuery (query, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="2b698-536">Der Entitätstyp der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-536">The entity type of the query.</span></span></typeparam>
        <param name="query"><span data-ttu-id="2b698-537">Eine TableQuery-Instanz, die die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-537">A TableQuery instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-538">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-538">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-539">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-539">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-540">Führt eine Abfrage für eine Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-540">Executes a query on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-541">Eine aufzählbare Auflistung für den Typ spezialisiert <c>TElement</c>, der die Ergebnisse der Ausführung der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-541">An enumerable collection, specialized for type <c>TElement</c>, of the results of executing the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuery&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;TResult&gt; ExecuteQuery&lt;TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;!!TResult&gt; ExecuteQuery&lt;TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuery``1(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.EntityResolver{``0},Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuery : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;'Result&gt;&#xA;override this.ExecuteQuery : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;'Result&gt;" Usage="cloudTable.ExecuteQuery (query, resolver, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">To be added.</typeparam>
        <param name="query"><span data-ttu-id="2b698-542">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-542">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="resolver"><span data-ttu-id="2b698-543">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-543">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-544">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-544">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-545">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-545">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-546">Führt eine Abfrage für eine Tabelle, und wendet die angegebene <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> auf das Ergebnis.</span><span class="sxs-lookup"><span data-stu-id="2b698-546">Executes a query on a table and applies the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the result.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-547">Eine aufzählbare Auflistung, die mit der Projektion in den Typ <c>TResult</c>, der die Ergebnisse der Ausführung der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-547">An enumerable collection, containing the projection into type <c>TResult</c>, of the results of executing the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuery&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;TResult&gt; ExecuteQuery&lt;TElement,TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;!!TResult&gt; ExecuteQuery&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuery``2(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.EntityResolver{``1},Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuery : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;'Result&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuery : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;'Result&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuery (query, resolver, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="2b698-548">Der Entitätstyp der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-548">The entity type of the query.</span></span></typeparam>
        <typeparam name="TResult"><span data-ttu-id="2b698-549">Der Typ, in dem <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> projiziert die Ergebnisse der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-549">The type into which the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> will project the query results.</span></span></typeparam>
        <param name="query"><span data-ttu-id="2b698-550">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-550">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="resolver"><span data-ttu-id="2b698-551">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-551">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-552">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-552">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-553">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-553">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-554">Führt eine Abfrage aus und wendet die angegebene <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> auf das Ergebnis.</span><span class="sxs-lookup"><span data-stu-id="2b698-554">Executes a query and applies the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the result.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-555">Eine aufzählbare Auflistung, die mit der Projektion in den Typ <c>TResult</c>, der die Ergebnisse der Ausführung der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-555">An enumerable collection, containing the projection into type <c>TResult</c>, of the results of executing the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQueryForKeyRotation">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt; ExecuteQueryForKeyRotation (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt; ExecuteQueryForKeyRotation(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQueryForKeyRotation(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQueryForKeyRotation : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&#xA;override this.ExecuteQueryForKeyRotation : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;" Usage="cloudTable.ExecuteQueryForKeyRotation (query, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="2b698-556">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-556">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-557">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-557">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-558">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-558">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-559">Führt eine Abfrage für eine Tabelle und gibt eine aufzählbare Auflistung von <see cref="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="2b698-559">Executes a query on a table and returns an enumerable collection of <see cref="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" /> objects.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-560">Eine aufzählbare Auflistung von <see cref="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" /> Objekten, die von der Abfrage zurückgegebenen Tabellenentitäten darstellen.</span><span class="sxs-lookup"><span data-stu-id="2b698-560">An enumerable collection of <see cref="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" /> objects, representing table entities returned by the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQueryForKeyRotationSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt; ExecuteQueryForKeyRotationSegmented (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt; ExecuteQueryForKeyRotationSegmented(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQueryForKeyRotationSegmented(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQueryForKeyRotationSegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&#xA;override this.ExecuteQueryForKeyRotationSegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;" Usage="cloudTable.ExecuteQueryForKeyRotationSegmented (query, token, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="2b698-561">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-561">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-562">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-562">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-563">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-563">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-564">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-564">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-565">Führt eine segmentierte Abfrage für eine Tabelle aus und gibt eine <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> mit <see cref="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="2b698-565">Executes a segmented query on a table and returns a <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> containing <see cref="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" /> objects.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-566">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" /> , die die Ergebnisse der Ausführung der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-566">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" /> containing the results of executing the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQueryForKeyRotationSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQueryForKeyRotationSegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteQueryForKeyRotationSegmentedAsync (query As TableQuery, token As TableContinuationToken) As Task(Of TableQuerySegment(Of KeyRotationEntity))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;&#xA;override this.ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;" Usage="cloudTable.ExecuteQueryForKeyRotationSegmentedAsync (query, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="2b698-567">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-567">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-568">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-568">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-569">Initiiert einen asynchronen Vorgang, um eine segmentierte Abfrage für eine Tabelle auszuführen.</span><span class="sxs-lookup"><span data-stu-id="2b698-569">Initiates an asynchronous operation to perform a segmented query on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-570">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-570">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQueryForKeyRotationSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQueryForKeyRotationSegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;&#xA;override this.ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;" Usage="cloudTable.ExecuteQueryForKeyRotationSegmentedAsync (query, token, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="2b698-571">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-571">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-572">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-572">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b698-573">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-573">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-574">Initiiert einen asynchronen Vorgang, um eine segmentierte Abfrage für eine Tabelle auszuführen.</span><span class="sxs-lookup"><span data-stu-id="2b698-574">Initiates an asynchronous operation to perform a segmented query on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-575">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-575">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQueryForKeyRotationSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQueryForKeyRotationSegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;&#xA;override this.ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;" Usage="cloudTable.ExecuteQueryForKeyRotationSegmentedAsync (query, token, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="2b698-576">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-576">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-577">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-577">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-578">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-578">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-579">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-579">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-580">Initiiert einen asynchronen Vorgang, um eine segmentierte Abfrage für eine Tabelle auszuführen.</span><span class="sxs-lookup"><span data-stu-id="2b698-580">Initiates an asynchronous operation to perform a segmented query on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-581">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-581">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQueryForKeyRotationSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQueryForKeyRotationSegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;&#xA;override this.ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;" Usage="cloudTable.ExecuteQueryForKeyRotationSegmentedAsync (query, token, requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.CosmosDB.Table.CloudTable/&lt;ExecuteQueryForKeyRotationSegmentedAsync&gt;d__85))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="2b698-582">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-582">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-583">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-583">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-584">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-584">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-585">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-585">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b698-586">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-586">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-587">Initiiert einen asynchronen Vorgang, um eine segmentierte Abfrage für eine Tabelle auszuführen.</span><span class="sxs-lookup"><span data-stu-id="2b698-587">Initiates an asynchronous operation to perform a segmented query on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-588">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-588">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt; ExecuteQuerySegmented (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt; ExecuteQuerySegmented(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmented(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&#xA;override this.ExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;" Usage="cloudTable.ExecuteQuerySegmented (query, token, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="2b698-589">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-589">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-590">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-590">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-591">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-591">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-592">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-592">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-593">Führt eine segmentierte Abfrage für eine Tabelle aus und gibt eine <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> mit <see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="2b698-593">Executes a segmented query on a table and returns a <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> containing <see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> objects.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-594">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> , die die Ergebnisse der Ausführung der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-594">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> containing the results of executing the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmented&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt; ExecuteQuerySegmented&lt;TElement&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TElement&gt; ExecuteQuerySegmented&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmented``1(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmented (query, token, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="2b698-595">Der Entitätstyp der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-595">The entity type of the query.</span></span></typeparam>
        <param name="query"><span data-ttu-id="2b698-596">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-596">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-597">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-597">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-598">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-598">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-599">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-599">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-600">Führt eine Abfrage für eine Tabelle im segmentierten Modus.</span><span class="sxs-lookup"><span data-stu-id="2b698-600">Executes a query on a table in segmented mode.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-601">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />, für den Typ spezielle <c>TElement</c>, mit den Ergebnissen der Ausführung der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-601">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />, specialized for type <c>TElement</c>, containing the results of executing the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmented&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt; ExecuteQuerySegmented&lt;TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt; ExecuteQuerySegmented&lt;TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmented``1(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.EntityResolver{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&#xA;override this.ExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;" Usage="cloudTable.ExecuteQuerySegmented (query, resolver, token, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">To be added.</typeparam>
        <param name="query"><span data-ttu-id="2b698-602">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-602">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="resolver"><span data-ttu-id="2b698-603">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-603">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-604">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-604">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-605">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-605">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-606">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-606">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-607">Führt eine segmentierte Abfrage für eine Tabelle und wendet die angegebene <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> auf das Ergebnis.</span><span class="sxs-lookup"><span data-stu-id="2b698-607">Executes a segmented query on a table and applies the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the result.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-608">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> Objekt, das die Ergebnisse der Ausführung der Abfrage enthält.</span><span class="sxs-lookup"><span data-stu-id="2b698-608">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> object containing the results of executing the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmented&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt; ExecuteQuerySegmented&lt;TElement,TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt; ExecuteQuerySegmented&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmented``2(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.EntityResolver{``1},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmented (query, resolver, token, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="2b698-609">Der Entitätstyp der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-609">The entity type of the query.</span></span></typeparam>
        <typeparam name="TResult"><span data-ttu-id="2b698-610">Der Typ, in dem <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> projiziert die Ergebnisse der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-610">The type into which the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> will project the query results.</span></span></typeparam>
        <param name="query"><span data-ttu-id="2b698-611">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-611">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="resolver"><span data-ttu-id="2b698-612">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-612">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-613">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-613">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-614">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-614">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-615">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-615">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-616">Führt eine Abfrage im segmentierten Modus und wendet die angegebene <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> mit den Ergebnissen.</span><span class="sxs-lookup"><span data-stu-id="2b698-616">Executes a query in segmented mode and applies the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the results.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-617">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , enthält die Projektion in den Typ <c>TResult</c> der Ergebnisse der Ausführung der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-617">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> containing the projection into type <c>TResult</c> of the results of executing the query.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteQuerySegmentedAsync (query As TableQuery, token As TableContinuationToken) As Task(Of TableQuerySegment(Of DynamicTableEntity))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="2b698-618">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-618">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-619">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-619">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-620">Initiiert einen asynchronen Vorgang, um eine segmentierte Abfrage für eine Tabelle auszuführen.</span><span class="sxs-lookup"><span data-stu-id="2b698-620">Initiates an asynchronous operation to perform a segmented query on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-621">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-621">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="2b698-622">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-622">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-623">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-623">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b698-624">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-624">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-625">Initiiert einen asynchronen Vorgang, um eine segmentierte Abfrage für eine Tabelle auszuführen.</span><span class="sxs-lookup"><span data-stu-id="2b698-625">Initiates an asynchronous operation to perform a segmented query on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-626">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-626">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="2b698-627">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-627">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-628">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-628">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-629">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-629">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-630">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-630">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-631">Initiiert einen asynchronen Vorgang, um eine segmentierte Abfrage für eine Tabelle auszuführen.</span><span class="sxs-lookup"><span data-stu-id="2b698-631">Initiates an asynchronous operation to perform a segmented query on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-632">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-632">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token, requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="2b698-633">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-633">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-634">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-634">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-635">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-635">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-636">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-636">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b698-637">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-637">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-638">Initiiert einen asynchronen Vorgang, um eine segmentierte Abfrage für eine Tabelle auszuführen.</span><span class="sxs-lookup"><span data-stu-id="2b698-638">Initiates an asynchronous operation to perform a segmented query on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-639">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-639">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteQuerySegmentedAsync(Of TElement As {ITableEntityNew}) (query As TableQuery(Of TElement), token As TableContinuationToken) As Task(Of TableQuerySegment(Of TElement))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="2b698-640">Der Entitätstyp der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-640">The entity type of the query.</span></span></typeparam>
        <param name="query"><span data-ttu-id="2b698-641">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-641">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-642">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-642">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-643">Initiiert einen asynchronen Vorgang zum Abfragen einer Tabelle im segmentierten Modus.</span><span class="sxs-lookup"><span data-stu-id="2b698-643">Initiates an asynchronous operation to query a table in segmented mode.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-644">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-644">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, System.Threading.CancellationToken cancellationToken) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="2b698-645">Der Entitätstyp der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-645">The entity type of the query.</span></span></typeparam>
        <param name="query"><span data-ttu-id="2b698-646">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-646">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-647">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-647">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b698-648">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-648">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-649">Initiiert einen asynchronen Vorgang zum Abfragen einer Tabelle im segmentierten Modus.</span><span class="sxs-lookup"><span data-stu-id="2b698-649">Initiates an asynchronous operation to query a table in segmented mode.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-650">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-650">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="2b698-651">Der Entitätstyp der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-651">The entity type of the query.</span></span></typeparam>
        <param name="query"><span data-ttu-id="2b698-652">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-652">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-653">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-653">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-654">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-654">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-655">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-655">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-656">Initiiert einen asynchronen Vorgang zum Abfragen einer Tabelle im segmentierten Modus.</span><span class="sxs-lookup"><span data-stu-id="2b698-656">Initiates an asynchronous operation to query a table in segmented mode.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-657">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-657">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token, requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="2b698-658">Der Entitätstyp der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-658">The entity type of the query.</span></span></typeparam>
        <param name="query"><span data-ttu-id="2b698-659">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-659">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-660">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-660">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-661">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-661">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-662">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-662">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b698-663">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-663">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-664">Initiiert einen asynchronen Vorgang zum Abfragen einer Tabelle im segmentierten Modus.</span><span class="sxs-lookup"><span data-stu-id="2b698-664">Initiates an asynchronous operation to query a table in segmented mode.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-665">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-665">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.EntityResolver{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteQuerySegmentedAsync(Of TResult) (query As TableQuery, resolver As EntityResolver(Of TResult), token As TableContinuationToken) As Task(Of TableQuerySegment(Of TResult))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TResult"><span data-ttu-id="2b698-666">Der Typ, in dem <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> projiziert die Ergebnisse der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-666">The type into which the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> will project the query results.</span></span></typeparam>
        <param name="query"><span data-ttu-id="2b698-667">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz unter Angabe der Tabelle Abfragen ausgeführt und die Abfrageparameter verwendet.</span><span class="sxs-lookup"><span data-stu-id="2b698-667">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use.</span></span></param>
        <param name="resolver"><span data-ttu-id="2b698-668">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-668">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-669">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-669">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-670">Initiiert einen asynchronen Vorgang zum Ausführen einer Abfrage segmentierten und Anwenden der angegebenen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> auf das Ergebnis.</span><span class="sxs-lookup"><span data-stu-id="2b698-670">Initiates an asynchronous operation to execute a segmented query and apply the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the result.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-671">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-671">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.EntityResolver{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TResult"><span data-ttu-id="2b698-672">Der Typ, in dem <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> projiziert die Ergebnisse der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-672">The type into which the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> will project the query results.</span></span></typeparam>
        <param name="query"><span data-ttu-id="2b698-673">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz unter Angabe der Tabelle Abfragen ausgeführt und die Abfrageparameter verwendet.</span><span class="sxs-lookup"><span data-stu-id="2b698-673">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use.</span></span></param>
        <param name="resolver"><span data-ttu-id="2b698-674">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-674">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-675">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-675">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b698-676">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-676">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-677">Initiiert einen asynchronen Vorgang zum Ausführen einer Abfrage segmentierten und Anwenden der angegebenen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> auf das Ergebnis.</span><span class="sxs-lookup"><span data-stu-id="2b698-677">Initiates an asynchronous operation to execute a segmented query and apply the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the result.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-678">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-678">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.EntityResolver{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TResult"><span data-ttu-id="2b698-679">Der Typ, in dem <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> projiziert die Ergebnisse der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-679">The type into which the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> will project the query results.</span></span></typeparam>
        <param name="query"><span data-ttu-id="2b698-680">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz unter Angabe der Tabelle Abfragen ausgeführt und die Abfrageparameter verwendet.</span><span class="sxs-lookup"><span data-stu-id="2b698-680">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use.</span></span></param>
        <param name="resolver"><span data-ttu-id="2b698-681">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-681">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-682">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-682">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-683">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-683">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-684">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-684">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-685">Initiiert einen asynchronen Vorgang zum Ausführen einer Abfrage segmentierten und Anwenden der angegebenen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> auf das Ergebnis.</span><span class="sxs-lookup"><span data-stu-id="2b698-685">Initiates an asynchronous operation to execute a segmented query and apply the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the result.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-686">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-686">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.EntityResolver{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token, requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TResult"><span data-ttu-id="2b698-687">Der Typ, in dem <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> projiziert die Ergebnisse der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-687">The type into which the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> will project the query results.</span></span></typeparam>
        <param name="query"><span data-ttu-id="2b698-688">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz unter Angabe der Tabelle Abfragen ausgeführt und die Abfrageparameter verwendet.</span><span class="sxs-lookup"><span data-stu-id="2b698-688">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use.</span></span></param>
        <param name="resolver"><span data-ttu-id="2b698-689">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-689">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-690">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-690">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-691">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-691">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-692">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-692">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b698-693">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-693">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-694">Initiiert einen asynchronen Vorgang zum Ausführen einer Abfrage segmentierten und Anwenden der angegebenen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> auf das Ergebnis.</span><span class="sxs-lookup"><span data-stu-id="2b698-694">Initiates an asynchronous operation to execute a segmented query and apply the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the result.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-695">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-695">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``2(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.EntityResolver{``1},Microsoft.Azure.CosmosDB.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteQuerySegmentedAsync(Of TElement As {ITableEntityNew}, TResult As {ITableEntityNew}) (query As TableQuery(Of TElement), resolver As EntityResolver(Of TResult), token As TableContinuationToken) As Task(Of TableQuerySegment(Of TResult))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="2b698-696">Der Entitätstyp der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-696">The entity type of the query.</span></span></typeparam>
        <typeparam name="TResult"><span data-ttu-id="2b698-697">Der Typ, in dem <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> projiziert die Ergebnisse der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-697">The type into which the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> will project the query results.</span></span></typeparam>
        <param name="query"><span data-ttu-id="2b698-698">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-698">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="resolver"><span data-ttu-id="2b698-699">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-699">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-700">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-700">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-701">Initiiert einen asynchronen Vorgang zum Ausführen einer Abfrage im segmentierten Modus und Anwenden der angegebenen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> mit den Ergebnissen.</span><span class="sxs-lookup"><span data-stu-id="2b698-701">Initiates an asynchronous operation to execute a query in segmented mode and apply the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the results.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-702">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-702">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, System.Threading.CancellationToken cancellationToken) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``2(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.EntityResolver{``1},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="2b698-703">Der Entitätstyp der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-703">The entity type of the query.</span></span></typeparam>
        <typeparam name="TResult"><span data-ttu-id="2b698-704">Der Typ, in dem <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> projiziert die Ergebnisse der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-704">The type into which the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> will project the query results.</span></span></typeparam>
        <param name="query"><span data-ttu-id="2b698-705">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-705">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="resolver"><span data-ttu-id="2b698-706">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-706">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-707">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-707">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b698-708">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-708">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-709">Initiiert einen asynchronen Vorgang zum Ausführen einer Abfrage im segmentierten Modus und Anwenden der angegebenen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> mit den Ergebnissen.</span><span class="sxs-lookup"><span data-stu-id="2b698-709">Initiates an asynchronous operation to execute a query in segmented mode and apply the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the results.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-710">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-710">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``2(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.EntityResolver{``1},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="2b698-711">Der Entitätstyp der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-711">The entity type of the query.</span></span></typeparam>
        <typeparam name="TResult"><span data-ttu-id="2b698-712">Der Typ, in dem <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> projiziert die Ergebnisse der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-712">The type into which the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> will project the query results.</span></span></typeparam>
        <param name="query"><span data-ttu-id="2b698-713">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-713">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="resolver"><span data-ttu-id="2b698-714">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-714">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-715">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-715">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-716">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-716">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-717">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-717">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-718">Initiiert einen asynchronen Vorgang zum Ausführen einer Abfrage im segmentierten Modus und Anwenden der angegebenen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> mit den Ergebnissen.</span><span class="sxs-lookup"><span data-stu-id="2b698-718">Initiates an asynchronous operation to execute a query in segmented mode and apply the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the results.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-719">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-719">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``2(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.EntityResolver{``1},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token, requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="2b698-720">Der Entitätstyp der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-720">The entity type of the query.</span></span></typeparam>
        <typeparam name="TResult"><span data-ttu-id="2b698-721">Der Typ, in dem <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> projiziert die Ergebnisse der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2b698-721">The type into which the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> will project the query results.</span></span></typeparam>
        <param name="query"><span data-ttu-id="2b698-722">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-722">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="resolver"><span data-ttu-id="2b698-723">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-723">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="token"><span data-ttu-id="2b698-724">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-724">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-725">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-725">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-726">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-726">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b698-727">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-727">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-728">Initiiert einen asynchronen Vorgang zum Ausführen einer Abfrage im segmentierten Modus und Anwenden der angegebenen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> mit den Ergebnissen.</span><span class="sxs-lookup"><span data-stu-id="2b698-728">Initiates an asynchronous operation to execute a query in segmented mode and apply the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the results.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-729">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-729">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exists">
      <MemberSignature Language="C#" Value="public virtual bool Exists (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Exists(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.Exists(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Exists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; bool&#xA;override this.Exists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; bool" Usage="cloudTable.Exists (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="2b698-730">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-730">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-731">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-731">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-732">Überprüft, ob die Tabelle vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-732">Checks whether the table exists.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="2b698-733"><c>"true"</c> Wenn Tabelle vorhanden ist; andernfalls <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-733"><c>true</c> if table exists; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.ExistsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2b698-734">Initiiert einen asynchronen Vorgang, um festzustellen, ob eine Tabelle vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-734">Initiates an asynchronous operation to determine whether a table exists.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-735">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-735">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExistsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.ExistsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="2b698-736">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-736">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-737">Initiiert einen asynchronen Vorgang, um festzustellen, ob eine Tabelle vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-737">Initiates an asynchronous operation to determine whether a table exists.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-738">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-738">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExistsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.ExistsAsync (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="2b698-739">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-739">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-740">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-740">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-741">Initiiert einen asynchronen Vorgang, um festzustellen, ob eine Tabelle vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-741">Initiates an asynchronous operation to determine whether a table exists.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-742">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-742">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExistsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.ExistsAsync (requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="2b698-743">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-743">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-744">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-744">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b698-745">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-745">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-746">Initiiert einen asynchronen Vorgang, um festzustellen, ob eine Tabelle vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2b698-746">Initiates an asynchronous operation to determine whether a table exists.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-747">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-747">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TablePermissions GetPermissions (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TablePermissions GetPermissions(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.GetPermissions(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissions : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TablePermissions&#xA;override this.GetPermissions : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TablePermissions" Usage="cloudTable.GetPermissions (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TablePermissions</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="2b698-748">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-748">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-749">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-749">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-750">Ruft die berechtigungseinstellungen für die Tabelle ab.</span><span class="sxs-lookup"><span data-stu-id="2b698-750">Gets the permissions settings for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-751">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="2b698-751">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt; GetPermissionsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TablePermissions&gt; GetPermissionsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.GetPermissionsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetPermissionsAsync () As Task(Of TablePermissions)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;&#xA;override this.GetPermissionsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;" Usage="cloudTable.GetPermissionsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2b698-752">Initiiert einen asynchronen Vorgang zum Abrufen der berechtigungseinstellungen für die Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-752">Initiates an asynchronous operation to get the permissions settings for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-753">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-753">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt; GetPermissionsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TablePermissions&gt; GetPermissionsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.GetPermissionsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;&#xA;override this.GetPermissionsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;" Usage="cloudTable.GetPermissionsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="2b698-754">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-754">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-755">Initiiert einen asynchronen Vorgang zum Abrufen der berechtigungseinstellungen für die Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-755">Initiates an asynchronous operation to get the permissions settings for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-756">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-756">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt; GetPermissionsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TablePermissions&gt; GetPermissionsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.GetPermissionsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;&#xA;override this.GetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;" Usage="cloudTable.GetPermissionsAsync (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="2b698-757">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-757">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-758">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-758">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-759">Initiiert einen asynchronen Vorgang zum Abrufen der berechtigungseinstellungen für die Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-759">Initiates an asynchronous operation to get the permissions settings for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-760">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-760">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt; GetPermissionsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TablePermissions&gt; GetPermissionsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.GetPermissionsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;&#xA;override this.GetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;" Usage="cloudTable.GetPermissionsAsync (requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="2b698-761">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-761">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-762">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-762">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b698-763">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-763">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-764">Initiiert einen asynchronen Vorgang zum Abrufen der berechtigungseinstellungen für die Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-764">Initiates an asynchronous operation to get the permissions settings for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-765">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-765">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy policy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetSharedAccessSignature(class Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy policy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.GetSharedAccessSignature(Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSharedAccessSignature (policy As SharedAccessTablePolicy) As String" />
      <MemberSignature Language="F#" Value="member this.GetSharedAccessSignature : Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy -&gt; string" Usage="cloudTable.GetSharedAccessSignature policy" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policy" Type="Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" />
      </Parameters>
      <Docs>
        <param name="policy"><span data-ttu-id="2b698-766">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" /> Objekt, das die Zugriffsrichtlinie für die SAS angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-766">A <see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" /> object specifying the access policy for the shared access signature.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-767">Gibt eine SAS für die Tabelle zurück.</span><span class="sxs-lookup"><span data-stu-id="2b698-767">Returns a shared access signature for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-768">Eine SAS als URI-Abfragezeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="2b698-768">A shared access signature, as a URI query string.</span></span></returns>
        <remarks><span data-ttu-id="2b698-769">Die zurückgegebene Abfragezeichenfolge enthält das vorangestellte Fragezeichen.</span><span class="sxs-lookup"><span data-stu-id="2b698-769">The query string returned includes the leading question mark.</span></span></remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="2b698-770">Wird ausgelöst, wenn die aktuellen Anmeldeinformationen nicht unterstützen, eine shared Access Signature erstellen.</span><span class="sxs-lookup"><span data-stu-id="2b698-770">Thrown if the current credentials don't support creating a shared access signature.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy policy, string accessPolicyIdentifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetSharedAccessSignature(class Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy policy, string accessPolicyIdentifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.GetSharedAccessSignature(Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSharedAccessSignature (policy As SharedAccessTablePolicy, accessPolicyIdentifier As String) As String" />
      <MemberSignature Language="F#" Value="member this.GetSharedAccessSignature : Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy * string -&gt; string" Usage="cloudTable.GetSharedAccessSignature (policy, accessPolicyIdentifier)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policy" Type="Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" />
        <Parameter Name="accessPolicyIdentifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="policy"><span data-ttu-id="2b698-771">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" /> Objekt, das die Zugriffsrichtlinie für die SAS angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-771">A <see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" /> object specifying the access policy for the shared access signature.</span></span></param>
        <param name="accessPolicyIdentifier"><span data-ttu-id="2b698-772">Eine Zeichenfolge, die eine gespeicherte Zugriffsrichtlinie identifiziert.</span><span class="sxs-lookup"><span data-stu-id="2b698-772">A string identifying a stored access policy.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-773">Gibt eine SAS für die Tabelle zurück.</span><span class="sxs-lookup"><span data-stu-id="2b698-773">Returns a shared access signature for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-774">Eine SAS als URI-Abfragezeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="2b698-774">A shared access signature, as a URI query string.</span></span></returns>
        <remarks><span data-ttu-id="2b698-775">Die zurückgegebene Abfragezeichenfolge enthält das vorangestellte Fragezeichen.</span><span class="sxs-lookup"><span data-stu-id="2b698-775">The query string returned includes the leading question mark.</span></span></remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="2b698-776">Wird ausgelöst, wenn die aktuellen Anmeldeinformationen nicht unterstützen, eine shared Access Signature erstellen.</span><span class="sxs-lookup"><span data-stu-id="2b698-776">Thrown if the current credentials don't support creating a shared access signature.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy policy, string accessPolicyIdentifier, string startPartitionKey, string startRowKey, string endPartitionKey, string endRowKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetSharedAccessSignature(class Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy policy, string accessPolicyIdentifier, string startPartitionKey, string startRowKey, string endPartitionKey, string endRowKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.GetSharedAccessSignature(Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSharedAccessSignature (policy As SharedAccessTablePolicy, accessPolicyIdentifier As String, startPartitionKey As String, startRowKey As String, endPartitionKey As String, endRowKey As String) As String" />
      <MemberSignature Language="F#" Value="member this.GetSharedAccessSignature : Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy * string * string * string * string * string -&gt; string" Usage="cloudTable.GetSharedAccessSignature (policy, accessPolicyIdentifier, startPartitionKey, startRowKey, endPartitionKey, endRowKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policy" Type="Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" />
        <Parameter Name="accessPolicyIdentifier" Type="System.String" />
        <Parameter Name="startPartitionKey" Type="System.String" />
        <Parameter Name="startRowKey" Type="System.String" />
        <Parameter Name="endPartitionKey" Type="System.String" />
        <Parameter Name="endRowKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="policy"><span data-ttu-id="2b698-777">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" /> Objekt, das die Zugriffsrichtlinie für die SAS angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-777">A <see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" /> object specifying the access policy for the shared access signature.</span></span></param>
        <param name="accessPolicyIdentifier"><span data-ttu-id="2b698-778">Eine Zeichenfolge, die eine gespeicherte Zugriffsrichtlinie identifiziert.</span><span class="sxs-lookup"><span data-stu-id="2b698-778">A string identifying a stored access policy.</span></span></param>
        <param name="startPartitionKey"><span data-ttu-id="2b698-779">Eine Zeichenfolge, die den startpartitionsschlüssel angibt oder <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-779">A string specifying the start partition key, or <c>null</c>.</span></span></param>
        <param name="startRowKey"><span data-ttu-id="2b698-780">Eine Zeichenfolge, die den Zeilenschlüssel Start angibt oder <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-780">A string specifying the start row key, or <c>null</c>.</span></span></param>
        <param name="endPartitionKey"><span data-ttu-id="2b698-781">Eine Zeichenfolge, die den endpartitionsschlüssel angibt oder <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-781">A string specifying the end partition key, or <c>null</c>.</span></span></param>
        <param name="endRowKey"><span data-ttu-id="2b698-782">Eine Zeichenfolge, die den endzeilenschlüssel angibt oder <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-782">A string specifying the end row key, or <c>null</c>.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-783">Gibt eine SAS für die Tabelle zurück.</span><span class="sxs-lookup"><span data-stu-id="2b698-783">Returns a shared access signature for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-784">Eine SAS als URI-Abfragezeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="2b698-784">A shared access signature, as a URI query string.</span></span></returns>
        <remarks><span data-ttu-id="2b698-785">Die zurückgegebene Abfragezeichenfolge enthält das vorangestellte Fragezeichen.</span><span class="sxs-lookup"><span data-stu-id="2b698-785">The query string returned includes the leading question mark.</span></span></remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="2b698-786">Wird ausgelöst, wenn die aktuellen Anmeldeinformationen nicht unterstützen, eine shared Access Signature erstellen.</span><span class="sxs-lookup"><span data-stu-id="2b698-786">Thrown if the current credentials don't support creating a shared access signature.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy policy, string accessPolicyIdentifier, string startPartitionKey, string startRowKey, string endPartitionKey, string endRowKey, Nullable&lt;Microsoft.Azure.Storage.SharedAccessProtocol&gt; protocols, Microsoft.Azure.Storage.IPAddressOrRange ipAddressOrRange);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetSharedAccessSignature(class Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy policy, string accessPolicyIdentifier, string startPartitionKey, string startRowKey, string endPartitionKey, string endRowKey, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Storage.SharedAccessProtocol&gt; protocols, class Microsoft.Azure.Storage.IPAddressOrRange ipAddressOrRange) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.GetSharedAccessSignature(Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy,System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Storage.SharedAccessProtocol},Microsoft.Azure.Storage.IPAddressOrRange)" />
      <MemberSignature Language="F#" Value="member this.GetSharedAccessSignature : Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy * string * string * string * string * string * Nullable&lt;Microsoft.Azure.Storage.SharedAccessProtocol&gt; * Microsoft.Azure.Storage.IPAddressOrRange -&gt; string" Usage="cloudTable.GetSharedAccessSignature (policy, accessPolicyIdentifier, startPartitionKey, startRowKey, endPartitionKey, endRowKey, protocols, ipAddressOrRange)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policy" Type="Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" />
        <Parameter Name="accessPolicyIdentifier" Type="System.String" />
        <Parameter Name="startPartitionKey" Type="System.String" />
        <Parameter Name="startRowKey" Type="System.String" />
        <Parameter Name="endPartitionKey" Type="System.String" />
        <Parameter Name="endRowKey" Type="System.String" />
        <Parameter Name="protocols" Type="System.Nullable&lt;Microsoft.Azure.Storage.SharedAccessProtocol&gt;" />
        <Parameter Name="ipAddressOrRange" Type="Microsoft.Azure.Storage.IPAddressOrRange" />
      </Parameters>
      <Docs>
        <param name="policy"><span data-ttu-id="2b698-787">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" /> Objekt, das die Zugriffsrichtlinie für die SAS angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-787">A <see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" /> object specifying the access policy for the shared access signature.</span></span></param>
        <param name="accessPolicyIdentifier"><span data-ttu-id="2b698-788">Eine Zeichenfolge, die eine gespeicherte Zugriffsrichtlinie identifiziert.</span><span class="sxs-lookup"><span data-stu-id="2b698-788">A string identifying a stored access policy.</span></span></param>
        <param name="startPartitionKey"><span data-ttu-id="2b698-789">Eine Zeichenfolge, die den startpartitionsschlüssel angibt oder <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-789">A string specifying the start partition key, or <c>null</c>.</span></span></param>
        <param name="startRowKey"><span data-ttu-id="2b698-790">Eine Zeichenfolge, die den Zeilenschlüssel Start angibt oder <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-790">A string specifying the start row key, or <c>null</c>.</span></span></param>
        <param name="endPartitionKey"><span data-ttu-id="2b698-791">Eine Zeichenfolge, die den endpartitionsschlüssel angibt oder <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-791">A string specifying the end partition key, or <c>null</c>.</span></span></param>
        <param name="endRowKey"><span data-ttu-id="2b698-792">Eine Zeichenfolge, die den endzeilenschlüssel angibt oder <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="2b698-792">A string specifying the end row key, or <c>null</c>.</span></span></param>
        <param name="protocols"><span data-ttu-id="2b698-793">Die zulässige Protokolle (nur Https oder http und Https).</span><span class="sxs-lookup"><span data-stu-id="2b698-793">The allowed protocols (https only, or http and https).</span></span> <span data-ttu-id="2b698-794">NULL, wenn Sie nicht Protokoll beschränken möchten.</span><span class="sxs-lookup"><span data-stu-id="2b698-794">Null if you don't want to restrict protocol.</span></span></param>
        <param name="ipAddressOrRange"><span data-ttu-id="2b698-795">Die zulässigen IP-Adresse oder IP-Adressbereich.</span><span class="sxs-lookup"><span data-stu-id="2b698-795">The allowed IP address or IP address range.</span></span> <span data-ttu-id="2b698-796">NULL, wenn Sie einschränken möchten, nicht basierend auf IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="2b698-796">Null if you don't want to restrict based on IP address.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-797">Gibt eine SAS für die Tabelle zurück.</span><span class="sxs-lookup"><span data-stu-id="2b698-797">Returns a shared access signature for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-798">Eine SAS als URI-Abfragezeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="2b698-798">A shared access signature, as a URI query string.</span></span></returns>
        <remarks><span data-ttu-id="2b698-799">Die zurückgegebene Abfragezeichenfolge enthält das vorangestellte Fragezeichen.</span><span class="sxs-lookup"><span data-stu-id="2b698-799">The query string returned includes the leading question mark.</span></span></remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="2b698-800">Wird ausgelöst, wenn die aktuellen Anmeldeinformationen nicht unterstützen, eine shared Access Signature erstellen.</span><span class="sxs-lookup"><span data-stu-id="2b698-800">Thrown if the current credentials don't support creating a shared access signature.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.CloudTable.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.CosmosDB.Table.CloudTable.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b698-801">Ruft den Namen der Tabelle ab.</span><span class="sxs-lookup"><span data-stu-id="2b698-801">Gets the name of the table.</span></span>
            </summary>
        <value><span data-ttu-id="2b698-802">Eine Zeichenfolge, die mit dem Namen der Tabelle.</span><span class="sxs-lookup"><span data-stu-id="2b698-802">A string containing the name of the table.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceClient">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.CloudTableClient ServiceClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.CosmosDB.Table.CloudTableClient ServiceClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.CloudTable.ServiceClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceClient As CloudTableClient" />
      <MemberSignature Language="F#" Value="member this.ServiceClient : Microsoft.Azure.CosmosDB.Table.CloudTableClient" Usage="Microsoft.Azure.CosmosDB.Table.CloudTable.ServiceClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.CloudTableClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b698-803">Ruft die <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTableClient" /> -Objekt, das den Tabellendienst darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-803">Gets the <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTableClient" /> object that represents the Table service.</span></span>
            </summary>
        <value><span data-ttu-id="2b698-804">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTableClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="2b698-804">A <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTableClient" /> object .</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissions">
      <MemberSignature Language="C#" Value="public virtual void SetPermissions (Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetPermissions(class Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.SetPermissions(Microsoft.Azure.CosmosDB.Table.TablePermissions,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissions : Microsoft.Azure.CosmosDB.Table.TablePermissions * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; unit&#xA;override this.SetPermissions : Microsoft.Azure.CosmosDB.Table.TablePermissions * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; unit" Usage="cloudTable.SetPermissions (permissions, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.Azure.CosmosDB.Table.TablePermissions" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="2b698-805">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> Objekt, das die Berechtigungen festgelegt darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-805">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> object that represents the permissions to set.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-806">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-806">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-807">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-807">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-808">Legt die berechtigungseinstellungen für die Tabelle fest.</span><span class="sxs-lookup"><span data-stu-id="2b698-808">Sets the permissions settings for the table.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.Azure.CosmosDB.Table.TablePermissions permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.Azure.CosmosDB.Table.TablePermissions permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.SetPermissionsAsync(Microsoft.Azure.CosmosDB.Table.TablePermissions)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetPermissionsAsync (permissions As TablePermissions) As Task" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TablePermissions -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TablePermissions -&gt; System.Threading.Tasks.Task" Usage="cloudTable.SetPermissionsAsync permissions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.Azure.CosmosDB.Table.TablePermissions" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="2b698-809">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> Objekt, das die Berechtigungen festgelegt darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-809">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> object that represents the permissions to set.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-810">Initiiert einen asynchronen Vorgang zum Festlegen von Berechtigungen für die Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-810">Initiates an asynchronous operation to set permissions for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-811">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-811">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.SetPermissionsAsync(Microsoft.Azure.CosmosDB.Table.TablePermissions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TablePermissions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TablePermissions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.SetPermissionsAsync (permissions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.Azure.CosmosDB.Table.TablePermissions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="2b698-812">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> Objekt, das die Berechtigungen festgelegt darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-812">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> object that represents the permissions to set.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b698-813">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-813">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-814">Initiiert einen asynchronen Vorgang zum Festlegen von Berechtigungen für die Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-814">Initiates an asynchronous operation to set permissions for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-815">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-815">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.SetPermissionsAsync(Microsoft.Azure.CosmosDB.Table.TablePermissions,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TablePermissions * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TablePermissions * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudTable.SetPermissionsAsync (permissions, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.Azure.CosmosDB.Table.TablePermissions" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="2b698-816">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> Objekt, das die Berechtigungen festgelegt darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-816">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> object that represents the permissions to set.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-817">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-817">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-818">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-818">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-819">Initiiert einen asynchronen Vorgang zum Festlegen von Berechtigungen für die Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-819">Initiates an asynchronous operation to set permissions for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-820">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-820">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.SetPermissionsAsync(Microsoft.Azure.CosmosDB.Table.TablePermissions,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TablePermissions * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TablePermissions * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.SetPermissionsAsync (permissions, requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.Azure.CosmosDB.Table.TablePermissions" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="2b698-821">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> Objekt, das die Berechtigungen festgelegt darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-821">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> object that represents the permissions to set.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="2b698-822">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="2b698-822">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="2b698-823">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-823">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b698-824">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="2b698-824">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="2b698-825">Initiiert einen asynchronen Vorgang zum Festlegen von Berechtigungen für die Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="2b698-825">Initiates an asynchronous operation to set permissions for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-826">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2b698-826">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Storage.StorageUri StorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Storage.StorageUri StorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.CloudTable.StorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.StorageUri : Microsoft.Azure.Storage.StorageUri" Usage="Microsoft.Azure.CosmosDB.Table.CloudTable.StorageUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.StorageUri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b698-827">Ruft die Tabellen URIs für die primären und sekundären Speicherorte ab.</span><span class="sxs-lookup"><span data-stu-id="2b698-827">Gets the table's URIs for both the primary and secondary locations.</span></span>
            </summary>
        <value><span data-ttu-id="2b698-828">Ein Objekt des Typs <see cref="P:Microsoft.Azure.CosmosDB.Table.CloudTable.StorageUri" /> , die die Tabellen URIs für die primären und sekundären Speicherorte enthält.</span><span class="sxs-lookup"><span data-stu-id="2b698-828">An object of type <see cref="P:Microsoft.Azure.CosmosDB.Table.CloudTable.StorageUri" /> containing the table's URIs for both the primary and secondary locations.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="cloudTable.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2b698-829">Gibt den Namen der Tabelle zurück.</span><span class="sxs-lookup"><span data-stu-id="2b698-829">Returns the name of the table.</span></span>
            </summary>
        <returns><span data-ttu-id="2b698-830">Eine Zeichenfolge, die mit dem Namen der Tabelle.</span><span class="sxs-lookup"><span data-stu-id="2b698-830">A string containing the name of the table.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Uri">
      <MemberSignature Language="C#" Value="public Uri Uri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Uri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.CloudTable.Uri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Uri As Uri" />
      <MemberSignature Language="F#" Value="member this.Uri : Uri" Usage="Microsoft.Azure.CosmosDB.Table.CloudTable.Uri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b698-831">Ruft den Tabelle-URI für den primären Speicherort ab.</span><span class="sxs-lookup"><span data-stu-id="2b698-831">Gets the table URI for the primary location.</span></span>
            </summary>
        <value><span data-ttu-id="2b698-832">Ein <see cref="T:System.Uri" /> den absoluten URI zur Tabelle am primären Standort angeben.</span><span class="sxs-lookup"><span data-stu-id="2b698-832">A <see cref="T:System.Uri" /> specifying the absolute URI to the table at the primary location.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>