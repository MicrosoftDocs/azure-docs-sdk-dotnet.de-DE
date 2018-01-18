<Type Name="TableServiceContext" FullName="Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext">
  <TypeSignature Language="C#" Value="public class TableServiceContext : System.Data.Services.Client.DataServiceContext, IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TableServiceContext extends System.Data.Services.Client.DataServiceContext implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" />
  <TypeSignature Language="VB.NET" Value="Public Class TableServiceContext&#xA;Inherits DataServiceContext&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type TableServiceContext = class&#xA;    inherit DataServiceContext&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Data.Services.Client.DataServiceContext</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="c2208-101">Stellt eine <see cref="T:System.Data.Services.Client.DataServiceContext" /> Objekt für die Verwendung mit dem Windows Azure-Tabellendienst.</span><span class="sxs-lookup"><span data-stu-id="c2208-101">Represents a <see cref="T:System.Data.Services.Client.DataServiceContext" /> object for use with the Windows Azure Table service.</span></span>
            </summary>
    <remarks><span data-ttu-id="c2208-102">Die <see cref="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" /> Klasse unterstützt keine gleichzeitigen Abfragen oder Anforderungen.</span><span class="sxs-lookup"><span data-stu-id="c2208-102">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" /> class does not support concurrent queries or requests.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableServiceContext (Microsoft.WindowsAzure.Storage.Table.CloudTableClient client);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.Table.CloudTableClient client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.#ctor(Microsoft.WindowsAzure.Storage.Table.CloudTableClient)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (client As CloudTableClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext : Microsoft.WindowsAzure.Storage.Table.CloudTableClient -&gt; Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" Usage="new Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext client" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <Parameters>
        <Parameter Name="client" Type="Microsoft.WindowsAzure.Storage.Table.CloudTableClient" />
      </Parameters>
      <Docs>
        <param name="client">To be added.</param>
        <summary>
            <span data-ttu-id="c2208-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c2208-103">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSaveChangesWithRetries">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSaveChangesWithRetries (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSaveChangesWithRetries(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.BeginSaveChangesWithRetries(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function BeginSaveChangesWithRetries (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="member this.BeginSaveChangesWithRetries : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="tableServiceContext.BeginSaveChangesWithRetries (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="c2208-104">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="c2208-104">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="c2208-105">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="c2208-105">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="c2208-106">Startet einen asynchronen Vorgang zum Speichern von Änderungen, über die wiederholungsrichtlinie für den Dienstkontext angegeben.</span><span class="sxs-lookup"><span data-stu-id="c2208-106">Begins an asynchronous operation to save changes, using the retry policy specified for the service context.</span></span>
            </summary>
        <returns><span data-ttu-id="c2208-107">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="c2208-107">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSaveChangesWithRetries">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSaveChangesWithRetries (System.Data.Services.Client.SaveChangesOptions options, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSaveChangesWithRetries(valuetype System.Data.Services.Client.SaveChangesOptions options, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.BeginSaveChangesWithRetries(System.Data.Services.Client.SaveChangesOptions,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function BeginSaveChangesWithRetries (options As SaveChangesOptions, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="member this.BeginSaveChangesWithRetries : System.Data.Services.Client.SaveChangesOptions * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="tableServiceContext.BeginSaveChangesWithRetries (options, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="System.Data.Services.Client.SaveChangesOptions" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="c2208-108">Ein <see cref="T:System.Data.Services.Client.SaveChangesOptions" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="c2208-108">A <see cref="T:System.Data.Services.Client.SaveChangesOptions" /> enumeration value.</span></span></param>
        <param name="callback"><span data-ttu-id="c2208-109">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="c2208-109">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="c2208-110">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="c2208-110">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="c2208-111">Startet einen asynchronen Vorgang zum Speichern von Änderungen, über die wiederholungsrichtlinie für den Dienstkontext angegeben.</span><span class="sxs-lookup"><span data-stu-id="c2208-111">Begins an asynchronous operation to save changes, using the retry policy specified for the service context.</span></span>
            </summary>
        <returns><span data-ttu-id="c2208-112">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="c2208-112">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSaveChangesWithRetries">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSaveChangesWithRetries (System.Data.Services.Client.SaveChangesOptions options, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSaveChangesWithRetries(valuetype System.Data.Services.Client.SaveChangesOptions options, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.BeginSaveChangesWithRetries(System.Data.Services.Client.SaveChangesOptions,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="member this.BeginSaveChangesWithRetries : System.Data.Services.Client.SaveChangesOptions * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="tableServiceContext.BeginSaveChangesWithRetries (options, requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="System.Data.Services.Client.SaveChangesOptions" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="c2208-113">Ein <see cref="T:System.Data.Services.Client.SaveChangesOptions" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="c2208-113">A <see cref="T:System.Data.Services.Client.SaveChangesOptions" /> enumeration value.</span></span></param>
        <param name="requestOptions"></param>
        <param name="operationContext"><span data-ttu-id="c2208-114">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c2208-114">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="c2208-115">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="c2208-115">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="c2208-116">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="c2208-116">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="c2208-117">Startet einen asynchronen Vorgang zum Speichern von Änderungen, über die wiederholungsrichtlinie für den Dienstkontext angegeben.</span><span class="sxs-lookup"><span data-stu-id="c2208-117">Begins an asynchronous operation to save changes, using the retry policy specified for the service context.</span></span>
            </summary>
        <returns><span data-ttu-id="c2208-118">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="c2208-118">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="tableServiceContext.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c2208-119">Gibt alle von der TableServiceContext verwendete Ressourcen frei.</span><span class="sxs-lookup"><span data-stu-id="c2208-119">Releases all resources used by the TableServiceContext.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected virtual void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="abstract member Dispose : bool -&gt; unit&#xA;override this.Dispose : bool -&gt; unit" Usage="tableServiceContext.Dispose disposing" />
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
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing">
          <span data-ttu-id="c2208-120"><c>"true"</c> um sowohl verwaltete als auch nicht verwaltete Ressourcen freizugeben <c>"false"</c> um ausschließlich nicht verwaltete Ressourcen freizugeben.</span><span class="sxs-lookup"><span data-stu-id="c2208-120"><c>true</c> to release both managed and unmanaged resources; <c>false</c> to release only unmanaged resources.</span></span></param>
        <summary>
            <span data-ttu-id="c2208-121">Die von der TableServiceContext verwendeten nicht verwalteten Ressourcen frei, und optional die verwalteten Ressourcen frei.</span><span class="sxs-lookup"><span data-stu-id="c2208-121">Releases the unmanaged resources used by the TableServiceContext and optionally releases the managed resources.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSaveChangesWithRetries">
      <MemberSignature Language="C#" Value="public System.Data.Services.Client.DataServiceResponse EndSaveChangesWithRetries (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Data.Services.Client.DataServiceResponse EndSaveChangesWithRetries(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.EndSaveChangesWithRetries(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Function EndSaveChangesWithRetries (asyncResult As IAsyncResult) As DataServiceResponse" />
      <MemberSignature Language="F#" Value="member this.EndSaveChangesWithRetries : IAsyncResult -&gt; System.Data.Services.Client.DataServiceResponse" Usage="tableServiceContext.EndSaveChangesWithRetries asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Data.Services.Client.DataServiceResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="c2208-122">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="c2208-122">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2208-123">Beendet einen asynchronen Vorgang, um Änderungen zu speichern.</span><span class="sxs-lookup"><span data-stu-id="c2208-123">Ends an asynchronous operation to save changes.</span></span>
            </summary>
        <returns> <span data-ttu-id="c2208-124">Ein <see cref="T:System.Data.Services.Client.DataServiceResponse" /> , die das Ergebnis des Vorgangs darstellt.</span><span class="sxs-lookup"><span data-stu-id="c2208-124">A <see cref="T:System.Data.Services.Client.DataServiceResponse" /> that represents the result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveChangesWithRetries">
      <MemberSignature Language="C#" Value="public System.Data.Services.Client.DataServiceResponse SaveChangesWithRetries ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Data.Services.Client.DataServiceResponse SaveChangesWithRetries() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.SaveChangesWithRetries" />
      <MemberSignature Language="VB.NET" Value="Public Function SaveChangesWithRetries () As DataServiceResponse" />
      <MemberSignature Language="F#" Value="member this.SaveChangesWithRetries : unit -&gt; System.Data.Services.Client.DataServiceResponse" Usage="tableServiceContext.SaveChangesWithRetries " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Data.Services.Client.DataServiceResponse</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c2208-125">Speichert die Änderungen, über die wiederholungsrichtlinie für den Dienstkontext angegeben.</span><span class="sxs-lookup"><span data-stu-id="c2208-125">Saves changes, using the retry policy specified for the service context.</span></span>
            </summary>
        <returns><span data-ttu-id="c2208-126">Ein <see cref="T:System.Data.Services.Client.DataServiceResponse" /> , die das Ergebnis des Vorgangs darstellt.</span><span class="sxs-lookup"><span data-stu-id="c2208-126">A <see cref="T:System.Data.Services.Client.DataServiceResponse" /> that represents the result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveChangesWithRetries">
      <MemberSignature Language="C#" Value="public System.Data.Services.Client.DataServiceResponse SaveChangesWithRetries (System.Data.Services.Client.SaveChangesOptions options, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Data.Services.Client.DataServiceResponse SaveChangesWithRetries(valuetype System.Data.Services.Client.SaveChangesOptions options, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.SaveChangesWithRetries(System.Data.Services.Client.SaveChangesOptions,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="member this.SaveChangesWithRetries : System.Data.Services.Client.SaveChangesOptions * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Data.Services.Client.DataServiceResponse" Usage="tableServiceContext.SaveChangesWithRetries (options, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Data.Services.Client.DataServiceResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="System.Data.Services.Client.SaveChangesOptions" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="c2208-127">Ein <see cref="T:System.Data.Services.Client.SaveChangesOptions" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="c2208-127">A <see cref="T:System.Data.Services.Client.SaveChangesOptions" /> enumeration value.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="c2208-128">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="c2208-128">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2208-129">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c2208-129">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2208-130">Speichert die Änderungen, über die wiederholungsrichtlinie für den Dienstkontext angegeben.</span><span class="sxs-lookup"><span data-stu-id="c2208-130">Saves changes, using the retry policy specified for the service context.</span></span>
            </summary>
        <returns> <span data-ttu-id="c2208-131">Ein <see cref="T:System.Data.Services.Client.DataServiceResponse" /> , die das Ergebnis des Vorgangs darstellt.</span><span class="sxs-lookup"><span data-stu-id="c2208-131">A <see cref="T:System.Data.Services.Client.DataServiceResponse" /> that represents the result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveChangesWithRetriesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.SaveChangesWithRetriesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function SaveChangesWithRetriesAsync () As Task(Of DataServiceResponse)" />
      <MemberSignature Language="F#" Value="member this.SaveChangesWithRetriesAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;" Usage="tableServiceContext.SaveChangesWithRetriesAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c2208-132">Initiiert einen asynchronen Vorgang zum Speichern von Änderungen, über die wiederholungsrichtlinie für den Dienstkontext angegeben.</span><span class="sxs-lookup"><span data-stu-id="c2208-132">Initiates an asynchronous operation to save changes, using the retry policy specified for the service context.</span></span>
            </summary>
        <returns><span data-ttu-id="c2208-133">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c2208-133">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveChangesWithRetriesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync (System.Data.Services.Client.SaveChangesOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync(valuetype System.Data.Services.Client.SaveChangesOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.SaveChangesWithRetriesAsync(System.Data.Services.Client.SaveChangesOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function SaveChangesWithRetriesAsync (options As SaveChangesOptions) As Task(Of DataServiceResponse)" />
      <MemberSignature Language="F#" Value="member this.SaveChangesWithRetriesAsync : System.Data.Services.Client.SaveChangesOptions -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;" Usage="tableServiceContext.SaveChangesWithRetriesAsync options" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="System.Data.Services.Client.SaveChangesOptions" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="c2208-134">Ein <see cref="T:System.Data.Services.Client.SaveChangesOptions" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="c2208-134">A <see cref="T:System.Data.Services.Client.SaveChangesOptions" /> enumeration value.</span></span></param>
        <summary>
            <span data-ttu-id="c2208-135">Initiiert einen asynchronen Vorgang zum Speichern von Änderungen, über die wiederholungsrichtlinie für den Dienstkontext angegeben.</span><span class="sxs-lookup"><span data-stu-id="c2208-135">Initiates an asynchronous operation to save changes, using the retry policy specified for the service context.</span></span>
            </summary>
        <returns><span data-ttu-id="c2208-136">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c2208-136">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveChangesWithRetriesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.SaveChangesWithRetriesAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SaveChangesWithRetriesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;" Usage="tableServiceContext.SaveChangesWithRetriesAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="c2208-137">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="c2208-137">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="c2208-138">Initiiert einen asynchronen Vorgang zum Speichern von Änderungen, über die wiederholungsrichtlinie für den Dienstkontext angegeben.</span><span class="sxs-lookup"><span data-stu-id="c2208-138">Initiates an asynchronous operation to save changes, using the retry policy specified for the service context.</span></span>
            </summary>
        <returns><span data-ttu-id="c2208-139">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c2208-139">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveChangesWithRetriesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync (System.Data.Services.Client.SaveChangesOptions options, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync(valuetype System.Data.Services.Client.SaveChangesOptions options, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.SaveChangesWithRetriesAsync(System.Data.Services.Client.SaveChangesOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SaveChangesWithRetriesAsync : System.Data.Services.Client.SaveChangesOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;" Usage="tableServiceContext.SaveChangesWithRetriesAsync (options, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="System.Data.Services.Client.SaveChangesOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="c2208-140">Ein <see cref="T:System.Data.Services.Client.SaveChangesOptions" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="c2208-140">A <see cref="T:System.Data.Services.Client.SaveChangesOptions" /> enumeration value.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c2208-141">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="c2208-141">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="c2208-142">Initiiert einen asynchronen Vorgang zum Speichern von Änderungen, über die wiederholungsrichtlinie für den Dienstkontext angegeben.</span><span class="sxs-lookup"><span data-stu-id="c2208-142">Initiates an asynchronous operation to save changes, using the retry policy specified for the service context.</span></span>
            </summary>
        <returns><span data-ttu-id="c2208-143">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c2208-143">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveChangesWithRetriesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync (System.Data.Services.Client.SaveChangesOptions options, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync(valuetype System.Data.Services.Client.SaveChangesOptions options, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.SaveChangesWithRetriesAsync(System.Data.Services.Client.SaveChangesOptions,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="member this.SaveChangesWithRetriesAsync : System.Data.Services.Client.SaveChangesOptions * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;" Usage="tableServiceContext.SaveChangesWithRetriesAsync (options, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="System.Data.Services.Client.SaveChangesOptions" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="c2208-144">Ein <see cref="T:System.Data.Services.Client.SaveChangesOptions" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="c2208-144">A <see cref="T:System.Data.Services.Client.SaveChangesOptions" /> enumeration value.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="c2208-145">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="c2208-145">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2208-146">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c2208-146">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2208-147">Initiiert einen asynchronen Vorgang zum Speichern von Änderungen, über die wiederholungsrichtlinie für den Dienstkontext angegeben.</span><span class="sxs-lookup"><span data-stu-id="c2208-147">Initiates an asynchronous operation to save changes, using the retry policy specified for the service context.</span></span>
            </summary>
        <returns><span data-ttu-id="c2208-148">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c2208-148">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveChangesWithRetriesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync (System.Data.Services.Client.SaveChangesOptions options, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync(valuetype System.Data.Services.Client.SaveChangesOptions options, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.SaveChangesWithRetriesAsync(System.Data.Services.Client.SaveChangesOptions,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SaveChangesWithRetriesAsync : System.Data.Services.Client.SaveChangesOptions * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;" Usage="tableServiceContext.SaveChangesWithRetriesAsync (options, requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="System.Data.Services.Client.SaveChangesOptions" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="c2208-149">Ein <see cref="T:System.Data.Services.Client.SaveChangesOptions" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="c2208-149">A <see cref="T:System.Data.Services.Client.SaveChangesOptions" /> enumeration value.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="c2208-150">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="c2208-150">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2208-151">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c2208-151">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c2208-152">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="c2208-152">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="c2208-153">Initiiert einen asynchronen Vorgang zum Speichern von Änderungen, über die wiederholungsrichtlinie für den Dienstkontext angegeben.</span><span class="sxs-lookup"><span data-stu-id="c2208-153">Initiates an asynchronous operation to save changes, using the retry policy specified for the service context.</span></span>
            </summary>
        <returns><span data-ttu-id="c2208-154">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c2208-154">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceClient">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.CloudTableClient ServiceClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Table.CloudTableClient ServiceClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.ServiceClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceClient As CloudTableClient" />
      <MemberSignature Language="F#" Value="member this.ServiceClient : Microsoft.WindowsAzure.Storage.Table.CloudTableClient" Usage="Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.ServiceClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.CloudTableClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c2208-155">Ruft die <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTableClient" /> -Objekt, das den Tabellendienst darstellt.</span><span class="sxs-lookup"><span data-stu-id="c2208-155">Gets the <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTableClient" /> object that represents the Table service.</span></span>
            </summary>
        <value><span data-ttu-id="c2208-156">Ein Clientobjekt, das den tabellendienstendpunkt angibt.</span><span class="sxs-lookup"><span data-stu-id="c2208-156">A client object that specifies the Table service endpoint.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>