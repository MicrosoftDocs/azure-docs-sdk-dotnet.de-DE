<Type Name="Epoch" FullName="System.Fabric.Epoch">
  <TypeSignature Language="C#" Value="public struct Epoch : IComparable&lt;System.Fabric.Epoch&gt;, IEquatable&lt;System.Fabric.Epoch&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public sequential ansi serializable sealed beforefieldinit Epoch extends System.ValueType implements class System.IComparable`1&lt;valuetype System.Fabric.Epoch&gt;, class System.IEquatable`1&lt;valuetype System.Fabric.Epoch&gt;" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Epoch" />
  <TypeSignature Language="VB.NET" Value="Public Structure Epoch&#xA;Implements IComparable(Of Epoch), IEquatable(Of Epoch)" />
  <TypeSignature Language="F#" Value="type Epoch = struct" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ValueType</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IComparable&lt;System.Fabric.Epoch&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IEquatable&lt;System.Fabric.Epoch&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para> <span data-ttu-id="b8a1b-101">Stellt die aktuelle Version der Service Fabric-Partition an.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-101">Represents the current version of the partition in Service Fabric.</span></span> </para>
    </summary>
    <remarks>
      <para><span data-ttu-id="b8a1b-102">Ein Epoche ist eine Konfigurationsnummer für die Partition als Ganzes.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-102">An Epoch is a configuration number for the partition as a whole.</span></span> <span data-ttu-id="b8a1b-103">Wenn die Konfiguration des Replikats Änderungen, z. B. wenn das primäre Replikat ändert, die Vorgänge, die vom neuen primären Replikat repliziert werden als sind eine neue Epoche aus. der von dem alten primären Replikat gesendet wurden festgelegt.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-103">When the configuration of the replica set changes, for example when the Primary replica changes, the operations that are replicated from the new Primary replica are said to be a new Epoch from the ones which were sent by the old Primary replica.</span></span> <span data-ttu-id="b8a1b-104">Die Tatsache, die dass das primäre geändert hat ist nicht direkt sichtbar auf sekundäre Replikate, die nicht durch einen Fehler in der Regel betroffen sind, die das ursprüngliche primäre Replikat betroffen.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-104">The fact that the Primary has changed is not directly visible to Secondary replicas, which are usually unaffected by the failure that affected the original Primary replica.</span></span> <span data-ttu-id="b8a1b-105">Um nachzuverfolgen, dass sich das primäre Replikat geändert wurde, an das sekundäre Replikat übertragen werden.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-105">To track that the Primary replica has changed has to be communicated to the Secondary replica.</span></span> <span data-ttu-id="b8a1b-106">Diese Kommunikation erfolgt über die <see cref="M:System.Fabric.IStateProvider.UpdateEpochAsync(System.Fabric.Epoch,System.Int64,System.Threading.CancellationToken)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-106">This communication occurs via the <see cref="M:System.Fabric.IStateProvider.UpdateEpochAsync(System.Fabric.Epoch,System.Int64,System.Threading.CancellationToken)" /> method.</span></span> <span data-ttu-id="b8a1b-107">Die meisten Dienste können die Details der inneren Felder der Epoche ignorieren, wie es in der Regel ausreichend ist, zu wissen, dass es sich bei Beginn des Zeitraums geändert hat und Epochs, um zu bestimmen, relative Reihenfolge der Vorgänge und-Ereignisse im System zu vergleichen.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-107">Most services can ignore the details of the inner fields of the Epoch as it is usually sufficient to know that the Epoch has changed and to compare Epochs to determine relative ordering of operations and events in the system.</span></span> <span data-ttu-id="b8a1b-108">Zu diesem Zweck sind Vergleichsoperationen bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-108">Comparison operations are provided for this purpose.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Epoch (long dataLossNumber, long configurationNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 dataLossNumber, int64 configurationNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.#ctor(System.Int64,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (dataLossNumber As Long, configurationNumber As Long)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Epoch : int64 * int64 -&gt; System.Fabric.Epoch" Usage="new System.Fabric.Epoch (dataLossNumber, configurationNumber)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dataLossNumber" Type="System.Int64" />
        <Parameter Name="configurationNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="dataLossNumber">
          <para><span data-ttu-id="b8a1b-109">Ein <see cref="T:System.Int64" /> , der einem zunehmenden entspricht, das aktualisiert wird, wenn Datenverlust vermutet wird.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-109">An <see cref="T:System.Int64" /> representing an increasing value which is updated whenever data loss is suspected.</span></span></para>
        </param>
        <param name="configurationNumber">
          <para><span data-ttu-id="b8a1b-110">Ein <see cref="T:System.Int64" /> , der einem zunehmenden entspricht, die aktualisiert wird, sobald die Konfiguration dieses Replikats Änderungen festgelegt.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-110">An <see cref="T:System.Int64" /> representing an increasing value that is updated whenever the configuration of this replica set changes.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b8a1b-111">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.Epoch" /> Klasse mit dem angegebenen datenverlustnummer und Konfigurationsnummer.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-111">Initializes a new instance of the <see cref="T:System.Fabric.Epoch" /> class with the specified data loss number and configuration number.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompareTo">
      <MemberSignature Language="C#" Value="public int CompareTo (System.Fabric.Epoch other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 CompareTo(valuetype System.Fabric.Epoch other) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.CompareTo(System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompareTo (other As Epoch) As Integer" />
      <MemberSignature Language="F#" Value="abstract member CompareTo : System.Fabric.Epoch -&gt; int&#xA;override this.CompareTo : System.Fabric.Epoch -&gt; int" Usage="epoch.CompareTo other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IComparable`1.CompareTo(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="other">
          <para><span data-ttu-id="b8a1b-112">Die <see cref="T:System.Fabric.Epoch" /> zu vergleichende Objekt.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-112">The <see cref="T:System.Fabric.Epoch" /> object to compare.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b8a1b-113">Vergleicht dieses <see cref="T:System.Fabric.Epoch" /> Objekt mit dem angegebenen <paramref name="other" /> <see cref="T:System.Fabric.Epoch" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-113">Compares this <see cref="T:System.Fabric.Epoch" /> object to the specified <paramref name="other" /><see cref="T:System.Fabric.Epoch" /> object.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="b8a1b-114">Gibt <see cref="T:System.Int32" />zurück.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-114">Returns <see cref="T:System.Int32" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigurationNumber">
      <MemberSignature Language="C#" Value="public long ConfigurationNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ConfigurationNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Epoch.ConfigurationNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property ConfigurationNumber As Long" />
      <MemberSignature Language="F#" Value="member this.ConfigurationNumber : int64 with get, set" Usage="System.Fabric.Epoch.ConfigurationNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b8a1b-115">Ruft ab oder legt die aktuelle Konfigurationseigenschaft in dieser <see cref="T:System.Fabric.Epoch" />.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-115">Gets or sets the current configuration number property in this <see cref="T:System.Fabric.Epoch" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b8a1b-116">Gibt eine <see cref="T:System.Int64" /> , der die Konfigurationsnummer darstellt.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-116">Returns an <see cref="T:System.Int64" /> representing the configuration number.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="b8a1b-117">Die Konfigurationsnummer ist eine zunehmende-Wert, der aktualisiert wird, sobald die Konfiguration dieses Replikats Änderungen festgelegt.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-117">The configuration number is an increasing value that is updated whenever the configuration of this replica set changes.</span></span> <span data-ttu-id="b8a1b-118">Die Dienste werden informiert, wenn der aktuellen Konfiguration Nummer nur, wenn <see cref="M:System.Fabric.IReplicator.UpdateEpochAsync(System.Fabric.Epoch,System.Threading.CancellationToken)" /> Methode wird aufgerufen, als Ergebnis der Versuch, das primäre Replikat der Replikatgruppe ändern.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-118">The services are informed of the current configuration number only when <see cref="M:System.Fabric.IReplicator.UpdateEpochAsync(System.Fabric.Epoch,System.Threading.CancellationToken)" /> method is called as a result of an attempt to change the Primary replica of the replica set.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DataLossNumber">
      <MemberSignature Language="C#" Value="public long DataLossNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DataLossNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Epoch.DataLossNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property DataLossNumber As Long" />
      <MemberSignature Language="F#" Value="member this.DataLossNumber : int64 with get, set" Usage="System.Fabric.Epoch.DataLossNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b8a1b-119">Ruft die aktuelle datenverlustnummer in dieser <see cref="T:System.Fabric.Epoch" />.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-119">Gets the current data loss number in this <see cref="T:System.Fabric.Epoch" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b8a1b-120">Gibt eine <see cref="T:System.Int64" /> , die die aktuelle datenverlustnummer darstellt.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-120">Returns an <see cref="T:System.Int64" /> representing the current data loss number.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="b8a1b-121">Die Daten verloren gehen Number-Eigenschaft ist eine zunehmende Wert, der aktualisiert wird, wenn Datenverlust vermutet wird, als beim Verlust des ein Quorum der Replikate im Replikat festgelegt, die das primäre Replikat enthält, an.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-121">The data loss number property is an increasing value which is updated whenever data loss is suspected, as when loss of a quorum of replicas in the replica set that includes the Primary replica.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (System.Fabric.Epoch other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(valuetype System.Fabric.Epoch other) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.Equals(System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As Epoch) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : System.Fabric.Epoch -&gt; bool" Usage="epoch.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="other">
          <para><span data-ttu-id="b8a1b-122">Das Objekt, das mit dem aktuellen <see cref="T:System.Fabric.Epoch" />-Objekt verglichen werden soll.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-122">The object to compare with the current <see cref="T:System.Fabric.Epoch" /> object.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b8a1b-123">Bestimmt, ob das angegebene <see cref="T:System.Fabric.Epoch" /> Objekt gleich der aktuellen <see cref="T:System.Fabric.Epoch" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-123">Determines whether the specified <see cref="T:System.Fabric.Epoch" /> object is equal to the current <see cref="T:System.Fabric.Epoch" /> object.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="b8a1b-124"><languageKeyword>"true"</languageKeyword> Wenn das angegebene <see cref="T:System.Fabric.Epoch" /> Objekt gleich der aktuellen <see cref="T:System.Fabric.Epoch" /> Objekt; andernfalls <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-124"><languageKeyword>true</languageKeyword> if the specified <see cref="T:System.Fabric.Epoch" /> object is equal to the current <see cref="T:System.Fabric.Epoch" /> object; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="epoch.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">
          <para><span data-ttu-id="b8a1b-125">Das Objekt, das mit dem aktuellen Objekt verglichen werden soll.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-125">The object to compare with the current object.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b8a1b-126">Bestimmt, ob das angegebene Objekt mit dem aktuellen Objekt identisch ist.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-126">Determines whether the specified object is equal to the current object.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="b8a1b-127"><languageKeyword>"true"</languageKeyword> ist das angegebene Objekt mit dem aktuellen Objekt identisch ist, andernfalls <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-127"><languageKeyword>true</languageKeyword> if the specified object is equal to the current object; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="epoch.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="b8a1b-128">Dient als Hashfunktion für die <see cref="T:System.Fabric.Epoch" /> Typ.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-128">Serves as a hash function for the <see cref="T:System.Fabric.Epoch" /> type.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="b8a1b-129">Ein <see cref="T:System.Int32" /> , das einen Hashcode für die aktuelle darstellt <see cref="T:System.Fabric.Epoch" />...</span><span class="sxs-lookup"><span data-stu-id="b8a1b-129">A <see cref="T:System.Int32" /> representing a hash code for the current <see cref="T:System.Fabric.Epoch" />..</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Equality">
      <MemberSignature Language="C#" Value="public static bool operator == (System.Fabric.Epoch left, System.Fabric.Epoch right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Equality(valuetype System.Fabric.Epoch left, valuetype System.Fabric.Epoch right) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.op_Equality(System.Fabric.Epoch,System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator == (left As Epoch, right As Epoch) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( = ) : System.Fabric.Epoch * System.Fabric.Epoch -&gt; bool" Usage="left = right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="System.Fabric.Epoch" />
        <Parameter Name="right" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="left">
          <para><span data-ttu-id="b8a1b-130">Links <see cref="T:System.Fabric.Epoch" /> zu vergleichende Objekt.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-130">The left <see cref="T:System.Fabric.Epoch" /> object to compare.</span></span></para>
        </param>
        <param name="right">
          <para><span data-ttu-id="b8a1b-131">Das Recht <see cref="T:System.Fabric.Epoch" /> zu vergleichende Objekt.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-131">The right <see cref="T:System.Fabric.Epoch" /> object to compare.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b8a1b-132">Bestimmt, ob zwei angegebene <see cref="T:System.Fabric.Epoch" />-Objekte denselben Wert haben.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-132">Determines whether two specified <see cref="T:System.Fabric.Epoch" /> objects have the same value.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="b8a1b-133"><languageKeyword>"true"</languageKeyword> Wenn der Wert der <paramref name="left" /> entspricht der Wert der <paramref name="right" />ist, andernfalls <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-133"><languageKeyword>true</languageKeyword> if the value of <paramref name="left" /> is the same as the value of <paramref name="right" />; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_GreaterThan">
      <MemberSignature Language="C#" Value="public static bool operator &gt; (System.Fabric.Epoch left, System.Fabric.Epoch right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_GreaterThan(valuetype System.Fabric.Epoch left, valuetype System.Fabric.Epoch right) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.op_GreaterThan(System.Fabric.Epoch,System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator &gt; (left As Epoch, right As Epoch) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( &gt; ) : System.Fabric.Epoch * System.Fabric.Epoch -&gt; bool" Usage="left &gt; right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="System.Fabric.Epoch" />
        <Parameter Name="right" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="left">
          <para><span data-ttu-id="b8a1b-134">Links <see cref="T:System.Fabric.Epoch" /> zu vergleichende Objekt.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-134">The left <see cref="T:System.Fabric.Epoch" /> object to compare.</span></span></para>
        </param>
        <param name="right">
          <para><span data-ttu-id="b8a1b-135">Das Recht <see cref="T:System.Fabric.Epoch" /> zu vergleichende Objekt.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-135">The right <see cref="T:System.Fabric.Epoch" /> object to compare.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b8a1b-136">Bestimmt, ob ein angegebener <see cref="T:System.Fabric.Epoch" /> -Quellobjekt ist größer als ein anderer angegebener <see cref="T:System.Fabric.Epoch" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-136">Determines whether one specified <see cref="T:System.Fabric.Epoch" /> object is greater than another specified <see cref="T:System.Fabric.Epoch" /> object.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="b8a1b-137"><languageKeyword>"true"</languageKeyword> Wenn der Wert der <paramref name="left" /> ist größer als der Wert der <paramref name="right" />ist, andernfalls <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-137"><languageKeyword>true</languageKeyword> if the value of <paramref name="left" /> is greater than the value of <paramref name="right" />; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_GreaterThanOrEqual">
      <MemberSignature Language="C#" Value="public static bool operator &gt;= (System.Fabric.Epoch left, System.Fabric.Epoch right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_GreaterThanOrEqual(valuetype System.Fabric.Epoch left, valuetype System.Fabric.Epoch right) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.op_GreaterThanOrEqual(System.Fabric.Epoch,System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator &gt;= (left As Epoch, right As Epoch) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( &gt;= ) : System.Fabric.Epoch * System.Fabric.Epoch -&gt; bool" Usage="left &gt;= right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="System.Fabric.Epoch" />
        <Parameter Name="right" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="left">
          <para><span data-ttu-id="b8a1b-138">Links <see cref="T:System.Fabric.Epoch" /> zu vergleichende Objekt.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-138">The left <see cref="T:System.Fabric.Epoch" /> object to compare.</span></span></para>
        </param>
        <param name="right">
          <para><span data-ttu-id="b8a1b-139">Das Recht <see cref="T:System.Fabric.Epoch" /> zu vergleichende Objekt.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-139">The right <see cref="T:System.Fabric.Epoch" /> object to compare.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b8a1b-140">Bestimmt, ob ein angegebener <see cref="T:System.Fabric.Epoch" /> Objekt ist größer als oder gleich einem anderen angegebenen <see cref="T:System.Fabric.Epoch" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-140">Determines whether one specified <see cref="T:System.Fabric.Epoch" /> object is greater than or equal to another specified <see cref="T:System.Fabric.Epoch" /> object.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="b8a1b-141"><languageKeyword>"true"</languageKeyword> Wenn der Wert der <paramref name="left" /> ist größer als oder gleich dem Wert der <paramref name="right" />ist, andernfalls <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-141"><languageKeyword>true</languageKeyword> if the value of <paramref name="left" /> is greater than or equal to the value of <paramref name="right" />; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Inequality">
      <MemberSignature Language="C#" Value="public static bool operator != (System.Fabric.Epoch left, System.Fabric.Epoch right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Inequality(valuetype System.Fabric.Epoch left, valuetype System.Fabric.Epoch right) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.op_Inequality(System.Fabric.Epoch,System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator != (left As Epoch, right As Epoch) As Boolean" />
      <MemberSignature Language="F#" Value="static member op_Inequality : System.Fabric.Epoch * System.Fabric.Epoch -&gt; bool" Usage="System.Fabric.Epoch.op_Inequality (left, right)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="System.Fabric.Epoch" />
        <Parameter Name="right" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="left">
          <para><span data-ttu-id="b8a1b-142">Links <see cref="T:System.Fabric.Epoch" /> zu vergleichende Objekt.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-142">The left <see cref="T:System.Fabric.Epoch" /> object to compare.</span></span></para>
        </param>
        <param name="right">
          <para><span data-ttu-id="b8a1b-143">Das Recht <see cref="T:System.Fabric.Epoch" /> zu vergleichende Objekt.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-143">The right <see cref="T:System.Fabric.Epoch" /> object to compare.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b8a1b-144">Bestimmt, ob zwei angegebene <see cref="T:System.Fabric.Epoch" /> -Objekte verschiedene Werte haben.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-144">Determines whether two specified <see cref="T:System.Fabric.Epoch" /> objects have different values.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="b8a1b-145"><languageKeyword>"true"</languageKeyword> Wenn der Wert der <paramref name="left" /> unterscheidet sich der Wert der <paramref name="right" />ist, andernfalls <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-145"><languageKeyword>true</languageKeyword> if the value of <paramref name="left" /> is different than the value of <paramref name="right" />; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_LessThan">
      <MemberSignature Language="C#" Value="public static bool operator &lt; (System.Fabric.Epoch left, System.Fabric.Epoch right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_LessThan(valuetype System.Fabric.Epoch left, valuetype System.Fabric.Epoch right) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.op_LessThan(System.Fabric.Epoch,System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator &lt; (left As Epoch, right As Epoch) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( &lt; ) : System.Fabric.Epoch * System.Fabric.Epoch -&gt; bool" Usage="left &lt; right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="System.Fabric.Epoch" />
        <Parameter Name="right" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="left">
          <para><span data-ttu-id="b8a1b-146">Links <see cref="T:System.Fabric.Epoch" /> zu vergleichende Objekt.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-146">The left <see cref="T:System.Fabric.Epoch" /> object to compare.</span></span></para>
        </param>
        <param name="right">
          <para><span data-ttu-id="b8a1b-147">Das Recht <see cref="T:System.Fabric.Epoch" /> zu vergleichende Objekt.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-147">The right <see cref="T:System.Fabric.Epoch" /> object to compare.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b8a1b-148">Bestimmt, ob ein angegebener <see cref="T:System.Fabric.Epoch" /> -Objekts kleiner ist als ein anderer angegebener <see cref="T:System.Fabric.Epoch" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-148">Determines whether one specified <see cref="T:System.Fabric.Epoch" /> object is less than another specified <see cref="T:System.Fabric.Epoch" /> object.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="b8a1b-149"><languageKeyword>"true"</languageKeyword> Wenn der Wert der <paramref name="left" /> ist kleiner als der Wert des <paramref name="right" />ist, andernfalls <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-149"><languageKeyword>true</languageKeyword> if the value of <paramref name="left" /> is less than the value of <paramref name="right" />; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_LessThanOrEqual">
      <MemberSignature Language="C#" Value="public static bool operator &lt;= (System.Fabric.Epoch left, System.Fabric.Epoch right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_LessThanOrEqual(valuetype System.Fabric.Epoch left, valuetype System.Fabric.Epoch right) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.op_LessThanOrEqual(System.Fabric.Epoch,System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator &lt;= (left As Epoch, right As Epoch) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( &lt;= ) : System.Fabric.Epoch * System.Fabric.Epoch -&gt; bool" Usage="left &lt;= right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="System.Fabric.Epoch" />
        <Parameter Name="right" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="left">
          <para><span data-ttu-id="b8a1b-150">Links <see cref="T:System.Fabric.Epoch" /> zu vergleichende Objekt.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-150">The left <see cref="T:System.Fabric.Epoch" /> object to compare.</span></span></para>
        </param>
        <param name="right">
          <para><span data-ttu-id="b8a1b-151">Das Recht <see cref="T:System.Fabric.Epoch" /> zu vergleichende Objekt.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-151">The right <see cref="T:System.Fabric.Epoch" /> object to compare.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b8a1b-152">Bestimmt, ob ein angegebener <see cref="T:System.Fabric.Epoch" /> Objekt ist kleiner oder gleich einem anderen angegebenen <see cref="T:System.Fabric.Epoch" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-152">Determines whether one specified <see cref="T:System.Fabric.Epoch" /> object is less than or equal to another specified <see cref="T:System.Fabric.Epoch" /> object.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="b8a1b-153"><languageKeyword>"true"</languageKeyword> Wenn der Wert der <paramref name="left" /> ist kleiner oder gleich dem Wert des <paramref name="right" />ist, andernfalls <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="b8a1b-153"><languageKeyword>true</languageKeyword> if the value of <paramref name="left" /> is less than or equal to the value of <paramref name="right" />; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>