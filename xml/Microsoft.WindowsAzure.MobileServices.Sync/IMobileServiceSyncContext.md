<Type Name="IMobileServiceSyncContext" FullName="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext">
  <TypeSignature Language="C#" Value="public interface IMobileServiceSyncContext" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMobileServiceSyncContext" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMobileServiceSyncContext" />
  <TypeSignature Language="F#" Value="type IMobileServiceSyncContext = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8723d-101">Bietet eine Möglichkeit, lokale Datenbank mit der entfernten Datenbank zu synchronisieren.</span><span class="sxs-lookup"><span data-stu-id="8723d-101">Provides a way to synchronize local database with remote database.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Handler">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler Handler { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler Handler" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.Handler" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Handler As IMobileServiceSyncHandler" />
      <MemberSignature Language="F#" Value="member this.Handler : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler" Usage="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.Handler" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8723d-102">Eine Instanz von <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler" />.</span><span class="sxs-lookup"><span data-stu-id="8723d-102">An instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler" /></span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task InitializeAsync (Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore store, Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler handler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task InitializeAsync(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore store, class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler handler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.InitializeAsync(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore,Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Function InitializeAsync (store As IMobileServiceLocalStore, handler As IMobileServiceSyncHandler) As Task" />
      <MemberSignature Language="F#" Value="abstract member InitializeAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore * Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncContext.InitializeAsync (store, handler)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="store" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" />
        <Parameter Name="handler" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler" />
      </Parameters>
      <Docs>
        <param name="store"><span data-ttu-id="8723d-103">Eine Instanz von <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" />.</span><span class="sxs-lookup"><span data-stu-id="8723d-103">An instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" />.</span></span></param>
        <param name="handler"><span data-ttu-id="8723d-104">Eine Instanz von <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler" />.</span><span class="sxs-lookup"><span data-stu-id="8723d-104">An instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler" /></span></span></param>
        <summary>
            <span data-ttu-id="8723d-105">Initialisiert das Sync-Kontext.</span><span class="sxs-lookup"><span data-stu-id="8723d-105">Initializes the sync context.</span></span>
            </summary>
        <returns><span data-ttu-id="8723d-106">Eine Aufgabe, die abgeschlossen wird, wenn die Synchronisierung Kontext initialisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="8723d-106">A task that completes when sync context has initialized.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task InitializeAsync (Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore store, Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler handler, Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions trackingOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task InitializeAsync(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore store, class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler handler, valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions trackingOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.InitializeAsync(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore,Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler,Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function InitializeAsync (store As IMobileServiceLocalStore, handler As IMobileServiceSyncHandler, trackingOptions As StoreTrackingOptions) As Task" />
      <MemberSignature Language="F#" Value="abstract member InitializeAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore * Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler * Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncContext.InitializeAsync (store, handler, trackingOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="store" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" />
        <Parameter Name="handler" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler" />
        <Parameter Name="trackingOptions" Type="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions" />
      </Parameters>
      <Docs>
        <param name="store"><span data-ttu-id="8723d-107">Eine Instanz von <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" />.</span><span class="sxs-lookup"><span data-stu-id="8723d-107">An instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" />.</span></span></param>
        <param name="handler"><span data-ttu-id="8723d-108">Eine Instanz von <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler" />.</span><span class="sxs-lookup"><span data-stu-id="8723d-108">An instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler" /></span></span></param>
        <param name="trackingOptions"><span data-ttu-id="8723d-109">Ein <see cref="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.StoreTrackingOptions" /> Wert, der angibt, wie Speichervorgängen nachverfolgt werden soll, die Auswirkungen auf die Store-Ereignisse ausgelöst werden.</span><span class="sxs-lookup"><span data-stu-id="8723d-109">A <see cref="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.StoreTrackingOptions" /> value indicating how store operations will be tracked, impacting which store events are raised.</span></span></param>
        <summary>
            <span data-ttu-id="8723d-110">Initialisiert das Sync-Kontext.</span><span class="sxs-lookup"><span data-stu-id="8723d-110">Initializes the sync context.</span></span>
            </summary>
        <returns><span data-ttu-id="8723d-111">Eine Aufgabe, die abgeschlossen wird, wenn die Synchronisierung Kontext initialisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="8723d-111">A task that completes when sync context has initialized.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsInitialized">
      <MemberSignature Language="C#" Value="public bool IsInitialized { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsInitialized" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.IsInitialized" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsInitialized As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsInitialized : bool" Usage="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.IsInitialized" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8723d-112">Gibt an, ob die Synchronisierung Kontext initialisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="8723d-112">Indicates whether sync context has been initialized or not.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PendingOperations">
      <MemberSignature Language="C#" Value="public long PendingOperations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 PendingOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.PendingOperations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PendingOperations As Long" />
      <MemberSignature Language="F#" Value="member this.PendingOperations : int64" Usage="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.PendingOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8723d-113">Gibt die Anzahl der ausstehenden Vorgänge, die noch nicht an die Remotetabelle weitergegeben werden.</span><span class="sxs-lookup"><span data-stu-id="8723d-113">Returns the number of pending operations that are not yet pushed to remote table.</span></span>
            </summary>
        <value><span data-ttu-id="8723d-114">Gibt die Anzahl der ausstehenden Vorgänge für die Remotetabelle zurück.</span><span class="sxs-lookup"><span data-stu-id="8723d-114">Returns the number of pending operations against the remote table.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PushAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PushAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PushAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.PushAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PushAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncContext.PushAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="8723d-115">Die <see cref="T:System.Threading.CancellationToken" /> Token beobachten</span><span class="sxs-lookup"><span data-stu-id="8723d-115">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span></param>
        <summary>
            <span data-ttu-id="8723d-116">Legt alle ausstehenden Vorgänge auf die Remotetabelle ab.</span><span class="sxs-lookup"><span data-stu-id="8723d-116">Pushes all pending operations up to the remote table.</span></span>
            </summary>
        <returns><span data-ttu-id="8723d-117">Eine Aufgabe, die abgeschlossen wird, wenn der Pullvorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="8723d-117">A task that completes when pull operation has finished.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Store">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore Store { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore Store" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.Store" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Store As IMobileServiceLocalStore" />
      <MemberSignature Language="F#" Value="member this.Store : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" Usage="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.Store" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8723d-118">Eine Instanz von <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" />.</span><span class="sxs-lookup"><span data-stu-id="8723d-118">An instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" /></span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreTrackingOptions">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions StoreTrackingOptions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions StoreTrackingOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.StoreTrackingOptions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoreTrackingOptions As StoreTrackingOptions" />
      <MemberSignature Language="F#" Value="member this.StoreTrackingOptions : Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions" Usage="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.StoreTrackingOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8723d-119">Ein Flag, der angibt, welche Store Überwachungsoptionen sind aktuell deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="8723d-119">A flag indicating which store tracking options are currently enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>