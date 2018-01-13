<Type Name="IMobileServiceLocalStore" FullName="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore">
  <TypeSignature Language="C#" Value="public interface IMobileServiceLocalStore : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMobileServiceLocalStore implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMobileServiceLocalStore&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IMobileServiceLocalStore = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="e06fb-101">Ermöglicht das Speichern und Lesen von Daten in den lokalen Tabellen.</span><span class="sxs-lookup"><span data-stu-id="e06fb-101">Allows saving and reading data in the local tables.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription query);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(class Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore.DeleteAsync(Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteAsync (query As MobileServiceTableQueryDescription) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceLocalStore.DeleteAsync query" />
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
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="e06fb-102">Instanz von<see cref="T:Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription" /></span><span class="sxs-lookup"><span data-stu-id="e06fb-102">Instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription" /></span></span></param>
        <summary>
            <span data-ttu-id="e06fb-103">Löscht alle Elemente aus der lokalen Tabelle, die der Abfrage entsprechen.</span><span class="sxs-lookup"><span data-stu-id="e06fb-103">Deletes all the items from local table that match the query.</span></span>
            </summary>
        <returns><span data-ttu-id="e06fb-104">Eine Aufgabe, die abgeschlossen wird, wenn Delete für lokale Tabelle ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="e06fb-104">A task that completes when delete has been executed on local table.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (string tableName, System.Collections.Generic.IEnumerable&lt;string&gt; ids);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(string tableName, class System.Collections.Generic.IEnumerable`1&lt;string&gt; ids) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore.DeleteAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteAsync (tableName As String, ids As IEnumerable(Of String)) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceLocalStore.DeleteAsync (tableName, ids)" />
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
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="ids" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="tableName"><span data-ttu-id="e06fb-105">Der Name der lokalen Tabelle.</span><span class="sxs-lookup"><span data-stu-id="e06fb-105">Name of the local table.</span></span></param>
        <param name="ids"><span data-ttu-id="e06fb-106">Eine Liste der Ids der Elemente, die gelöscht werden</span><span class="sxs-lookup"><span data-stu-id="e06fb-106">A list of ids of the items to be deleted</span></span></param>
        <summary>
            <span data-ttu-id="e06fb-107">Löscht Elemente aus der lokalen Tabelle mit der angegebenen Liste von ids</span><span class="sxs-lookup"><span data-stu-id="e06fb-107">Deletes items from local table with the given list of ids</span></span>
            </summary>
        <returns><span data-ttu-id="e06fb-108">Löschen Sie eine Aufgabe, die beim Abschluss Abfrage ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="e06fb-108">A task that completes when delete query has executed.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task InitializeAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task InitializeAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore.InitializeAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function InitializeAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member InitializeAsync : unit -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceLocalStore.InitializeAsync " />
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
            <span data-ttu-id="e06fb-109">Initialisiert den Speicher für die Verwendung an.</span><span class="sxs-lookup"><span data-stu-id="e06fb-109">Initializes the store for use.</span></span>
            </summary>
        <returns><span data-ttu-id="e06fb-110">Eine Aufgabe, die abgeschlossen wird, wenn der Informationsspeicher wurde initialisiert.</span><span class="sxs-lookup"><span data-stu-id="e06fb-110">A task that completes when store has initialized.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LookupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JObject&gt; LookupAsync (string tableName, string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JObject&gt; LookupAsync(string tableName, string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore.LookupAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function LookupAsync (tableName As String, id As String) As Task(Of JObject)" />
      <MemberSignature Language="F#" Value="abstract member LookupAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JObject&gt;" Usage="iMobileServiceLocalStore.LookupAsync (tableName, id)" />
      <MemberType>Method</MemberType>
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
        <param name="tableName"><span data-ttu-id="e06fb-111">Der Name der lokalen Tabelle.</span><span class="sxs-lookup"><span data-stu-id="e06fb-111">Name of the local table.</span></span></param>
        <param name="id"><span data-ttu-id="e06fb-112">Die ID für das Objekt gelesen werden.</span><span class="sxs-lookup"><span data-stu-id="e06fb-112">Id for the object to be read.</span></span></param>
        <summary>
            <span data-ttu-id="e06fb-113">Liest ein einzelnes Element aus der lokalen Tabelle mit der angegebenen Id an.</span><span class="sxs-lookup"><span data-stu-id="e06fb-113">Reads a single item from local table with specified id.</span></span>
            </summary>
        <returns><span data-ttu-id="e06fb-114">Eine Aufgabe, die das Element zurückgibt, die aus lokalen Tabelle gelesen werden.</span><span class="sxs-lookup"><span data-stu-id="e06fb-114">A task that returns the item read from local table.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; ReadAsync (Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription query);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; ReadAsync(class Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore.ReadAsync(Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadAsync (query As MobileServiceTableQueryDescription) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member ReadAsync : Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceLocalStore.ReadAsync query" />
      <MemberType>Method</MemberType>
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
        <param name="query"><span data-ttu-id="e06fb-115">Instanz des <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription" /> , die für lokale Tabelle auszuführende Abfrage definiert.</span><span class="sxs-lookup"><span data-stu-id="e06fb-115">Instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription" /> that defines the query to be executed on local table.</span></span></param>
        <summary>
            <span data-ttu-id="e06fb-116">Liest Daten aus lokalen Tabelle durch Ausführen der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="e06fb-116">Reads data from local table by executing the query.</span></span>
            </summary>
        <returns><span data-ttu-id="e06fb-117">Eine Aufgabe, die mit Elementen, die mit der Abfrage übereinstimmenden Instanz JObject oder JArray zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="e06fb-117">A task that returns instance of JObject or JArray with items matching the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpsertAsync (string tableName, System.Collections.Generic.IEnumerable&lt;Newtonsoft.Json.Linq.JObject&gt; items, bool ignoreMissingColumns);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpsertAsync(string tableName, class System.Collections.Generic.IEnumerable`1&lt;class Newtonsoft.Json.Linq.JObject&gt; items, bool ignoreMissingColumns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore.UpsertAsync(System.String,System.Collections.Generic.IEnumerable{Newtonsoft.Json.Linq.JObject},System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpsertAsync (tableName As String, items As IEnumerable(Of JObject), ignoreMissingColumns As Boolean) As Task" />
      <MemberSignature Language="F#" Value="abstract member UpsertAsync : string * seq&lt;Newtonsoft.Json.Linq.JObject&gt; * bool -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceLocalStore.UpsertAsync (tableName, items, ignoreMissingColumns)" />
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
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="items" Type="System.Collections.Generic.IEnumerable&lt;Newtonsoft.Json.Linq.JObject&gt;" />
        <Parameter Name="ignoreMissingColumns" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="tableName"><span data-ttu-id="e06fb-118">Der Name der lokalen Tabelle.</span><span class="sxs-lookup"><span data-stu-id="e06fb-118">Name of the local table.</span></span></param>
        <param name="items"><span data-ttu-id="e06fb-119">Eine Liste von Elementen, die eingefügt werden soll.</span><span class="sxs-lookup"><span data-stu-id="e06fb-119">A list of items to be inserted.</span></span></param>
        <param name="ignoreMissingColumns">
          <span data-ttu-id="e06fb-120"><code>true</code>Wenn die zusätzlichen Eigenschaften Elements ignoriert werden können; <code>false</code> andernfalls.</span><span class="sxs-lookup"><span data-stu-id="e06fb-120"><code>true</code> if the extra properties on item can be ignored; <code>false</code> otherwise.</span></span></param>
        <summary>
            <span data-ttu-id="e06fb-121">Aktualisieren oder Daten in die lokale Tabelle einfügt.</span><span class="sxs-lookup"><span data-stu-id="e06fb-121">Updates or inserts data in local table.</span></span>
            </summary>
        <returns><span data-ttu-id="e06fb-122">Eine Aufgabe, die beim Element schließt wurde Upserted in lokalen Tabelle.</span><span class="sxs-lookup"><span data-stu-id="e06fb-122">A task that completes when item has been upserted in local table.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>