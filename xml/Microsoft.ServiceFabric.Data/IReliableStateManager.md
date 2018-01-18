<Type Name="IReliableStateManager" FullName="Microsoft.ServiceFabric.Data.IReliableStateManager">
  <TypeSignature Language="C#" Value="public interface IReliableStateManager : Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReliableStateManager implements class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;class Microsoft.ServiceFabric.Data.IReliableState&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReliableStateManager&#xA;Implements IAsyncEnumerable(Of IReliableState)" />
  <TypeSignature Language="F#" Value="type IReliableStateManager = interface&#xA;    interface IAsyncEnumerable&lt;IReliableState&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="5af25-101">Verwaltet alle <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> für ein Replikat des Diensts.</span><span class="sxs-lookup"><span data-stu-id="5af25-101">Manages all <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> for a service replica.</span></span>
            <span data-ttu-id="5af25-102">Jedes Replikat in einem Dienst verfügt über einen eigenen Status-Manager, und daher einen eigenen Satz von <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-102">Each replica in a service has its own state manager and thus its own set of <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateTransaction">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.ITransaction CreateTransaction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Data.ITransaction CreateTransaction() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.CreateTransaction" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateTransaction () As ITransaction" />
      <MemberSignature Language="F#" Value="abstract member CreateTransaction : unit -&gt; Microsoft.ServiceFabric.Data.ITransaction" Usage="iReliableStateManager.CreateTransaction " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.ITransaction</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5af25-103">Erstellen Sie und starten Sie eine neue Transaktion, die zum Gruppieren von Operationen verwendet werden kann, um atomar ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-103">Create and start a new transaction that can be used to group operations to be performed atomically.</span></span>
            </summary>
        <returns><span data-ttu-id="5af25-104">Eine neue Transaktion.</span><span class="sxs-lookup"><span data-stu-id="5af25-104">A new transaction.</span></span></returns>
        <remarks>
            <span data-ttu-id="5af25-105">Vorgänge werden für die Transaktion hinzugefügt, durch das Übergeben der <see cref="T:Microsoft.ServiceFabric.Data.ITransaction" /> -Objekt in zuverlässigen Zustand Methoden.</span><span class="sxs-lookup"><span data-stu-id="5af25-105">Operations are added to the transaction by passing the <see cref="T:Microsoft.ServiceFabric.Data.ITransaction" /> object in to reliable state methods.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (string name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (name As String) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : string -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="5af25-106">Beim Angeben der <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typ Sie Fragen sich vielleicht für einen Klassentyp oder einen Schnittstellentyp aufweisen.</span><span class="sxs-lookup"><span data-stu-id="5af25-106">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="5af25-107"><para>Wenn Sie einen Klassentyp angeben, wird versucht, eine Instanz dieses Typs zurückzugeben. Wenn eine Instanz dieses Typs instanziiert werden kann (z. B. abstrakte Klasse, es ist kein geeigneter Konstruktor) ArgumentException ausgelöst wird. </para><para>Wenn Sie einen Schnittstellentyp angeben, versucht der Manager die Schnittstelle in einen konkreten Typ aufgelöst. Wenn Typzuordnung vom Benutzer angegeben wird, wird diese Methode die benutzerdefinierte Zuordnung verwenden, um den Typ (noch nicht unterstützt) aufzulösen. Wenn die Typzuordnung nicht angegeben wird, wird der Benutzer wählt diese Methode die standardmäßige Implementierung für die angegebene Schnittstelle. Wenn Sie der angegebenen Schnittstellentyp verfügt nicht über eine Standardimplementierung oder eine benutzerdefinierte Zuordnung für den Typ nicht angegeben ist, oder der Typ ist ungültig, löst diese Methode ArgumentException.</para></span><span class="sxs-lookup"><span data-stu-id="5af25-107"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="name">
            <span data-ttu-id="5af25-108">Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-108">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="5af25-109">Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.</span><span class="sxs-lookup"><span data-stu-id="5af25-109">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5af25-110">Ruft eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen, wenn es vorhanden ist, oder erstellt und wird zurückgegeben, wenn er nicht bereits vorhanden.</span><span class="sxs-lookup"><span data-stu-id="5af25-110">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="5af25-111">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5af25-111">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="5af25-112">Das Ergebnis der Aufgabe ist die zuverlässige Status-Instanz.</span><span class="sxs-lookup"><span data-stu-id="5af25-112">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="5af25-113">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="5af25-113">This is an atomic operation.</span></span> <span data-ttu-id="5af25-114">Wenn ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> muss erstellt werden, wird entweder abgeschlossen und erfolgreich abgeschlossen oder er wird nicht erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-114">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="5af25-115"><paramref name="name" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="5af25-115"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="5af25-116">Eine Instanz des Typs <typeparamref name="T" /> kann nicht erstellt werden, oder die vorhandene <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht vom Typ <typeparamref name="T" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-116">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="5af25-117">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-117">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="5af25-118">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-118">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="5af25-119">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="5af25-119">Indicates that the Reliable State Manager is closed.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="5af25-120">Der Vorgang wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="5af25-120">The operation has been internally faulted by the system.</span></span> <span data-ttu-id="5af25-121">Wiederholen Sie den Vorgang</span><span class="sxs-lookup"><span data-stu-id="5af25-121">Retry the operation</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (Uri name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (name As Uri) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Uri -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="5af25-122">Beim Angeben der <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typ Sie Fragen sich vielleicht für einen Klassentyp oder einen Schnittstellentyp aufweisen.</span><span class="sxs-lookup"><span data-stu-id="5af25-122">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="5af25-123"><para>Wenn Sie einen Klassentyp angeben, wird versucht, eine Instanz dieses Typs zurückzugeben. Wenn eine Instanz dieses Typs instanziiert werden kann (z. B. abstrakte Klasse, es ist kein geeigneter Konstruktor) ArgumentException ausgelöst wird. </para><para>Wenn Sie einen Schnittstellentyp angeben, versucht der Manager die Schnittstelle in einen konkreten Typ aufgelöst. Wenn Typzuordnung vom Benutzer angegeben wird, wird diese Methode die benutzerdefinierte Zuordnung verwenden, um den Typ (noch nicht unterstützt) aufzulösen. Wenn die Typzuordnung nicht angegeben wird, wird der Benutzer wählt diese Methode die standardmäßige Implementierung für die angegebene Schnittstelle. Wenn Sie der angegebenen Schnittstellentyp verfügt nicht über eine Standardimplementierung oder eine benutzerdefinierte Zuordnung für den Typ nicht angegeben ist, oder der Typ ist ungültig, löst diese Methode ArgumentException.</para></span><span class="sxs-lookup"><span data-stu-id="5af25-123"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="name">
            <span data-ttu-id="5af25-124">Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-124">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="5af25-125">Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.</span><span class="sxs-lookup"><span data-stu-id="5af25-125">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5af25-126">Ruft eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen, wenn es vorhanden ist, oder erstellt und wird zurückgegeben, wenn er nicht bereits vorhanden.</span><span class="sxs-lookup"><span data-stu-id="5af25-126">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="5af25-127">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5af25-127">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="5af25-128">Das Ergebnis der Aufgabe ist die zuverlässige Status-Instanz.</span><span class="sxs-lookup"><span data-stu-id="5af25-128">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="5af25-129">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="5af25-129">This is an atomic operation.</span></span> <span data-ttu-id="5af25-130">Wenn ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> muss erstellt werden, wird entweder abgeschlossen und erfolgreich abgeschlossen oder er wird nicht erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-130">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="5af25-131"><paramref name="name" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="5af25-131"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="5af25-132">Eine Instanz des Typs <typeparamref name="T" /> kann nicht erstellt werden, oder die vorhandene <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht vom Typ <typeparamref name="T" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-132">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="5af25-133">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-133">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="5af25-134">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-134">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="5af25-135">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="5af25-135">Indicates that the Reliable State Manager is closed.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="5af25-136">Der Vorgang wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="5af25-136">The operation has been internally faulted by the system.</span></span> <span data-ttu-id="5af25-137">Wiederholen Sie den Vorgang</span><span class="sxs-lookup"><span data-stu-id="5af25-137">Retry the operation</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, string name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As String) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Microsoft.ServiceFabric.Data.ITransaction * string -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync (tx, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="5af25-138">Beim Angeben der <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typ Sie Fragen sich vielleicht für einen Klassentyp oder einen Schnittstellentyp aufweisen.</span><span class="sxs-lookup"><span data-stu-id="5af25-138">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="5af25-139"><para>Wenn Sie einen Klassentyp angeben, wird versucht, eine Instanz dieses Typs zurückzugeben. Wenn eine Instanz dieses Typs instanziiert werden kann (z. B. abstrakte Klasse, es ist kein geeigneter Konstruktor) ArgumentException ausgelöst wird. </para><para>Wenn Sie einen Schnittstellentyp angeben, versucht der Manager die Schnittstelle in einen konkreten Typ aufgelöst. Wenn Typzuordnung vom Benutzer angegeben wird, wird diese Methode die benutzerdefinierte Zuordnung verwenden, um den Typ (noch nicht unterstützt) aufzulösen. Wenn die Typzuordnung nicht angegeben wird, wird der Benutzer wählt diese Methode die standardmäßige Implementierung für die angegebene Schnittstelle. Wenn Sie der angegebenen Schnittstellentyp verfügt nicht über eine Standardimplementierung oder eine benutzerdefinierte Zuordnung für den Typ nicht angegeben ist, oder der Typ ist ungültig, löst diese Methode ArgumentException.</para></span><span class="sxs-lookup"><span data-stu-id="5af25-139"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="tx"><span data-ttu-id="5af25-140">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="5af25-140">Transaction to associate this operation with.</span></span></param>
        <param name="name">
            <span data-ttu-id="5af25-141">Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-141">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="5af25-142">Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.</span><span class="sxs-lookup"><span data-stu-id="5af25-142">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5af25-143">Ruft eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen, wenn es vorhanden ist, oder erstellt und wird zurückgegeben, wenn er nicht bereits vorhanden.</span><span class="sxs-lookup"><span data-stu-id="5af25-143">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="5af25-144">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5af25-144">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="5af25-145">Das Ergebnis der Aufgabe ist die zuverlässige Status-Instanz.</span><span class="sxs-lookup"><span data-stu-id="5af25-145">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="5af25-146">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="5af25-146">This is an atomic operation.</span></span> <span data-ttu-id="5af25-147">Wenn ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> muss erstellt werden, wird entweder abgeschlossen und erfolgreich abgeschlossen oder er wird nicht erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-147">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span> <span data-ttu-id="5af25-148">Wenn diese Methode eine Ausnahme auslöst, muss die Transaktion abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="5af25-148">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="5af25-149"><paramref name="tx" />ist null, oder <paramref name="name" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="5af25-149"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="5af25-150">Eine Instanz des Typs <typeparamref name="T" /> kann nicht erstellt werden, oder die vorhandene <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht vom Typ <typeparamref name="T" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-150">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="5af25-151">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-151">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="5af25-152">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-152">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="5af25-153">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="5af25-153">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="5af25-154">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="5af25-154">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="5af25-155">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="5af25-155">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="5af25-156">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="5af25-156">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="5af25-157">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5af25-157">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="5af25-158">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="5af25-158">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As Uri) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Microsoft.ServiceFabric.Data.ITransaction * Uri -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync (tx, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="5af25-159">Beim Angeben der <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typ Sie Fragen sich vielleicht für einen Klassentyp oder einen Schnittstellentyp aufweisen.</span><span class="sxs-lookup"><span data-stu-id="5af25-159">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="5af25-160"><para>Wenn Sie einen Klassentyp angeben, wird versucht, eine Instanz dieses Typs zurückzugeben. Wenn eine Instanz dieses Typs instanziiert werden kann (z. B. abstrakte Klasse, es ist kein geeigneter Konstruktor) ArgumentException ausgelöst wird. </para><para>Wenn Sie einen Schnittstellentyp angeben, versucht der Manager die Schnittstelle in einen konkreten Typ aufgelöst. Wenn Typzuordnung vom Benutzer angegeben wird, wird diese Methode die benutzerdefinierte Zuordnung verwenden, um den Typ (noch nicht unterstützt) aufzulösen. Wenn die Typzuordnung nicht angegeben wird, wird der Benutzer wählt diese Methode die standardmäßige Implementierung für die angegebene Schnittstelle. Wenn Sie der angegebenen Schnittstellentyp verfügt nicht über eine Standardimplementierung oder eine benutzerdefinierte Zuordnung für den Typ nicht angegeben ist, oder der Typ ist ungültig, löst diese Methode ArgumentException.</para></span><span class="sxs-lookup"><span data-stu-id="5af25-160"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="tx"><span data-ttu-id="5af25-161">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="5af25-161">Transaction to associate this operation with.</span></span></param>
        <param name="name">
            <span data-ttu-id="5af25-162">Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-162">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="5af25-163">Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.</span><span class="sxs-lookup"><span data-stu-id="5af25-163">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5af25-164">Ruft eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen, wenn es vorhanden ist, oder erstellt und wird zurückgegeben, wenn er nicht bereits vorhanden.</span><span class="sxs-lookup"><span data-stu-id="5af25-164">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="5af25-165">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5af25-165">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="5af25-166">Das Ergebnis der Aufgabe ist die zuverlässige Status-Instanz.</span><span class="sxs-lookup"><span data-stu-id="5af25-166">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="5af25-167">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="5af25-167">This is an atomic operation.</span></span> <span data-ttu-id="5af25-168">Wenn ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> muss erstellt werden, wird entweder abgeschlossen und erfolgreich abgeschlossen oder er wird nicht erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-168">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span> <span data-ttu-id="5af25-169">Wenn diese Methode eine Ausnahme auslöst, muss die Transaktion abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="5af25-169">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="5af25-170"><paramref name="tx" />ist null, oder <paramref name="name" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="5af25-170"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="5af25-171">Eine Instanz des Typs <typeparamref name="T" /> kann nicht erstellt werden, oder die vorhandene <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht vom Typ <typeparamref name="T" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-171">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="5af25-172">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-172">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="5af25-173">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-173">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="5af25-174">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="5af25-174">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="5af25-175">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="5af25-175">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="5af25-176">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="5af25-176">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="5af25-177">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="5af25-177">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="5af25-178">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5af25-178">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="5af25-179">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="5af25-179">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (string name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (name As String, timeout As TimeSpan) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync (name, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="5af25-180">Beim Angeben der <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typ Sie Fragen sich vielleicht für einen Klassentyp oder einen Schnittstellentyp aufweisen.</span><span class="sxs-lookup"><span data-stu-id="5af25-180">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="5af25-181"><para>Wenn Sie einen Klassentyp angeben, wird versucht, eine Instanz dieses Typs zurückzugeben. Wenn eine Instanz dieses Typs instanziiert werden kann (z. B. abstrakte Klasse, es ist kein geeigneter Konstruktor) ArgumentException ausgelöst wird. </para><para>Wenn Sie einen Schnittstellentyp angeben, versucht der Manager die Schnittstelle in einen konkreten Typ aufgelöst. Wenn Typzuordnung vom Benutzer angegeben wird, wird diese Methode die benutzerdefinierte Zuordnung verwenden, um den Typ (noch nicht unterstützt) aufzulösen. Wenn die Typzuordnung nicht angegeben wird, wird der Benutzer wählt diese Methode die standardmäßige Implementierung für die angegebene Schnittstelle. Wenn Sie der angegebenen Schnittstellentyp verfügt nicht über eine Standardimplementierung oder eine benutzerdefinierte Zuordnung für den Typ nicht angegeben ist, oder der Typ ist ungültig, löst diese Methode ArgumentException.</para></span><span class="sxs-lookup"><span data-stu-id="5af25-181"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="name">
            <span data-ttu-id="5af25-182">Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-182">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="5af25-183">Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.</span><span class="sxs-lookup"><span data-stu-id="5af25-183">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <param name="timeout"><span data-ttu-id="5af25-184">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="5af25-184">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="5af25-185">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="5af25-185">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="5af25-186">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="5af25-186">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="5af25-187">Ruft eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen, wenn es vorhanden ist, oder erstellt und wird zurückgegeben, wenn er nicht bereits vorhanden.</span><span class="sxs-lookup"><span data-stu-id="5af25-187">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="5af25-188">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5af25-188">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="5af25-189">Das Ergebnis der Aufgabe ist die zuverlässige Status-Instanz.</span><span class="sxs-lookup"><span data-stu-id="5af25-189">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="5af25-190">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="5af25-190">This is an atomic operation.</span></span> <span data-ttu-id="5af25-191">Wenn ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> muss erstellt werden, wird entweder abgeschlossen und erfolgreich abgeschlossen oder er wird nicht erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-191">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="5af25-192"><paramref name="name" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="5af25-192"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="5af25-193">Eine Instanz des Typs <typeparamref name="T" /> kann nicht erstellt werden, oder die vorhandene <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht vom Typ <typeparamref name="T" />, oder <paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="5af25-193">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="5af25-194">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-194">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="5af25-195">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-195">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="5af25-196">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="5af25-196">Indicates that the Reliable State Manager is closed.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="5af25-197">Der Vorgang wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="5af25-197">The operation has been internally faulted by the system.</span></span> <span data-ttu-id="5af25-198">Wiederholen Sie den Vorgang</span><span class="sxs-lookup"><span data-stu-id="5af25-198">Retry the operation</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (Uri name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (name As Uri, timeout As TimeSpan) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Uri * TimeSpan -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync (name, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="5af25-199">Beim Angeben der <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typ Sie Fragen sich vielleicht für einen Klassentyp oder einen Schnittstellentyp aufweisen.</span><span class="sxs-lookup"><span data-stu-id="5af25-199">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="5af25-200"><para>Wenn Sie einen Klassentyp angeben, wird versucht, eine Instanz dieses Typs zurückzugeben. Wenn eine Instanz dieses Typs instanziiert werden kann (z. B. abstrakte Klasse, es ist kein geeigneter Konstruktor) ArgumentException ausgelöst wird. </para><para>Wenn Sie einen Schnittstellentyp angeben, versucht der Manager die Schnittstelle in einen konkreten Typ aufgelöst. Wenn Typzuordnung vom Benutzer angegeben wird, wird diese Methode die benutzerdefinierte Zuordnung verwenden, um den Typ (noch nicht unterstützt) aufzulösen. Wenn die Typzuordnung nicht angegeben wird, wird der Benutzer wählt diese Methode die standardmäßige Implementierung für die angegebene Schnittstelle. Wenn Sie der angegebenen Schnittstellentyp verfügt nicht über eine Standardimplementierung oder eine benutzerdefinierte Zuordnung für den Typ nicht angegeben ist, oder der Typ ist ungültig, löst diese Methode ArgumentException.</para></span><span class="sxs-lookup"><span data-stu-id="5af25-200"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="name">
            <span data-ttu-id="5af25-201">Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-201">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="5af25-202">Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.</span><span class="sxs-lookup"><span data-stu-id="5af25-202">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <param name="timeout"><span data-ttu-id="5af25-203">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="5af25-203">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="5af25-204">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="5af25-204">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="5af25-205">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="5af25-205">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="5af25-206">Ruft eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen, wenn es vorhanden ist, oder erstellt und wird zurückgegeben, wenn er nicht bereits vorhanden.</span><span class="sxs-lookup"><span data-stu-id="5af25-206">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="5af25-207">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5af25-207">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="5af25-208">Das Ergebnis der Aufgabe ist die zuverlässige Status-Instanz.</span><span class="sxs-lookup"><span data-stu-id="5af25-208">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="5af25-209">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="5af25-209">This is an atomic operation.</span></span> <span data-ttu-id="5af25-210">Wenn ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> muss erstellt werden, wird entweder abgeschlossen und erfolgreich abgeschlossen oder er wird nicht erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-210">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="5af25-211"><paramref name="name" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="5af25-211"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="5af25-212">Eine Instanz des Typs <typeparamref name="T" /> kann nicht erstellt werden, oder die vorhandene <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht vom Typ <typeparamref name="T" />, oder <paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="5af25-212">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="5af25-213">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-213">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="5af25-214">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-214">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="5af25-215">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="5af25-215">Indicates that the Reliable State Manager is closed.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="5af25-216">Der Vorgang wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="5af25-216">The operation has been internally faulted by the system.</span></span> <span data-ttu-id="5af25-217">Wiederholen Sie den Vorgang</span><span class="sxs-lookup"><span data-stu-id="5af25-217">Retry the operation</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, string name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As String, timeout As TimeSpan) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Microsoft.ServiceFabric.Data.ITransaction * string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync (tx, name, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="5af25-218">Beim Angeben der <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typ Sie Fragen sich vielleicht für einen Klassentyp oder einen Schnittstellentyp aufweisen.</span><span class="sxs-lookup"><span data-stu-id="5af25-218">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="5af25-219"><para>Wenn Sie einen Klassentyp angeben, wird versucht, eine Instanz dieses Typs zurückzugeben. Wenn eine Instanz dieses Typs instanziiert werden kann (z. B. abstrakte Klasse, es ist kein geeigneter Konstruktor) ArgumentException ausgelöst wird. </para><para>Wenn Sie einen Schnittstellentyp angeben, versucht der Manager die Schnittstelle in einen konkreten Typ aufgelöst. Wenn Typzuordnung vom Benutzer angegeben wird, wird diese Methode die benutzerdefinierte Zuordnung verwenden, um den Typ (noch nicht unterstützt) aufzulösen. Wenn die Typzuordnung nicht angegeben wird, wird der Benutzer wählt diese Methode die standardmäßige Implementierung für die angegebene Schnittstelle. Wenn Sie der angegebenen Schnittstellentyp verfügt nicht über eine Standardimplementierung oder eine benutzerdefinierte Zuordnung für den Typ nicht angegeben ist, oder der Typ ist ungültig, löst diese Methode ArgumentException.</para></span><span class="sxs-lookup"><span data-stu-id="5af25-219"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="tx"><span data-ttu-id="5af25-220">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="5af25-220">Transaction to associate this operation with.</span></span></param>
        <param name="name">
            <span data-ttu-id="5af25-221">Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-221">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="5af25-222">Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.</span><span class="sxs-lookup"><span data-stu-id="5af25-222">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <param name="timeout"><span data-ttu-id="5af25-223">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="5af25-223">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="5af25-224">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="5af25-224">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="5af25-225">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="5af25-225">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="5af25-226">Ruft eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen, wenn es vorhanden ist, oder erstellt und wird zurückgegeben, wenn er nicht bereits vorhanden.</span><span class="sxs-lookup"><span data-stu-id="5af25-226">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="5af25-227">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5af25-227">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="5af25-228">Das Ergebnis der Aufgabe ist die zuverlässige Status-Instanz.</span><span class="sxs-lookup"><span data-stu-id="5af25-228">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="5af25-229">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="5af25-229">This is an atomic operation.</span></span> <span data-ttu-id="5af25-230">Wenn ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> muss erstellt werden, wird entweder abgeschlossen und erfolgreich abgeschlossen oder er wird nicht erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-230">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span> <span data-ttu-id="5af25-231">Wenn diese Methode eine Ausnahme auslöst, muss die Transaktion abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="5af25-231">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="5af25-232"><paramref name="tx" />ist null, oder <paramref name="name" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="5af25-232"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="5af25-233">Eine Instanz des Typs <typeparamref name="T" /> kann nicht erstellt werden, oder die vorhandene <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht vom Typ <typeparamref name="T" />, oder <paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="5af25-233">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="5af25-234">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-234">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="5af25-235">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-235">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="5af25-236">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="5af25-236">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="5af25-237">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="5af25-237">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="5af25-238">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="5af25-238">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="5af25-239">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="5af25-239">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="5af25-240">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5af25-240">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="5af25-241">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="5af25-241">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As Uri, timeout As TimeSpan) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Microsoft.ServiceFabric.Data.ITransaction * Uri * TimeSpan -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync (tx, name, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="5af25-242">Beim Angeben der <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typ Sie Fragen sich vielleicht für einen Klassentyp oder einen Schnittstellentyp aufweisen.</span><span class="sxs-lookup"><span data-stu-id="5af25-242">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="5af25-243"><para>Wenn Sie einen Klassentyp angeben, wird versucht, eine Instanz dieses Typs zurückzugeben. Wenn eine Instanz dieses Typs instanziiert werden kann (z. B. abstrakte Klasse, es ist kein geeigneter Konstruktor) ArgumentException ausgelöst wird. </para><para>Wenn Sie einen Schnittstellentyp angeben, versucht der Manager die Schnittstelle in einen konkreten Typ aufgelöst. Wenn Typzuordnung vom Benutzer angegeben wird, wird diese Methode die benutzerdefinierte Zuordnung verwenden, um den Typ (noch nicht unterstützt) aufzulösen. Wenn die Typzuordnung nicht angegeben wird, wird der Benutzer wählt diese Methode die standardmäßige Implementierung für die angegebene Schnittstelle. Wenn Sie der angegebenen Schnittstellentyp verfügt nicht über eine Standardimplementierung oder eine benutzerdefinierte Zuordnung für den Typ nicht angegeben ist, oder der Typ ist ungültig, löst diese Methode ArgumentException.</para></span><span class="sxs-lookup"><span data-stu-id="5af25-243"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="tx"><span data-ttu-id="5af25-244">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="5af25-244">Transaction to associate this operation with.</span></span></param>
        <param name="name">
            <span data-ttu-id="5af25-245">Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-245">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="5af25-246">Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.</span><span class="sxs-lookup"><span data-stu-id="5af25-246">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <param name="timeout"><span data-ttu-id="5af25-247">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="5af25-247">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="5af25-248">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="5af25-248">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="5af25-249">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="5af25-249">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="5af25-250">Ruft eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen, wenn es vorhanden ist, oder erstellt und wird zurückgegeben, wenn er nicht bereits vorhanden.</span><span class="sxs-lookup"><span data-stu-id="5af25-250">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="5af25-251">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5af25-251">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="5af25-252">Das Ergebnis der Aufgabe ist die zuverlässige Status-Instanz.</span><span class="sxs-lookup"><span data-stu-id="5af25-252">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="5af25-253">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="5af25-253">This is an atomic operation.</span></span> <span data-ttu-id="5af25-254">Wenn ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> muss erstellt werden, wird entweder abgeschlossen und erfolgreich abgeschlossen oder er wird nicht erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-254">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span> <span data-ttu-id="5af25-255">Wenn diese Methode eine Ausnahme auslöst, muss die Transaktion abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="5af25-255">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="5af25-256"><paramref name="tx" />ist null, oder <paramref name="name" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="5af25-256"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="5af25-257">Eine Instanz des Typs <typeparamref name="T" /> kann nicht erstellt werden, oder die vorhandene <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht vom Typ <typeparamref name="T" />, oder <paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="5af25-257">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="5af25-258">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-258">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="5af25-259">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-259">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="5af25-260">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="5af25-260">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="5af25-261">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="5af25-261">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="5af25-262">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="5af25-262">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="5af25-263">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="5af25-263">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="5af25-264">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5af25-264">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="5af25-265">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="5af25-265">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (name As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : string -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="5af25-266">Der Name des zu entfernenden <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-266">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <summary>
            <span data-ttu-id="5af25-267">Entfernt die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen aus diesem Status-Manager.</span><span class="sxs-lookup"><span data-stu-id="5af25-267">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="5af25-268">Der Status wird dauerhaft aus dem persistenten Speicher und alle Replikate entfernt.</span><span class="sxs-lookup"><span data-stu-id="5af25-268">The state is permanently removed from persistent storage and all replicas.</span></span>
            </summary>
        <returns><span data-ttu-id="5af25-269">Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5af25-269">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="5af25-270">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="5af25-270">This is an atomic operation.</span></span> <span data-ttu-id="5af25-271">Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> in intakt gelassen werden oder wird zusammen mit allen Zustand erfolgreich entfernt werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-271">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="5af25-272"><paramref name="name" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="5af25-272"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="5af25-273">Ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="5af25-273">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="5af25-274">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-274">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="5af25-275">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-275">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="5af25-276">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="5af25-276">Indicates that the Reliable State Manager is closed.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="5af25-277">Der Vorgang wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="5af25-277">The operation has been internally faulted by the system.</span></span> <span data-ttu-id="5af25-278">Wiederholen Sie den Vorgang</span><span class="sxs-lookup"><span data-stu-id="5af25-278">Retry the operation</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (Uri name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (name As Uri) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : Uri -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="5af25-279">Der Name des zu entfernenden <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-279">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <summary>
            <span data-ttu-id="5af25-280">Entfernt die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen aus diesem Status-Manager.</span><span class="sxs-lookup"><span data-stu-id="5af25-280">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="5af25-281">Der Status wird dauerhaft aus dem persistenten Speicher und alle Replikate entfernt.</span><span class="sxs-lookup"><span data-stu-id="5af25-281">The state is permanently removed from persistent storage and all replicas.</span></span>
            </summary>
        <returns><span data-ttu-id="5af25-282">Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5af25-282">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="5af25-283">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="5af25-283">This is an atomic operation.</span></span> <span data-ttu-id="5af25-284">Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> in intakt gelassen werden oder wird zusammen mit allen Zustand erfolgreich entfernt werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-284">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="5af25-285"><paramref name="name" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="5af25-285"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="5af25-286">Ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="5af25-286">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="5af25-287">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-287">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="5af25-288">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-288">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="5af25-289">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="5af25-289">Indicates that the Reliable State Manager is closed.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="5af25-290">Der Vorgang wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="5af25-290">The operation has been internally faulted by the system.</span></span> <span data-ttu-id="5af25-291">Wiederholen Sie den Vorgang</span><span class="sxs-lookup"><span data-stu-id="5af25-291">Retry the operation</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (tx As ITransaction, name As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : Microsoft.ServiceFabric.Data.ITransaction * string -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync (tx, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="5af25-292">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="5af25-292">Transaction to associate this operation with.</span></span></param>
        <param name="name"><span data-ttu-id="5af25-293">Der Name des zu entfernenden <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-293">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <summary>
            <span data-ttu-id="5af25-294">Entfernt die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen aus diesem Status-Manager.</span><span class="sxs-lookup"><span data-stu-id="5af25-294">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="5af25-295">Der Zustand ist endgültig aus dem persistenten Speicher und alle Replikate entfernt, wenn die Transaktion ein Commit ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="5af25-295">The state is permanently removed from persistent storage and all replicas when the transaction is committed.</span></span>
            </summary>
        <returns><span data-ttu-id="5af25-296">Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5af25-296">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="5af25-297">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="5af25-297">This is an atomic operation.</span></span> <span data-ttu-id="5af25-298">Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> in intakt gelassen werden oder wird zusammen mit allen Zustand erfolgreich entfernt werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-298">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span> <span data-ttu-id="5af25-299">Wenn diese Methode eine Ausnahme auslöst, muss die Transaktion abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="5af25-299">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="5af25-300"><paramref name="tx" />ist null, oder <paramref name="name" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="5af25-300"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="5af25-301">Ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="5af25-301">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="5af25-302">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-302">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="5af25-303">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-303">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="5af25-304">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="5af25-304">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="5af25-305">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="5af25-305">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="5af25-306">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="5af25-306">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="5af25-307">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="5af25-307">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="5af25-308">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5af25-308">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="5af25-309">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="5af25-309">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (tx As ITransaction, name As Uri) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : Microsoft.ServiceFabric.Data.ITransaction * Uri -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync (tx, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="5af25-310">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="5af25-310">Transaction to associate this operation with.</span></span></param>
        <param name="name"><span data-ttu-id="5af25-311">Der Name des zu entfernenden <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-311">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <summary>
            <span data-ttu-id="5af25-312">Entfernt die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen aus diesem Status-Manager.</span><span class="sxs-lookup"><span data-stu-id="5af25-312">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="5af25-313">Der Zustand ist endgültig aus dem persistenten Speicher und alle Replikate entfernt, wenn die Transaktion ein Commit ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="5af25-313">The state is permanently removed from persistent storage and all replicas when the transaction is committed.</span></span>
            </summary>
        <returns><span data-ttu-id="5af25-314">Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5af25-314">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="5af25-315">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="5af25-315">This is an atomic operation.</span></span> <span data-ttu-id="5af25-316">Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> in intakt gelassen werden oder wird zusammen mit allen Zustand erfolgreich entfernt werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-316">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span> <span data-ttu-id="5af25-317">Wenn diese Methode eine Ausnahme auslöst, muss die Transaktion abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="5af25-317">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="5af25-318"><paramref name="tx" />ist null, oder <paramref name="name" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="5af25-318"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="5af25-319">Ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="5af25-319">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="5af25-320">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-320">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="5af25-321">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-321">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="5af25-322">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="5af25-322">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="5af25-323">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="5af25-323">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="5af25-324">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="5af25-324">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="5af25-325">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="5af25-325">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="5af25-326">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5af25-326">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="5af25-327">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="5af25-327">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (string name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (name As String, timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync (name, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="5af25-328">Der Name des zu entfernenden <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-328">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <param name="timeout"><span data-ttu-id="5af25-329">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="5af25-329">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="5af25-330">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="5af25-330">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="5af25-331">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="5af25-331">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="5af25-332">Entfernt die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen aus diesem Status-Manager.</span><span class="sxs-lookup"><span data-stu-id="5af25-332">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="5af25-333">Der Status wird dauerhaft aus dem persistenten Speicher und alle Replikate entfernt.</span><span class="sxs-lookup"><span data-stu-id="5af25-333">The state is permanently removed from persistent storage and all replicas.</span></span>
            </summary>
        <returns><span data-ttu-id="5af25-334">Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5af25-334">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="5af25-335">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="5af25-335">This is an atomic operation.</span></span> <span data-ttu-id="5af25-336">Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> in intakt gelassen werden oder wird zusammen mit allen Zustand erfolgreich entfernt werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-336">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="5af25-337"><paramref name="name" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="5af25-337"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="5af25-338">Ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen ist nicht vorhanden, oder <paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="5af25-338">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="5af25-339">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-339">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="5af25-340">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-340">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="5af25-341">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="5af25-341">Indicates that the Reliable State Manager is closed.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="5af25-342">Der Vorgang wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="5af25-342">The operation has been internally faulted by the system.</span></span> <span data-ttu-id="5af25-343">Wiederholen Sie den Vorgang</span><span class="sxs-lookup"><span data-stu-id="5af25-343">Retry the operation</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (Uri name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (name As Uri, timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : Uri * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync (name, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="5af25-344">Der Name des zu entfernenden <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-344">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <param name="timeout"><span data-ttu-id="5af25-345">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="5af25-345">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="5af25-346">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="5af25-346">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="5af25-347">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="5af25-347">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="5af25-348">Entfernt die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen aus diesem Status-Manager.</span><span class="sxs-lookup"><span data-stu-id="5af25-348">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="5af25-349">Der Status wird dauerhaft aus dem persistenten Speicher und alle Replikate entfernt.</span><span class="sxs-lookup"><span data-stu-id="5af25-349">The state is permanently removed from persistent storage and all replicas.</span></span>
            </summary>
        <returns><span data-ttu-id="5af25-350">Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5af25-350">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="5af25-351">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="5af25-351">This is an atomic operation.</span></span> <span data-ttu-id="5af25-352">Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> in intakt gelassen werden oder wird zusammen mit allen Zustand erfolgreich entfernt werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-352">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="5af25-353"><paramref name="name" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="5af25-353"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="5af25-354">Ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen ist nicht vorhanden, oder <paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="5af25-354">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="5af25-355">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-355">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="5af25-356">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-356">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="5af25-357">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="5af25-357">Indicates that the Reliable State Manager is closed.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="5af25-358">Der Vorgang wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="5af25-358">The operation has been internally faulted by the system.</span></span> <span data-ttu-id="5af25-359">Wiederholen Sie den Vorgang</span><span class="sxs-lookup"><span data-stu-id="5af25-359">Retry the operation</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, string name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (tx As ITransaction, name As String, timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : Microsoft.ServiceFabric.Data.ITransaction * string * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync (tx, name, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
        <param name="tx"><span data-ttu-id="5af25-360">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="5af25-360">Transaction to associate this operation with.</span></span></param>
        <param name="name"><span data-ttu-id="5af25-361">Der Name des zu entfernenden <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-361">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <param name="timeout"><span data-ttu-id="5af25-362">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="5af25-362">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="5af25-363">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="5af25-363">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="5af25-364">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="5af25-364">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="5af25-365">Entfernt die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen aus diesem Status-Manager.</span><span class="sxs-lookup"><span data-stu-id="5af25-365">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="5af25-366">Der Zustand ist endgültig aus dem persistenten Speicher und alle Replikate entfernt, wenn die Transaktion ein Commit ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="5af25-366">The state is permanently removed from persistent storage and all replicas when the transaction is committed.</span></span>
            </summary>
        <returns><span data-ttu-id="5af25-367">Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5af25-367">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="5af25-368">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="5af25-368">This is an atomic operation.</span></span> <span data-ttu-id="5af25-369">Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> in intakt gelassen werden oder wird zusammen mit allen Zustand erfolgreich entfernt werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-369">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span> <span data-ttu-id="5af25-370">Wenn diese Methode eine Ausnahme auslöst, muss die Transaktion abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="5af25-370">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="5af25-371"><paramref name="tx" />ist null, oder <paramref name="name" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="5af25-371"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="5af25-372">Ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen ist nicht vorhanden, oder <paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="5af25-372">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="5af25-373">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-373">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="5af25-374">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-374">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="5af25-375">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="5af25-375">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="5af25-376">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="5af25-376">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="5af25-377">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="5af25-377">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="5af25-378">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="5af25-378">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="5af25-379">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5af25-379">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="5af25-380">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="5af25-380">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (tx As ITransaction, name As Uri, timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : Microsoft.ServiceFabric.Data.ITransaction * Uri * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync (tx, name, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
        <param name="tx"><span data-ttu-id="5af25-381">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="5af25-381">Transaction to associate this operation with.</span></span></param>
        <param name="name"><span data-ttu-id="5af25-382">Der Name des zu entfernenden <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-382">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <param name="timeout"><span data-ttu-id="5af25-383">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="5af25-383">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="5af25-384">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="5af25-384">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="5af25-385">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="5af25-385">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="5af25-386">Entfernt die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen aus diesem Status-Manager.</span><span class="sxs-lookup"><span data-stu-id="5af25-386">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="5af25-387">Der Zustand ist endgültig aus dem persistenten Speicher und alle Replikate entfernt, wenn die Transaktion ein Commit ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="5af25-387">The state is permanently removed from persistent storage and all replicas when the transaction is committed.</span></span>
            </summary>
        <returns><span data-ttu-id="5af25-388">Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5af25-388">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="5af25-389">Dies ist einer atomaren Operation.</span><span class="sxs-lookup"><span data-stu-id="5af25-389">This is an atomic operation.</span></span> <span data-ttu-id="5af25-390">Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> in intakt gelassen werden oder wird zusammen mit allen Zustand erfolgreich entfernt werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-390">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span> <span data-ttu-id="5af25-391">Wenn diese Methode eine Ausnahme auslöst, muss die Transaktion abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="5af25-391">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="5af25-392"><paramref name="tx" />ist null, oder <paramref name="name" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="5af25-392"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="5af25-393">Ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen ist nicht vorhanden, oder <paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="5af25-393">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="5af25-394">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-394">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="5af25-395">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-395">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="5af25-396">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="5af25-396">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="5af25-397">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="5af25-397">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="5af25-398">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="5af25-398">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="5af25-399">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="5af25-399">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="5af25-400">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5af25-400">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="5af25-401">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="5af25-401">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StateManagerChanged">
      <MemberSignature Language="C#" Value="event EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; StateManagerChanged;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; StateManagerChanged" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Data.IReliableStateManager.StateManagerChanged" />
      <MemberSignature Language="VB.NET" Value="Event StateManagerChanged As EventHandler(Of NotifyStateManagerChangedEventArgs) " />
      <MemberSignature Language="F#" Value="member this.StateManagerChanged : EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; " Usage="member this.StateManagerChanged : System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5af25-402">Tritt auf, wenn Status-Manager Zustand ändert.</span><span class="sxs-lookup"><span data-stu-id="5af25-402">Occurs when State Manager's state changes.</span></span>
            <span data-ttu-id="5af25-403">Beispielsweise erstellen oder Löschen von zuverlässigen Zustand oder Neuerstellung des zuverlässigen Status-Managers.</span><span class="sxs-lookup"><span data-stu-id="5af25-403">For example, creation or delete of reliable state or rebuild of the reliable state manager.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransactionChanged">
      <MemberSignature Language="C#" Value="event EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; TransactionChanged;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; TransactionChanged" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Data.IReliableStateManager.TransactionChanged" />
      <MemberSignature Language="VB.NET" Value="Event TransactionChanged As EventHandler(Of NotifyTransactionChangedEventArgs) " />
      <MemberSignature Language="F#" Value="member this.TransactionChanged : EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; " Usage="member this.TransactionChanged : System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5af25-404">Tritt auf, wenn eine Transaktion Zustand ändert.</span><span class="sxs-lookup"><span data-stu-id="5af25-404">Occurs when a transaction's state changes.</span></span>
            <span data-ttu-id="5af25-405">Beispielsweise ein Commit einer Transaktion ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="5af25-405">For example, commit of a transaction.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryAddStateSerializer&lt;T&gt;">
      <MemberSignature Language="C#" Value="public bool TryAddStateSerializer&lt;T&gt; (Microsoft.ServiceFabric.Data.IStateSerializer&lt;T&gt; stateSerializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool TryAddStateSerializer&lt;T&gt;(class Microsoft.ServiceFabric.Data.IStateSerializer`1&lt;!!T&gt; stateSerializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryAddStateSerializer``1(Microsoft.ServiceFabric.Data.IStateSerializer{``0})" />
      <MemberSignature Language="VB.NET" Value="Public Function TryAddStateSerializer(Of T) (stateSerializer As IStateSerializer(Of T)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member TryAddStateSerializer : Microsoft.ServiceFabric.Data.IStateSerializer&lt;'T&gt; -&gt; bool" Usage="iReliableStateManager.TryAddStateSerializer stateSerializer" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
        <typeparam name="T"><span data-ttu-id="5af25-406">Typ, der serialisiert bzw. deserialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-406">Type that will be serialized and deserialized.</span></span></typeparam>
        <param name="stateSerializer">
            <span data-ttu-id="5af25-407">Das Serialisierungsprogramm Zustand hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-407">The state serializer to be added.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5af25-408">Registriert ein benutzerdefiniertes Serialisierungsprogramm für alle zuverlässige Auflistungen.</span><span class="sxs-lookup"><span data-stu-id="5af25-408">Registers a custom serializer for all reliable collections.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5af25-409">"True", wenn das benutzerdefinierte Serialisierungsprogramm hinzugefügt wurde.</span><span class="sxs-lookup"><span data-stu-id="5af25-409">True if the custom serializer was added.</span></span>
            <span data-ttu-id="5af25-410">"False", wenn ein benutzerdefiniertes Serialisierungsprogramm für den angegebenen Typ ist bereits vorhanden.</span><span class="sxs-lookup"><span data-stu-id="5af25-410">False if a custom serializer for the given type already exists.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="5af25-411">Wenn eine zuverlässige Auflistung ein Objekt zu serialisieren muss, fordert er den Status-Manager für ein Serialisierungsprogramm für den angegebenen Typ.</span><span class="sxs-lookup"><span data-stu-id="5af25-411">When a reliable collection needs to serialize an object, it asks the state manager for a serializer for the given type.</span></span>
            <span data-ttu-id="5af25-412">Der Status-Manager prüft zunächst, wenn es ein benutzerdefiniertes Serialisierungsprogramm für den Eingabetyp registriert ist.</span><span class="sxs-lookup"><span data-stu-id="5af25-412">The state manager will first check if there is a custom serializer registered for the input type.</span></span> <span data-ttu-id="5af25-413">Ist dies nicht der Fall, wird überprüft, ob eines der integrierten Serialisierungsprogramme den Typ serialisieren kann.</span><span class="sxs-lookup"><span data-stu-id="5af25-413">If not, it will check if one of the built-in serializers can serialize the type.</span></span> <span data-ttu-id="5af25-414">Der Status-Manager verfügt über integrierte Serialisierungsprogrammen für die folgenden Typen: Guid, Bool, Byte, Sbyte, Char, Decimal, double, Float, Int, Uint, long, Ulong, Short, Ushort und Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="5af25-414">The state manager has built-in serializers for the following types: guid, bool, byte, sbyte, char, decimal, double, float, int, uint, long, ulong, short, ushort and string.</span></span> <span data-ttu-id="5af25-415">Falls nicht, er verwendet <see cref="T:System.Runtime.Serialization.DataContractSerializer" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-415">If not, it will use <see cref="T:System.Runtime.Serialization.DataContractSerializer" />.</span></span>
            </para>
          <para>
            <span data-ttu-id="5af25-416">Serialisierungsprogramme müssen unbegrenzt Rückwärtsrichtung kompatibel sein.</span><span class="sxs-lookup"><span data-stu-id="5af25-416">Serializers must be infinitely forwards and backwards compatible.</span></span> <span data-ttu-id="5af25-417">Für die Typen, die integrierte Serialisierungsprogramme verwenden, stellt Service Fabric Aufwärts- und Abwärtskompatibilität sicher.</span><span class="sxs-lookup"><span data-stu-id="5af25-417">For the types that are using built-in serializers, Service Fabric ensures forwards and backwards compatibility.</span></span> <span data-ttu-id="5af25-418">Allerdings muss ein benutzerdefiniertes Serialisierers mit einem integrierten Serialisierungsprogramm für einen Typ hinzugefügt wird, kompatibel mit der integrierten Serialisierungsformat für diesen Typ der benutzerdefinierten Serialisierung sein.</span><span class="sxs-lookup"><span data-stu-id="5af25-418">However, if a custom serializer is added for a type with a built-in serializer, the custom serializer must be compatible with the built-in serialization format for that type.</span></span>
            </para>
          <para>
            <span data-ttu-id="5af25-419">Diese Methode sollte vom Konstruktor der Stateful Service aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-419">This method should be called from the constructor of the Stateful Service.</span></span> <span data-ttu-id="5af25-420">Dadurch wird sichergestellt, dass die zuverlässige Auflistungen erforderlichen Serialisierungsprogramme aufweisen, vor Beginn der Wiederherstellung des persistenten Zustands.</span><span class="sxs-lookup"><span data-stu-id="5af25-420">This ensures that the Reliable Collections have the necessary serializers before recovery of the persisted state begins.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryGetAsync&lt;T&gt; (string name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!!T&gt;&gt; TryGetAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetAsync(Of T As IReliableState) (name As String) As Task(Of ConditionalValue(Of T))" />
      <MemberSignature Language="F#" Value="abstract member TryGetAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.TryGetAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="5af25-421">Wenn Sie den Typ angeben, können Sie einen konkreten Typ oder einen Schnittstellentyp anfordern.</span><span class="sxs-lookup"><span data-stu-id="5af25-421">When specifying the type, you may ask for either a concrete type or an interface type.</span></span> <span data-ttu-id="5af25-422">Das abgerufene Objekt wird für den angegebenen Typ umgewandelt werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-422">The retrieved object will be cast to the given type.</span></span>
            </typeparam>
        <param name="name">
            <span data-ttu-id="5af25-423">Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-423">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="5af25-424">Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.</span><span class="sxs-lookup"><span data-stu-id="5af25-424">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5af25-425">Versucht, erhalten eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="5af25-425">Attempts to get an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name.</span></span>
            </summary>
        <returns><span data-ttu-id="5af25-426">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5af25-426">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="5af25-427">Das Ergebnis der Aufgabe ist ein Tupel, die angibt, ob die zuverlässige Zustand gefunden wurde, und wenn dies der Fall ist die Instanz.</span><span class="sxs-lookup"><span data-stu-id="5af25-427">The task result is a tuple indicating whether the reliable state was found, and if so the instance.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="5af25-428"><paramref name="name" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="5af25-428"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="5af25-429">Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht in den Typ <typeparamref name="T" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-429">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not convertible to type <typeparamref name="T" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="5af25-430">Ausnahme gibt an, dass der Status-Manager abrufen eine zuverlässige Auflistung kann nicht.</span><span class="sxs-lookup"><span data-stu-id="5af25-430">Exception indicates that the State Manager cannot retrive a reliable collection.</span></span>
            <span data-ttu-id="5af25-431"><see cref="T:System.Fabric.FabricNotReadableException" />ausgelöst werden kann, in allen <see cref="T:System.Fabric.ReplicaRole" />s.</span><span class="sxs-lookup"><span data-stu-id="5af25-431"><see cref="T:System.Fabric.FabricNotReadableException" /> can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="5af25-432">Beispielsweise, wenn eine <see cref="F:System.Fabric.ReplicaRole.Primary" /> oder <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> verliert <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-432">For example, when a <see cref="F:System.Fabric.ReplicaRole.Primary" /> or <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> looses <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="5af25-433">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="5af25-433">Indicates that the Reliable State Manager is closed.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="5af25-434">Der Vorgang wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="5af25-434">The operation has been internally faulted by the system.</span></span> <span data-ttu-id="5af25-435">Wiederholen Sie den Vorgang</span><span class="sxs-lookup"><span data-stu-id="5af25-435">Retry the operation</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="TryGetAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryGetAsync&lt;T&gt; (Uri name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!!T&gt;&gt; TryGetAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync``1(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetAsync(Of T As IReliableState) (name As Uri) As Task(Of ConditionalValue(Of T))" />
      <MemberSignature Language="F#" Value="abstract member TryGetAsync : Uri -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.TryGetAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="5af25-436">Wenn Sie den Typ angeben, können Sie einen konkreten Typ oder einen Schnittstellentyp anfordern.</span><span class="sxs-lookup"><span data-stu-id="5af25-436">When specifying the type, you may ask for either a concrete type or an interface type.</span></span> <span data-ttu-id="5af25-437">Das abgerufene Objekt wird für den angegebenen Typ umgewandelt werden.</span><span class="sxs-lookup"><span data-stu-id="5af25-437">The retrieved object will be cast to the given type.</span></span>
            </typeparam>
        <param name="name">
            <span data-ttu-id="5af25-438">Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-438">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="5af25-439">Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.</span><span class="sxs-lookup"><span data-stu-id="5af25-439">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5af25-440">Versucht, erhalten eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="5af25-440">Attempts to get an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name.</span></span>
            </summary>
        <returns><span data-ttu-id="5af25-441">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5af25-441">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="5af25-442">Das Ergebnis der Aufgabe ist ein Tupel, die angibt, ob die zuverlässige Zustand gefunden wurde, und wenn dies der Fall ist die Instanz.</span><span class="sxs-lookup"><span data-stu-id="5af25-442">The task result is a tuple indicating whether the reliable state was found, and if so the instance.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="5af25-443"><paramref name="name" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="5af25-443"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="5af25-444">Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht in den Typ <typeparamref name="T" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-444">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not convertible to type <typeparamref name="T" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="5af25-445">Ausnahme gibt an, dass der Status-Manager abrufen eine zuverlässige Auflistung kann nicht.</span><span class="sxs-lookup"><span data-stu-id="5af25-445">Exception indicates that the State Manager cannot retrive a reliable collection.</span></span>
            <span data-ttu-id="5af25-446"><see cref="T:System.Fabric.FabricNotReadableException" />ausgelöst werden kann, in allen <see cref="T:System.Fabric.ReplicaRole" />s.</span><span class="sxs-lookup"><span data-stu-id="5af25-446"><see cref="T:System.Fabric.FabricNotReadableException" /> can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="5af25-447">Beispielsweise, wenn eine <see cref="F:System.Fabric.ReplicaRole.Primary" /> oder <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> verliert <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span><span class="sxs-lookup"><span data-stu-id="5af25-447">For example, when a <see cref="F:System.Fabric.ReplicaRole.Primary" /> or <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> looses <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="5af25-448">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="5af25-448">Indicates that the Reliable State Manager is closed.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="5af25-449">Der Vorgang wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="5af25-449">The operation has been internally faulted by the system.</span></span> <span data-ttu-id="5af25-450">Wiederholen Sie den Vorgang</span><span class="sxs-lookup"><span data-stu-id="5af25-450">Retry the operation</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>