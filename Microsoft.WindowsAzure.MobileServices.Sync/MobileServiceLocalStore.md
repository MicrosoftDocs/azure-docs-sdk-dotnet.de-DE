<Type Name="MobileServiceLocalStore" FullName="Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore">
  <TypeSignature Language="C#" Value="public abstract class MobileServiceLocalStore : IDisposable, Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit MobileServiceLocalStore extends System.Object implements class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class MobileServiceLocalStore&#xA;Implements IDisposable, IMobileServiceLocalStore" />
  <TypeSignature Language="F#" Value="type MobileServiceLocalStore = class&#xA;    interface IMobileServiceLocalStore&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="5d5f1-101">Die basisimplementierung für<see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" /></span><span class="sxs-lookup"><span data-stu-id="5d5f1-101">Base implementation for <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" /></span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MobileServiceLocalStore ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefineTable">
      <MemberSignature Language="C#" Value="public virtual void DefineTable (string tableName, Newtonsoft.Json.Linq.JObject item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DefineTable(string tableName, class Newtonsoft.Json.Linq.JObject item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore.DefineTable(System.String,Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub DefineTable (tableName As String, item As JObject)" />
      <MemberSignature Language="F#" Value="abstract member DefineTable : string * Newtonsoft.Json.Linq.JObject -&gt; unit&#xA;override this.DefineTable : string * Newtonsoft.Json.Linq.JObject -&gt; unit" Usage="mobileServiceLocalStore.DefineTable (tableName, item)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="item" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="tableName"><span data-ttu-id="5d5f1-102">Der Name der lokalen Tabelle.</span><span class="sxs-lookup"><span data-stu-id="5d5f1-102">Name of the local table.</span></span></param>
        <param name="item"><span data-ttu-id="5d5f1-103">Ein Objekt, das die Struktur der Tabelle darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d5f1-103">An object that represents the structure of the table.</span></span></param>
        <summary>
            <span data-ttu-id="5d5f1-104">Definiert die lokale Tabelle auf den Speicher.</span><span class="sxs-lookup"><span data-stu-id="5d5f1-104">Defines the local table on the store.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task DeleteAsync (Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription query);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(class Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore.DeleteAsync(Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function DeleteAsync (query As MobileServiceTableQueryDescription) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription -&gt; System.Threading.Tasks.Task" Usage="mobileServiceLocalStore.DeleteAsync query" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore.DeleteAsync(Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="5d5f1-105">Instanz von<see cref="T:Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription" /></span><span class="sxs-lookup"><span data-stu-id="5d5f1-105">Instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription" /></span></span></param>
        <summary>
            <span data-ttu-id="5d5f1-106">Löscht alle Elemente aus der lokalen Tabelle, die der Abfrage entsprechen.</span><span class="sxs-lookup"><span data-stu-id="5d5f1-106">Deletes all the items from local table that match the query.</span></span>
            </summary>
        <returns><span data-ttu-id="5d5f1-107">Eine Aufgabe, die abgeschlossen wird, wenn Delete für lokale Tabelle ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="5d5f1-107">A task that completes when delete has been executed on local table.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task DeleteAsync (string tableName, System.Collections.Generic.IEnumerable&lt;string&gt; ids);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(string tableName, class System.Collections.Generic.IEnumerable`1&lt;string&gt; ids) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore.DeleteAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function DeleteAsync (tableName As String, ids As IEnumerable(Of String)) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task" Usage="mobileServiceLocalStore.DeleteAsync (tableName, ids)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore.DeleteAsync(System.String,System.Collections.Generic.IEnumerable{System.String})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="ids" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="tableName"><span data-ttu-id="5d5f1-108">Der Name der lokalen Tabelle.</span><span class="sxs-lookup"><span data-stu-id="5d5f1-108">Name of the local table.</span></span></param>
        <param name="ids"><span data-ttu-id="5d5f1-109">Eine Liste der Ids der Elemente, die gelöscht werden</span><span class="sxs-lookup"><span data-stu-id="5d5f1-109">A list of ids of the items to be deleted</span></span></param>
        <summary>
            <span data-ttu-id="5d5f1-110">Löscht Elemente aus der lokalen Tabelle mit der angegebenen Liste von ids</span><span class="sxs-lookup"><span data-stu-id="5d5f1-110">Deletes items from local table with the given list of ids</span></span>
            </summary>
        <returns><span data-ttu-id="5d5f1-111">Löschen Sie eine Aufgabe, die beim Abschluss Abfrage ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="5d5f1-111">A task that completes when delete query has executed.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="mobileServiceLocalStore.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5d5f1-112">Die Instanz freigeben</span><span class="sxs-lookup"><span data-stu-id="5d5f1-112">Dispose the instance</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected virtual void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="abstract member Dispose : bool -&gt; unit&#xA;override this.Dispose : bool -&gt; unit" Usage="mobileServiceLocalStore.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing"></param>
        <summary>
            <span data-ttu-id="5d5f1-113">Ausgeführt, um das Bereinigen von Ressourcen</span><span class="sxs-lookup"><span data-stu-id="5d5f1-113">Executed to clean up resources</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnsureInitialized">
      <MemberSignature Language="C#" Value="protected void EnsureInitialized ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void EnsureInitialized() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore.EnsureInitialized" />
      <MemberSignature Language="VB.NET" Value="Protected Sub EnsureInitialized ()" />
      <MemberSignature Language="F#" Value="member this.EnsureInitialized : unit -&gt; unit" Usage="mobileServiceLocalStore.EnsureInitialized " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5d5f1-114">Löst eine Ausnahme aus, wenn der Speicher nicht initialisiert ist.</span><span class="sxs-lookup"><span data-stu-id="5d5f1-114">Throws an exception if store is not initialized.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task InitializeAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task InitializeAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore.InitializeAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function InitializeAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member InitializeAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.InitializeAsync : unit -&gt; System.Threading.Tasks.Task" Usage="mobileServiceLocalStore.InitializeAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore.InitializeAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore/&lt;InitializeAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5d5f1-115">Initialisiert den Speicher für die Verwendung an.</span><span class="sxs-lookup"><span data-stu-id="5d5f1-115">Initializes the store for use.</span></span>
            </summary>
        <returns><span data-ttu-id="5d5f1-116">Eine Aufgabe, die abgeschlossen wird, wenn der Informationsspeicher wurde initialisiert.</span><span class="sxs-lookup"><span data-stu-id="5d5f1-116">A task that completes when store has initialized.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Initialized">
      <MemberSignature Language="C#" Value="protected bool Initialized { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Initialized" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore.Initialized" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property Initialized As Boolean" />
      <MemberSignature Language="F#" Value="member this.Initialized : bool" Usage="Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore.Initialized" />
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
            <span data-ttu-id="5d5f1-117">Gibt an, ob Store oder nicht initialisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="5d5f1-117">Indicates whether store has been initialized or not.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LookupAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JObject&gt; LookupAsync (string tableName, string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JObject&gt; LookupAsync(string tableName, string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore.LookupAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function LookupAsync (tableName As String, id As String) As Task(Of JObject)" />
      <MemberSignature Language="F#" Value="abstract member LookupAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JObject&gt;" Usage="mobileServiceLocalStore.LookupAsync (tableName, id)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore.LookupAsync(System.String,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tableName"><span data-ttu-id="5d5f1-118">Der Name der lokalen Tabelle.</span><span class="sxs-lookup"><span data-stu-id="5d5f1-118">Name of the local table.</span></span></param>
        <param name="id"><span data-ttu-id="5d5f1-119">Die ID für das Objekt gelesen werden.</span><span class="sxs-lookup"><span data-stu-id="5d5f1-119">Id for the object to be read.</span></span></param>
        <summary>
            <span data-ttu-id="5d5f1-120">Liest ein einzelnes Element aus der lokalen Tabelle mit der angegebenen Id an.</span><span class="sxs-lookup"><span data-stu-id="5d5f1-120">Reads a single item from local table with specified id.</span></span>
            </summary>
        <returns><span data-ttu-id="5d5f1-121">Eine Aufgabe, die das Element zurückgibt, die aus lokalen Tabelle gelesen werden.</span><span class="sxs-lookup"><span data-stu-id="5d5f1-121">A task that returns the item read from local table.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnInitialize">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnInitialize ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnInitialize() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore.OnInitialize" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnInitialize () As Task" />
      <MemberSignature Language="F#" Value="abstract member OnInitialize : unit -&gt; System.Threading.Tasks.Task&#xA;override this.OnInitialize : unit -&gt; System.Threading.Tasks.Task" Usage="mobileServiceLocalStore.OnInitialize " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5d5f1-122">Beim Initialisieren, auf die Store-Instanz aufgerufen wird ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="5d5f1-122">Executed when Initilize is called on the store instance.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; ReadAsync (Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription query);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; ReadAsync(class Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore.ReadAsync(Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function ReadAsync (query As MobileServiceTableQueryDescription) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member ReadAsync : Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="mobileServiceLocalStore.ReadAsync query" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore.ReadAsync(Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="5d5f1-123">Instanz des <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription" /> , die für lokale Tabelle auszuführende Abfrage definiert.</span><span class="sxs-lookup"><span data-stu-id="5d5f1-123">Instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription" /> that defines the query to be executed on local table.</span></span></param>
        <summary>
            <span data-ttu-id="5d5f1-124">Liest Daten aus lokalen Tabelle durch Ausführen der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="5d5f1-124">Reads data from local table by executing the query.</span></span>
            </summary>
        <returns><span data-ttu-id="5d5f1-125">Eine Aufgabe, die mit Elementen, die mit der Abfrage übereinstimmenden Instanz JObject oder JArray zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="5d5f1-125">A task that returns instance of JObject or JArray with items matching the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task UpsertAsync (string tableName, System.Collections.Generic.IEnumerable&lt;Newtonsoft.Json.Linq.JObject&gt; items, bool ignoreMissingColumns);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpsertAsync(string tableName, class System.Collections.Generic.IEnumerable`1&lt;class Newtonsoft.Json.Linq.JObject&gt; items, bool ignoreMissingColumns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore.UpsertAsync(System.String,System.Collections.Generic.IEnumerable{Newtonsoft.Json.Linq.JObject},System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function UpsertAsync (tableName As String, items As IEnumerable(Of JObject), ignoreMissingColumns As Boolean) As Task" />
      <MemberSignature Language="F#" Value="abstract member UpsertAsync : string * seq&lt;Newtonsoft.Json.Linq.JObject&gt; * bool -&gt; System.Threading.Tasks.Task" Usage="mobileServiceLocalStore.UpsertAsync (tableName, items, ignoreMissingColumns)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore.UpsertAsync(System.String,System.Collections.Generic.IEnumerable{Newtonsoft.Json.Linq.JObject},System.Boolean)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="items" Type="System.Collections.Generic.IEnumerable&lt;Newtonsoft.Json.Linq.JObject&gt;" />
        <Parameter Name="ignoreMissingColumns" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="tableName"><span data-ttu-id="5d5f1-126">Der Name der lokalen Tabelle.</span><span class="sxs-lookup"><span data-stu-id="5d5f1-126">Name of the local table.</span></span></param>
        <param name="items"><span data-ttu-id="5d5f1-127">Eine Liste von Elementen, die eingefügt werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d5f1-127">A list of items to be inserted.</span></span></param>
        <param name="ignoreMissingColumns">
          <span data-ttu-id="5d5f1-128"><code>true</code>Wenn die zusätzlichen Eigenschaften Elements ignoriert werden können; <code>false</code> andernfalls.</span><span class="sxs-lookup"><span data-stu-id="5d5f1-128"><code>true</code> if the extra properties on item can be ignored; <code>false</code> otherwise.</span></span></param>
        <summary>
            <span data-ttu-id="5d5f1-129">Aktualisieren oder Daten in die lokale Tabelle einfügt.</span><span class="sxs-lookup"><span data-stu-id="5d5f1-129">Updates or inserts data in local table.</span></span>
            </summary>
        <returns><span data-ttu-id="5d5f1-130">Eine Aufgabe, die beim Element schließt wurde Upserted in lokalen Tabelle.</span><span class="sxs-lookup"><span data-stu-id="5d5f1-130">A task that completes when item has been upserted in local table.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>