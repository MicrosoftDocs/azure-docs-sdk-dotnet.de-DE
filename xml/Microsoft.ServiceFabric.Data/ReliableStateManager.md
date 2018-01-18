<Type Name="ReliableStateManager" FullName="Microsoft.ServiceFabric.Data.ReliableStateManager">
  <TypeSignature Language="C#" Value="public class ReliableStateManager : Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;, Microsoft.ServiceFabric.Data.IReliableStateManagerReplica2" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi ReliableStateManager extends System.Object implements class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;class Microsoft.ServiceFabric.Data.IReliableState&gt;, class Microsoft.ServiceFabric.Data.IReliableStateManager, class Microsoft.ServiceFabric.Data.IReliableStateManagerReplica, class Microsoft.ServiceFabric.Data.IReliableStateManagerReplica2, class Microsoft.ServiceFabric.Data.IStateProviderReplica, class Microsoft.ServiceFabric.Data.IStateProviderReplica2" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.ReliableStateManager" />
  <TypeSignature Language="VB.NET" Value="Public Class ReliableStateManager&#xA;Implements IAsyncEnumerable(Of IReliableState), IReliableStateManagerReplica2" />
  <TypeSignature Language="F#" Value="type ReliableStateManager = class&#xA;    interface IReliableStateManagerReplica2&#xA;    interface IReliableStateManagerReplica&#xA;    interface IStateProviderReplica&#xA;    interface IReliableStateManager&#xA;    interface IAsyncEnumerable&lt;IReliableState&gt;&#xA;    interface IStateProviderReplica2" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.IReliableStateManagerReplica2</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para>
            <span data-ttu-id="66d95-101">Die ReliableStateManager-Klasse ist verantwortlich für die Verwaltung von <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> für ein Replikat des Diensts.</span><span class="sxs-lookup"><span data-stu-id="66d95-101">The ReliableStateManager class is responsible for managing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> for a service replica.</span></span>
            <span data-ttu-id="66d95-102">Jedes Replikat in einem Dienst hat seinen eigenen <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> und <see cref="T:Microsoft.ServiceFabric.Data.ReliableStateManager" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-102">Each replica in a service has its own <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> and <see cref="T:Microsoft.ServiceFabric.Data.ReliableStateManager" />.</span></span> 
            <span data-ttu-id="66d95-103"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />zählen <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />, <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" />, oder eine beliebige <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1" /> Typen.</span><span class="sxs-lookup"><span data-stu-id="66d95-103"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> can include <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />, <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" />, or any <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1" /> types.</span></span>
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReliableStateManager (System.Fabric.StatefulServiceContext serviceContext, Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration configuration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.StatefulServiceContext serviceContext, class Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration configuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.#ctor(System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (serviceContext As StatefulServiceContext, Optional configuration As ReliableStateManagerConfiguration = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.ReliableStateManager : System.Fabric.StatefulServiceContext * Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration -&gt; Microsoft.ServiceFabric.Data.ReliableStateManager" Usage="new Microsoft.ServiceFabric.Data.ReliableStateManager (serviceContext, configuration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.StatefulServiceContext" />
        <Parameter Name="configuration" Type="Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration" />
      </Parameters>
      <Docs>
        <param name="serviceContext"><span data-ttu-id="66d95-104">Ein <see cref="T:System.Fabric.StatefulServiceContext" /> , beschreibt der Kontext.</span><span class="sxs-lookup"><span data-stu-id="66d95-104">A <see cref="T:System.Fabric.StatefulServiceContext" /> that describes the service context.</span></span></param>
        <param name="configuration"><span data-ttu-id="66d95-105">Konfigurationsparameter.</span><span class="sxs-lookup"><span data-stu-id="66d95-105">Configuration parameters.</span></span></param>
        <summary>
            <span data-ttu-id="66d95-106">Erstellen Sie eine neue ReliableStateManager.</span><span class="sxs-lookup"><span data-stu-id="66d95-106">Create a new ReliableStateManager.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BackupAsync (Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; backupCallback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task BackupAsync(class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; backupCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberSignature Language="VB.NET" Value="Public Function BackupAsync (backupCallback As Func(Of BackupInfo, CancellationToken, Task(Of Boolean))) As Task" />
      <MemberSignature Language="F#" Value="abstract member BackupAsync : Func&lt;Microsoft.ServiceFabric.Data.BackupInfo, System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.BackupAsync : Func&lt;Microsoft.ServiceFabric.Data.BackupInfo, System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; System.Threading.Tasks.Task" Usage="reliableStateManager.BackupAsync backupCallback" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupCallback" Type="System.Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="backupCallback"><span data-ttu-id="66d95-107">Rückruf, der aufgerufen wird, wenn sich der Sicherungsordner lokal erstellt wurde, und kann jetzt aus dem Knoten verschoben werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-107">Callback to be called when the backup folder has been created locally and is ready to be moved out of the node.</span></span></param>
        <summary>
            <span data-ttu-id="66d95-108">Führt eine vollständige Sicherung alle zuverlässigen Zustand, die von diesem verwaltet <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-108">Performs a full backup of all reliable state managed by this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />.</span></span>
            </summary>
        <returns><span data-ttu-id="66d95-109">Eine Aufgabe, die den asynchronen backup-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="66d95-109">Task that represents the asynchronous backup operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="66d95-110">Eine vollständige Sicherung wird mit einem Timeout einer Stunde ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="66d95-110">A FULL backup will be performed with a one-hour timeout.</span></span>
            <span data-ttu-id="66d95-111">Boolescher Wert zurückgegeben, die für die BackupCallback Geben Sie an, ob der Dienst konnte erfolgreich den Sicherungsordner in einem externen Speicherort zu verschieben.</span><span class="sxs-lookup"><span data-stu-id="66d95-111">Boolean returned by the backupCallback indicate whether the service was able to successfully move the backup folder to an external location.</span></span>
            <span data-ttu-id="66d95-112">Wenn "false" zurückgegeben wird, löst BackupAsync InvalidOperationException aus der entsprechenden Fehlermeldung BackupCallback "false" zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="66d95-112">If false is returned, BackupAsync throws InvalidOperationException with the relevant message indicating backupCallback returned false.</span></span>
            <span data-ttu-id="66d95-113">Darüber hinaus wird Sicherung als fehlgeschlagen markiert.</span><span class="sxs-lookup"><span data-stu-id="66d95-113">Also, backup will be marked as unsuccessful.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BackupAsync (Microsoft.ServiceFabric.Data.BackupOption option, TimeSpan timeout, System.Threading.CancellationToken cancellationToken, Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; backupCallback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task BackupAsync(valuetype Microsoft.ServiceFabric.Data.BackupOption option, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken, class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; backupCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberSignature Language="F#" Value="abstract member BackupAsync : Microsoft.ServiceFabric.Data.BackupOption * TimeSpan * System.Threading.CancellationToken * Func&lt;Microsoft.ServiceFabric.Data.BackupInfo, System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.BackupAsync : Microsoft.ServiceFabric.Data.BackupOption * TimeSpan * System.Threading.CancellationToken * Func&lt;Microsoft.ServiceFabric.Data.BackupInfo, System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; System.Threading.Tasks.Task" Usage="reliableStateManager.BackupAsync (option, timeout, cancellationToken, backupCallback)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="option" Type="Microsoft.ServiceFabric.Data.BackupOption" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="backupCallback" Type="System.Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="option"><span data-ttu-id="66d95-114">Der Typ der Sicherung ausführen.</span><span class="sxs-lookup"><span data-stu-id="66d95-114">The type of backup to perform.</span></span></param>
        <param name="timeout"><span data-ttu-id="66d95-115">Das Timeout für diesen Vorgang.</span><span class="sxs-lookup"><span data-stu-id="66d95-115">The timeout for this operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="66d95-116">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="66d95-116">The token to monitor for cancellation requests.</span></span></param>
        <param name="backupCallback"><span data-ttu-id="66d95-117">Rückruf, der aufgerufen wird, wenn sich der Sicherungsordner lokal erstellt wurde, und kann jetzt aus dem Knoten verschoben werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-117">Callback to be called when the backup folder has been created locally and is ready to be moved out of the node.</span></span></param>
        <summary>
            <span data-ttu-id="66d95-118">Führt eine Sicherung alle zuverlässige Status, die von diesem verwaltet <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-118">Performs a backup of all reliable state managed by this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />.</span></span>
            </summary>
        <returns><span data-ttu-id="66d95-119">Eine Aufgabe, die den asynchronen backup-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="66d95-119">Task that represents the asynchronous backup operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="66d95-120">Boolescher Wert zurückgegeben, die für die BackupCallback Geben Sie an, ob der Dienst konnte erfolgreich den Sicherungsordner in einem externen Speicherort zu verschieben.</span><span class="sxs-lookup"><span data-stu-id="66d95-120">Boolean returned by the backupCallback indicate whether the service was able to successfully move the backup folder to an external location.</span></span>
            <span data-ttu-id="66d95-121">Wenn "false" zurückgegeben wird, löst BackupAsync InvalidOperationException aus der entsprechenden Fehlermeldung BackupCallback "false" zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="66d95-121">If false is returned, BackupAsync throws InvalidOperationException with the relevant message indicating backupCallback returned false.</span></span>
            <span data-ttu-id="66d95-122">Darüber hinaus wird Sicherung als fehlgeschlagen markiert.</span><span class="sxs-lookup"><span data-stu-id="66d95-122">Also, backup will be marked as unsuccessful.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsyncEnumerator">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.IAsyncEnumerator&lt;Microsoft.ServiceFabric.Data.IReliableState&gt; GetAsyncEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Data.IAsyncEnumerator`1&lt;class Microsoft.ServiceFabric.Data.IReliableState&gt; GetAsyncEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.GetAsyncEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAsyncEnumerator () As IAsyncEnumerator(Of IReliableState)" />
      <MemberSignature Language="F#" Value="abstract member GetAsyncEnumerator : unit -&gt; Microsoft.ServiceFabric.Data.IAsyncEnumerator&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;&#xA;override this.GetAsyncEnumerator : unit -&gt; Microsoft.ServiceFabric.Data.IAsyncEnumerator&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;" Usage="reliableStateManager.GetAsyncEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IAsyncEnumerable`1.GetAsyncEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.IAsyncEnumerator&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="66d95-123">Gibt einen Enumerator zurück, der die Auflistung durchläuft.</span><span class="sxs-lookup"><span data-stu-id="66d95-123">Returns an enumerator that iterates through the collection.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="66d95-124">Ein <see cref="T:Microsoft.ServiceFabric.Data.IAsyncEnumerator`1" />-Objekt, das zum Durchlaufen der Auflistung verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="66d95-124">An <see cref="T:Microsoft.ServiceFabric.Data.IAsyncEnumerator`1" /> object that can be used to iterate through the collection.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <filterpriority><span data-ttu-id="66d95-125">1</span><span class="sxs-lookup"><span data-stu-id="66d95-125">1</span></span></filterpriority>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.CreateTransaction">
      <MemberSignature Language="C#" Value="Microsoft.ServiceFabric.Data.ITransaction IReliableStateManager.CreateTransaction ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class Microsoft.ServiceFabric.Data.ITransaction Microsoft.ServiceFabric.Data.IReliableStateManager.CreateTransaction() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#CreateTransaction" />
      <MemberSignature Language="VB.NET" Value="Function CreateTransaction () As ITransaction Implements IReliableStateManager.CreateTransaction" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.CreateTransaction</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.ITransaction</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="66d95-126">Erstellen Sie und starten Sie eine neue Transaktion, die zum Gruppieren von Operationen verwendet werden kann, um atomar ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-126">Create and start a new transaction that can be used to group operations to be performed atomically.</span></span>
            </summary>
        <returns><span data-ttu-id="66d95-127">Eine neue Transaktion.</span><span class="sxs-lookup"><span data-stu-id="66d95-127">A new transaction.</span></span></returns>
        <remarks>
            <span data-ttu-id="66d95-128">Vorgänge werden für die Transaktion hinzugefügt, durch das Übergeben der <see cref="T:Microsoft.ServiceFabric.Data.ITransaction" /> -Objekt in zuverlässigen Zustand Methoden.</span><span class="sxs-lookup"><span data-stu-id="66d95-128">Operations are added to the transaction by passing the <see cref="T:Microsoft.ServiceFabric.Data.ITransaction" /> object in to reliable state methods.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (string name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (name As String) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="66d95-129">Beim Angeben der <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typ Sie Fragen sich vielleicht für einen Klassentyp oder einen Schnittstellentyp aufweisen.</span><span class="sxs-lookup"><span data-stu-id="66d95-129">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="66d95-130"><para>Wenn Sie einen Klassentyp angeben, wird versucht, eine Instanz dieses Typs zurückzugeben. Wenn eine Instanz dieses Typs instanziiert werden kann (z. B. abstrakte Klasse, es ist kein geeigneter Konstruktor) ArgumentException ausgelöst wird. </para><para>Wenn Sie einen Schnittstellentyp angeben, versucht der Manager die Schnittstelle in einen konkreten Typ aufgelöst. Wenn Typzuordnung vom Benutzer angegeben wird, wird diese Methode die benutzerdefinierte Zuordnung verwenden, um den Typ (noch nicht unterstützt) aufzulösen. Wenn die Typzuordnung nicht angegeben wird, wird der Benutzer wählt diese Methode die standardmäßige Implementierung für die angegebene Schnittstelle. Wenn Sie der angegebenen Schnittstellentyp verfügt nicht über eine Standardimplementierung oder eine benutzerdefinierte Zuordnung für den Typ nicht angegeben ist, oder der Typ ist ungültig, löst diese Methode ArgumentException.</para></span><span class="sxs-lookup"><span data-stu-id="66d95-130"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="name">
            <span data-ttu-id="66d95-131">Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-131">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="66d95-132">Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.</span><span class="sxs-lookup"><span data-stu-id="66d95-132">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <summary>
            <span data-ttu-id="66d95-133">Ruft eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen, wenn es vorhanden ist, oder erstellt und wird zurückgegeben, wenn er nicht bereits vorhanden.</span><span class="sxs-lookup"><span data-stu-id="66d95-133">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="66d95-134">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="66d95-134">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="66d95-135">Das Ergebnis der Aufgabe ist die zuverlässige Status-Instanz.</span><span class="sxs-lookup"><span data-stu-id="66d95-135">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="66d95-136">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="66d95-136">This is an atomic operation.</span></span> <span data-ttu-id="66d95-137">Wenn ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> muss erstellt werden, wird entweder abgeschlossen und erfolgreich abgeschlossen oder er wird nicht erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-137">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="66d95-138"><paramref name="name" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="66d95-138"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="66d95-139">Eine Instanz des Typs <typeparamref name="T" /> kann nicht erstellt werden, oder die vorhandene <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht vom Typ <typeparamref name="T" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-139">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="66d95-140">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-140">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="66d95-141">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-141">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="66d95-142">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="66d95-142">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (Uri name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (name As Uri) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.Uri)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="66d95-143">Beim Angeben der <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typ Sie Fragen sich vielleicht für einen Klassentyp oder einen Schnittstellentyp aufweisen.</span><span class="sxs-lookup"><span data-stu-id="66d95-143">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="66d95-144"><para>Wenn Sie einen Klassentyp angeben, wird versucht, eine Instanz dieses Typs zurückzugeben. Wenn eine Instanz dieses Typs instanziiert werden kann (z. B. abstrakte Klasse, es ist kein geeigneter Konstruktor) ArgumentException ausgelöst wird. </para><para>Wenn Sie einen Schnittstellentyp angeben, versucht der Manager die Schnittstelle in einen konkreten Typ aufgelöst. Wenn Typzuordnung vom Benutzer angegeben wird, wird diese Methode die benutzerdefinierte Zuordnung verwenden, um den Typ (noch nicht unterstützt) aufzulösen. Wenn die Typzuordnung nicht angegeben wird, wird der Benutzer wählt diese Methode die standardmäßige Implementierung für die angegebene Schnittstelle. Wenn Sie der angegebenen Schnittstellentyp verfügt nicht über eine Standardimplementierung oder eine benutzerdefinierte Zuordnung für den Typ nicht angegeben ist, oder der Typ ist ungültig, löst diese Methode ArgumentException.</para></span><span class="sxs-lookup"><span data-stu-id="66d95-144"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="name">
            <span data-ttu-id="66d95-145">Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-145">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="66d95-146">Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.</span><span class="sxs-lookup"><span data-stu-id="66d95-146">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <summary>
            <span data-ttu-id="66d95-147">Ruft eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen, wenn es vorhanden ist, oder erstellt und wird zurückgegeben, wenn er nicht bereits vorhanden.</span><span class="sxs-lookup"><span data-stu-id="66d95-147">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="66d95-148">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="66d95-148">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="66d95-149">Das Ergebnis der Aufgabe ist die zuverlässige Status-Instanz.</span><span class="sxs-lookup"><span data-stu-id="66d95-149">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="66d95-150">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="66d95-150">This is an atomic operation.</span></span> <span data-ttu-id="66d95-151">Wenn ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> muss erstellt werden, wird entweder abgeschlossen und erfolgreich abgeschlossen oder er wird nicht erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-151">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="66d95-152"><paramref name="name" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="66d95-152"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="66d95-153">Eine Instanz des Typs <typeparamref name="T" /> kann nicht erstellt werden, oder die vorhandene <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht vom Typ <typeparamref name="T" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-153">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="66d95-154">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-154">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="66d95-155">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-155">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="66d95-156">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="66d95-156">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, string name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.String)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As String) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="66d95-157">Beim Angeben der <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typ Sie Fragen sich vielleicht für einen Klassentyp oder einen Schnittstellentyp aufweisen.</span><span class="sxs-lookup"><span data-stu-id="66d95-157">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="66d95-158"><para>Wenn Sie einen Klassentyp angeben, wird versucht, eine Instanz dieses Typs zurückzugeben. Wenn eine Instanz dieses Typs instanziiert werden kann (z. B. abstrakte Klasse, es ist kein geeigneter Konstruktor) ArgumentException ausgelöst wird. </para><para>Wenn Sie einen Schnittstellentyp angeben, versucht der Manager die Schnittstelle in einen konkreten Typ aufgelöst. Wenn Typzuordnung vom Benutzer angegeben wird, wird diese Methode die benutzerdefinierte Zuordnung verwenden, um den Typ (noch nicht unterstützt) aufzulösen. Wenn die Typzuordnung nicht angegeben wird, wird der Benutzer wählt diese Methode die standardmäßige Implementierung für die angegebene Schnittstelle. Wenn Sie der angegebenen Schnittstellentyp verfügt nicht über eine Standardimplementierung oder eine benutzerdefinierte Zuordnung für den Typ nicht angegeben ist, oder der Typ ist ungültig, löst diese Methode ArgumentException.</para></span><span class="sxs-lookup"><span data-stu-id="66d95-158"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="tx"><span data-ttu-id="66d95-159">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="66d95-159">Transaction to associate this operation with.</span></span></param>
        <param name="name">
            <span data-ttu-id="66d95-160">Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-160">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="66d95-161">Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.</span><span class="sxs-lookup"><span data-stu-id="66d95-161">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <summary>
            <span data-ttu-id="66d95-162">Ruft eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen, wenn es vorhanden ist, oder erstellt und wird zurückgegeben, wenn er nicht bereits vorhanden.</span><span class="sxs-lookup"><span data-stu-id="66d95-162">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="66d95-163">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="66d95-163">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="66d95-164">Das Ergebnis der Aufgabe ist die zuverlässige Status-Instanz.</span><span class="sxs-lookup"><span data-stu-id="66d95-164">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="66d95-165">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="66d95-165">This is an atomic operation.</span></span> <span data-ttu-id="66d95-166">Wenn ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> muss erstellt werden, wird entweder abgeschlossen und erfolgreich abgeschlossen oder er wird nicht erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-166">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span> <span data-ttu-id="66d95-167">Wenn diese Methode eine Ausnahme auslöst, muss die Transaktion abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="66d95-167">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="66d95-168"><paramref name="tx" />ist null, oder <paramref name="name" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="66d95-168"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="66d95-169">Eine Instanz des Typs <typeparamref name="T" /> kann nicht erstellt werden, oder die vorhandene <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht vom Typ <typeparamref name="T" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-169">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="66d95-170">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-170">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="66d95-171">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-171">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="66d95-172">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="66d95-172">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="66d95-173">Z. B. für die Transaktion verwendet bereits beendet: löschen oder zusichern.</span><span class="sxs-lookup"><span data-stu-id="66d95-173">For example, transaction used is already terminated: committed or aborted.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="66d95-174">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="66d95-174">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As Uri) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.Uri)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="66d95-175">Beim Angeben der <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typ Sie Fragen sich vielleicht für einen Klassentyp oder einen Schnittstellentyp aufweisen.</span><span class="sxs-lookup"><span data-stu-id="66d95-175">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="66d95-176"><para>Wenn Sie einen Klassentyp angeben, wird versucht, eine Instanz dieses Typs zurückzugeben. Wenn eine Instanz dieses Typs instanziiert werden kann (z. B. abstrakte Klasse, es ist kein geeigneter Konstruktor) ArgumentException ausgelöst wird. </para><para>Wenn Sie einen Schnittstellentyp angeben, versucht der Manager die Schnittstelle in einen konkreten Typ aufgelöst. Wenn Typzuordnung vom Benutzer angegeben wird, wird diese Methode die benutzerdefinierte Zuordnung verwenden, um den Typ (noch nicht unterstützt) aufzulösen. Wenn die Typzuordnung nicht angegeben wird, wird der Benutzer wählt diese Methode die standardmäßige Implementierung für die angegebene Schnittstelle. Wenn Sie der angegebenen Schnittstellentyp verfügt nicht über eine Standardimplementierung oder eine benutzerdefinierte Zuordnung für den Typ nicht angegeben ist, oder der Typ ist ungültig, löst diese Methode ArgumentException.</para></span><span class="sxs-lookup"><span data-stu-id="66d95-176"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="tx"><span data-ttu-id="66d95-177">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="66d95-177">Transaction to associate this operation with.</span></span></param>
        <param name="name">
            <span data-ttu-id="66d95-178">Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-178">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="66d95-179">Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.</span><span class="sxs-lookup"><span data-stu-id="66d95-179">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <summary>
            <span data-ttu-id="66d95-180">Ruft eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen, wenn es vorhanden ist, oder erstellt und wird zurückgegeben, wenn er nicht bereits vorhanden.</span><span class="sxs-lookup"><span data-stu-id="66d95-180">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="66d95-181">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="66d95-181">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="66d95-182">Das Ergebnis der Aufgabe ist die zuverlässige Status-Instanz.</span><span class="sxs-lookup"><span data-stu-id="66d95-182">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="66d95-183">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="66d95-183">This is an atomic operation.</span></span> <span data-ttu-id="66d95-184">Wenn ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> muss erstellt werden, wird entweder abgeschlossen und erfolgreich abgeschlossen oder er wird nicht erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-184">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span> <span data-ttu-id="66d95-185">Wenn diese Methode eine Ausnahme auslöst, muss die Transaktion abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="66d95-185">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="66d95-186"><paramref name="tx" />ist null, oder <paramref name="name" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="66d95-186"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="66d95-187">Eine Instanz des Typs <typeparamref name="T" /> kann nicht erstellt werden, oder die vorhandene <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht vom Typ <typeparamref name="T" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-187">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="66d95-188">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-188">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="66d95-189">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-189">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="66d95-190">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="66d95-190">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="66d95-191">Z. B. für die Transaktion verwendet bereits beendet: löschen oder zusichern.</span><span class="sxs-lookup"><span data-stu-id="66d95-191">For example, transaction used is already terminated: committed or aborted.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="66d95-192">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="66d95-192">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (string name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (name As String, timeout As TimeSpan) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.String,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="66d95-193">Beim Angeben der <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typ Sie Fragen sich vielleicht für einen Klassentyp oder einen Schnittstellentyp aufweisen.</span><span class="sxs-lookup"><span data-stu-id="66d95-193">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="66d95-194"><para>Wenn Sie einen Klassentyp angeben, wird versucht, eine Instanz dieses Typs zurückzugeben. Wenn eine Instanz dieses Typs instanziiert werden kann (z. B. abstrakte Klasse, es ist kein geeigneter Konstruktor) ArgumentException ausgelöst wird. </para><para>Wenn Sie einen Schnittstellentyp angeben, versucht der Manager die Schnittstelle in einen konkreten Typ aufgelöst. Wenn Typzuordnung vom Benutzer angegeben wird, wird diese Methode die benutzerdefinierte Zuordnung verwenden, um den Typ (noch nicht unterstützt) aufzulösen. Wenn die Typzuordnung nicht angegeben wird, wird der Benutzer wählt diese Methode die standardmäßige Implementierung für die angegebene Schnittstelle. Wenn Sie der angegebenen Schnittstellentyp verfügt nicht über eine Standardimplementierung oder eine benutzerdefinierte Zuordnung für den Typ nicht angegeben ist, oder der Typ ist ungültig, löst diese Methode ArgumentException.</para></span><span class="sxs-lookup"><span data-stu-id="66d95-194"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="name">
            <span data-ttu-id="66d95-195">Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-195">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="66d95-196">Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.</span><span class="sxs-lookup"><span data-stu-id="66d95-196">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <param name="timeout"><span data-ttu-id="66d95-197">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="66d95-197">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="66d95-198">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="66d95-198">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="66d95-199">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="66d95-199">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="66d95-200">Ruft eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen, wenn es vorhanden ist, oder erstellt und wird zurückgegeben, wenn er nicht bereits vorhanden.</span><span class="sxs-lookup"><span data-stu-id="66d95-200">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="66d95-201">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="66d95-201">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="66d95-202">Das Ergebnis der Aufgabe ist die zuverlässige Status-Instanz.</span><span class="sxs-lookup"><span data-stu-id="66d95-202">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="66d95-203">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="66d95-203">This is an atomic operation.</span></span> <span data-ttu-id="66d95-204">Wenn ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> muss erstellt werden, wird entweder abgeschlossen und erfolgreich abgeschlossen oder er wird nicht erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-204">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="66d95-205"><paramref name="name" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="66d95-205"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="66d95-206">Eine Instanz des Typs <typeparamref name="T" /> kann nicht erstellt werden, oder die vorhandene <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht vom Typ <typeparamref name="T" />, oder <paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="66d95-206">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="66d95-207">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-207">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="66d95-208">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-208">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="66d95-209">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="66d95-209">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (Uri name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (name As Uri, timeout As TimeSpan) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.Uri,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="66d95-210">Beim Angeben der <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typ Sie Fragen sich vielleicht für einen Klassentyp oder einen Schnittstellentyp aufweisen.</span><span class="sxs-lookup"><span data-stu-id="66d95-210">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="66d95-211"><para>Wenn Sie einen Klassentyp angeben, wird versucht, eine Instanz dieses Typs zurückzugeben. Wenn eine Instanz dieses Typs instanziiert werden kann (z. B. abstrakte Klasse, es ist kein geeigneter Konstruktor) ArgumentException ausgelöst wird. </para><para>Wenn Sie einen Schnittstellentyp angeben, versucht der Manager die Schnittstelle in einen konkreten Typ aufgelöst. Wenn Typzuordnung vom Benutzer angegeben wird, wird diese Methode die benutzerdefinierte Zuordnung verwenden, um den Typ (noch nicht unterstützt) aufzulösen. Wenn die Typzuordnung nicht angegeben wird, wird der Benutzer wählt diese Methode die standardmäßige Implementierung für die angegebene Schnittstelle. Wenn Sie der angegebenen Schnittstellentyp verfügt nicht über eine Standardimplementierung oder eine benutzerdefinierte Zuordnung für den Typ nicht angegeben ist, oder der Typ ist ungültig, löst diese Methode ArgumentException.</para></span><span class="sxs-lookup"><span data-stu-id="66d95-211"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="name">
            <span data-ttu-id="66d95-212">Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-212">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="66d95-213">Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.</span><span class="sxs-lookup"><span data-stu-id="66d95-213">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <param name="timeout"><span data-ttu-id="66d95-214">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="66d95-214">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="66d95-215">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="66d95-215">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="66d95-216">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="66d95-216">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="66d95-217">Ruft eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen, wenn es vorhanden ist, oder erstellt und wird zurückgegeben, wenn er nicht bereits vorhanden.</span><span class="sxs-lookup"><span data-stu-id="66d95-217">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="66d95-218">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="66d95-218">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="66d95-219">Das Ergebnis der Aufgabe ist die zuverlässige Status-Instanz.</span><span class="sxs-lookup"><span data-stu-id="66d95-219">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="66d95-220">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="66d95-220">This is an atomic operation.</span></span> <span data-ttu-id="66d95-221">Wenn ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> muss erstellt werden, wird entweder abgeschlossen und erfolgreich abgeschlossen oder er wird nicht erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-221">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="66d95-222"><paramref name="name" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="66d95-222"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="66d95-223">Eine Instanz des Typs <typeparamref name="T" /> kann nicht erstellt werden, oder die vorhandene <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht vom Typ <typeparamref name="T" />, oder <paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="66d95-223">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="66d95-224">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-224">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="66d95-225">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-225">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="66d95-226">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="66d95-226">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, string name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As String, timeout As TimeSpan) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.String,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="66d95-227">Beim Angeben der <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typ Sie Fragen sich vielleicht für einen Klassentyp oder einen Schnittstellentyp aufweisen.</span><span class="sxs-lookup"><span data-stu-id="66d95-227">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="66d95-228"><para>Wenn Sie einen Klassentyp angeben, wird versucht, eine Instanz dieses Typs zurückzugeben. Wenn eine Instanz dieses Typs instanziiert werden kann (z. B. abstrakte Klasse, es ist kein geeigneter Konstruktor) ArgumentException ausgelöst wird. </para><para>Wenn Sie einen Schnittstellentyp angeben, versucht der Manager die Schnittstelle in einen konkreten Typ aufgelöst. Wenn Typzuordnung vom Benutzer angegeben wird, wird diese Methode die benutzerdefinierte Zuordnung verwenden, um den Typ (noch nicht unterstützt) aufzulösen. Wenn die Typzuordnung nicht angegeben wird, wird der Benutzer wählt diese Methode die standardmäßige Implementierung für die angegebene Schnittstelle. Wenn Sie der angegebenen Schnittstellentyp verfügt nicht über eine Standardimplementierung oder eine benutzerdefinierte Zuordnung für den Typ nicht angegeben ist, oder der Typ ist ungültig, löst diese Methode ArgumentException.</para></span><span class="sxs-lookup"><span data-stu-id="66d95-228"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="tx"><span data-ttu-id="66d95-229">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="66d95-229">Transaction to associate this operation with.</span></span></param>
        <param name="name">
            <span data-ttu-id="66d95-230">Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-230">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="66d95-231">Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.</span><span class="sxs-lookup"><span data-stu-id="66d95-231">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <param name="timeout"><span data-ttu-id="66d95-232">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="66d95-232">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="66d95-233">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="66d95-233">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="66d95-234">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="66d95-234">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="66d95-235">Ruft eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen, wenn es vorhanden ist, oder erstellt und wird zurückgegeben, wenn er nicht bereits vorhanden.</span><span class="sxs-lookup"><span data-stu-id="66d95-235">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="66d95-236">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="66d95-236">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="66d95-237">Das Ergebnis der Aufgabe ist die zuverlässige Status-Instanz.</span><span class="sxs-lookup"><span data-stu-id="66d95-237">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="66d95-238">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="66d95-238">This is an atomic operation.</span></span> <span data-ttu-id="66d95-239">Wenn ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> muss erstellt werden, wird entweder abgeschlossen und erfolgreich abgeschlossen oder er wird nicht erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-239">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span> <span data-ttu-id="66d95-240">Wenn diese Methode eine Ausnahme auslöst, muss die Transaktion abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="66d95-240">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="66d95-241"><paramref name="tx" />ist null, oder <paramref name="name" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="66d95-241"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="66d95-242">Eine Instanz des Typs <typeparamref name="T" /> kann nicht erstellt werden, oder die vorhandene <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht vom Typ <typeparamref name="T" />, oder <paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="66d95-242">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="66d95-243">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-243">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="66d95-244">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-244">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="66d95-245">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="66d95-245">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="66d95-246">Z. B. für die Transaktion verwendet bereits beendet: löschen oder zusichern.</span><span class="sxs-lookup"><span data-stu-id="66d95-246">For example, transaction used is already terminated: committed or aborted.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="66d95-247">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="66d95-247">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As Uri, timeout As TimeSpan) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.Uri,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="66d95-248">Beim Angeben der <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typ Sie Fragen sich vielleicht für einen Klassentyp oder einen Schnittstellentyp aufweisen.</span><span class="sxs-lookup"><span data-stu-id="66d95-248">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="66d95-249"><para>Wenn Sie einen Klassentyp angeben, wird versucht, eine Instanz dieses Typs zurückzugeben. Wenn eine Instanz dieses Typs instanziiert werden kann (z. B. abstrakte Klasse, es ist kein geeigneter Konstruktor) ArgumentException ausgelöst wird. </para><para>Wenn Sie einen Schnittstellentyp angeben, versucht der Manager die Schnittstelle in einen konkreten Typ aufgelöst. Wenn Typzuordnung vom Benutzer angegeben wird, wird diese Methode die benutzerdefinierte Zuordnung verwenden, um den Typ (noch nicht unterstützt) aufzulösen. Wenn die Typzuordnung nicht angegeben wird, wird der Benutzer wählt diese Methode die standardmäßige Implementierung für die angegebene Schnittstelle. Wenn Sie der angegebenen Schnittstellentyp verfügt nicht über eine Standardimplementierung oder eine benutzerdefinierte Zuordnung für den Typ nicht angegeben ist, oder der Typ ist ungültig, löst diese Methode ArgumentException.</para></span><span class="sxs-lookup"><span data-stu-id="66d95-249"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="tx"><span data-ttu-id="66d95-250">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="66d95-250">Transaction to associate this operation with.</span></span></param>
        <param name="name">
            <span data-ttu-id="66d95-251">Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-251">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="66d95-252">Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.</span><span class="sxs-lookup"><span data-stu-id="66d95-252">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <param name="timeout"><span data-ttu-id="66d95-253">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="66d95-253">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="66d95-254">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="66d95-254">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="66d95-255">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="66d95-255">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="66d95-256">Ruft eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen, wenn es vorhanden ist, oder erstellt und wird zurückgegeben, wenn er nicht bereits vorhanden.</span><span class="sxs-lookup"><span data-stu-id="66d95-256">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="66d95-257">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="66d95-257">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="66d95-258">Das Ergebnis der Aufgabe ist die zuverlässige Status-Instanz.</span><span class="sxs-lookup"><span data-stu-id="66d95-258">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="66d95-259">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="66d95-259">This is an atomic operation.</span></span> <span data-ttu-id="66d95-260">Wenn ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> muss erstellt werden, wird entweder abgeschlossen und erfolgreich abgeschlossen oder er wird nicht erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-260">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span> <span data-ttu-id="66d95-261">Wenn diese Methode eine Ausnahme auslöst, muss die Transaktion abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="66d95-261">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="66d95-262"><paramref name="tx" />ist null, oder <paramref name="name" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="66d95-262"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="66d95-263">Eine Instanz des Typs <typeparamref name="T" /> kann nicht erstellt werden, oder die vorhandene <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht vom Typ <typeparamref name="T" />, oder <paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="66d95-263">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="66d95-264">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-264">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="66d95-265">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-265">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="66d95-266">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="66d95-266">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="66d95-267">Z. B. für die Transaktion verwendet bereits beendet: löschen oder zusichern.</span><span class="sxs-lookup"><span data-stu-id="66d95-267">For example, transaction used is already terminated: committed or aborted.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="66d95-268">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="66d95-268">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (string name);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (name As String) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="66d95-269">Der Name des zu entfernenden <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-269">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <summary>
            <span data-ttu-id="66d95-270">Entfernt die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen aus diesem Status-Manager.</span><span class="sxs-lookup"><span data-stu-id="66d95-270">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="66d95-271">Der Status wird dauerhaft aus dem persistenten Speicher und alle Replikate entfernt.</span><span class="sxs-lookup"><span data-stu-id="66d95-271">The state is permanently removed from persistent storage and all replicas.</span></span>
            </summary>
        <returns><span data-ttu-id="66d95-272">Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="66d95-272">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="66d95-273">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="66d95-273">This is an atomic operation.</span></span> <span data-ttu-id="66d95-274">Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> in intakt gelassen werden oder wird zusammen mit allen Zustand erfolgreich entfernt werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-274">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="66d95-275"><paramref name="name" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="66d95-275"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="66d95-276">Ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="66d95-276">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="66d95-277">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-277">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="66d95-278">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-278">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="66d95-279">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="66d95-279">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (Uri name);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (name As Uri) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.Uri)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="66d95-280">Der Name des zu entfernenden <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-280">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <summary>
            <span data-ttu-id="66d95-281">Entfernt die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen aus diesem Status-Manager.</span><span class="sxs-lookup"><span data-stu-id="66d95-281">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="66d95-282">Der Status wird dauerhaft aus dem persistenten Speicher und alle Replikate entfernt.</span><span class="sxs-lookup"><span data-stu-id="66d95-282">The state is permanently removed from persistent storage and all replicas.</span></span>
            </summary>
        <returns><span data-ttu-id="66d95-283">Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="66d95-283">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="66d95-284">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="66d95-284">This is an atomic operation.</span></span> <span data-ttu-id="66d95-285">Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> in intakt gelassen werden oder wird zusammen mit allen Zustand erfolgreich entfernt werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-285">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="66d95-286"><paramref name="name" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="66d95-286"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="66d95-287">Ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="66d95-287">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="66d95-288">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-288">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="66d95-289">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-289">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="66d95-290">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="66d95-290">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, string name);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.String)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (tx As ITransaction, name As String) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="66d95-291">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="66d95-291">Transaction to associate this operation with.</span></span></param>
        <param name="name"><span data-ttu-id="66d95-292">Der Name des zu entfernenden <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-292">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <summary>
            <span data-ttu-id="66d95-293">Entfernt die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen aus diesem Status-Manager.</span><span class="sxs-lookup"><span data-stu-id="66d95-293">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="66d95-294">Der Zustand ist endgültig aus dem persistenten Speicher und alle Replikate entfernt, wenn die Transaktion ein Commit ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="66d95-294">The state is permanently removed from persistent storage and all replicas when the transaction is committed.</span></span>
            </summary>
        <returns><span data-ttu-id="66d95-295">Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="66d95-295">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="66d95-296">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="66d95-296">This is an atomic operation.</span></span> <span data-ttu-id="66d95-297">Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> in intakt gelassen werden oder wird zusammen mit allen Zustand erfolgreich entfernt werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-297">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span> <span data-ttu-id="66d95-298">Wenn diese Methode eine Ausnahme auslöst, muss die Transaktion abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="66d95-298">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="66d95-299"><paramref name="tx" />ist null, oder <paramref name="name" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="66d95-299"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="66d95-300">Ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="66d95-300">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="66d95-301">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-301">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="66d95-302">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-302">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="66d95-303">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="66d95-303">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="66d95-304">Z. B. für die Transaktion verwendet bereits beendet: löschen oder zusichern.</span><span class="sxs-lookup"><span data-stu-id="66d95-304">For example, transaction used is already terminated: committed or aborted.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="66d95-305">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="66d95-305">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (tx As ITransaction, name As Uri) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Uri)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="66d95-306">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="66d95-306">Transaction to associate this operation with.</span></span></param>
        <param name="name"><span data-ttu-id="66d95-307">Der Name des zu entfernenden <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-307">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <summary>
            <span data-ttu-id="66d95-308">Entfernt die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen aus diesem Status-Manager.</span><span class="sxs-lookup"><span data-stu-id="66d95-308">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="66d95-309">Der Zustand ist endgültig aus dem persistenten Speicher und alle Replikate entfernt, wenn die Transaktion ein Commit ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="66d95-309">The state is permanently removed from persistent storage and all replicas when the transaction is committed.</span></span>
            </summary>
        <returns><span data-ttu-id="66d95-310">Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="66d95-310">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="66d95-311">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="66d95-311">This is an atomic operation.</span></span> <span data-ttu-id="66d95-312">Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> in intakt gelassen werden oder wird zusammen mit allen Zustand erfolgreich entfernt werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-312">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span> <span data-ttu-id="66d95-313">Wenn diese Methode eine Ausnahme auslöst, muss die Transaktion abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="66d95-313">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="66d95-314"><paramref name="tx" />ist null, oder <paramref name="name" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="66d95-314"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="66d95-315">Ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="66d95-315">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="66d95-316">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-316">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="66d95-317">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-317">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="66d95-318">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="66d95-318">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="66d95-319">Z. B. für die Transaktion verwendet bereits beendet: löschen oder zusichern.</span><span class="sxs-lookup"><span data-stu-id="66d95-319">For example, transaction used is already terminated: committed or aborted.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="66d95-320">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="66d95-320">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (string name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (name As String, timeout As TimeSpan) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.String,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="66d95-321">Der Name des zu entfernenden <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-321">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <param name="timeout"><span data-ttu-id="66d95-322">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="66d95-322">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="66d95-323">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="66d95-323">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="66d95-324">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="66d95-324">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="66d95-325">Entfernt die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen aus diesem Status-Manager.</span><span class="sxs-lookup"><span data-stu-id="66d95-325">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="66d95-326">Der Status wird dauerhaft aus dem persistenten Speicher und alle Replikate entfernt.</span><span class="sxs-lookup"><span data-stu-id="66d95-326">The state is permanently removed from persistent storage and all replicas.</span></span>
            </summary>
        <returns><span data-ttu-id="66d95-327">Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="66d95-327">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="66d95-328">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="66d95-328">This is an atomic operation.</span></span> <span data-ttu-id="66d95-329">Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> in intakt gelassen werden oder wird zusammen mit allen Zustand erfolgreich entfernt werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-329">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="66d95-330"><paramref name="name" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="66d95-330"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="66d95-331">Ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen ist nicht vorhanden, oder <paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="66d95-331">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="66d95-332">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-332">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="66d95-333">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-333">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="66d95-334">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="66d95-334">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (Uri name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (name As Uri, timeout As TimeSpan) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.Uri,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="66d95-335">Der Name des zu entfernenden <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-335">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <param name="timeout"><span data-ttu-id="66d95-336">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="66d95-336">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="66d95-337">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="66d95-337">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="66d95-338">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="66d95-338">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="66d95-339">Entfernt die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen aus diesem Status-Manager.</span><span class="sxs-lookup"><span data-stu-id="66d95-339">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="66d95-340">Der Status wird dauerhaft aus dem persistenten Speicher und alle Replikate entfernt.</span><span class="sxs-lookup"><span data-stu-id="66d95-340">The state is permanently removed from persistent storage and all replicas.</span></span>
            </summary>
        <returns><span data-ttu-id="66d95-341">Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="66d95-341">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="66d95-342">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="66d95-342">This is an atomic operation.</span></span> <span data-ttu-id="66d95-343">Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> in intakt gelassen werden oder wird zusammen mit allen Zustand erfolgreich entfernt werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-343">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="66d95-344"><paramref name="name" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="66d95-344"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="66d95-345">Ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen ist nicht vorhanden, oder <paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="66d95-345">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="66d95-346">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-346">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="66d95-347">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-347">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="66d95-348">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="66d95-348">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, string name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (tx As ITransaction, name As String, timeout As TimeSpan) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.String,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="66d95-349">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="66d95-349">Transaction to associate this operation with.</span></span></param>
        <param name="name"><span data-ttu-id="66d95-350">Der Name des zu entfernenden <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-350">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <param name="timeout"><span data-ttu-id="66d95-351">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="66d95-351">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="66d95-352">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="66d95-352">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="66d95-353">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="66d95-353">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="66d95-354">Entfernt die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen aus diesem Status-Manager.</span><span class="sxs-lookup"><span data-stu-id="66d95-354">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="66d95-355">Der Zustand ist endgültig aus dem persistenten Speicher und alle Replikate entfernt, wenn die Transaktion ein Commit ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="66d95-355">The state is permanently removed from persistent storage and all replicas when the transaction is committed.</span></span>
            </summary>
        <returns><span data-ttu-id="66d95-356">Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="66d95-356">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="66d95-357">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="66d95-357">This is an atomic operation.</span></span> <span data-ttu-id="66d95-358">Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> in intakt gelassen werden oder wird zusammen mit allen Zustand erfolgreich entfernt werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-358">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span> <span data-ttu-id="66d95-359">Wenn diese Methode eine Ausnahme auslöst, muss die Transaktion abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="66d95-359">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="66d95-360"><paramref name="tx" />ist null, oder <paramref name="name" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="66d95-360"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="66d95-361">Ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen ist nicht vorhanden, oder <paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="66d95-361">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="66d95-362">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-362">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="66d95-363">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-363">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="66d95-364">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="66d95-364">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="66d95-365">Z. B. für die Transaktion verwendet bereits beendet: löschen oder zusichern.</span><span class="sxs-lookup"><span data-stu-id="66d95-365">For example, transaction used is already terminated: committed or aborted.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="66d95-366">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="66d95-366">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (tx As ITransaction, name As Uri, timeout As TimeSpan) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Uri,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="66d95-367">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="66d95-367">Transaction to associate this operation with.</span></span></param>
        <param name="name"><span data-ttu-id="66d95-368">Der Name des zu entfernenden <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-368">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <param name="timeout"><span data-ttu-id="66d95-369">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="66d95-369">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="66d95-370">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="66d95-370">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="66d95-371">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="66d95-371">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="66d95-372">Entfernt die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen aus diesem Status-Manager.</span><span class="sxs-lookup"><span data-stu-id="66d95-372">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="66d95-373">Der Zustand ist endgültig aus dem persistenten Speicher und alle Replikate entfernt, wenn die Transaktion ein Commit ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="66d95-373">The state is permanently removed from persistent storage and all replicas when the transaction is committed.</span></span>
            </summary>
        <returns><span data-ttu-id="66d95-374">Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="66d95-374">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="66d95-375">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="66d95-375">This is an atomic operation.</span></span> <span data-ttu-id="66d95-376">Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> in intakt gelassen werden oder wird zusammen mit allen Zustand erfolgreich entfernt werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-376">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span> <span data-ttu-id="66d95-377">Wenn diese Methode eine Ausnahme auslöst, muss die Transaktion abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="66d95-377">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="66d95-378"><paramref name="tx" />ist null, oder <paramref name="name" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="66d95-378"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="66d95-379">Ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen ist nicht vorhanden, oder <paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="66d95-379">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="66d95-380">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-380">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="66d95-381">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-381">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="66d95-382">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="66d95-382">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="66d95-383">Z. B. für die Transaktion verwendet bereits beendet: löschen oder zusichern.</span><span class="sxs-lookup"><span data-stu-id="66d95-383">For example, transaction used is already terminated: committed or aborted.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="66d95-384">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="66d95-384">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.TryAddStateSerializer&lt;T&gt;">
      <MemberSignature Language="C#" Value="bool IReliableStateManager.TryAddStateSerializer&lt;T&gt; (Microsoft.ServiceFabric.Data.IStateSerializer&lt;T&gt; stateSerializer);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance bool Microsoft.ServiceFabric.Data.IReliableStateManager.TryAddStateSerializer&lt;T&gt;(class Microsoft.ServiceFabric.Data.IStateSerializer`1&lt;!!T&gt; stateSerializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#TryAddStateSerializer``1(Microsoft.ServiceFabric.Data.IStateSerializer{``0})" />
      <MemberSignature Language="VB.NET" Value="Function TryAddStateSerializer(Of T) (stateSerializer As IStateSerializer(Of T)) As Boolean Implements IReliableStateManager.TryAddStateSerializer" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryAddStateSerializer``1(Microsoft.ServiceFabric.Data.IStateSerializer{``0})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="stateSerializer" Type="Microsoft.ServiceFabric.Data.IStateSerializer&lt;T&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="66d95-385">Typ, der serialisiert und deserialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-385">Type that will be serialized and de-serialized.</span></span></typeparam>
        <param name="stateSerializer">
            <span data-ttu-id="66d95-386">Das Serialisierungsprogramm Zustand hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-386">The state serializer to be added.</span></span>
            </param>
        <summary>
            <span data-ttu-id="66d95-387">Fügt eine Status-Serialisierer hinzu.</span><span class="sxs-lookup"><span data-stu-id="66d95-387">Adds a state serializer.</span></span>
            <span data-ttu-id="66d95-388">Wird für alle Instanzen von zuverlässigen Auflistung hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="66d95-388">Adds it for all reliable collection instances.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="66d95-389">"True", wenn das Serialisierungsprogramm hinzugefügt wurde.</span><span class="sxs-lookup"><span data-stu-id="66d95-389">True if the serializer was added.</span></span>
            <span data-ttu-id="66d95-390">"False", wenn eine Serailizer bereits registriert ist.</span><span class="sxs-lookup"><span data-stu-id="66d95-390">False if a serailizer is already registered.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="66d95-391">Diese Methode kann nur in InitializeStateSerializers aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-391">This method can only be called in InitializeStateSerializers.</span></span>
            <span data-ttu-id="66d95-392">Instanz bestimmten Zustand Serialisierungsprogramme haben immer Vorrang vor.</span><span class="sxs-lookup"><span data-stu-id="66d95-392">Instance specific state serializers always take precedence.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; IReliableStateManager.TryGetAsync&lt;T&gt; (string name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!!T&gt;&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#TryGetAsync``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Function TryGetAsync(Of T As IReliableState) (name As String) As Task(Of ConditionalValue(Of T)) Implements IReliableStateManager.TryGetAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync``1(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="66d95-393">Wenn Sie den Typ angeben, können Sie einen konkreten Typ oder einen Schnittstellentyp anfordern.</span><span class="sxs-lookup"><span data-stu-id="66d95-393">When specifying the type, you may ask for either a concrete type or an interface type.</span></span> <span data-ttu-id="66d95-394">Das abgerufene Objekt wird für den angegebenen Typ umgewandelt werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-394">The retrieved object will be cast to the given type.</span></span>
            </typeparam>
        <param name="name">
            <span data-ttu-id="66d95-395">Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-395">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="66d95-396">Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.</span><span class="sxs-lookup"><span data-stu-id="66d95-396">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <summary>
            <span data-ttu-id="66d95-397">Versucht, erhalten eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="66d95-397">Attempts to get an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name.</span></span>
            </summary>
        <returns><span data-ttu-id="66d95-398">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="66d95-398">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="66d95-399">Das Ergebnis der Aufgabe ist ein Tupel, die angibt, ob die zuverlässige Zustand gefunden wurde, und wenn dies der Fall ist die Instanz.</span><span class="sxs-lookup"><span data-stu-id="66d95-399">The task result is a tuple indicating whether the reliable state was found, and if so the instance.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="66d95-400"><paramref name="name" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="66d95-400"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="66d95-401">Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht in den Typ <typeparamref name="T" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-401">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not convertible to type <typeparamref name="T" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="66d95-402">Ausnahme gibt an, dass der Status-Manager abrufen eine zuverlässige Auflistung kann nicht.</span><span class="sxs-lookup"><span data-stu-id="66d95-402">Exception indicates that the State Manager cannot retrive a reliable collection.</span></span>
            <span data-ttu-id="66d95-403"><see cref="T:System.Fabric.FabricNotReadableException" />ausgelöst werden kann, in allen <see cref="T:System.Fabric.ReplicaRole" />s.</span><span class="sxs-lookup"><span data-stu-id="66d95-403"><see cref="T:System.Fabric.FabricNotReadableException" /> can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="66d95-404">Beispielsweise, wenn eine <see cref="F:System.Fabric.ReplicaRole.Primary" /> oder <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> verliert <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-404">For example, when a <see cref="F:System.Fabric.ReplicaRole.Primary" /> or <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> looses <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="66d95-405">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="66d95-405">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; IReliableStateManager.TryGetAsync&lt;T&gt; (Uri name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!!T&gt;&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#TryGetAsync``1(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Function TryGetAsync(Of T As IReliableState) (name As Uri) As Task(Of ConditionalValue(Of T)) Implements IReliableStateManager.TryGetAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync``1(System.Uri)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="66d95-406">Wenn Sie den Typ angeben, können Sie einen konkreten Typ oder einen Schnittstellentyp anfordern.</span><span class="sxs-lookup"><span data-stu-id="66d95-406">When specifying the type, you may ask for either a concrete type or an interface type.</span></span> <span data-ttu-id="66d95-407">Das abgerufene Objekt wird für den angegebenen Typ umgewandelt werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-407">The retrieved object will be cast to the given type.</span></span>
            </typeparam>
        <param name="name">
            <span data-ttu-id="66d95-408">Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-408">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="66d95-409">Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.</span><span class="sxs-lookup"><span data-stu-id="66d95-409">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <summary>
            <span data-ttu-id="66d95-410">Versucht, erhalten eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="66d95-410">Attempts to get an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name.</span></span>
            </summary>
        <returns><span data-ttu-id="66d95-411">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="66d95-411">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="66d95-412">Das Ergebnis der Aufgabe ist ein Tupel, die angibt, ob die zuverlässige Zustand gefunden wurde, und wenn dies der Fall ist die Instanz.</span><span class="sxs-lookup"><span data-stu-id="66d95-412">The task result is a tuple indicating whether the reliable state was found, and if so the instance.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="66d95-413"><paramref name="name" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="66d95-413"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="66d95-414">Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht in den Typ <typeparamref name="T" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-414">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not convertible to type <typeparamref name="T" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="66d95-415">Ausnahme gibt an, dass der Status-Manager abrufen eine zuverlässige Auflistung kann nicht.</span><span class="sxs-lookup"><span data-stu-id="66d95-415">Exception indicates that the State Manager cannot retrive a reliable collection.</span></span>
            <span data-ttu-id="66d95-416"><see cref="T:System.Fabric.FabricNotReadableException" />ausgelöst werden kann, in allen <see cref="T:System.Fabric.ReplicaRole" />s.</span><span class="sxs-lookup"><span data-stu-id="66d95-416"><see cref="T:System.Fabric.FabricNotReadableException" /> can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="66d95-417">Beispielsweise, wenn eine <see cref="F:System.Fabric.ReplicaRole.Primary" /> oder <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> verliert <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-417">For example, when a <see cref="F:System.Fabric.ReplicaRole.Primary" /> or <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> looses <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="66d95-418">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="66d95-418">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.Abort">
      <MemberSignature Language="C#" Value="void IStateProviderReplica.Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Data.IStateProviderReplica.Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IStateProviderReplica#Abort" />
      <MemberSignature Language="VB.NET" Value="Sub Abort () Implements IStateProviderReplica.Abort" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.Abort</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="66d95-419">Bricht einen Zustand Anbieter Replikat erzwungen ab.</span><span class="sxs-lookup"><span data-stu-id="66d95-419">Forcefully abort the state provider replica.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="66d95-420">Dies tritt normalerweise auf, wenn auf dem Knoten ein dauerhafter Fehler erkannt wird oder wenn das Replikat Lifecycle aufgrund von internen Fehlern von Service Fabric zuverlässig verwalten kann.</span><span class="sxs-lookup"><span data-stu-id="66d95-420">This generally occurs when a permanent fault is detected on the node, or when Service Fabric cannot reliably manage the replica's lifecycle due to internal failures.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.ChangeRoleAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.ChangeRoleAsync (System.Fabric.ReplicaRole newRole, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.ChangeRoleAsync(valuetype System.Fabric.ReplicaRole newRole, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IStateProviderReplica#ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="newRole" Type="System.Fabric.ReplicaRole" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="newRole"><span data-ttu-id="66d95-421">Die neue replikatrolle, z. B. Primary oder Secondary sein.</span><span class="sxs-lookup"><span data-stu-id="66d95-421">The new replica role, such as primary or secondary.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="66d95-422">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="66d95-422">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="66d95-423">Dem State-Anbieter-Replikat zu benachrichtigen, dass seine Rolle geändert hat, z. B. um Primary oder Secondary sein.</span><span class="sxs-lookup"><span data-stu-id="66d95-423">Notify the state provider replica that its role is changing, for example to Primary or Secondary.</span></span>
            </summary>
        <returns><span data-ttu-id="66d95-424">Eine Aufgabe, die den asynchronen Rolle Änderungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="66d95-424">Task that represents the asynchronous change role operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.CloseAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IStateProviderReplica#CloseAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.CloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="66d95-425">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="66d95-425">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="66d95-426">Geschlossen Sie das Replikat der State-Anbieter ordnungsgemäß werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-426">Gracefully close the state provider replica.</span></span>
            </summary>
        <returns><span data-ttu-id="66d95-427">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="66d95-427">Task that represents the asynchronous close operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="66d95-428">Dies tritt normalerweise auf, wenn das Replikat Code ein Upgrade wird, das Replikat aufgrund des Lastenausgleichs verschoben wird oder ein vorübergehender Fehler erkannt wird.</span><span class="sxs-lookup"><span data-stu-id="66d95-428">This generally occurs when the replica's code is being upgrade, the replica is being moved due to load balancing, or a transient fault is detected.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.Initialize">
      <MemberSignature Language="C#" Value="void IStateProviderReplica.Initialize (System.Fabric.StatefulServiceInitializationParameters initializationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Data.IStateProviderReplica.Initialize(class System.Fabric.StatefulServiceInitializationParameters initializationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IStateProviderReplica#Initialize(System.Fabric.StatefulServiceInitializationParameters)" />
      <MemberSignature Language="VB.NET" Value="Sub Initialize (initializationParameters As StatefulServiceInitializationParameters) Implements IStateProviderReplica.Initialize" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.Initialize(System.Fabric.StatefulServiceInitializationParameters)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="initializationParameters" Type="System.Fabric.StatefulServiceInitializationParameters" />
      </Parameters>
      <Docs>
        <param name="initializationParameters"><span data-ttu-id="66d95-429">Initialisierungsinformationen für Dienst z. B. Dienstnamen, Partitions-Id, Replikat-Id und Code-Paketinformationen.</span><span class="sxs-lookup"><span data-stu-id="66d95-429">Service initialization information such as service name, partition id, replica id, and code package information.</span></span></param>
        <summary>
            <span data-ttu-id="66d95-430">Das Status Anbieter Replikat unter Verwendung des Diensts Initialisierung zu initialisieren.</span><span class="sxs-lookup"><span data-stu-id="66d95-430">Initialize the state provider replica using the service initialization information.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="66d95-431">Keine komplexen Verarbeitung sollte bei der Initialisierung erfolgen.</span><span class="sxs-lookup"><span data-stu-id="66d95-431">No complex processing should be done during Initialize.</span></span> <span data-ttu-id="66d95-432">Teuer oder lang ausgeführte Initialisierung sollte im OpenAsync erfolgen.</span><span class="sxs-lookup"><span data-stu-id="66d95-432">Expensive or long-running initialization should be done in OpenAsync.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.OpenAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt; IStateProviderReplica.OpenAsync (System.Fabric.ReplicaOpenMode openMode, System.Fabric.IStatefulServicePartition partition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.IReplicator&gt; Microsoft.ServiceFabric.Data.IStateProviderReplica.OpenAsync(valuetype System.Fabric.ReplicaOpenMode openMode, class System.Fabric.IStatefulServicePartition partition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IStateProviderReplica#OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="openMode" Type="System.Fabric.ReplicaOpenMode" />
        <Parameter Name="partition" Type="System.Fabric.IStatefulServicePartition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="openMode"><span data-ttu-id="66d95-433">Gibt an, ob es sich um ein neues oder vorhandenes Replikat handelt.</span><span class="sxs-lookup"><span data-stu-id="66d95-433">Indicates whether this is a new or existing replica.</span></span></param>
        <param name="partition"><span data-ttu-id="66d95-434">Die Partition dieses Replikat gehört.</span><span class="sxs-lookup"><span data-stu-id="66d95-434">The partition this replica belongs to.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="66d95-435">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="66d95-435">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="66d95-436">Öffnen Sie das Replikat des Status-Anbieter für die Verwendung an.</span><span class="sxs-lookup"><span data-stu-id="66d95-436">Open the state provider replica for use.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="66d95-437">Eine Aufgabe, die den asynchronen Öffnungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="66d95-437">Task that represents the asynchronous open operation.</span></span> <span data-ttu-id="66d95-438">Das Ergebnis enthält Replikator für die Replikation des Status zwischen Replikaten Anbieter Status in der Partition verantwortlich.</span><span class="sxs-lookup"><span data-stu-id="66d95-438">The result contains the replicator responsible for replicating state between other state provider replicas in the partition.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="66d95-439">Erweiterte Status anbieterinitialisierung, die Aufgaben zu diesem Zeitpunkt gestartet werden können.</span><span class="sxs-lookup"><span data-stu-id="66d95-439">Extended state provider initialization tasks can be started at this time.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDataLossAsync">
      <MemberSignature Language="C#" Value="public Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; OnDataLossAsync { set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; OnDataLossAsync" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManager.OnDataLossAsync" />
      <MemberSignature Language="VB.NET" Value="Public Property OnDataLossAsync As Func(Of CancellationToken, Task(Of Boolean))" />
      <MemberSignature Language="F#" Value="member this.OnDataLossAsync : Func&lt;System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt;" Usage="Microsoft.ServiceFabric.Data.ReliableStateManager.OnDataLossAsync" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Data.IStateProviderReplica.OnDataLossAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66d95-440">Legen Sie diese Eigenschaft, um Benachrichtigungen zu Wenn dies <see cref="T:Microsoft.ServiceFabric.Data.IStateProviderReplica" /> vermutet Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="66d95-440">Set this property to receive notification when this <see cref="T:Microsoft.ServiceFabric.Data.IStateProviderReplica" /> suspects data loss.</span></span>
            </summary>
        <value>
            <span data-ttu-id="66d95-441">Funktion, die als Teil der Verarbeitung von mutmaßlicher Verlust aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="66d95-441">Function called as part of suspected data loss processing.</span></span>
            </value>
        <remarks>
          <para>
            <span data-ttu-id="66d95-442">OnDataLossAsync Funktion nimmt CancellationToken und muss eine Aufgabe zurückgeben, die die asynchrone Verarbeitung des Ereignisses darstellt.</span><span class="sxs-lookup"><span data-stu-id="66d95-442">OnDataLossAsync function takes in CancellationToken and needs to return a Task that represents the asynchronous processing of the event.</span></span>
            <span data-ttu-id="66d95-443">Rückgabe "true" gibt an, dass die zuverlässige Status-Manager-Zustand wiederhergestellt wurde.</span><span class="sxs-lookup"><span data-stu-id="66d95-443">Returning true indicates that the reliable state manager's state has been restored.</span></span>
            <span data-ttu-id="66d95-444">Rückgabe "false" gibt an, dass die zuverlässige Status-Manager-Zustand nicht geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="66d95-444">Returning false indicates that the reliable state manager's state has not been changed.</span></span>
            </para>
          <para>
            <span data-ttu-id="66d95-445">Der übergebene Delegat sollte das angegebene Abbruchtoken, das auf abbruchanforderungen überwachen.</span><span class="sxs-lookup"><span data-stu-id="66d95-445">The passed delegate should monitor the given cancellation token for cancellation requests.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRestoreCompletedAsync">
      <MemberSignature Language="C#" Value="public Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; OnRestoreCompletedAsync { set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; OnRestoreCompletedAsync" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManager.OnRestoreCompletedAsync" />
      <MemberSignature Language="VB.NET" Value="Public Property OnRestoreCompletedAsync As Func(Of CancellationToken, Task)" />
      <MemberSignature Language="F#" Value="member this.OnRestoreCompletedAsync : Func&lt;System.Threading.CancellationToken, System.Threading.Tasks.Task&gt;" Usage="Microsoft.ServiceFabric.Data.ReliableStateManager.OnRestoreCompletedAsync" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Data.IStateProviderReplica2.OnRestoreCompletedAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66d95-446">Funktion mit dem Namen nach Wiederherstellung wurde auf dem Replikat ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="66d95-446">Function called post restore has been performed on the replica.</span></span>
            </summary>
        <value>
            <span data-ttu-id="66d95-447">Funktion wird aufgerufen, wenn der Status des Replikats durch das Framework erfolgreich wiederhergestellt wurde</span><span class="sxs-lookup"><span data-stu-id="66d95-447">Function called when the replica's state has been restored successfully by the framework</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (string backupFolderPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RestoreAsync(string backupFolderPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.RestoreAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RestoreAsync (backupFolderPath As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member RestoreAsync : string -&gt; System.Threading.Tasks.Task&#xA;override this.RestoreAsync : string -&gt; System.Threading.Tasks.Task" Usage="reliableStateManager.RestoreAsync backupFolderPath" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupFolderPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupFolderPath">
            <span data-ttu-id="66d95-448">Das Verzeichnis, in dem das Replikat aus wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-448">The directory where the replica is to be restored from.</span></span>
            <span data-ttu-id="66d95-449">Dieser Parameter kann nicht null, leer oder enthält nur Leerzeichen.</span><span class="sxs-lookup"><span data-stu-id="66d95-449">This parameter cannot be null, empty or contain just whitespace.</span></span> <span data-ttu-id="66d95-450">UNC-Pfade können auch angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-450">UNC paths may also be provided.</span></span>
            </param>
        <summary>
            <span data-ttu-id="66d95-451">Wiederherstellen eine Sicherung von <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" /> oder <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-451">Restore a backup taken by <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" /> or <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />.</span></span>
            </summary>
        <returns><span data-ttu-id="66d95-452">Eine Aufgabe, die den asynchronen Restore-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="66d95-452">Task that represents the asynchronous restore operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="66d95-453">Eine sichere Sicherung wird ausgeführt werden, was bedeutet, dass die Wiederherstellung wird nur ausgeführt wird, wenn Sie die Daten zum Wiederherstellen nach Status, der das aktuelle Replikat ist.</span><span class="sxs-lookup"><span data-stu-id="66d95-453">A safe backup will be performed, meaning the restore will only be completed if the data to restore is ahead of state of the current replica.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (string backupFolderPath, Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RestoreAsync(string backupFolderPath, valuetype Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.RestoreAsync(System.String,Microsoft.ServiceFabric.Data.RestorePolicy,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RestoreAsync : string * Microsoft.ServiceFabric.Data.RestorePolicy * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RestoreAsync : string * Microsoft.ServiceFabric.Data.RestorePolicy * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="reliableStateManager.RestoreAsync (backupFolderPath, restorePolicy, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync(System.String,Microsoft.ServiceFabric.Data.RestorePolicy,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupFolderPath" Type="System.String" />
        <Parameter Name="restorePolicy" Type="Microsoft.ServiceFabric.Data.RestorePolicy" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="backupFolderPath">
            <span data-ttu-id="66d95-454">Das Verzeichnis, in dem das Replikat aus wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-454">The directory where the replica is to be restored from.</span></span>
            <span data-ttu-id="66d95-455">Dieser Parameter kann nicht null, leer oder enthält nur Leerzeichen.</span><span class="sxs-lookup"><span data-stu-id="66d95-455">This parameter cannot be null, empty or contain just whitespace.</span></span> <span data-ttu-id="66d95-456">UNC-Pfade können auch angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="66d95-456">UNC paths may also be provided.</span></span>
            </param>
        <param name="restorePolicy"><span data-ttu-id="66d95-457">Die Richtlinie für die Wiederherstellung.</span><span class="sxs-lookup"><span data-stu-id="66d95-457">The restore policy.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="66d95-458">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="66d95-458">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="66d95-459">Wiederherstellen eine Sicherung von <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" /> oder <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />.</span><span class="sxs-lookup"><span data-stu-id="66d95-459">Restore a backup taken by <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" /> or <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />.</span></span>
            </summary>
        <returns><span data-ttu-id="66d95-460">Eine Aufgabe, die den asynchronen Restore-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="66d95-460">Task that represents the asynchronous restore operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateManagerChanged">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; StateManagerChanged;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; StateManagerChanged" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Data.ReliableStateManager.StateManagerChanged" />
      <MemberSignature Language="VB.NET" Value="Public Custom Event StateManagerChanged As EventHandler(Of NotifyStateManagerChangedEventArgs) " />
      <MemberSignature Language="F#" Value="member this.StateManagerChanged : EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; " Usage="member this.StateManagerChanged : System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.ServiceFabric.Data.IReliableStateManager.StateManagerChanged</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66d95-461">Tritt auf, wenn der Status-Manager geändert wird.</span><span class="sxs-lookup"><span data-stu-id="66d95-461">Occurs when the state manager changes.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="66d95-462">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="66d95-462">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="TransactionChanged">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; TransactionChanged;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; TransactionChanged" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Data.ReliableStateManager.TransactionChanged" />
      <MemberSignature Language="VB.NET" Value="Public Custom Event TransactionChanged As EventHandler(Of NotifyTransactionChangedEventArgs) " />
      <MemberSignature Language="F#" Value="member this.TransactionChanged : EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; " Usage="member this.TransactionChanged : System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.ServiceFabric.Data.IReliableStateManager.TransactionChanged</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66d95-463">Tritt auf, wenn eine Transaktion ändert.</span><span class="sxs-lookup"><span data-stu-id="66d95-463">Occurs when a transaction changes.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="66d95-464">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="66d95-464">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>