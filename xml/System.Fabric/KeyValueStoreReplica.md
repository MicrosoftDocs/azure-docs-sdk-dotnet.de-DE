<Type Name="KeyValueStoreReplica" FullName="System.Fabric.KeyValueStoreReplica">
  <TypeSignature Language="C#" Value="public class KeyValueStoreReplica : System.Fabric.IStatefulServiceReplica" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyValueStoreReplica extends System.Object implements class System.Fabric.IStatefulServiceReplica" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.KeyValueStoreReplica" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyValueStoreReplica&#xA;Implements IStatefulServiceReplica" />
  <TypeSignature Language="F#" Value="type KeyValueStoreReplica = class&#xA;    interface IStatefulServiceReplica&#xA;    interface IBackupRestoreReplica" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Fabric.IStatefulServiceReplica</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <span data-ttu-id="70d80-101"><para>Stellt eine Komponente Transaktions-, assoziative replizierten Daten für Service-Writer - bereit für die Integration in jeder Service Fabric-Dienst bereit.</para></span><span class="sxs-lookup"><span data-stu-id="70d80-101"><para>Provides a transactional, replicated, associative data storage component to service writers - ready for integration into any Service Fabric service.</para></span></span>
            <span data-ttu-id="70d80-102">Dies wird von älteren Service Fabric-Diensten.</span><span class="sxs-lookup"><span data-stu-id="70d80-102">This is used by legacy Service Fabric services.</span></span> <span data-ttu-id="70d80-103">Alle neuen Dienste verwenden, sollten die <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-reliable-collections">zuverlässige Sammlungen</see>.</span><span class="sxs-lookup"><span data-stu-id="70d80-103">All new services should use the <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-reliable-collections">Reliable Collections</see>.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyValueStoreReplica (string storeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (storeName As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.KeyValueStoreReplica : string -&gt; System.Fabric.KeyValueStoreReplica" Usage="new System.Fabric.KeyValueStoreReplica storeName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storeName">
          <para><span data-ttu-id="70d80-104">Der Name des Schlüssel/Wert-Speichers.</span><span class="sxs-lookup"><span data-stu-id="70d80-104">The name of the key/value store.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-105">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.KeyValueStoreReplica" /> Klasse mit dem angegebenen Schlüssel/Wert-Geschäftsnamen.</span><span class="sxs-lookup"><span data-stu-id="70d80-105">Initializes a new instance of the <see cref="T:System.Fabric.KeyValueStoreReplica" /> class with the specified key/value store name.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="70d80-106">Der Speichername muss gültige Dateinamenzeichen entsprechen.</span><span class="sxs-lookup"><span data-stu-id="70d80-106">The store name should conform to valid filename characters.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyValueStoreReplica (string storeName, System.Fabric.LocalStoreSettings localStoreSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storeName, class System.Fabric.LocalStoreSettings localStoreSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.#ctor(System.String,System.Fabric.LocalStoreSettings)" />
      <MemberSignature Language="F#" Value="new System.Fabric.KeyValueStoreReplica : string * System.Fabric.LocalStoreSettings -&gt; System.Fabric.KeyValueStoreReplica" Usage="new System.Fabric.KeyValueStoreReplica (storeName, localStoreSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storeName" Type="System.String" />
        <Parameter Name="localStoreSettings" Type="System.Fabric.LocalStoreSettings" />
      </Parameters>
      <Docs>
        <param name="storeName">
          <para><span data-ttu-id="70d80-107">Der Name des Schlüssel/Wert-Speichers.</span><span class="sxs-lookup"><span data-stu-id="70d80-107">The name of the key/value store.</span></span></para>
        </param>
        <param name="localStoreSettings">
          <para><span data-ttu-id="70d80-108">Die optionalen Einstellungen für den lokalen Speicher.</span><span class="sxs-lookup"><span data-stu-id="70d80-108">The optional settings for the local store.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-109">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.KeyValueStoreReplica" /> Klasse mit dem angegebenen Schlüssel/Wert zu speichern, Namen und Einstellungen für lokalen Speicher.</span><span class="sxs-lookup"><span data-stu-id="70d80-109">Initializes a new instance of the <see cref="T:System.Fabric.KeyValueStoreReplica" /> class with the specified key/value store name and local store settings.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyValueStoreReplica (string storeName, System.Fabric.ReplicatorSettings replicatorSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storeName, class System.Fabric.ReplicatorSettings replicatorSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.#ctor(System.String,System.Fabric.ReplicatorSettings)" />
      <MemberSignature Language="F#" Value="new System.Fabric.KeyValueStoreReplica : string * System.Fabric.ReplicatorSettings -&gt; System.Fabric.KeyValueStoreReplica" Usage="new System.Fabric.KeyValueStoreReplica (storeName, replicatorSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storeName" Type="System.String" />
        <Parameter Name="replicatorSettings" Type="System.Fabric.ReplicatorSettings" />
      </Parameters>
      <Docs>
        <param name="storeName">
          <para><span data-ttu-id="70d80-110">Der Name des Schlüssel/Wert-Speichers.</span><span class="sxs-lookup"><span data-stu-id="70d80-110">The name of the key/value store.</span></span></para>
        </param>
        <param name="replicatorSettings">
          <para><span data-ttu-id="70d80-111">Die optionseinstellungen für den Schlüssel/Wert speichern Replikator.</span><span class="sxs-lookup"><span data-stu-id="70d80-111">The option settings for the key/value store replicator.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-112">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.KeyValueStoreReplica" /> -Klasse mit den angegebenen Schlüssel/Wert-Geschäftsnamen und Replikator Einstellungen speichern.</span><span class="sxs-lookup"><span data-stu-id="70d80-112">Initializes a new instance of the <see cref="T:System.Fabric.KeyValueStoreReplica" /> class with the specified key/value store name and store replicator settings.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="70d80-113">Der Speichername muss gültige Dateinamenzeichen entsprechen.</span><span class="sxs-lookup"><span data-stu-id="70d80-113">The store name should conform to valid filename characters.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyValueStoreReplica (string storeName, System.Fabric.LocalStoreSettings localStoreSettings, System.Fabric.ReplicatorSettings replicatorSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storeName, class System.Fabric.LocalStoreSettings localStoreSettings, class System.Fabric.ReplicatorSettings replicatorSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.#ctor(System.String,System.Fabric.LocalStoreSettings,System.Fabric.ReplicatorSettings)" />
      <MemberSignature Language="F#" Value="new System.Fabric.KeyValueStoreReplica : string * System.Fabric.LocalStoreSettings * System.Fabric.ReplicatorSettings -&gt; System.Fabric.KeyValueStoreReplica" Usage="new System.Fabric.KeyValueStoreReplica (storeName, localStoreSettings, replicatorSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storeName" Type="System.String" />
        <Parameter Name="localStoreSettings" Type="System.Fabric.LocalStoreSettings" />
        <Parameter Name="replicatorSettings" Type="System.Fabric.ReplicatorSettings" />
      </Parameters>
      <Docs>
        <param name="storeName">
          <para><span data-ttu-id="70d80-114">Der Name des Schlüssel/Wert-Speichers.</span><span class="sxs-lookup"><span data-stu-id="70d80-114">The name of the key/value store.</span></span></para>
        </param>
        <param name="localStoreSettings">
          <para><span data-ttu-id="70d80-115">Die optionalen Einstellungen für den lokalen Speicher.</span><span class="sxs-lookup"><span data-stu-id="70d80-115">The optional settings for the local store.</span></span></para>
        </param>
        <param name="replicatorSettings">
          <para><span data-ttu-id="70d80-116">Die optionseinstellungen für den Schlüssel/Wert speichern Replikator.</span><span class="sxs-lookup"><span data-stu-id="70d80-116">The option settings for the key/value store replicator.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-117">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.KeyValueStoreReplica" /> Klasse mit dem angegebenen Schlüssel/Wert zu speichern, Name, der lokalen Speicher und Replikator Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="70d80-117">Initializes a new instance of the <see cref="T:System.Fabric.KeyValueStoreReplica" /> class with the specified key/value store name, local store settings, and replicator settings.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyValueStoreReplica (string storeName, System.Fabric.LocalStoreSettings localStoreSettings, System.Fabric.ReplicatorSettings replicatorSettings, System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode notificationMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storeName, class System.Fabric.LocalStoreSettings localStoreSettings, class System.Fabric.ReplicatorSettings replicatorSettings, valuetype System.Fabric.KeyValueStoreReplica/SecondaryNotificationMode notificationMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.#ctor(System.String,System.Fabric.LocalStoreSettings,System.Fabric.ReplicatorSettings,System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.KeyValueStoreReplica : string * System.Fabric.LocalStoreSettings * System.Fabric.ReplicatorSettings * System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode -&gt; System.Fabric.KeyValueStoreReplica" Usage="new System.Fabric.KeyValueStoreReplica (storeName, localStoreSettings, replicatorSettings, notificationMode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storeName" Type="System.String" />
        <Parameter Name="localStoreSettings" Type="System.Fabric.LocalStoreSettings" />
        <Parameter Name="replicatorSettings" Type="System.Fabric.ReplicatorSettings" />
        <Parameter Name="notificationMode" Type="System.Fabric.KeyValueStoreReplica+SecondaryNotificationMode" />
      </Parameters>
      <Docs>
        <param name="storeName">
          <para><span data-ttu-id="70d80-118">Der Name des Schlüssel/Wert-Speichers.</span><span class="sxs-lookup"><span data-stu-id="70d80-118">The name of the key/value store.</span></span></para>
        </param>
        <param name="localStoreSettings">
          <para><span data-ttu-id="70d80-119">Die optionalen Einstellungen für den lokalen Speicher.</span><span class="sxs-lookup"><span data-stu-id="70d80-119">The optional settings for the local store.</span></span></para>
        </param>
        <param name="replicatorSettings">
          <para><span data-ttu-id="70d80-120">Die optionseinstellungen für den Schlüssel/Wert speichern Replikator.</span><span class="sxs-lookup"><span data-stu-id="70d80-120">The option settings for the key/value store replicator.</span></span></para>
        </param>
        <param name="notificationMode">
          <para><span data-ttu-id="70d80-121">So aktivieren Sie die sekundäre Benachrichtigungsmodus <see cref="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" /> und <see cref="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" /> Rückrufe auf diesem Replikat.</span><span class="sxs-lookup"><span data-stu-id="70d80-121">The secondary notification mode to enable <see cref="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" /> and <see cref="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" /> callbacks on this replica.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-122">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.KeyValueStoreReplica" /> Klasse mit dem angegebenen Schlüssel/Wert zu speichern, Name, der lokalen Speicher und Replikator Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="70d80-122">Initializes a new instance of the <see cref="T:System.Fabric.KeyValueStoreReplica" /> class with the specified key/value store name, local store settings, and replicator settings.</span></span> <span data-ttu-id="70d80-123">Sekundäres Replikat Benachrichtigungen sind über den Benachrichtigungsmodus aktiviert.</span><span class="sxs-lookup"><span data-stu-id="70d80-123">Secondary replica notifications are enabled via the notification mode.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyValueStoreReplica (string storeName, System.Fabric.LocalStoreSettings localStoreSettings, System.Fabric.ReplicatorSettings replicatorSettings, System.Fabric.KeyValueStoreReplicaSettings kvsSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storeName, class System.Fabric.LocalStoreSettings localStoreSettings, class System.Fabric.ReplicatorSettings replicatorSettings, class System.Fabric.KeyValueStoreReplicaSettings kvsSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.#ctor(System.String,System.Fabric.LocalStoreSettings,System.Fabric.ReplicatorSettings,System.Fabric.KeyValueStoreReplicaSettings)" />
      <MemberSignature Language="F#" Value="new System.Fabric.KeyValueStoreReplica : string * System.Fabric.LocalStoreSettings * System.Fabric.ReplicatorSettings * System.Fabric.KeyValueStoreReplicaSettings -&gt; System.Fabric.KeyValueStoreReplica" Usage="new System.Fabric.KeyValueStoreReplica (storeName, localStoreSettings, replicatorSettings, kvsSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storeName" Type="System.String" />
        <Parameter Name="localStoreSettings" Type="System.Fabric.LocalStoreSettings" />
        <Parameter Name="replicatorSettings" Type="System.Fabric.ReplicatorSettings" />
        <Parameter Name="kvsSettings" Type="System.Fabric.KeyValueStoreReplicaSettings" />
      </Parameters>
      <Docs>
        <param name="storeName"><span data-ttu-id="70d80-124">Der Name des Schlüssel/Wert-Speichers.</span><span class="sxs-lookup"><span data-stu-id="70d80-124">The name of the key/value store.</span></span></param>
        <param name="localStoreSettings"><span data-ttu-id="70d80-125">Die optionalen Einstellungen für den lokalen Speicher.</span><span class="sxs-lookup"><span data-stu-id="70d80-125">The optional settings for the local store.</span></span></param>
        <param name="replicatorSettings"><span data-ttu-id="70d80-126">Die optionalen Einstellungen für den Schlüssel/Wert speichern Replikator.</span><span class="sxs-lookup"><span data-stu-id="70d80-126">The optional settings for the key/value store replicator.</span></span></param>
        <param name="kvsSettings"><span data-ttu-id="70d80-127">Die optionalen Einstellungen für das Replikat der Schlüssel/Wert-Speicher.</span><span class="sxs-lookup"><span data-stu-id="70d80-127">The optional settings for the key/value store replica.</span></span></param>
        <summary>
            <span data-ttu-id="70d80-128">Initialisiert eine neue Instanz der Klasse mit der angegebene Schlüssel-Wert-Speichername, Einstellungen des lokalen Speicher Replikator Einstellungen und replikateinstellungen KeyValueStoreReplica.</span><span class="sxs-lookup"><span data-stu-id="70d80-128">Initializes a new instance of the KeyValueStoreReplica class with the specified key/value store name, local store settings, replicator settings, and replica settings.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Abort">
      <MemberSignature Language="C#" Value="public void Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Abort" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abort ()" />
      <MemberSignature Language="F#" Value="abstract member Abort : unit -&gt; unit&#xA;override this.Abort : unit -&gt; unit" Usage="keyValueStoreReplica.Abort " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStatefulServiceReplica.Abort</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="70d80-129">Bricht diese Instanz die <see cref="T:System.Fabric.KeyValueStoreReplica" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="70d80-129">Aborts this instance of the <see cref="T:System.Fabric.KeyValueStoreReplica" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (System.Fabric.TransactionBase transactionBase, string key, byte[] value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Add(class System.Fabric.TransactionBase transactionBase, string key, unsigned int8[] value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Add(System.Fabric.TransactionBase,System.String,System.Byte[])" />
      <MemberSignature Language="F#" Value="member this.Add : System.Fabric.TransactionBase * string * byte[] -&gt; unit" Usage="keyValueStoreReplica.Add (transactionBase, key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para><span data-ttu-id="70d80-130">Die Transaktion-Instanz.</span><span class="sxs-lookup"><span data-stu-id="70d80-130">The transaction instance.</span></span></para>
        </param>
        <param name="key">
          <para><span data-ttu-id="70d80-131">Der Schlüssel oder Index des Werts (als eine Zeichenfolge) hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="70d80-131">The key or index of the value to be added (as a string).</span></span> <span data-ttu-id="70d80-132">Beschränkt auf 800 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="70d80-132">Limited to 800 characters in length.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="70d80-133">Der Wert (als Bytearray) gespeichert werden, beschränkt auf 2GB umfassen.</span><span class="sxs-lookup"><span data-stu-id="70d80-133">The value (as a byte array) to be stored, limited to 2GB in length.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-134">Fügt einen Wert, der durch den angegebenen Schlüssel im Schlüssel/Wert-Speicher indiziert.</span><span class="sxs-lookup"><span data-stu-id="70d80-134">Adds a value indexed by the specified key to the key/value store.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Backup">
      <MemberSignature Language="C#" Value="public void Backup (string backupDirectory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Backup(string backupDirectory) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Backup(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Backup (backupDirectory As String)" />
      <MemberSignature Language="F#" Value="member this.Backup : string -&gt; unit" Usage="keyValueStoreReplica.Backup backupDirectory" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use BackupAsync instead")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDirectory" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupDirectory">
          <para><span data-ttu-id="70d80-135">Der vollständige Pfad des Verzeichnisses Sicherungsziel.</span><span class="sxs-lookup"><span data-stu-id="70d80-135">The full path of the backup destination directory.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-136">ALS VERALTET MARKIERT.</span><span class="sxs-lookup"><span data-stu-id="70d80-136">DEPRECATED.</span></span> <span data-ttu-id="70d80-137">Führt eine vollständige Sicherung der lokale Speicher das Replikat des angegebenen Zielverzeichnisses an.</span><span class="sxs-lookup"><span data-stu-id="70d80-137">Performs a full backup of the replica's local store to the specified destination directory.</span></span> </para>
        </summary>
        <remarks>
          <para>
            <span data-ttu-id="70d80-138">Diese Methode ist veraltet.</span><span class="sxs-lookup"><span data-stu-id="70d80-138">This method is obsolete.</span></span> <span data-ttu-id="70d80-139">Verwenden Sie stattdessen <see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" />.</span><span class="sxs-lookup"><span data-stu-id="70d80-139">Use <see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" /> instead.</span></span></para>
          <para>
            <span data-ttu-id="70d80-140">Inkrementelle Sicherungen werden nach dem Erstellen einer vollständigen Sicherung, die mit dieser Methode nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="70d80-140">Incremental backups are not supported after creating a full backup using this method.</span></span> <span data-ttu-id="70d80-141">Verwendung <see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" /> , eine vollständige Sicherung zu erstellen, wenn es sich bei nachfolgende inkrementelle Sicherungen erstellt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="70d80-141">Use <see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" /> to create a full backup if subsequent incremental backups are to be created.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BackupAsync (string backupDirectory, System.Fabric.StoreBackupOption backupOption, Func&lt;System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task&lt;bool&gt;&gt; postBackupAsyncFunc);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task BackupAsync(string backupDirectory, valuetype System.Fabric.StoreBackupOption backupOption, class System.Func`2&lt;class System.Fabric.StoreBackupInfo, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; postBackupAsyncFunc) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberSignature Language="VB.NET" Value="Public Function BackupAsync (backupDirectory As String, backupOption As StoreBackupOption, postBackupAsyncFunc As Func(Of StoreBackupInfo, Task(Of Boolean))) As Task" />
      <MemberSignature Language="F#" Value="member this.BackupAsync : string * System.Fabric.StoreBackupOption * Func&lt;System.Fabric.StoreBackupInfo, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.BackupAsync (backupDirectory, backupOption, postBackupAsyncFunc)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDirectory" Type="System.String" />
        <Parameter Name="backupOption" Type="System.Fabric.StoreBackupOption" />
        <Parameter Name="postBackupAsyncFunc" Type="System.Func&lt;System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="backupDirectory">
            <span data-ttu-id="70d80-142">Das Verzeichnis, in dem die Sicherung gespeichert werden soll.</span><span class="sxs-lookup"><span data-stu-id="70d80-142">The directory where the backup is to be stored.</span></span> <span data-ttu-id="70d80-143">Wenn <b>BackupOption</b> ist <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />, sollte dieser Parameter werden <b>null</b>.</span><span class="sxs-lookup"><span data-stu-id="70d80-143">If <b>backupOption</b> is <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />, then this parameter should be <b>null</b>.</span></span>
            <span data-ttu-id="70d80-144">Dieser Parameter darf nicht sein, anderenfalls <b>null</b>, leer oder enthält nur Leerzeichen.</span><span class="sxs-lookup"><span data-stu-id="70d80-144">Otherwise, this parameter cannot be <b>null</b>, empty or contain just whitespace.</span></span> <span data-ttu-id="70d80-145">UNC-Pfade können auch angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="70d80-145">UNC paths may also be provided.</span></span>
            <span data-ttu-id="70d80-146">Wenn das Verzeichnis nicht vorhanden ist, wird es erstellt.</span><span class="sxs-lookup"><span data-stu-id="70d80-146">If the directory doesn't exist, it is created.</span></span> <span data-ttu-id="70d80-147">Wenn es vorhanden ist und nicht leer ist, misslingt die inkrementeller Sicherung mit <see cref="T:System.Fabric.FabricBackupDirectoryNotEmptyException" />.</span><span class="sxs-lookup"><span data-stu-id="70d80-147">If it exists and isn't empty, then incremental backup fails with <see cref="T:System.Fabric.FabricBackupDirectoryNotEmptyException" />.</span></span>
            </param>
        <param name="backupOption">
          <para><span data-ttu-id="70d80-148">Die Optionen für die Sicherung.</span><span class="sxs-lookup"><span data-stu-id="70d80-148">The options for the backup.</span></span></para>
        </param>
        <param name="postBackupAsyncFunc">
            <span data-ttu-id="70d80-149">Im Beitrag sichern asynchrone Methode, die von Service Fabric, damit der Benutzer alle nach der Sicherung Aktivität abgeschlossen wird, vor dem Zurückgeben der Steuerung an das System kann aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="70d80-149">The post backup asynchronous method that is invoked by Service Fabric to allow the user to complete any post backup activity before returning control to the system.</span></span>
            <span data-ttu-id="70d80-150">Wenn <b>null</b> übergeben, inkrementelle Sicherungen sind nicht zulässig.</span><span class="sxs-lookup"><span data-stu-id="70d80-150">If <b>null</b> is passed in for this, incremental backups are disallowed.</span></span>
            <span data-ttu-id="70d80-151">Wenn die Methode nach der Sicherung auf "false" zurückgibt, sind dann erneut inkrementelle Sicherungen nicht zulässig.</span><span class="sxs-lookup"><span data-stu-id="70d80-151">If the post-backup method returns false, then again, incremental backups are disallowed.</span></span>
            </param>
        <summary>
          <para><span data-ttu-id="70d80-152">Erstellt asynchron eine Sicherung des Schlüssel/Wert-Speichers.</span><span class="sxs-lookup"><span data-stu-id="70d80-152">Asynchronously creates a backup of the key/value store.</span></span></para>
        </summary>
        <returns><span data-ttu-id="70d80-153">Eine Aufgabe, die den asynchronen backup-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="70d80-153">A task that represents the asynchronous backup operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="70d80-154">Die <b>PostBackupAsyncFunc</b> wird nicht aufgerufen, wenn während der Sicherung ein Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="70d80-154">The <b>postBackupAsyncFunc</b> is not invoked if there is an error during backup.</span></span> <span data-ttu-id="70d80-155">Außerdem ist es nicht aufgerufen wird, wenn <b>BackupOption</b> ist <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" /> , da es ist keine weitere Aktion, die vom Benutzer in diesem Fall einen einzelnen Sicherungszyklus abgeschlossen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="70d80-155">Also, it is not invoked when <b>backupOption</b> is <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" /> since there is no further action needed from the user in this case to complete a single backup cycle.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="70d80-156"><b>BackupDirectory</b> ist <b>null</b> Wenn <b>BackupOption</b> nicht <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />.</span><span class="sxs-lookup"><span data-stu-id="70d80-156"><b>backupDirectory</b> is <b>null</b> when <b>backupOption</b> is not <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />.</span></span>
            </exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="70d80-157"><b>BackupDirectory</b> ist leer oder enthält nur Leerzeichen beim <b>BackupOption</b> nicht <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" /> oder <b>BackupDirectory</b> nicht <b>null</b> bei <b>BackupOption</b> ist <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />.</span><span class="sxs-lookup"><span data-stu-id="70d80-157"><b>backupDirectory</b> is empty or contains just whitespaces when <b>backupOption</b> is not <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" /> or <b>backupDirectory</b> is not <b>null</b> when <b>backupOption</b> is <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricBackupDirectoryNotEmptyException">
            <span data-ttu-id="70d80-158">Wenn <b>BackupOption</b> ist <see cref="F:System.Fabric.StoreBackupOption.Incremental" /> und das Sicherungsverzeichnis Dateien oder Unterverzeichnisse bereits enthält.</span><span class="sxs-lookup"><span data-stu-id="70d80-158">When <b>backupOption</b> is <see cref="F:System.Fabric.StoreBackupOption.Incremental" /> and the backup directory already contains files or sub-directories.</span></span>        
            </exception>
        <exception cref="T:System.Fabric.FabricBackupInProgressException">
            <span data-ttu-id="70d80-159">Wenn eine zuvor begonnene Sicherung gerade ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="70d80-159">When a previously initiated backup is currently in progress.</span></span>
            </exception>
        <example>
            <span data-ttu-id="70d80-160">Im folgenden finden Sie ein Beispiel für eine einfache Implementierung der <b>PostBackupAsyncFunc</b><code>
            private async Task&lt;bool&gt; SimplePostBackupHandler(StoreBackupInfo info)
            {
                return await CopyBackupToAzureBlobStorage(info);
            }</span><span class="sxs-lookup"><span data-stu-id="70d80-160">Below is an example of a simple implementation of <b>postBackupAsyncFunc</b><code>
            private async Task&lt;bool&gt; SimplePostBackupHandler(StoreBackupInfo info)
{
return await CopyBackupToAzureBlobStorage(info);
}</span></span>
</code></example>
      </Docs>
    </Member>
    <Member MemberName="BackupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BackupAsync (string backupDirectory, System.Fabric.StoreBackupOption backupOption, Func&lt;System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task&lt;bool&gt;&gt; postBackupAsyncFunc, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task BackupAsync(string backupDirectory, valuetype System.Fabric.StoreBackupOption backupOption, class System.Func`2&lt;class System.Fabric.StoreBackupInfo, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; postBackupAsyncFunc, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.BackupAsync : string * System.Fabric.StoreBackupOption * Func&lt;System.Fabric.StoreBackupInfo, System.Threading.Tasks.Task&lt;bool&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.BackupAsync (backupDirectory, backupOption, postBackupAsyncFunc, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDirectory" Type="System.String" />
        <Parameter Name="backupOption" Type="System.Fabric.StoreBackupOption" />
        <Parameter Name="postBackupAsyncFunc" Type="System.Func&lt;System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="backupDirectory">
            <span data-ttu-id="70d80-161">Das Verzeichnis, in dem die Sicherung gespeichert werden soll.</span><span class="sxs-lookup"><span data-stu-id="70d80-161">The directory where the backup is to be stored.</span></span> <span data-ttu-id="70d80-162">Wenn <b>BackupOption</b> ist <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />, sollte dieser Parameter werden <b>null</b>.</span><span class="sxs-lookup"><span data-stu-id="70d80-162">If <b>backupOption</b> is <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />, then this parameter should be <b>null</b>.</span></span>
            <span data-ttu-id="70d80-163">Dieser Parameter darf nicht sein, anderenfalls <b>null</b>, leer oder enthält nur Leerzeichen.</span><span class="sxs-lookup"><span data-stu-id="70d80-163">Otherwise, this parameter cannot be <b>null</b>, empty or contain just whitespace.</span></span> <span data-ttu-id="70d80-164">UNC-Pfade können auch angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="70d80-164">UNC paths may also be provided.</span></span>
            <span data-ttu-id="70d80-165">Wenn das Verzeichnis nicht vorhanden ist, wird es erstellt.</span><span class="sxs-lookup"><span data-stu-id="70d80-165">If the directory doesn't exist, it is created.</span></span> <span data-ttu-id="70d80-166">Wenn es vorhanden ist und nicht leer ist, misslingt die inkrementeller Sicherung mit <see cref="T:System.Fabric.FabricBackupDirectoryNotEmptyException" />.</span><span class="sxs-lookup"><span data-stu-id="70d80-166">If it exists and isn't empty, then incremental backup fails with <see cref="T:System.Fabric.FabricBackupDirectoryNotEmptyException" />.</span></span>
            </param>
        <param name="backupOption">
          <para><span data-ttu-id="70d80-167">Die Optionen für die Sicherung.</span><span class="sxs-lookup"><span data-stu-id="70d80-167">The options for the backup.</span></span></para>
        </param>
        <param name="postBackupAsyncFunc">
            <span data-ttu-id="70d80-168">Im Beitrag sichern asynchrone Methode, die von Service Fabric, damit der Benutzer alle nach der Sicherung Aktivität abgeschlossen wird, vor dem Zurückgeben der Steuerung an das System kann aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="70d80-168">The post backup asynchronous method that is invoked by Service Fabric to allow the user to complete any post backup activity before returning control to the system.</span></span>
            <span data-ttu-id="70d80-169">Wenn <b>null</b> übergeben, inkrementelle Sicherungen sind nicht zulässig.</span><span class="sxs-lookup"><span data-stu-id="70d80-169">If <b>null</b> is passed in for this, incremental backups are disallowed.</span></span>
            <span data-ttu-id="70d80-170">Wenn die Methode nach der Sicherung auf "false" zurückgibt, sind dann erneut inkrementelle Sicherungen nicht zulässig.</span><span class="sxs-lookup"><span data-stu-id="70d80-170">If the post-backup method returns false, then again, incremental backups are disallowed.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="70d80-171">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="70d80-171">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="70d80-172">Erstellt asynchron eine Sicherung des Schlüssel/Wert-Speichers.</span><span class="sxs-lookup"><span data-stu-id="70d80-172">Asynchronously creates a backup of the key/value store.</span></span>
            </summary>
        <returns><span data-ttu-id="70d80-173">Eine Aufgabe, die den asynchronen backup-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="70d80-173">A task that represents the asynchronous backup operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="70d80-174">Die <b>PostBackupAsyncFunc</b> wird nicht aufgerufen, wenn während der Sicherung ein Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="70d80-174">The <b>postBackupAsyncFunc</b> is not invoked if there is an error during backup.</span></span> <span data-ttu-id="70d80-175">Außerdem ist es nicht aufgerufen wird, wenn <b>BackupOption</b> ist <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" /> , da es ist keine weitere Aktion, die vom Benutzer in diesem Fall einen einzelnen Sicherungszyklus abgeschlossen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="70d80-175">Also, it is not invoked when <b>backupOption</b> is <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" /> since there is no further action needed from the user in this case to complete a single backup cycle.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="70d80-176"><b>BackupDirectory</b> ist <b>null</b> Wenn <b>BackupOption</b> nicht <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />.</span><span class="sxs-lookup"><span data-stu-id="70d80-176"><b>backupDirectory</b> is <b>null</b> when <b>backupOption</b> is not <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />.</span></span>
            </exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="70d80-177"><b>BackupDirectory</b> ist leer oder enthält nur Leerzeichen beim <b>BackupOption</b> nicht <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" /> oder <b>BackupDirectory</b> nicht <b>null</b> bei <b>BackupOption</b> ist <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />.</span><span class="sxs-lookup"><span data-stu-id="70d80-177"><b>backupDirectory</b> is empty or contains just whitespaces when <b>backupOption</b> is not <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" /> or <b>backupDirectory</b> is not <b>null</b> when <b>backupOption</b> is <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricBackupDirectoryNotEmptyException">
            <span data-ttu-id="70d80-178">Wenn <b>BackupOption</b> ist <see cref="F:System.Fabric.StoreBackupOption.Incremental" /> und das Sicherungsverzeichnis Dateien oder Unterverzeichnisse bereits enthält.</span><span class="sxs-lookup"><span data-stu-id="70d80-178">When <b>backupOption</b> is <see cref="F:System.Fabric.StoreBackupOption.Incremental" /> and the backup directory already contains files or sub-directories.</span></span>        
            </exception>
        <exception cref="T:System.Fabric.FabricBackupInProgressException">
            <span data-ttu-id="70d80-179">Wenn eine zuvor begonnene Sicherung gerade ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="70d80-179">When a previously initiated backup is currently in progress.</span></span>
            </exception>
        <example>
            <span data-ttu-id="70d80-180">Im folgenden finden Sie ein Beispiel für eine einfache Implementierung der <b>PostBackupAsyncFunc</b><code>
            private async Task&lt;bool&gt; SimplePostBackupHandler(StoreBackupInfo info)
            {
                return await CopyBackupToAzureBlobStorage(info);
            }</span><span class="sxs-lookup"><span data-stu-id="70d80-180">Below is an example of a simple implementation of <b>postBackupAsyncFunc</b><code>
            private async Task&lt;bool&gt; SimplePostBackupHandler(StoreBackupInfo info)
{
return await CopyBackupToAzureBlobStorage(info);
}</span></span>
</code></example>
      </Docs>
    </Member>
    <Member MemberName="ChangeRoleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; ChangeRoleAsync (System.Fabric.ReplicaRole newRole, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; ChangeRoleAsync(valuetype System.Fabric.ReplicaRole newRole, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.ChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="keyValueStoreReplica.ChangeRoleAsync (newRole, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStatefulServiceReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.KeyValueStoreReplica/&lt;ChangeRoleAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="newRole" Type="System.Fabric.ReplicaRole" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="newRole">
          <para><span data-ttu-id="70d80-181">Die replikatrolle Ziel.</span><span class="sxs-lookup"><span data-stu-id="70d80-181">The target replica role.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="70d80-182">Derzeit wird nicht verwendet.</span><span class="sxs-lookup"><span data-stu-id="70d80-182">Currently unused.</span></span> <span data-ttu-id="70d80-183">Für zukünftige Verwendung reserviert.</span><span class="sxs-lookup"><span data-stu-id="70d80-183">Reserved for future use.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-184">Ändert die replikatrolle, der das Replikat als auch ihre Replikator an.</span><span class="sxs-lookup"><span data-stu-id="70d80-184">Changes the replica role of the replica and its replicator.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="70d80-185">Eine Aufgabe, deren Ergebnis die Adresse für dieses Replikat ist.</span><span class="sxs-lookup"><span data-stu-id="70d80-185">A task whose result is the address of this replica.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="70d80-186">Diese Methode muss nicht explizit aufgerufen werden, wenn das Replikat für die Anwendung abgeleitet <see cref="T:System.Fabric.KeyValueStoreReplica" />, dies ist das empfohlene Muster.</span><span class="sxs-lookup"><span data-stu-id="70d80-186">This method does not need to be called explicitly if the application replica derives from <see cref="T:System.Fabric.KeyValueStoreReplica" />, which is the recommended pattern.</span></span> <span data-ttu-id="70d80-187">In diesem Fall sollte die anwendungsreplikaten überschreiben <see cref="M:System.Fabric.KeyValueStoreReplica.OnChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" /> stattdessen.</span><span class="sxs-lookup"><span data-stu-id="70d80-187">In this case, the application replica should override <see cref="M:System.Fabric.KeyValueStoreReplica.OnChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" /> instead.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.CloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.CloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStatefulServiceReplica.CloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.KeyValueStoreReplica/&lt;CloseAsync&gt;d__58))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para><span data-ttu-id="70d80-188">Derzeit wird nicht verwendet.</span><span class="sxs-lookup"><span data-stu-id="70d80-188">Currently unused.</span></span> <span data-ttu-id="70d80-189">Für zukünftige Verwendung reserviert.</span><span class="sxs-lookup"><span data-stu-id="70d80-189">Reserved for future use.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-190">Schließt das Replikat und ihre Replikator Vorbereitung aus einem Replikatsatz offline geschaltet.</span><span class="sxs-lookup"><span data-stu-id="70d80-190">Closes the replica and its replicator in preparation for going offline from a replica set.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="70d80-191">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="70d80-191">A task that represents the asynchronous operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="70d80-192">Das Replikat nicht zwangsläufig entfernt dauerhaft aus dem Replikatsatz und kann zu einem späteren Zeitpunkt erneut geöffnet werden.</span><span class="sxs-lookup"><span data-stu-id="70d80-192">The replica has not necessarily been removed permanently from the replica set and may be re-opened at a later time.</span></span> <span data-ttu-id="70d80-193">Die häufigsten Ursachen für das Schließen eines Replikats ist als Vorbereitung für das Upgrade oder Lastenausgleich ein ordnungsgemäßes Herunterfahren.</span><span class="sxs-lookup"><span data-stu-id="70d80-193">The most common causes for closing a replica is graceful shutdown in preparation for upgrade or load balancing.</span></span> <span data-ttu-id="70d80-194">Diese Methode muss nicht explizit aufgerufen werden, wenn das Replikat für die Anwendung abgeleitet <see cref="T:System.Fabric.KeyValueStoreReplica" />, dies ist das empfohlene Muster.</span><span class="sxs-lookup"><span data-stu-id="70d80-194">This method does not need to be called explicitly if the application replica derives from <see cref="T:System.Fabric.KeyValueStoreReplica" />, which is the recommended pattern.</span></span> <span data-ttu-id="70d80-195">In diesem Fall sollte die anwendungsreplikaten überschreiben <see cref="M:System.Fabric.KeyValueStoreReplica.OnCloseAsync(System.Threading.CancellationToken)" /> stattdessen.</span><span class="sxs-lookup"><span data-stu-id="70d80-195">In this case, the application replica should override <see cref="M:System.Fabric.KeyValueStoreReplica.OnCloseAsync(System.Threading.CancellationToken)" /> instead.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool Contains(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Contains(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.Contains : System.Fabric.TransactionBase * string -&gt; bool" Usage="keyValueStoreReplica.Contains (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para><span data-ttu-id="70d80-196">Die Transaktion-Instanz.</span><span class="sxs-lookup"><span data-stu-id="70d80-196">The transaction instance.</span></span></para>
        </param>
        <param name="key">
          <para><span data-ttu-id="70d80-197">Der Schlüssel oder Index des Werts, die (als Zeichenfolge) gesucht.</span><span class="sxs-lookup"><span data-stu-id="70d80-197">The key or index of the value to look up (as a string).</span></span> <span data-ttu-id="70d80-198">Beschränkt auf 800 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="70d80-198">Limited to 800 characters in length.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-199">Bestimmt, ob ein Wert im Schlüssel/Wert-Speicher enthalten ist.</span><span class="sxs-lookup"><span data-stu-id="70d80-199">Determines whether a value is contained in the key/value store.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="70d80-200"><languageKeyword>"true"</languageKeyword> , wenn der Wert im Schlüssel/Wert-Speicher; enthalten ist <languageKeyword>"false"</languageKeyword>, andernfalls.</span><span class="sxs-lookup"><span data-stu-id="70d80-200"><languageKeyword>true</languageKeyword> if the value is contained in the key/value store; <languageKeyword>false</languageKeyword>, otherwise.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTransaction">
      <MemberSignature Language="C#" Value="public System.Fabric.Transaction CreateTransaction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.Transaction CreateTransaction() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.CreateTransaction" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateTransaction () As Transaction" />
      <MemberSignature Language="F#" Value="member this.CreateTransaction : unit -&gt; System.Fabric.Transaction" Usage="keyValueStoreReplica.CreateTransaction " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Transaction</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="70d80-201">Erstellt einen eindeutigen <see cref="T:System.Fabric.Transaction" /> -Instanz, die verwendet wird, um einen commit oder Rollback-Gruppen von Schlüssel/Wert-Speichervorgänge.</span><span class="sxs-lookup"><span data-stu-id="70d80-201">Creates a unique <see cref="T:System.Fabric.Transaction" /> instance, which is used to commit or rollback groups of key/value store operations.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="70d80-202">Ein <see cref="T:System.Fabric.Transaction" /> Objekt, das eine Transaktion darstellt.</span><span class="sxs-lookup"><span data-stu-id="70d80-202">A <see cref="T:System.Fabric.Transaction" /> object representing a transaction.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTransaction">
      <MemberSignature Language="C#" Value="public System.Fabric.Transaction CreateTransaction (System.Fabric.KeyValueStoreTransactionSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.Transaction CreateTransaction(class System.Fabric.KeyValueStoreTransactionSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.CreateTransaction(System.Fabric.KeyValueStoreTransactionSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateTransaction (settings As KeyValueStoreTransactionSettings) As Transaction" />
      <MemberSignature Language="F#" Value="member this.CreateTransaction : System.Fabric.KeyValueStoreTransactionSettings -&gt; System.Fabric.Transaction" Usage="keyValueStoreReplica.CreateTransaction settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Transaction</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="System.Fabric.KeyValueStoreTransactionSettings" />
      </Parameters>
      <Docs>
        <param name="settings">
          <para><span data-ttu-id="70d80-203">Die transaktionseinstellungen.</span><span class="sxs-lookup"><span data-stu-id="70d80-203">The transaction settings.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-204">Erstellt einen eindeutigen <see cref="T:System.Fabric.Transaction" /> -Instanz, die verwendet wird, um einen commit oder Rollback-Gruppen von Schlüssel/Wert-Speichervorgänge.</span><span class="sxs-lookup"><span data-stu-id="70d80-204">Creates a unique <see cref="T:System.Fabric.Transaction" /> instance, which is used to commit or rollback groups of key/value store operations.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="70d80-205">Ein <see cref="T:System.Fabric.Transaction" /> Objekt, das eine Transaktion darstellt.</span><span class="sxs-lookup"><span data-stu-id="70d80-205">A <see cref="T:System.Fabric.Transaction" /> object representing a transaction.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataLossReported">
      <MemberSignature Language="C#" Value="public event EventHandler DataLossReported;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler DataLossReported" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.KeyValueStoreReplica.DataLossReported" />
      <MemberSignature Language="VB.NET" Value="Public Event DataLossReported As EventHandler " />
      <MemberSignature Language="F#" Value="member this.DataLossReported : EventHandler " Usage="member this.DataLossReported : System.EventHandler " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70d80-206">Handler für einem Datenverlust.</span><span class="sxs-lookup"><span data-stu-id="70d80-206">Handler for data loss events.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enumerate">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt; Enumerate (System.Fabric.TransactionBase transactionBase);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItem&gt; Enumerate(class System.Fabric.TransactionBase transactionBase) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Enumerate(System.Fabric.TransactionBase)" />
      <MemberSignature Language="F#" Value="member this.Enumerate : System.Fabric.TransactionBase -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;" Usage="keyValueStoreReplica.Enumerate transactionBase" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para><span data-ttu-id="70d80-207">Die Transaktion-Instanz.</span><span class="sxs-lookup"><span data-stu-id="70d80-207">The transaction instance.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-208">Gibt einen Enumerator, der durchläuft die <see cref="T:System.Fabric.KeyValueStoreItem" /> Werte im Schlüssel/Wert-Speicher.</span><span class="sxs-lookup"><span data-stu-id="70d80-208">Returns an enumerator that iterates through the <see cref="T:System.Fabric.KeyValueStoreItem" /> values in the key/value store.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="70d80-209">Ein <see cref="T:System.Fabric.KeyValueStoreItem" /> Enumerator.</span><span class="sxs-lookup"><span data-stu-id="70d80-209">A <see cref="T:System.Fabric.KeyValueStoreItem" /> enumerator.</span></span></para>
        </returns>
        <remarks>
          <para>
            <span data-ttu-id="70d80-210">Die Elemente werden in aufsteigender lexikografisch nach Schlüssel aufgelistet.</span><span class="sxs-lookup"><span data-stu-id="70d80-210">The items are enumerated in lexicographically increasing order by key.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Enumerate">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt; Enumerate (System.Fabric.TransactionBase transactionBase, string keyPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItem&gt; Enumerate(class System.Fabric.TransactionBase transactionBase, string keyPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Enumerate(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.Enumerate : System.Fabric.TransactionBase * string -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;" Usage="keyValueStoreReplica.Enumerate (transactionBase, keyPrefix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="keyPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para><span data-ttu-id="70d80-211">Die Transaktion-Instanz.</span><span class="sxs-lookup"><span data-stu-id="70d80-211">The transaction instance.</span></span></para>
        </param>
        <param name="keyPrefix">
          <para><span data-ttu-id="70d80-212">Der Schlüssel oder Index, Präfix entsprechend (als Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="70d80-212">The key, or index, prefix to match (as a string).</span></span> <span data-ttu-id="70d80-213">Beschränkt auf 800 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="70d80-213">Limited to 800 characters in length.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-214">Gibt einen Enumerator, der durchläuft die <see cref="T:System.Fabric.KeyValueStoreItem" /> Werte im Schlüssel/Wert speichern, bei denen die Wert-Schlüssel für das angegebene Präfix übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="70d80-214">Returns an enumerator that iterates through the <see cref="T:System.Fabric.KeyValueStoreItem" /> values in the key/value store, where the value keys match the specified key prefix.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="70d80-215">Ein <see cref="T:System.Fabric.KeyValueStoreItem" /> Enumerator.</span><span class="sxs-lookup"><span data-stu-id="70d80-215">A <see cref="T:System.Fabric.KeyValueStoreItem" /> enumerator.</span></span></para>
        </returns>
        <remarks>
          <para>
            <span data-ttu-id="70d80-216">Entspricht dem Aufruf von <see cref="M:System.Fabric.KeyValueStoreReplica.Enumerate(System.Fabric.TransactionBase,System.String,System.Boolean)" /> mit <b>StrictPrefix</b> festgelegt <languageKeyword>"true"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="70d80-216">Equivalent to calling <see cref="M:System.Fabric.KeyValueStoreReplica.Enumerate(System.Fabric.TransactionBase,System.String,System.Boolean)" /> with <b>strictPrefix</b> set to <languageKeyword>true</languageKeyword>.</span></span>
            </para>
          <para>
            <span data-ttu-id="70d80-217">Die Elemente werden in aufsteigender lexikografisch nach Schlüssel aufgelistet.</span><span class="sxs-lookup"><span data-stu-id="70d80-217">The items are enumerated in lexicographically increasing order by key.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Enumerate">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt; Enumerate (System.Fabric.TransactionBase transactionBase, string keyPrefix, bool strictPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItem&gt; Enumerate(class System.Fabric.TransactionBase transactionBase, string keyPrefix, bool strictPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Enumerate(System.Fabric.TransactionBase,System.String,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enumerate : System.Fabric.TransactionBase * string * bool -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;" Usage="keyValueStoreReplica.Enumerate (transactionBase, keyPrefix, strictPrefix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="keyPrefix" Type="System.String" />
        <Parameter Name="strictPrefix" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="transactionBase"><span data-ttu-id="70d80-218">Die Transaktion-Instanz.</span><span class="sxs-lookup"><span data-stu-id="70d80-218">The transaction instance.</span></span></param>
        <param name="keyPrefix"><span data-ttu-id="70d80-219">Der Schlüssel oder Index, Präfix entsprechend (als Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="70d80-219">The key, or index, prefix to match (as a string).</span></span> <span data-ttu-id="70d80-220">Beschränkt auf 800 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="70d80-220">Limited to 800 characters in length.</span></span></param>
        <param name="strictPrefix"><span data-ttu-id="70d80-221">Wenn "true" werden nur Schlüssel, die durch den Wert für das Präfix <b>KeyPrefix</b> werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="70d80-221">When true, only keys prefixed by the value specified for <b>keyPrefix</b> are returned.</span></span> <span data-ttu-id="70d80-222">Andernfalls Enumeration beginnt bei den ersten Schlüssel übereinstimmenden oder lexikografisch größer als <b>KeyPrefix</b> und wird fortgesetzt, bis keine weitere Schlüssel sind.</span><span class="sxs-lookup"><span data-stu-id="70d80-222">Otherwise, enumeration starts at the first key matching or lexicographically greater than <b>keyPrefix</b> and continues until there are no more keys.</span></span> <span data-ttu-id="70d80-223">Der Standardwert ist <b>True</b>.</span><span class="sxs-lookup"><span data-stu-id="70d80-223">The default is <b>true</b>.</span></span></param>
        <summary>
            <span data-ttu-id="70d80-224">Gibt einen Enumerator, der durchläuft die <see cref="T:System.Fabric.KeyValueStoreItem" /> Werte im Schlüssel/Wert-Speicher.</span><span class="sxs-lookup"><span data-stu-id="70d80-224">Returns an enumerator that iterates through the <see cref="T:System.Fabric.KeyValueStoreItem" /> values in the key/value store.</span></span>
            </summary>
        <returns><span data-ttu-id="70d80-225">Ein <see cref="T:System.Fabric.KeyValueStoreItem" /> Enumerator.</span><span class="sxs-lookup"><span data-stu-id="70d80-225">A <see cref="T:System.Fabric.KeyValueStoreItem" /> enumerator.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="70d80-226">Die Elemente werden in aufsteigender lexikografisch nach Schlüssel aufgelistet.</span><span class="sxs-lookup"><span data-stu-id="70d80-226">The items are enumerated in lexicographically increasing order by key.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnumerateMetadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata (System.Fabric.TransactionBase transactionBase);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata(class System.Fabric.TransactionBase transactionBase) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.EnumerateMetadata(System.Fabric.TransactionBase)" />
      <MemberSignature Language="F#" Value="member this.EnumerateMetadata : System.Fabric.TransactionBase -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;" Usage="keyValueStoreReplica.EnumerateMetadata transactionBase" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para><span data-ttu-id="70d80-227">Die Transaktion-Instanz.</span><span class="sxs-lookup"><span data-stu-id="70d80-227">The transaction instance.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-228">Gibt einen Enumerator, der durchläuft die <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> Werte im Schlüssel/Wert-Speicher.</span><span class="sxs-lookup"><span data-stu-id="70d80-228">Returns an enumerator that iterates through the <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> values in the key/value store.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="70d80-229">Ein <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> Enumerator.</span><span class="sxs-lookup"><span data-stu-id="70d80-229">A <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> enumerator.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnumerateMetadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata (System.Fabric.TransactionBase transactionBase, string keyPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata(class System.Fabric.TransactionBase transactionBase, string keyPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.EnumerateMetadata(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.EnumerateMetadata : System.Fabric.TransactionBase * string -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;" Usage="keyValueStoreReplica.EnumerateMetadata (transactionBase, keyPrefix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="keyPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para><span data-ttu-id="70d80-230">Die Transaktion-Instanz.</span><span class="sxs-lookup"><span data-stu-id="70d80-230">The transaction instance.</span></span></para>
        </param>
        <param name="keyPrefix">
          <para><span data-ttu-id="70d80-231">Der Schlüssel oder Index, Präfix entsprechend (als Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="70d80-231">The key, or index, prefix to match (as a string).</span></span> <span data-ttu-id="70d80-232">Beschränkt auf 800 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="70d80-232">Limited to 800 characters in length.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-233">Gibt einen Enumerator, der durchläuft die <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> Werte im Schlüssel/Wert speichern, bei denen die Wert-Schlüssel für das angegebene Präfix übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="70d80-233">Returns an enumerator that iterates through the <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> values in the key/value store, where the value keys match the specified key prefix.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="70d80-234">Ein <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> Enumerator.</span><span class="sxs-lookup"><span data-stu-id="70d80-234">A <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> enumerator.</span></span></para>
        </returns>
        <remarks>
            <span data-ttu-id="70d80-235">Entspricht dem Aufruf von <see cref="M:System.Fabric.KeyValueStoreReplica.EnumerateMetadata(System.Fabric.TransactionBase,System.String,System.Boolean)" /> mit <b>StrictPrefix</b> festgelegt <languageKeyword>"true"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="70d80-235">Equivalent to calling <see cref="M:System.Fabric.KeyValueStoreReplica.EnumerateMetadata(System.Fabric.TransactionBase,System.String,System.Boolean)" /> with <b>strictPrefix</b> set to <languageKeyword>true</languageKeyword>.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnumerateMetadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata (System.Fabric.TransactionBase transactionBase, string keyPrefix, bool strictPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata(class System.Fabric.TransactionBase transactionBase, string keyPrefix, bool strictPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.EnumerateMetadata(System.Fabric.TransactionBase,System.String,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnumerateMetadata : System.Fabric.TransactionBase * string * bool -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;" Usage="keyValueStoreReplica.EnumerateMetadata (transactionBase, keyPrefix, strictPrefix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="keyPrefix" Type="System.String" />
        <Parameter Name="strictPrefix" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="transactionBase"><span data-ttu-id="70d80-236">Die Transaktion-Instanz.</span><span class="sxs-lookup"><span data-stu-id="70d80-236">The transaction instance.</span></span></param>
        <param name="keyPrefix"><span data-ttu-id="70d80-237">Der Schlüssel oder Index, Präfix entsprechend (als Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="70d80-237">The key, or index, prefix to match (as a string).</span></span> <span data-ttu-id="70d80-238">Beschränkt auf 800 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="70d80-238">Limited to 800 characters in length.</span></span></param>
        <param name="strictPrefix"><span data-ttu-id="70d80-239">Wenn "true" werden nur Schlüssel, die durch den Wert für das Präfix <b>KeyPrefix</b> werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="70d80-239">When true, only keys prefixed by the value specified for <b>keyPrefix</b> are returned.</span></span> <span data-ttu-id="70d80-240">Andernfalls Enumeration beginnt bei den ersten Schlüssel übereinstimmenden oder lexikografisch größer als <b>KeyPrefix</b> und wird fortgesetzt, bis keine weitere Schlüssel sind.</span><span class="sxs-lookup"><span data-stu-id="70d80-240">Otherwise, enumeration starts at the first key matching or lexicographically greater than <b>keyPrefix</b> and continues until there are no more keys.</span></span> <span data-ttu-id="70d80-241">Der Standardwert ist <b>True</b>.</span><span class="sxs-lookup"><span data-stu-id="70d80-241">The default is <b>true</b>.</span></span></param>
        <summary>
            <span data-ttu-id="70d80-242">Gibt einen Enumerator, der durchläuft die <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> Werte im Schlüssel/Wert-Speicher.</span><span class="sxs-lookup"><span data-stu-id="70d80-242">Returns an enumerator that iterates through the <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> values in the key/value store.</span></span>
            </summary>
        <returns><span data-ttu-id="70d80-243">Ein <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> Enumerator.</span><span class="sxs-lookup"><span data-stu-id="70d80-243">A <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> enumerator.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreItem Get (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.KeyValueStoreItem Get(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Get(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.Get : System.Fabric.TransactionBase * string -&gt; System.Fabric.KeyValueStoreItem" Usage="keyValueStoreReplica.Get (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreItem</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para><span data-ttu-id="70d80-244">Die Transaktion-Instanz.</span><span class="sxs-lookup"><span data-stu-id="70d80-244">The transaction instance.</span></span></para>
        </param>
        <param name="key">
          <para><span data-ttu-id="70d80-245">Der Schlüssel oder Index des Werts (als Zeichenfolge) abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="70d80-245">The key or index of the value to be retrieved (as a string).</span></span> <span data-ttu-id="70d80-246">Beschränkt auf 800 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="70d80-246">Limited to 800 characters in length.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-247">Ruft den gespeicherten Wert als ein <see cref="T:System.Fabric.KeyValueStoreItem" /> -Objekt, dem angegebenen Schlüssel zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="70d80-247">Gets the stored value, as a <see cref="T:System.Fabric.KeyValueStoreItem" /> object, associated with the specified key.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="70d80-248">Ein <see cref="T:System.Fabric.KeyValueStoreItem" /> Objekt, das den gespeicherten Wert darstellt.</span><span class="sxs-lookup"><span data-stu-id="70d80-248">A <see cref="T:System.Fabric.KeyValueStoreItem" /> object representing the stored value.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCurrentEpoch">
      <MemberSignature Language="C#" Value="public System.Fabric.Epoch GetCurrentEpoch ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance valuetype System.Fabric.Epoch GetCurrentEpoch() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.GetCurrentEpoch" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCurrentEpoch () As Epoch" />
      <MemberSignature Language="F#" Value="member this.GetCurrentEpoch : unit -&gt; System.Fabric.Epoch" Usage="keyValueStoreReplica.GetCurrentEpoch " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Epoch</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="70d80-249">Ruft die aktuelle Epoche für den Schlüssel/Wert-Speicher ab.</span><span class="sxs-lookup"><span data-stu-id="70d80-249">Gets the current epoch for the key/value store.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="70d80-250">Der aktuelle Epoche für den Schlüssel/Wert-Speicher.</span><span class="sxs-lookup"><span data-stu-id="70d80-250">The current epoch for the key/value store.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreItemMetadata GetMetadata (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.KeyValueStoreItemMetadata GetMetadata(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.GetMetadata(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.GetMetadata : System.Fabric.TransactionBase * string -&gt; System.Fabric.KeyValueStoreItemMetadata" Usage="keyValueStoreReplica.GetMetadata (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreItemMetadata</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para><span data-ttu-id="70d80-251">Die Transaktion-Instanz.</span><span class="sxs-lookup"><span data-stu-id="70d80-251">The transaction instance.</span></span></para>
        </param>
        <param name="key">
          <para><span data-ttu-id="70d80-252">Der Schlüssel oder Index des Werts (als Zeichenfolge) abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="70d80-252">The key or index of the value to be retrieved (as a string).</span></span> <span data-ttu-id="70d80-253">Beschränkt auf 800 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="70d80-253">Limited to 800 characters in length.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-254">Ruft die Metadaten als eine <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> -Objekt für den angegebenen Schlüssel zugeordnete Wert.</span><span class="sxs-lookup"><span data-stu-id="70d80-254">Gets the metadata, as a <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> object, for the value associated with the specified key.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="70d80-255">Ein <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> Objekt, das den angegebenen Wert zugeordnete Metadaten darstellt.</span><span class="sxs-lookup"><span data-stu-id="70d80-255">A <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> object representing the metadata associated with the specified value.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetValue">
      <MemberSignature Language="C#" Value="public byte[] GetValue (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance unsigned int8[] GetValue(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.GetValue(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.GetValue : System.Fabric.TransactionBase * string -&gt; byte[]" Usage="keyValueStoreReplica.GetValue (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para><span data-ttu-id="70d80-256">Die Transaktion-Instanz.</span><span class="sxs-lookup"><span data-stu-id="70d80-256">The transaction instance.</span></span></para>
        </param>
        <param name="key">
          <para><span data-ttu-id="70d80-257">Der Schlüssel oder Index des Werts (als Zeichenfolge) abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="70d80-257">The key or index of the value to be retrieved (as a string).</span></span> <span data-ttu-id="70d80-258">Beschränkt auf 800 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="70d80-258">Limited to 800 characters in length.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-259">Ruft den gespeicherten Wert als ein Byte-Array, das dem angegebenen Schlüssel zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="70d80-259">Gets the stored value as a byte array, associated with the specified key.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="70d80-260">Ein Bytearray, das den gespeicherten Wert darstellt.</span><span class="sxs-lookup"><span data-stu-id="70d80-260">A byte array representing the stored value.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreSequenceNumberCheck">
      <MemberSignature Language="C#" Value="public const long IgnoreSequenceNumberCheck = 0;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal int64 IgnoreSequenceNumberCheck = (0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.KeyValueStoreReplica.IgnoreSequenceNumberCheck" />
      <MemberSignature Language="VB.NET" Value="Public Const IgnoreSequenceNumberCheck As Long  = 0" />
      <MemberSignature Language="F#" Value="val mutable IgnoreSequenceNumberCheck : int64" Usage="System.Fabric.KeyValueStoreReplica.IgnoreSequenceNumberCheck" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="70d80-261">Gibt an, dass es sich bei Sequence Number Überprüfung nicht ausgeführt werden soll.</span><span class="sxs-lookup"><span data-stu-id="70d80-261">Indicates that sequence number checking should not occur.</span></span></para>
        </summary>
        <remarks>
          <para>
             <span data-ttu-id="70d80-262">Kann verwendet werden in einer Check Sequence-Number-Parameter akzeptieren-APIs um anzugeben, dass die Sequenz Anzahl Überprüfung nicht ausgeführt werden soll:<list type="bullet"><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Update(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Remove(System.Fabric.TransactionBase,System.String,System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryUpdate(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryRemove(System.Fabric.TransactionBase,System.String,System.Int64)" /></description></item></list></span><span class="sxs-lookup"><span data-stu-id="70d80-262">Can be used in APIs accepting a check sequence number parameter to indicate that sequence number checking should not occur: <list type="bullet"><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Update(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Remove(System.Fabric.TransactionBase,System.String,System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryUpdate(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryRemove(System.Fabric.TransactionBase,System.String,System.Int64)" /></description></item></list></span></span>
             
             <span data-ttu-id="70d80-263">Dies ist äquivalent zum Aufrufen des API-Überladungen, die nicht über eine Check Sequence-Number-Parameter verfügen:<list type="bullet"><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Update(System.Fabric.TransactionBase,System.String,System.Byte[])" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Remove(System.Fabric.TransactionBase,System.String)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryUpdate(System.Fabric.TransactionBase,System.String,System.Byte[])" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryRemove(System.Fabric.TransactionBase,System.String)" /></description></item></list></span><span class="sxs-lookup"><span data-stu-id="70d80-263">This is equivalent to calling API overloads that do not have a check sequence number parameter: <list type="bullet"><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Update(System.Fabric.TransactionBase,System.String,System.Byte[])" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Remove(System.Fabric.TransactionBase,System.String)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryUpdate(System.Fabric.TransactionBase,System.String,System.Byte[])" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryRemove(System.Fabric.TransactionBase,System.String)" /></description></item></list></span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Initialize">
      <MemberSignature Language="C#" Value="public void Initialize (System.Fabric.StatefulServiceInitializationParameters initializationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Initialize(class System.Fabric.StatefulServiceInitializationParameters initializationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Initialize(System.Fabric.StatefulServiceInitializationParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Initialize (initializationParameters As StatefulServiceInitializationParameters)" />
      <MemberSignature Language="F#" Value="abstract member Initialize : System.Fabric.StatefulServiceInitializationParameters -&gt; unit&#xA;override this.Initialize : System.Fabric.StatefulServiceInitializationParameters -&gt; unit" Usage="keyValueStoreReplica.Initialize initializationParameters" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStatefulServiceReplica.Initialize(System.Fabric.StatefulServiceInitializationParameters)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="initializationParameters" Type="System.Fabric.StatefulServiceInitializationParameters" />
      </Parameters>
      <Docs>
        <param name="initializationParameters">
          <para><span data-ttu-id="70d80-264">Die Initialisierungsinformationen für das Replikat.</span><span class="sxs-lookup"><span data-stu-id="70d80-264">The initialization information for the replica.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-265">Initialisiert das Replikat als Vorbereitung für das Öffnen.</span><span class="sxs-lookup"><span data-stu-id="70d80-265">Initializes the replica in preparation for opening.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="70d80-266">Diese Methode muss nicht explizit aufgerufen werden, wenn das Replikat für die Anwendung abgeleitet <see cref="T:System.Fabric.KeyValueStoreReplica" />, dies ist das empfohlene Muster.</span><span class="sxs-lookup"><span data-stu-id="70d80-266">This method does not need to be called explicitly if the application replica derives from <see cref="T:System.Fabric.KeyValueStoreReplica" />, which is the recommended pattern.</span></span> <span data-ttu-id="70d80-267">In diesem Fall sollte die anwendungsreplikaten überschreiben <see cref="M:System.Fabric.KeyValueStoreReplica.OnInitialize(System.Fabric.StatefulServiceInitializationParameters)" /> stattdessen.</span><span class="sxs-lookup"><span data-stu-id="70d80-267">In this case, the application replica should override <see cref="M:System.Fabric.KeyValueStoreReplica.OnInitialize(System.Fabric.StatefulServiceInitializationParameters)" /> instead.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyValueStoreReplicaSettings">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreReplicaSettings KeyValueStoreReplicaSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.KeyValueStoreReplicaSettings KeyValueStoreReplicaSettings" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplica.KeyValueStoreReplicaSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyValueStoreReplicaSettings As KeyValueStoreReplicaSettings" />
      <MemberSignature Language="F#" Value="member this.KeyValueStoreReplicaSettings : System.Fabric.KeyValueStoreReplicaSettings" Usage="System.Fabric.KeyValueStoreReplica.KeyValueStoreReplicaSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreReplicaSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="70d80-268">Ruft ab oder legt die optionseinstellungen für die <see cref="T:System.Fabric.KeyValueStoreReplica" />.</span><span class="sxs-lookup"><span data-stu-id="70d80-268">Gets or sets the option settings for the <see cref="T:System.Fabric.KeyValueStoreReplica" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="70d80-269">Die <see cref="T:System.Fabric.KeyValueStoreReplica" /> option Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="70d80-269">The <see cref="T:System.Fabric.KeyValueStoreReplica" /> option settings.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalStoreSettings">
      <MemberSignature Language="C#" Value="public System.Fabric.LocalStoreSettings LocalStoreSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.LocalStoreSettings LocalStoreSettings" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplica.LocalStoreSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LocalStoreSettings As LocalStoreSettings" />
      <MemberSignature Language="F#" Value="member this.LocalStoreSettings : System.Fabric.LocalStoreSettings" Usage="System.Fabric.KeyValueStoreReplica.LocalStoreSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.LocalStoreSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="70d80-270">Ruft ab oder legt die optionseinstellungen für den lokalen Schlüssel/Wert-Speicher.</span><span class="sxs-lookup"><span data-stu-id="70d80-270">Gets or sets the option settings for the local key/value store.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="70d80-271">Die Einstellungen für den lokalen Speicher-Option.</span><span class="sxs-lookup"><span data-stu-id="70d80-271">The local store option settings.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NotificationMode">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode NotificationMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.KeyValueStoreReplica/SecondaryNotificationMode NotificationMode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplica.NotificationMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NotificationMode As KeyValueStoreReplica.SecondaryNotificationMode" />
      <MemberSignature Language="F#" Value="member this.NotificationMode : System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode" Usage="System.Fabric.KeyValueStoreReplica.NotificationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreReplica+SecondaryNotificationMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="70d80-272">Ruft die sekundäre Benachrichtigungsmodus während der Erstellung dieses Replikats angegeben.</span><span class="sxs-lookup"><span data-stu-id="70d80-272">Gets the secondary notification mode specified during construction of this replica.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="70d80-273">Der aktuelle Benachrichtigungsmodus des sekundären</span><span class="sxs-lookup"><span data-stu-id="70d80-273">The current secondary notification mode</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected virtual void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="abstract member OnAbort : unit -&gt; unit&#xA;override this.OnAbort : unit -&gt; unit" Usage="keyValueStoreReplica.OnAbort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="70d80-274">Wird aufgerufen, um diese Instanz zu beenden.</span><span class="sxs-lookup"><span data-stu-id="70d80-274">Called to shut down this instance.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnChangeRoleAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;string&gt; OnChangeRoleAsync (System.Fabric.ReplicaRole newRole, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; OnChangeRoleAsync(valuetype System.Fabric.ReplicaRole newRole, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.OnChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="keyValueStoreReplica.OnChangeRoleAsync (newRole, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="newRole" Type="System.Fabric.ReplicaRole" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="newRole">
          <para><span data-ttu-id="70d80-275">Die Zielrolle.</span><span class="sxs-lookup"><span data-stu-id="70d80-275">The target role.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="70d80-276">Derzeit wird nicht verwendet.</span><span class="sxs-lookup"><span data-stu-id="70d80-276">Currently unused.</span></span> <span data-ttu-id="70d80-277">Für zukünftige Verwendung reserviert.</span><span class="sxs-lookup"><span data-stu-id="70d80-277">Reserved for future use.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-278">Gibt an, dass dieses Replikat Rollen geändert hat.</span><span class="sxs-lookup"><span data-stu-id="70d80-278">Indicates that this replica is changing roles.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="70d80-279">Eine Aufgabe, deren Ergebnis die auflösbaren Adresse für dieses Replikat ist.</span><span class="sxs-lookup"><span data-stu-id="70d80-279">A task whose result is the resolvable address of this replica.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="70d80-280">Das Replikat für die Anwendung sollte diese Methode außer Kraft setzen, ableiten von <see cref="T:System.Fabric.KeyValueStoreReplica" />, dies ist das empfohlene Muster.</span><span class="sxs-lookup"><span data-stu-id="70d80-280">The application replica should override this method if deriving from <see cref="T:System.Fabric.KeyValueStoreReplica" />, which is the recommended pattern.</span></span> <span data-ttu-id="70d80-281">Das Replikat für die Anwendung sollte Zurückgeben einer <see cref="T:System.Threading.Tasks.Task" /> , dessen Ergebnis ist die Adresse von diesem Replikat.</span><span class="sxs-lookup"><span data-stu-id="70d80-281">The application replica should return a <see cref="T:System.Threading.Tasks.Task" /> whose result is the address of this replica.</span></span> <span data-ttu-id="70d80-282">Diese Adresse Replikat wird als ist und kann abgerufen (unverändert) mit vom System gespeichert <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />.</span><span class="sxs-lookup"><span data-stu-id="70d80-282">This replica address is stored by the system as is and can be retrieved (unmodified) using <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />.</span></span> <span data-ttu-id="70d80-283">Die Anwendung muss darauf achten, den Rollenwechsel rechtzeitig abgeschlossen werden, da die Neukonfiguration der Replikatgruppe hinter den Abschluss aller ausstehenden Änderung Rolle Aufrufe blockiert werden.</span><span class="sxs-lookup"><span data-stu-id="70d80-283">The application must take care to complete the role change in a timely manner since reconfiguration of the replica set will be blocked behind the completion of all outstanding change role calls.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCloseAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnCloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnCloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnCloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnCloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnCloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.OnCloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para><span data-ttu-id="70d80-284">Ein <see cref="T:System.Threading.CancellationToken" /> Objekt, das der Vorgang überwacht wird, die verwendet werden kann, um die Aufgabe des Abbruchs zu benachrichtigen.</span><span class="sxs-lookup"><span data-stu-id="70d80-284">A <see cref="T:System.Threading.CancellationToken" /> object that the operation is monitoring, which can be used to notify the task of cancellation.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-285">Wird aufgerufen, wenn dieses Replikat Dienst beendet wird, und muss geschlossen.</span><span class="sxs-lookup"><span data-stu-id="70d80-285">Called when this service replica is being shut down and needs to close.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="70d80-286">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="70d80-286">The asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCopyComplete">
      <MemberSignature Language="C#" Value="protected virtual void OnCopyComplete (System.Fabric.KeyValueStoreEnumerator enumerator);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnCopyComplete(class System.Fabric.KeyValueStoreEnumerator enumerator) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnCopyComplete (enumerator As KeyValueStoreEnumerator)" />
      <MemberSignature Language="F#" Value="abstract member OnCopyComplete : System.Fabric.KeyValueStoreEnumerator -&gt; unit&#xA;override this.OnCopyComplete : System.Fabric.KeyValueStoreEnumerator -&gt; unit" Usage="keyValueStoreReplica.OnCopyComplete enumerator" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="enumerator" Type="System.Fabric.KeyValueStoreEnumerator" />
      </Parameters>
      <Docs>
        <param name="enumerator">
          <para><span data-ttu-id="70d80-287">Der Enumerator, der zum Lesen von Daten auf dem sekundären Replikat verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="70d80-287">The enumerator used to read data on the secondary.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-288">Vom System auf sekundären Replikaten aufgerufen, wenn sie erstellen, die vom primären Server abgeschlossen haben und bereit sind, starten Replikationsvorgängen anwenden.</span><span class="sxs-lookup"><span data-stu-id="70d80-288">Called by the system on secondary replicas when they have finished building from the primary and are ready to start applying replication operations.</span></span></para>
          <para><span data-ttu-id="70d80-289">Diese Methode wird nur auf sekundären Replikaten aufgerufen werden, wenn die <see cref="T:System.Fabric.KeyValueStoreReplica" /> Objekt erstellt wurde, durch einen gültigen <see cref="T:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode" /> Parameter.</span><span class="sxs-lookup"><span data-stu-id="70d80-289">This method will only be called on secondary replicas if the <see cref="T:System.Fabric.KeyValueStoreReplica" /> object was constructed with a valid <see cref="T:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode" /> parameter.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="70d80-290">Die <see cref="T:System.Fabric.KeyValueStoreEnumerator" /> Objekt kann verwendet werden, um Daten auf dem sekundären Replikat im Rahmen dieser Methode lesen, bevor alle Replikationsvorgängen angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="70d80-290">The <see cref="T:System.Fabric.KeyValueStoreEnumerator" /> object can be used to read data on the secondary within the context of this method before any replication operations are applied.</span></span> <span data-ttu-id="70d80-291">Die <see cref="T:System.Fabric.KeyValueStoreEnumerator" /> Objekt ist nicht mehr gültig, nachdem diese Methode zurückgegeben und kann nicht im Kontext dieser Methode verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="70d80-291">The <see cref="T:System.Fabric.KeyValueStoreEnumerator" /> object is no longer valid after this method returns and cannot be used outside the context of this method.</span></span> <span data-ttu-id="70d80-292">Die Anwendung muss diesen Rückruf rechtzeitig abgeschlossen, da Replikationsvorgängen sind auf dem sekundären Replikat in die Warteschlange gestellt und erste angewendet, bis dieser Methode werden nicht gestartet werden. achten.</span><span class="sxs-lookup"><span data-stu-id="70d80-292">The application must take care to complete this callback in a timely manner since replication operations are being queued on the secondary replica and will not start getting applied until this method returns.</span></span> <span data-ttu-id="70d80-293">Die <see cref="T:System.Fabric.KeyValueStoreEnumerator" /> -Objekt wird in einer einzelnen zugrunde liegenden lokale Transaktion gesichert und ist nicht threadsicher.</span><span class="sxs-lookup"><span data-stu-id="70d80-293">The <see cref="T:System.Fabric.KeyValueStoreEnumerator" /> object is backed by a single underlying local transaction and is not thread-safe.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDataLossAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;bool&gt; OnDataLossAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; OnDataLossAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnDataLossAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnDataLossAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.OnDataLossAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="keyValueStoreReplica.OnDataLossAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="70d80-294">Das Token verwendet, um nach einem Abbruch des Vorgangs überprüfen.</span><span class="sxs-lookup"><span data-stu-id="70d80-294">The token used to check for cancellation of the operation.</span></span></param>
        <summary>
            <span data-ttu-id="70d80-295">Signale, die das Replikat festgelegt, können Datenverlust aufgetreten sind.</span><span class="sxs-lookup"><span data-stu-id="70d80-295">Signals that the replica set may have experienced data loss.</span></span> <span data-ttu-id="70d80-296">Die Anwendung kann entweder überschreiben diese Methode, um das Ereignis asynchron zu verarbeiten, oder verwenden Sie die <see cref="E:System.Fabric.KeyValueStoreReplica.DataLossReported" /> Ereignis synchron zu verarbeiten.</span><span class="sxs-lookup"><span data-stu-id="70d80-296">The application can either override this method to process the event asynchronously or use the <see cref="E:System.Fabric.KeyValueStoreReplica.DataLossReported" /> event to process synchronously.</span></span> <span data-ttu-id="70d80-297">Beide stellen das gleiche Ereignis dar.</span><span class="sxs-lookup"><span data-stu-id="70d80-297">Both represent the same event.</span></span>
            </summary>
        <returns><span data-ttu-id="70d80-298">"True", um anzugeben, dass die Daten wurden geändert, während der Wiederherstellung, und legen Sie das Replikat muss neu synchronisiert werden.</span><span class="sxs-lookup"><span data-stu-id="70d80-298">True to indicate that data was modified during recovery and the replica set needs to be resynchronized.</span></span> <span data-ttu-id="70d80-299">Andernfalls "false", um anzugeben, dass die Daten nicht modifiziert wurden.</span><span class="sxs-lookup"><span data-stu-id="70d80-299">Otherwise, false to indicate that data has not been modified.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDatalossReported">
      <MemberSignature Language="C#" Value="protected virtual void OnDatalossReported (EventArgs args);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnDatalossReported(class System.EventArgs args) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnDatalossReported(System.EventArgs)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnDatalossReported (args As EventArgs)" />
      <MemberSignature Language="F#" Value="abstract member OnDatalossReported : EventArgs -&gt; unit&#xA;override this.OnDatalossReported : EventArgs -&gt; unit" Usage="keyValueStoreReplica.OnDatalossReported args" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="args" Type="System.EventArgs" />
      </Parameters>
      <Docs>
        <param name="args">
          <para><span data-ttu-id="70d80-300">Derzeit enthält keine Daten.</span><span class="sxs-lookup"><span data-stu-id="70d80-300">Currently contains no data.</span></span> <span data-ttu-id="70d80-301">Für zukünftige Verwendung reserviert.</span><span class="sxs-lookup"><span data-stu-id="70d80-301">Reserved for future use.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-302">Signale, die das Replikat festgelegt, können Datenverlust aufgetreten sind.</span><span class="sxs-lookup"><span data-stu-id="70d80-302">Signals that the replica set may have experienced data loss.</span></span> <span data-ttu-id="70d80-303">Die Anwendung kann diese Methode überschreiben, oder merken Sie sich die <see cref="E:System.Fabric.KeyValueStoreReplica.DataLossReported" /> Ereignis.</span><span class="sxs-lookup"><span data-stu-id="70d80-303">The application can either override this method or listen for the <see cref="E:System.Fabric.KeyValueStoreReplica.DataLossReported" /> Event.</span></span> <span data-ttu-id="70d80-304">Sowohl darstellen das gleiche Ereignis</span><span class="sxs-lookup"><span data-stu-id="70d80-304">Both represent the same event</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnInitialize">
      <MemberSignature Language="C#" Value="protected virtual void OnInitialize (System.Fabric.StatefulServiceInitializationParameters initializationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnInitialize(class System.Fabric.StatefulServiceInitializationParameters initializationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnInitialize(System.Fabric.StatefulServiceInitializationParameters)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnInitialize (initializationParameters As StatefulServiceInitializationParameters)" />
      <MemberSignature Language="F#" Value="abstract member OnInitialize : System.Fabric.StatefulServiceInitializationParameters -&gt; unit&#xA;override this.OnInitialize : System.Fabric.StatefulServiceInitializationParameters -&gt; unit" Usage="keyValueStoreReplica.OnInitialize initializationParameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="initializationParameters" Type="System.Fabric.StatefulServiceInitializationParameters" />
      </Parameters>
      <Docs>
        <param name="initializationParameters">
          <para><span data-ttu-id="70d80-305">Der Initialisierungsparameter für das Replikat Dienst dargestellt, als ein <see cref="T:System.Fabric.StatefulServiceInitializationParameters" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="70d80-305">The initialization parameters for the service replica, represented as a <see cref="T:System.Fabric.StatefulServiceInitializationParameters" /> object.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-306">Initialisiert eine neu erstellte dienstreplikats an.</span><span class="sxs-lookup"><span data-stu-id="70d80-306">Initializes a newly created service replica.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnOpenAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnOpenAsync (System.Fabric.ReplicaOpenMode openMode, System.Fabric.IStatefulServicePartition partition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnOpenAsync(valuetype System.Fabric.ReplicaOpenMode openMode, class System.Fabric.IStatefulServicePartition partition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnOpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnOpenAsync : System.Fabric.ReplicaOpenMode * System.Fabric.IStatefulServicePartition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnOpenAsync : System.Fabric.ReplicaOpenMode * System.Fabric.IStatefulServicePartition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.OnOpenAsync (openMode, partition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="openMode" Type="System.Fabric.ReplicaOpenMode" />
        <Parameter Name="partition" Type="System.Fabric.IStatefulServicePartition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="openMode">
          <para><span data-ttu-id="70d80-307">Ein <see cref="T:System.Fabric.ReplicaOpenMode" /> Objekt, das für dieses Replikat angibt, ob es sich um neuen oder wiederhergestellten handelt.</span><span class="sxs-lookup"><span data-stu-id="70d80-307">A <see cref="T:System.Fabric.ReplicaOpenMode" /> object specifying for this replica whether it is new or recovered.</span></span></para>
        </param>
        <param name="partition">
          <para><span data-ttu-id="70d80-308">Ein <see cref="T:System.Fabric.IStatefulServicePartition" /> Objekt, das die Partitionsinformationen zustandsbehaftete Dienst für dieses Replikat darstellt.</span><span class="sxs-lookup"><span data-stu-id="70d80-308">A <see cref="T:System.Fabric.IStatefulServicePartition" /> object representing the stateful service partition information for this replica.</span></span> </para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="70d80-309">Ein <see cref="T:System.Threading.CancellationToken" /> Objekt, das der Vorgang überwacht wird, die verwendet werden kann, um die Aufgabe des Abbruchs zu benachrichtigen.</span><span class="sxs-lookup"><span data-stu-id="70d80-309">A <see cref="T:System.Threading.CancellationToken" /> object that the operation is monitoring, which can be used to notify the task of cancellation.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-310">Wird aufgerufen, auf einem Replikat initialisierten Dienst, um ihn zu öffnen, sodass zusätzliche Aktionen ausgeführt werden können.</span><span class="sxs-lookup"><span data-stu-id="70d80-310">Called on an initialized service replica to open it so that additional actions can be taken.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="70d80-311">Ein <see cref="T:System.Threading.Tasks.Task" /> Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="70d80-311">A <see cref="T:System.Threading.Tasks.Task" /> object representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnReplicationOperation">
      <MemberSignature Language="C#" Value="protected virtual void OnReplicationOperation (System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreNotification&gt; enumerator);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnReplicationOperation(class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreNotification&gt; enumerator) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnReplicationOperation (enumerator As IEnumerator(Of KeyValueStoreNotification))" />
      <MemberSignature Language="F#" Value="abstract member OnReplicationOperation : System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreNotification&gt; -&gt; unit&#xA;override this.OnReplicationOperation : System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreNotification&gt; -&gt; unit" Usage="keyValueStoreReplica.OnReplicationOperation enumerator" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="enumerator" Type="System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreNotification&gt;" />
      </Parameters>
      <Docs>
        <param name="enumerator">
          <para><span data-ttu-id="70d80-312">Der Enumerator, der zum Lesen der Daten in diesen Replikationsvorgang verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="70d80-312">The enumerator used to read the data in this replication operation.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-313">Vom System auf sekundären Replikaten für eingehende Replikationsvorgängen aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="70d80-313">Called by the system on secondary replicas for incoming replication operations.</span></span> <span data-ttu-id="70d80-314">Jede <see cref="T:System.Fabric.KeyValueStoreNotification" /> Objekt enthält alle Daten für einen einzelnen atomic Replikationsvorgang.</span><span class="sxs-lookup"><span data-stu-id="70d80-314">Each <see cref="T:System.Fabric.KeyValueStoreNotification" /> object contains all the data for a single atomic replication operation.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="70d80-315">Diese Methode wird nur auf sekundären Replikaten aufgerufen werden, wenn die <see cref="T:System.Fabric.KeyValueStoreReplica" /> Objekt erstellt wurde, durch einen gültigen <see cref="T:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode" />.</span><span class="sxs-lookup"><span data-stu-id="70d80-315">This method will only be called on secondary replicas if the <see cref="T:System.Fabric.KeyValueStoreReplica" /> object was constructed with a valid <see cref="T:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode" />.</span></span></para>
          <para><span data-ttu-id="70d80-316">Wenn die <see cref="F:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode.BlockSecondaryAck" /> Modus wurde angegeben, wird der eingehende Replikationsvorgang ist nicht lokal auf dem sekundären Replikat angewendet und mit dem primären Replikat bestätigt wurde, bis die Methode einen Wert zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="70d80-316">If the <see cref="F:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode.BlockSecondaryAck" /> mode was specified, then the incoming replication operation is not applied locally on the secondary replica and acknowledged to the primary until the method returns.</span></span> <span data-ttu-id="70d80-317">Dies bedeutet, dass die Anwendung dafür sorgen, dass muss zum Blockieren der replikationsdatenstrom Vermeiden von dieser Methode rechtzeitig zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="70d80-317">This implies that the application must take care to return from this method in a timely manner to avoiding blocking the replication stream.</span></span> <span data-ttu-id="70d80-318">Da die Bestätigung nicht mit dem primären Replikat gesendet werden, bis diese Methode einen Wert zurückgibt, es kann nicht als gegeben angenommen, dass der beobachteten Replikationsvorgang bereits wurde (oder ist garantiert in der Zukunft) durch ein Quorum der Replikate in der Replikatgruppe angewendet.</span><span class="sxs-lookup"><span data-stu-id="70d80-318">Since the acknowledgment is not sent to the primary until this method returns, it cannot be assumed that the observed replication operation has already been (or is guaranteed to be in the future) applied by a quorum of replicas in the replica set.</span></span></para>
          <para><span data-ttu-id="70d80-319">Wenn die <see cref="F:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode.NonBlockingQuorumAcked" /> -Modus festgelegt wurde, dann wird sichergestellt, dass der beobachteten Replikationsvorgang bereits durch ein Quorum der Replikate in der Replikatgruppe angewendet wurden.</span><span class="sxs-lookup"><span data-stu-id="70d80-319">If the <see cref="F:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode.NonBlockingQuorumAcked" /> mode was specified, then the observed replication operation is guaranteed to have already been applied by a quorum of replicas in the replica set.</span></span> <span data-ttu-id="70d80-320">Darüber hinaus der beobachteten Replikationsvorgang möglicherweise bereits lokal durch diese sekundäre Datenbank angewendet und bestätigt wurden mit dem primären Replikat zu dem Zeitpunkt, den die Methode, die vom System aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="70d80-320">Furthermore, the observed replication operation may have already been applied locally by this secondary and acknowledged to the primary at the time the method is invoked by the system.</span></span> <span data-ttu-id="70d80-321">Der Rückruf für die Methode wird nicht verhindert, die replikationsdatenstrom in diesem Modus, aber die Replikation Benachrichtigung vorgangsdatenstrom weiterhin blockiert.</span><span class="sxs-lookup"><span data-stu-id="70d80-321">The method callback will not block the replication stream in this mode, but it will still block the replication operation notification stream.</span></span> <span data-ttu-id="70d80-322">D. h. ist es rein eine ausstehende OnReplicationOperation Methode Rückruf zu einem beliebigen Zeitpunkt.</span><span class="sxs-lookup"><span data-stu-id="70d80-322">That is, there will only be one outstanding OnReplicationOperation method callback at any given time.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRestoreCompletedAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnRestoreCompletedAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnRestoreCompletedAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnRestoreCompletedAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnRestoreCompletedAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnRestoreCompletedAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.OnRestoreCompletedAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="70d80-323">Das Token verwendet, um nach einem Abbruch des Vorgangs überprüfen.</span><span class="sxs-lookup"><span data-stu-id="70d80-323">The token used to check for cancellation of the operation.</span></span></param>
        <summary>
            <span data-ttu-id="70d80-324">Signalisiert, dass das Replikat Zustand erfolgreich vom System wiederhergestellt wurde.</span><span class="sxs-lookup"><span data-stu-id="70d80-324">Signals that the replica's state was successfully restored by the system.</span></span>
            <span data-ttu-id="70d80-325">Dies wird nur aufgerufen, wenn System intern eine Wiederherstellung über den Service Wiederherstellung ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="70d80-325">This is invoked only when system internally triggers a restore via the Backup Restore service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt; OpenAsync (System.Fabric.ReplicaOpenMode openMode, System.Fabric.IStatefulServicePartition partition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.IReplicator&gt; OpenAsync(valuetype System.Fabric.ReplicaOpenMode openMode, class System.Fabric.IStatefulServicePartition partition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : System.Fabric.ReplicaOpenMode * System.Fabric.IStatefulServicePartition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt;&#xA;override this.OpenAsync : System.Fabric.ReplicaOpenMode * System.Fabric.IStatefulServicePartition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt;" Usage="keyValueStoreReplica.OpenAsync (openMode, partition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStatefulServiceReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.KeyValueStoreReplica/&lt;OpenAsync&gt;d__56))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="openMode" Type="System.Fabric.ReplicaOpenMode" />
        <Parameter Name="partition" Type="System.Fabric.IStatefulServicePartition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="openMode">
          <para><span data-ttu-id="70d80-326">Gibt den Kontext, unter dem dieses Replikat geöffnet wird.</span><span class="sxs-lookup"><span data-stu-id="70d80-326">Specifies the context under which this replica is being opened.</span></span></para>
        </param>
        <param name="partition">
          <para><span data-ttu-id="70d80-327">Enthält Informationen zur Beschreibung der Replikatgruppe zu dem das Replikat gehört.</span><span class="sxs-lookup"><span data-stu-id="70d80-327">Contains information describing the replica set to which this replica belongs.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="70d80-328">Derzeit wird nicht verwendet.</span><span class="sxs-lookup"><span data-stu-id="70d80-328">Currently unused.</span></span> <span data-ttu-id="70d80-329">Für zukünftige Verwendung reserviert.</span><span class="sxs-lookup"><span data-stu-id="70d80-329">Reserved for future use.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-330">Öffnet das Replikat als auch ihre Replikator als Vorbereitung für die in einer Replikatgruppe online geschaltet.</span><span class="sxs-lookup"><span data-stu-id="70d80-330">Opens the replica and its replicator in preparation for coming online in a replica set.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="70d80-331">Eine Aufgabe an, dass der Abschluss der geöffneten <see cref="T:System.Threading.Tasks.Task`1" />.</span><span class="sxs-lookup"><span data-stu-id="70d80-331">A Task to indicate completion of the open <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="70d80-332">Diese Methode muss nicht explizit aufgerufen werden, wenn das Replikat für die Anwendung abgeleitet <see cref="T:System.Fabric.KeyValueStoreReplica" />, dies ist das empfohlene Muster.</span><span class="sxs-lookup"><span data-stu-id="70d80-332">This method does not need to be called explicitly if the application replica derives from <see cref="T:System.Fabric.KeyValueStoreReplica" />, which is the recommended pattern.</span></span> <span data-ttu-id="70d80-333">In diesem Fall sollte die anwendungsreplikaten OnOpenAsync stattdessen außer Kraft setzen.</span><span class="sxs-lookup"><span data-stu-id="70d80-333">In this case, the application replica should override OnOpenAsync instead.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public void Remove (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Remove(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Remove(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.Remove : System.Fabric.TransactionBase * string -&gt; unit" Usage="keyValueStoreReplica.Remove (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para><span data-ttu-id="70d80-334">Die Transaktion-Instanz.</span><span class="sxs-lookup"><span data-stu-id="70d80-334">The transaction instance.</span></span></para>
        </param>
        <param name="key">
          <para><span data-ttu-id="70d80-335">Der Schlüssel oder Index, der den Wert (als Zeichenfolge) entfernt werden soll.</span><span class="sxs-lookup"><span data-stu-id="70d80-335">The key, or index, of the value to be removed (as a string).</span></span> <span data-ttu-id="70d80-336">Beschränkt auf 800 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="70d80-336">Limited to 800 characters in length.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-337">Entfernt den Wert, der durch den angegebenen Schlüssel indiziert.</span><span class="sxs-lookup"><span data-stu-id="70d80-337">Removes the value indexed by the specified key.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public void Remove (System.Fabric.TransactionBase transactionBase, string key, long checkSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Remove(class System.Fabric.TransactionBase transactionBase, string key, int64 checkSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Remove(System.Fabric.TransactionBase,System.String,System.Int64)" />
      <MemberSignature Language="F#" Value="member this.Remove : System.Fabric.TransactionBase * string * int64 -&gt; unit" Usage="keyValueStoreReplica.Remove (transactionBase, key, checkSequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="checkSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para><span data-ttu-id="70d80-338">Die Transaktion-Instanz.</span><span class="sxs-lookup"><span data-stu-id="70d80-338">The transaction instance.</span></span></para>
        </param>
        <param name="key">
          <para><span data-ttu-id="70d80-339">Der Schlüssel oder Index, der den Wert (als Zeichenfolge) entfernt werden soll.</span><span class="sxs-lookup"><span data-stu-id="70d80-339">The key, or index, of the value to be removed (as a string).</span></span> <span data-ttu-id="70d80-340">Beschränkt auf 800 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="70d80-340">Limited to 800 characters in length.</span></span></para>
        </param>
        <param name="checkSequenceNumber">
          <para><span data-ttu-id="70d80-341">Die erwartete Sequenznummer des Schlüssels, der entfernt werden soll.</span><span class="sxs-lookup"><span data-stu-id="70d80-341">The expected sequence number of the key to be removed.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-342">Entfernt den Wert, der durch den angegebenen Schlüssel indiziert.</span><span class="sxs-lookup"><span data-stu-id="70d80-342">Removes the value indexed by the specified key.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicatorSettings">
      <MemberSignature Language="C#" Value="public System.Fabric.ReplicatorSettings ReplicatorSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ReplicatorSettings ReplicatorSettings" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplica.ReplicatorSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicatorSettings As ReplicatorSettings" />
      <MemberSignature Language="F#" Value="member this.ReplicatorSettings : System.Fabric.ReplicatorSettings" Usage="System.Fabric.KeyValueStoreReplica.ReplicatorSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicatorSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="70d80-343">Ruft ab oder legt die optionseinstellungen für Schlüssel/Wert-Speicher Replikator.</span><span class="sxs-lookup"><span data-stu-id="70d80-343">Gets or sets the option settings for the key/value store replicator.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="70d80-344">Die Einstellungen der Store Replikator-Option.</span><span class="sxs-lookup"><span data-stu-id="70d80-344">The store replicator option settings.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Restore">
      <MemberSignature Language="C#" Value="public void Restore (string backupDirectory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Restore(string backupDirectory) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Restore(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Restore (backupDirectory As String)" />
      <MemberSignature Language="F#" Value="member this.Restore : string -&gt; unit" Usage="keyValueStoreReplica.Restore backupDirectory" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use RestoreAsync instead")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDirectory" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupDirectory">
          <para><span data-ttu-id="70d80-345">Der vollständige Pfad zu einem Verzeichnis mit einer Sicherung.</span><span class="sxs-lookup"><span data-stu-id="70d80-345">The full path to a directory containing a backup.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-346">Dieses Replikat lokalen Speicher-Datenbank aus einer Sicherung, die zuvor durch den Aufruf erstellt wurde wiederhergestellt <see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" />.</span><span class="sxs-lookup"><span data-stu-id="70d80-346">Restores this replica's local store database from a backup that was previously created by calling <see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" />.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="70d80-347">Dies ist nur ein lokales Replikat wiederherstellen und die Replikatgruppe werden nicht automatisch wiederhergestellt.</span><span class="sxs-lookup"><span data-stu-id="70d80-347">This is only a local replica restore and the replica set is not automatically restored.</span></span> <span data-ttu-id="70d80-348">Die gesamte Replikatgruppe muss zusätzliche Schritte ausführen, die dazu führen, dass einen natürlichen Build der anderen Replikate über die Neukonfiguration wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="70d80-348">The entire replica set must be restored by taking additional steps to cause a natural build of other replicas via reconfiguration.</span></span> <span data-ttu-id="70d80-349">Die empfohlene Vorgehensweise ist in einem leeren Dienst mit nur einem einzelnen Replikat und danach mit einem Aufruf von Größe der zielreplikatgruppe Erhöhung wiederherstellen <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" /> bei Bedarf.</span><span class="sxs-lookup"><span data-stu-id="70d80-349">The recommended approach is to restore to an empty service with only a single replica and increase the target replica set size afterwards with a call to <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" /> if needed.</span></span></para>
          <para><span data-ttu-id="70d80-350">Wenn die Wiederherstellung erfolgreich ist, wird das Replikat sich selbst neu starten und beginnen mit den wiederhergestellten lokalen Daten nach wieder online geschaltet, davon ausgehend, dass die Empfehlung, die in einer Replikatgruppe, enthält nur ein einzelnes Replikat wiederherstellen ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="70d80-350">If the restore is successful, then the replica will restart itself and start using the restored local data after coming back online given that the recommendation to restore to a replica set containing only a single replica was followed.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (string backupDirectory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RestoreAsync(string backupDirectory) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.RestoreAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RestoreAsync (backupDirectory As String) As Task" />
      <MemberSignature Language="F#" Value="member this.RestoreAsync : string -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.RestoreAsync backupDirectory" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDirectory" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupDirectory">
            <span data-ttu-id="70d80-351">Das Verzeichnis, in dem das Replikat aus wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="70d80-351">The directory where the replica is to be restored from.</span></span>
            <span data-ttu-id="70d80-352">Dieser Parameter kann nicht null, leer oder enthält nur Leerzeichen.</span><span class="sxs-lookup"><span data-stu-id="70d80-352">This parameter cannot be null, empty or contain just whitespace.</span></span> <span data-ttu-id="70d80-353">UNC-Pfade können auch angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="70d80-353">UNC paths may also be provided.</span></span>
            </param>
        <summary>
          <para><span data-ttu-id="70d80-354">Dieses Replikat lokalen Speicher-Datenbank aus einer Sicherung, die zuvor durch den Aufruf erstellt wurde wiederhergestellt <see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" />.</span><span class="sxs-lookup"><span data-stu-id="70d80-354">Restores this replica's local store database from a backup that was previously created by calling <see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" />.</span></span></para>
        </summary>
        <returns><span data-ttu-id="70d80-355">Eine Aufgabe, die den asynchronen Restore-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="70d80-355">A task that represents the asynchronous restore operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="70d80-356">Es wird empfohlen, alle Schreibvorgänge in den Schlüssel/Wert-Speicher nicht ausgeführt werden, während die Wiederherstellung ausgeführt wird, da die aktualisierten Daten verloren gehen würden aus den Dateien in der Speicher wiederhergestellt wird <b>BackupDirectory</b>.</span><span class="sxs-lookup"><span data-stu-id="70d80-356">It is recommended to not perform any write operations to the key/value store while restore is underway since the updated data would be lost when the store is restored from the files in <b>backupDirectory</b>.</span></span> </para>
          <para><span data-ttu-id="70d80-357">Dies ist nur ein lokales Replikat wiederherstellen und die Replikatgruppe werden nicht automatisch wiederhergestellt.</span><span class="sxs-lookup"><span data-stu-id="70d80-357">This is only a local replica restore and the replica set is not automatically restored.</span></span> <span data-ttu-id="70d80-358">Die gesamte Replikatgruppe muss zusätzliche Schritte ausführen, die dazu führen, dass einen natürlichen Build der anderen Replikate über die Neukonfiguration wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="70d80-358">The entire replica set must be restored by taking additional steps to cause a natural build of other replicas via reconfiguration.</span></span> <span data-ttu-id="70d80-359">Die empfohlene Vorgehensweise ist in einem leeren Dienst mit nur einem einzelnen Replikat und danach mit einem Aufruf von Größe der zielreplikatgruppe Erhöhung wiederherstellen <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" /> bei Bedarf.</span><span class="sxs-lookup"><span data-stu-id="70d80-359">The recommended approach is to restore to an empty service with only a single replica and increase the target replica set size afterwards with a call to <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" /> if needed.</span></span></para>
          <para><span data-ttu-id="70d80-360">Wenn die Wiederherstellung erfolgreich ist, wird das Replikat sich selbst neu starten und beginnen mit den wiederhergestellten lokalen Daten nach wieder online geschaltet, davon ausgehend, dass die Empfehlung, die in einer Replikatgruppe, enthält nur ein einzelnes Replikat wiederherstellen ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="70d80-360">If the restore is successful, then the replica will restart itself and start using the restored local data after coming back online given that the recommendation to restore to a replica set containing only a single replica was followed.</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="70d80-361"><b>BackupDirectory</b> ist <b>null</b>.</span><span class="sxs-lookup"><span data-stu-id="70d80-361"><b>backupDirectory</b> is <b>null</b>.</span></span>
            </exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="70d80-362"><b>BackupDirectory</b> ist leer oder enthält nur Leerzeichen.</span><span class="sxs-lookup"><span data-stu-id="70d80-362"><b>backupDirectory</b> is empty or contains just whitespaces.</span></span>
            </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <span data-ttu-id="70d80-363"><b>BackupDirectory</b> ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="70d80-363"><b>backupDirectory</b> does not exist.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (string backupDirectory, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RestoreAsync(string backupDirectory, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.RestoreAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestoreAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.RestoreAsync (backupDirectory, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDirectory" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="backupDirectory">
            <span data-ttu-id="70d80-364">Das Verzeichnis, in dem das Replikat aus wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="70d80-364">The directory where the replica is to be restored from.</span></span>
            <span data-ttu-id="70d80-365">Dieser Parameter kann nicht null, leer oder enthält nur Leerzeichen.</span><span class="sxs-lookup"><span data-stu-id="70d80-365">This parameter cannot be null, empty or contain just whitespace.</span></span> <span data-ttu-id="70d80-366">UNC-Pfade können auch angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="70d80-366">UNC paths may also be provided.</span></span>
            </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="70d80-367">das Abbruchtoken, das</span><span class="sxs-lookup"><span data-stu-id="70d80-367">The cancellation token</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-368">Dieses Replikat lokalen Speicher-Datenbank aus einer Sicherung, die zuvor durch den Aufruf erstellt wurde wiederhergestellt <see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" />.</span><span class="sxs-lookup"><span data-stu-id="70d80-368">Restores this replica's local store database from a backup that was previously created by calling <see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" />.</span></span></para>
        </summary>
        <returns><span data-ttu-id="70d80-369">Eine Aufgabe, die den asynchronen Restore-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="70d80-369">A task that represents the asynchronous restore operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="70d80-370">Es wird empfohlen, alle Schreibvorgänge in den Schlüssel/Wert-Speicher nicht ausgeführt werden, während die Wiederherstellung ausgeführt wird, da die aktualisierten Daten verloren gehen würden aus den Dateien in der Speicher wiederhergestellt wird <b>BackupDirectory</b>.</span><span class="sxs-lookup"><span data-stu-id="70d80-370">It is recommended to not perform any write operations to the key/value store while restore is underway since the updated data would be lost when the store is restored from the files in <b>backupDirectory</b>.</span></span> </para>
          <para><span data-ttu-id="70d80-371">Dies ist nur ein lokales Replikat wiederherstellen und die Replikatgruppe werden nicht automatisch wiederhergestellt.</span><span class="sxs-lookup"><span data-stu-id="70d80-371">This is only a local replica restore and the replica set is not automatically restored.</span></span> <span data-ttu-id="70d80-372">Die gesamte Replikatgruppe muss zusätzliche Schritte ausführen, die dazu führen, dass einen natürlichen Build der anderen Replikate über die Neukonfiguration wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="70d80-372">The entire replica set must be restored by taking additional steps to cause a natural build of other replicas via reconfiguration.</span></span> <span data-ttu-id="70d80-373">Die empfohlene Vorgehensweise ist in einem leeren Dienst mit nur einem einzelnen Replikat und danach mit einem Aufruf von Größe der zielreplikatgruppe Erhöhung wiederherstellen <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" /> bei Bedarf.</span><span class="sxs-lookup"><span data-stu-id="70d80-373">The recommended approach is to restore to an empty service with only a single replica and increase the target replica set size afterwards with a call to <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" /> if needed.</span></span></para>
          <para><span data-ttu-id="70d80-374">Wenn die Wiederherstellung erfolgreich ist, wird das Replikat sich selbst neu starten und beginnen mit den wiederhergestellten lokalen Daten nach wieder online geschaltet, davon ausgehend, dass die Empfehlung, die in einer Replikatgruppe, enthält nur ein einzelnes Replikat wiederherstellen ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="70d80-374">If the restore is successful, then the replica will restart itself and start using the restored local data after coming back online given that the recommendation to restore to a replica set containing only a single replica was followed.</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="70d80-375"><b>BackupDirectory</b> ist <b>null</b>.</span><span class="sxs-lookup"><span data-stu-id="70d80-375"><b>backupDirectory</b> is <b>null</b>.</span></span>
            </exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="70d80-376"><b>BackupDirectory</b> ist leer oder enthält nur Leerzeichen.</span><span class="sxs-lookup"><span data-stu-id="70d80-376"><b>backupDirectory</b> is empty or contains just whitespaces.</span></span>
            </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <span data-ttu-id="70d80-377"><b>BackupDirectory</b> ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="70d80-377"><b>backupDirectory</b> does not exist.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (string backupDirectory, System.Fabric.RestoreSettings settings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RestoreAsync(string backupDirectory, class System.Fabric.RestoreSettings settings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.RestoreAsync(System.String,System.Fabric.RestoreSettings,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestoreAsync : string * System.Fabric.RestoreSettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.RestoreAsync (backupDirectory, settings, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDirectory" Type="System.String" />
        <Parameter Name="settings" Type="System.Fabric.RestoreSettings" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="backupDirectory">
            <span data-ttu-id="70d80-378">Das Verzeichnis, in dem das Replikat aus wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="70d80-378">The directory where the replica is to be restored from.</span></span>
            <span data-ttu-id="70d80-379">Dieser Parameter kann nicht null, leer oder enthält nur Leerzeichen.</span><span class="sxs-lookup"><span data-stu-id="70d80-379">This parameter cannot be null, empty or contain just whitespace.</span></span> <span data-ttu-id="70d80-380">UNC-Pfade können auch angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="70d80-380">UNC paths may also be provided.</span></span>
            </param>
        <param name="settings">
            <span data-ttu-id="70d80-381">Verhalten wiederherstellen, die Einstellungen zu ändern.</span><span class="sxs-lookup"><span data-stu-id="70d80-381">Settings to modify restore behavior.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="70d80-382">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="70d80-382">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="70d80-383">Asynchron wiederhergestellt, das Schlüssel/Wert-Speicher-Replikat.</span><span class="sxs-lookup"><span data-stu-id="70d80-383">Asynchronously restores the key/value store replica.</span></span>
            </summary>
        <returns><span data-ttu-id="70d80-384">Eine Aufgabe, die den asynchronen Restore-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="70d80-384">A task that represents the asynchronous restore operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="70d80-385">Es wird empfohlen, alle Schreibvorgänge in den Schlüssel/Wert-Speicher nicht ausgeführt werden, während die Wiederherstellung ausgeführt wird, da die aktualisierten Daten verloren gehen würden aus den Dateien in der Speicher wiederhergestellt wird <b>BackupDirectory</b>.</span><span class="sxs-lookup"><span data-stu-id="70d80-385">It is recommended to not perform any write operations to the key/value store while restore is underway since the updated data would be lost when the store is restored from the files in <b>backupDirectory</b>.</span></span> </para>
          <para><span data-ttu-id="70d80-386">Dies ist nur ein lokales Replikat wiederherstellen und die Replikatgruppe werden nicht automatisch wiederhergestellt.</span><span class="sxs-lookup"><span data-stu-id="70d80-386">This is only a local replica restore and the replica set is not automatically restored.</span></span> <span data-ttu-id="70d80-387">Die gesamte Replikatgruppe muss zusätzliche Schritte ausführen, die dazu führen, dass einen natürlichen Build der anderen Replikate über die Neukonfiguration wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="70d80-387">The entire replica set must be restored by taking additional steps to cause a natural build of other replicas via reconfiguration.</span></span> <span data-ttu-id="70d80-388">Die empfohlene Vorgehensweise ist in einem leeren Dienst mit nur einem einzelnen Replikat und danach mit einem Aufruf von Größe der zielreplikatgruppe Erhöhung wiederherstellen <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" /> bei Bedarf.</span><span class="sxs-lookup"><span data-stu-id="70d80-388">The recommended approach is to restore to an empty service with only a single replica and increase the target replica set size afterwards with a call to <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" /> if needed.</span></span></para>
          <para><span data-ttu-id="70d80-389">Wenn die Wiederherstellung erfolgreich ist, wird das Replikat sich selbst neu starten und beginnen mit den wiederhergestellten lokalen Daten nach wieder online geschaltet, davon ausgehend, dass die Empfehlung, die in einer Replikatgruppe, enthält nur ein einzelnes Replikat wiederherstellen ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="70d80-389">If the restore is successful, then the replica will restart itself and start using the restored local data after coming back online given that the recommendation to restore to a replica set containing only a single replica was followed.</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="70d80-390"><b>BackupDirectory</b> ist <b>null</b>.</span><span class="sxs-lookup"><span data-stu-id="70d80-390"><b>backupDirectory</b> is <b>null</b>.</span></span>
            </exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="70d80-391"><b>BackupDirectory</b> ist leer oder enthält nur Leerzeichen.</span><span class="sxs-lookup"><span data-stu-id="70d80-391"><b>backupDirectory</b> is empty or contains just whitespaces.</span></span>
            </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <span data-ttu-id="70d80-392"><b>BackupDirectory</b> ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="70d80-392"><b>backupDirectory</b> does not exist.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="StoreName">
      <MemberSignature Language="C#" Value="public string StoreName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StoreName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplica.StoreName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoreName As String" />
      <MemberSignature Language="F#" Value="member this.StoreName : string" Usage="System.Fabric.KeyValueStoreReplica.StoreName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="70d80-393">Ruft ab oder legt den Namen des Schlüssel/Wert-Speichers.</span><span class="sxs-lookup"><span data-stu-id="70d80-393">Gets or sets the name of the key/value store.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="70d80-394">Der Name des Schlüssel/Wert-Speichers.</span><span class="sxs-lookup"><span data-stu-id="70d80-394">The name of the key/value store.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="70d80-395">Der Speichername muss gültige Dateinamenzeichen entsprechen.</span><span class="sxs-lookup"><span data-stu-id="70d80-395">The store name should conform to valid filename characters.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TryAdd">
      <MemberSignature Language="C#" Value="public bool TryAdd (System.Fabric.TransactionBase transactionBase, string key, byte[] value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryAdd(class System.Fabric.TransactionBase transactionBase, string key, unsigned int8[] value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryAdd(System.Fabric.TransactionBase,System.String,System.Byte[])" />
      <MemberSignature Language="F#" Value="member this.TryAdd : System.Fabric.TransactionBase * string * byte[] -&gt; bool" Usage="keyValueStoreReplica.TryAdd (transactionBase, key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="transactionBase"><span data-ttu-id="70d80-396">Die Transaktion-Instanz.</span><span class="sxs-lookup"><span data-stu-id="70d80-396">The transaction instance.</span></span></param>
        <param name="key"><span data-ttu-id="70d80-397">Der Schlüssel oder Index, der den Wert (als eine Zeichenfolge) hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="70d80-397">The key, or index, of the value to be added (as a string).</span></span> <span data-ttu-id="70d80-398">Beschränkt auf 800 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="70d80-398">Limited to 800 characters in length.</span></span></param>
        <param name="value"><span data-ttu-id="70d80-399">Der Wert (als Bytearray) gespeichert werden, beschränkt auf 2GB umfassen.</span><span class="sxs-lookup"><span data-stu-id="70d80-399">The value (as a byte array) to be stored, limited to 2GB in length.</span></span></param>
        <summary>
            <span data-ttu-id="70d80-400">Speichern Versuche, einen Wert, der durch den angegebenen Schlüssel auf den Schlüssel/Wert indiziert hinzuzufügen.</span><span class="sxs-lookup"><span data-stu-id="70d80-400">Attempts to add a value indexed by the specified key to the key/value store.</span></span>
            </summary>
        <returns><span data-ttu-id="70d80-401">"True", wenn der angegebene Schlüssel nicht bereits gefunden und hinzugefügt wurde.</span><span class="sxs-lookup"><span data-stu-id="70d80-401">True if the specified key was not already found and added.</span></span> <span data-ttu-id="70d80-402">"False", wenn der angegebene Schlüssel bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="70d80-402">False if the specified key already exists.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGet">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreItem TryGet (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.KeyValueStoreItem TryGet(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryGet(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.TryGet : System.Fabric.TransactionBase * string -&gt; System.Fabric.KeyValueStoreItem" Usage="keyValueStoreReplica.TryGet (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreItem</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase"><span data-ttu-id="70d80-403">Die Transaktion-Instanz.</span><span class="sxs-lookup"><span data-stu-id="70d80-403">The transaction instance.</span></span></param>
        <param name="key"><span data-ttu-id="70d80-404">Der Schlüssel oder Index, der den Wert (als Zeichenfolge) abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="70d80-404">The key, or index, of the value to be retrieved (as a string).</span></span> <span data-ttu-id="70d80-405">Beschränkt auf 800 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="70d80-405">Limited to 800 characters in length.</span></span></param>
        <summary>
            <span data-ttu-id="70d80-406">Versucht, erhalten den gespeicherten Wert als ein <see cref="T:System.Fabric.KeyValueStoreItem" /> -Objekt, dem angegebenen Schlüssel zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="70d80-406">Attempts to get the stored value, as a <see cref="T:System.Fabric.KeyValueStoreItem" /> object, associated with the specified key.</span></span>
            </summary>
        <returns><span data-ttu-id="70d80-407">Ein <see cref="T:System.Fabric.KeyValueStoreItem" /> Objekt, das den gespeicherten Wert darstellt, oder null, wenn der angegebene Schlüssel nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="70d80-407">A <see cref="T:System.Fabric.KeyValueStoreItem" /> object representing the stored value or null if the specified key does not exist.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetMetadata">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreItemMetadata TryGetMetadata (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.KeyValueStoreItemMetadata TryGetMetadata(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryGetMetadata(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.TryGetMetadata : System.Fabric.TransactionBase * string -&gt; System.Fabric.KeyValueStoreItemMetadata" Usage="keyValueStoreReplica.TryGetMetadata (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreItemMetadata</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase"><span data-ttu-id="70d80-408">Die Transaktion-Instanz.</span><span class="sxs-lookup"><span data-stu-id="70d80-408">The transaction instance.</span></span></param>
        <param name="key"><span data-ttu-id="70d80-409">Der Schlüssel oder Index, der den Wert (als Zeichenfolge) abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="70d80-409">The key, or index, of the value to be retrieved (as a string).</span></span> <span data-ttu-id="70d80-410">Beschränkt auf 800 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="70d80-410">Limited to 800 characters in length.</span></span></param>
        <summary>
            <span data-ttu-id="70d80-411">Versucht, die Metadaten als Abrufen einer <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> -Objekt für den angegebenen Schlüssel zugeordnete Wert.</span><span class="sxs-lookup"><span data-stu-id="70d80-411">Attempts to get the metadata as a <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> object, for the value associated with the specified key.</span></span>
            </summary>
        <returns><span data-ttu-id="70d80-412">Ein <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> -Objekt, das die Metadaten darstellt, die mit dem angegebenen Wert verknüpft sind, oder null, wenn der angegebene Schlüssel nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="70d80-412">A <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> object representing the metadata associated with the specified value or null if the specified key does not exist.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetValue">
      <MemberSignature Language="C#" Value="public byte[] TryGetValue (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance unsigned int8[] TryGetValue(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryGetValue(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.TryGetValue : System.Fabric.TransactionBase * string -&gt; byte[]" Usage="keyValueStoreReplica.TryGetValue (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase"><span data-ttu-id="70d80-413">Die Transaktion-Instanz.</span><span class="sxs-lookup"><span data-stu-id="70d80-413">The transaction instance.</span></span></param>
        <param name="key"><span data-ttu-id="70d80-414">Der Schlüssel oder Index, der den Wert (als Zeichenfolge) abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="70d80-414">The key, or index, of the value to be retrieved (as a string).</span></span> <span data-ttu-id="70d80-415">Beschränkt auf 800 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="70d80-415">Limited to 800 characters in length.</span></span></param>
        <summary>
            <span data-ttu-id="70d80-416">Versucht, den gespeicherten Wert als ein Bytearray mit dem angegebenen Schlüssel verknüpfte abzurufen.</span><span class="sxs-lookup"><span data-stu-id="70d80-416">Attempts to get the stored value as a byte array, associated with the specified key.</span></span>
            </summary>
        <returns><span data-ttu-id="70d80-417">Ein Bytearray, das den gespeicherten Wert oder Null darstellt, wenn der angegebene Schlüssel nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="70d80-417">A byte array representing the stored value or null if the specified key does not exist.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryRemove">
      <MemberSignature Language="C#" Value="public bool TryRemove (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryRemove(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryRemove(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.TryRemove : System.Fabric.TransactionBase * string -&gt; bool" Usage="keyValueStoreReplica.TryRemove (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase"><span data-ttu-id="70d80-418">Die Transaktion-Instanz.</span><span class="sxs-lookup"><span data-stu-id="70d80-418">The transaction instance.</span></span></param>
        <param name="key"><span data-ttu-id="70d80-419">Der Schlüssel oder Index, der den Wert (als Zeichenfolge) entfernt werden soll.</span><span class="sxs-lookup"><span data-stu-id="70d80-419">The key, or index, of the value to be removed (as a string).</span></span> <span data-ttu-id="70d80-420">Beschränkt auf 800 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="70d80-420">Limited to 800 characters in length.</span></span></param>
        <summary>
            <span data-ttu-id="70d80-421">Versucht, den Wert, der durch den angegebenen Schlüssel indiziert zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="70d80-421">Attempts to remove the value indexed by the specified key.</span></span>
            </summary>
        <returns><span data-ttu-id="70d80-422">"True", wenn der angegebene Schlüssel gefunden und entfernt wurde.</span><span class="sxs-lookup"><span data-stu-id="70d80-422">True if the specified key was found and removed.</span></span> <span data-ttu-id="70d80-423">"False", wenn der angegebene Schlüssel nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="70d80-423">False if the specified key does not exist.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryRemove">
      <MemberSignature Language="C#" Value="public bool TryRemove (System.Fabric.TransactionBase transactionBase, string key, long checkSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryRemove(class System.Fabric.TransactionBase transactionBase, string key, int64 checkSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryRemove(System.Fabric.TransactionBase,System.String,System.Int64)" />
      <MemberSignature Language="F#" Value="member this.TryRemove : System.Fabric.TransactionBase * string * int64 -&gt; bool" Usage="keyValueStoreReplica.TryRemove (transactionBase, key, checkSequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="checkSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="transactionBase"><span data-ttu-id="70d80-424">Die Transaktion-Instanz.</span><span class="sxs-lookup"><span data-stu-id="70d80-424">The transaction instance.</span></span></param>
        <param name="key"><span data-ttu-id="70d80-425">Der Schlüssel oder Index, der den Wert (als Zeichenfolge) entfernt werden soll.</span><span class="sxs-lookup"><span data-stu-id="70d80-425">The key, or index, of the value to be removed (as a string).</span></span> <span data-ttu-id="70d80-426">Beschränkt auf 800 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="70d80-426">Limited to 800 characters in length.</span></span></param>
        <param name="checkSequenceNumber"><span data-ttu-id="70d80-427">Die erwartete Sequenznummer des Schlüssels, der entfernt werden soll.</span><span class="sxs-lookup"><span data-stu-id="70d80-427">The expected sequence number of the key to be removed.</span></span></param>
        <summary>
            <span data-ttu-id="70d80-428">Versucht, den Wert, der durch den angegebenen Schlüssel indiziert zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="70d80-428">Attempts to remove the value indexed by the specified key.</span></span>
            </summary>
        <returns><span data-ttu-id="70d80-429">"True", wenn der angegebene Schlüssel gefunden und entfernt wurde.</span><span class="sxs-lookup"><span data-stu-id="70d80-429">True if the specified key was found and removed.</span></span> <span data-ttu-id="70d80-430">"False", wenn der angegebene Schlüssel nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="70d80-430">False if the specified key does not exist.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryUpdate">
      <MemberSignature Language="C#" Value="public bool TryUpdate (System.Fabric.TransactionBase transactionBase, string key, byte[] value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryUpdate(class System.Fabric.TransactionBase transactionBase, string key, unsigned int8[] value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryUpdate(System.Fabric.TransactionBase,System.String,System.Byte[])" />
      <MemberSignature Language="F#" Value="member this.TryUpdate : System.Fabric.TransactionBase * string * byte[] -&gt; bool" Usage="keyValueStoreReplica.TryUpdate (transactionBase, key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="transactionBase"><span data-ttu-id="70d80-431">Die Transaktion-Instanz.</span><span class="sxs-lookup"><span data-stu-id="70d80-431">The transaction instance.</span></span></param>
        <param name="key"><span data-ttu-id="70d80-432">Der Schlüssel oder Index, der den Wert (als Zeichenfolge) aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="70d80-432">The key, or index, of the value to be updated (as a string).</span></span> <span data-ttu-id="70d80-433">Beschränkt auf 800 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="70d80-433">Limited to 800 characters in length.</span></span></param>
        <param name="value"><span data-ttu-id="70d80-434">Der Wert (als Bytearray) gespeichert werden, beschränkt auf 2GB umfassen.</span><span class="sxs-lookup"><span data-stu-id="70d80-434">The value (as a byte array) to be stored, limited to 2GB in length.</span></span></param>
        <summary>
            <span data-ttu-id="70d80-435">Versucht, den Wert, der durch den angegebenen Schlüssel indiziert zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="70d80-435">Attempts to update the value indexed by the specified key.</span></span>
            </summary>
        <returns><span data-ttu-id="70d80-436">"True", wenn der angegebene Schlüssel gefunden und aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="70d80-436">True if the specified key was found and updated.</span></span> <span data-ttu-id="70d80-437">"False", wenn der angegebene Schlüssel nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="70d80-437">False if the specified key does not exist.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryUpdate">
      <MemberSignature Language="C#" Value="public bool TryUpdate (System.Fabric.TransactionBase transactionBase, string key, byte[] value, long checkSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryUpdate(class System.Fabric.TransactionBase transactionBase, string key, unsigned int8[] value, int64 checkSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryUpdate(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" />
      <MemberSignature Language="F#" Value="member this.TryUpdate : System.Fabric.TransactionBase * string * byte[] * int64 -&gt; bool" Usage="keyValueStoreReplica.TryUpdate (transactionBase, key, value, checkSequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="checkSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="transactionBase"><span data-ttu-id="70d80-438">Die Transaktion-Instanz.</span><span class="sxs-lookup"><span data-stu-id="70d80-438">The transaction instance.</span></span></param>
        <param name="key"><span data-ttu-id="70d80-439">Der Schlüssel oder Index, der den Wert (als Zeichenfolge) aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="70d80-439">The key, or index, of the value to be updated (as a string).</span></span> <span data-ttu-id="70d80-440">Beschränkt auf 800 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="70d80-440">Limited to 800 characters in length.</span></span></param>
        <param name="value"><span data-ttu-id="70d80-441">Der Wert (als Bytearray) gespeichert werden, beschränkt auf 2GB umfassen.</span><span class="sxs-lookup"><span data-stu-id="70d80-441">The value (as a byte array) to be stored, limited to 2GB in length.</span></span></param>
        <param name="checkSequenceNumber"><span data-ttu-id="70d80-442">Die erwartete Sequenznummer des zu aktualisierenden Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="70d80-442">The expected sequence number of the key to be updated.</span></span></param>
        <summary>
            <span data-ttu-id="70d80-443">Versucht, den Wert, der durch den angegebenen Schlüssel indiziert zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="70d80-443">Attempts to update the value indexed by the specified key.</span></span>
            </summary>
        <returns><span data-ttu-id="70d80-444">"True", wenn der angegebene Schlüssel gefunden und aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="70d80-444">True if the specified key was found and updated.</span></span> <span data-ttu-id="70d80-445">"False", wenn der angegebene Schlüssel nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="70d80-445">False if the specified key does not exist.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public void Update (System.Fabric.TransactionBase transactionBase, string key, byte[] value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Update(class System.Fabric.TransactionBase transactionBase, string key, unsigned int8[] value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Update(System.Fabric.TransactionBase,System.String,System.Byte[])" />
      <MemberSignature Language="F#" Value="member this.Update : System.Fabric.TransactionBase * string * byte[] -&gt; unit" Usage="keyValueStoreReplica.Update (transactionBase, key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para><span data-ttu-id="70d80-446">Die Transaktion-Instanz.</span><span class="sxs-lookup"><span data-stu-id="70d80-446">The transaction instance.</span></span></para>
        </param>
        <param name="key">
          <para><span data-ttu-id="70d80-447">Der Schlüssel oder Index des Werts (als Zeichenfolge) aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="70d80-447">The key or index of the value to be updated (as a string).</span></span> <span data-ttu-id="70d80-448">Beschränkt auf 800 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="70d80-448">Limited to 800 characters in length.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="70d80-449">Der Wert (als Bytearray) gespeichert werden, beschränkt auf 2GB umfassen.</span><span class="sxs-lookup"><span data-stu-id="70d80-449">The value (as a byte array) to be stored, limited to 2GB in length.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-450">Aktualisiert den gespeicherten Wert, der dem angegebenen Schlüssel zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="70d80-450">Updates the stored value associated with the specified key.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public void Update (System.Fabric.TransactionBase transactionBase, string key, byte[] value, long checkSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Update(class System.Fabric.TransactionBase transactionBase, string key, unsigned int8[] value, int64 checkSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Update(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" />
      <MemberSignature Language="F#" Value="member this.Update : System.Fabric.TransactionBase * string * byte[] * int64 -&gt; unit" Usage="keyValueStoreReplica.Update (transactionBase, key, value, checkSequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="checkSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para><span data-ttu-id="70d80-451">Die Transaktion-Instanz.</span><span class="sxs-lookup"><span data-stu-id="70d80-451">The transaction instance.</span></span></para>
        </param>
        <param name="key">
          <para><span data-ttu-id="70d80-452">Der Schlüssel oder Index des Werts (als Zeichenfolge) aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="70d80-452">The key or index of the value to be updated (as a string).</span></span> <span data-ttu-id="70d80-453">Beschränkt auf 800 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="70d80-453">Limited to 800 characters in length.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="70d80-454">Der Wert (als Bytearray) gespeichert werden, beschränkt auf 2GB umfassen.</span><span class="sxs-lookup"><span data-stu-id="70d80-454">The value (as a byte array) to be stored, limited to 2GB in length.</span></span></para>
        </param>
        <param name="checkSequenceNumber">
          <para><span data-ttu-id="70d80-455">Die erwartete Sequenznummer des zu aktualisierenden Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="70d80-455">The expected sequence number of the key to be updated.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-456">Aktualisiert den Wert, der durch den angegebenen Schlüssel indiziert.</span><span class="sxs-lookup"><span data-stu-id="70d80-456">Updates the value indexed by the specified key.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateReplicatorSettings">
      <MemberSignature Language="C#" Value="public void UpdateReplicatorSettings (System.Fabric.ReplicatorSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpdateReplicatorSettings(class System.Fabric.ReplicatorSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.UpdateReplicatorSettings(System.Fabric.ReplicatorSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateReplicatorSettings (settings As ReplicatorSettings)" />
      <MemberSignature Language="F#" Value="member this.UpdateReplicatorSettings : System.Fabric.ReplicatorSettings -&gt; unit" Usage="keyValueStoreReplica.UpdateReplicatorSettings settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="System.Fabric.ReplicatorSettings" />
      </Parameters>
      <Docs>
        <param name="settings">
          <para><span data-ttu-id="70d80-457">Die Einstellungen, die zum Aktualisieren der Schlüssel-Wert zu Replikator speichern.</span><span class="sxs-lookup"><span data-stu-id="70d80-457">The settings used to update the key/value store replicator.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70d80-458">Aktualisiert die Schlüssel/Wert-Speicher Replicator mit den Einstellungen in der angegebenen <see cref="T:System.Fabric.ReplicatorSettings" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="70d80-458">Updates the key/value store replicator with the settings in the specified <see cref="T:System.Fabric.ReplicatorSettings" /> object.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>