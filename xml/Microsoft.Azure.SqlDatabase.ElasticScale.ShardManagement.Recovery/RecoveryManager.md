<Type Name="RecoveryManager" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager">
  <TypeSignature Language="C#" Value="public sealed class RecoveryManager" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RecoveryManager extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RecoveryManager" />
  <TypeSignature Language="F#" Value="type RecoveryManager = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0b25c-101">Verwaltet unterschiedliche Recovery Aufgaben im Zusammenhang mit für eine shardzuordnungs-Manager.</span><span class="sxs-lookup"><span data-stu-id="0b25c-101">Manages various recovery related tasks for a shard map manager.</span></span> <span data-ttu-id="0b25c-102">Er erleichtert das Auflösen von Probleme mit beschädigten Daten zwischen Shards Zuordnung Informationen lokal gespeichert werden, auf die Shards und in der globalen Shard Map-Manager-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="0b25c-102">It helps resolving data corruption issues between shard map information stored locally on the shards and in the global shard map manager database.</span></span> <span data-ttu-id="0b25c-103">Es wird auch mit bestimmten "leider" Recovery-Szenarien, in der Wiederherstellung der shardzuordnungen von datenbanksicherungen oder Datenbankkopien erforderlich ist.</span><span class="sxs-lookup"><span data-stu-id="0b25c-103">It also helps with certain 'oops' recovery scenarios where reconstruction of shard maps from database backups or database copies is necessary.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="0b25c-104">Beachten Sie, dass einige der Wiederherstellungsmethoden nicht behebbaren Datenverlust bei nicht ordnungsgemäßer verursachen können.</span><span class="sxs-lookup"><span data-stu-id="0b25c-104">Note that some of the recovery methods can cause unrecoverable data loss when not used properly.</span></span> <span data-ttu-id="0b25c-105">Es wird empfohlen, Sicherungen oder Kopien aller Datenbanken, die in Wiederherstellungsvorgänge einbezogen werden.</span><span class="sxs-lookup"><span data-stu-id="0b25c-105">It is recommend to take backups or copies of all databases that participate in recovery operations.</span></span> 
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="AttachShard">
      <MemberSignature Language="C#" Value="public void AttachShard (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AttachShard(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.AttachShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AttachShard (location As ShardLocation)" />
      <MemberSignature Language="F#" Value="member this.AttachShard : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation -&gt; unit" Usage="recoveryManager.AttachShard location" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="0b25c-106">Der Speicherort des betreffenden Shards angefügt wird.</span><span class="sxs-lookup"><span data-stu-id="0b25c-106">Location of the shard being attached.</span></span></param>
        <summary>
            <span data-ttu-id="0b25c-107">Fügt einen Shard an die shardzuordnungs-Manager an.</span><span class="sxs-lookup"><span data-stu-id="0b25c-107">Attaches a shard to the shard map manager.</span></span> <span data-ttu-id="0b25c-108">Frühere Versionen von Zuordnungen für die gleiche shardzuordnung werden automatisch aktualisiert werden, wenn neuere Versionen auf den Shard anzufügenden gefunden werden.</span><span class="sxs-lookup"><span data-stu-id="0b25c-108">Earlier versions of mappings for the same shard map will automatically be updated if more recent versions are found on the shard to be attached.</span></span>
            <span data-ttu-id="0b25c-109">Nach dem Anfügen eines Shards <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" /> aufgerufen werden, um das Prüfen auf Inkonsistenzen, die manuelle rechtfertigen Auflösung in Konflikt stehen.</span><span class="sxs-lookup"><span data-stu-id="0b25c-109">After attaching a shard, <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" /> should be called to check for any inconsistencies that warrant manual conflict resolution.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="0b25c-110">Beachten Sie, dass diese Methode nicht behebbaren Datenverlust führen kann.</span><span class="sxs-lookup"><span data-stu-id="0b25c-110">Note that this method can cause unrecoverable data loss.</span></span> <span data-ttu-id="0b25c-111">Stellen Sie sicher, dass Sie Sicherungen oder Kopien Ihrer Datenbanken erstellt haben, und nur mit großer Umsicht fortfahren.</span><span class="sxs-lookup"><span data-stu-id="0b25c-111">Make sure you have taken backups or copies of your databases and only then proceed with great care.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AttachShard">
      <MemberSignature Language="C#" Value="public void AttachShard (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location, string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AttachShard(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location, string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.AttachShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AttachShard (location As ShardLocation, shardMapName As String)" />
      <MemberSignature Language="F#" Value="member this.AttachShard : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation * string -&gt; unit" Usage="recoveryManager.AttachShard (location, shardMapName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Maintainability", "CA1502:AvoidExcessiveComplexity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="0b25c-112">Der Speicherort des betreffenden Shards angefügt wird.</span><span class="sxs-lookup"><span data-stu-id="0b25c-112">Location of the shard being attached.</span></span></param>
        <param name="shardMapName"><span data-ttu-id="0b25c-113">Optionale Zeichenfolge, die auf den Namen der shardzuordnung filtern.</span><span class="sxs-lookup"><span data-stu-id="0b25c-113">Optional string to filter on the shard map name.</span></span></param>
        <summary>
            <span data-ttu-id="0b25c-114">Fügt einen Shard an die shardzuordnungs-Manager an.</span><span class="sxs-lookup"><span data-stu-id="0b25c-114">Attaches a shard to the shard map manager.</span></span> <span data-ttu-id="0b25c-115">Frühere Versionen von Zuordnungen für die gleiche shardzuordnung werden automatisch aktualisiert werden, wenn neuere Versionen auf den Shard anzufügenden gefunden werden.</span><span class="sxs-lookup"><span data-stu-id="0b25c-115">Earlier versions of mappings for the same shard map will automatically be updated if more recent versions are found on the shard to be attached.</span></span>
            <span data-ttu-id="0b25c-116">Shard Speicherort wird auf neueste Version des lokalen Speichers im Rahmen dieses Vorgangs aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="0b25c-116">Shard location will be upgraded to latest version of local store as part of this operation.</span></span>
            <span data-ttu-id="0b25c-117">Nach dem Anfügen eines Shards <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" /> aufgerufen werden, um das Prüfen auf Inkonsistenzen, die manuelle rechtfertigen Auflösung in Konflikt stehen.</span><span class="sxs-lookup"><span data-stu-id="0b25c-117">After attaching a shard, <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" /> should be called to check for any inconsistencies that warrant manual conflict resolution.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="0b25c-118">Beachten Sie, dass diese Methode nicht behebbaren Datenverlust führen kann.</span><span class="sxs-lookup"><span data-stu-id="0b25c-118">Note that this method can cause unrecoverable data loss.</span></span> <span data-ttu-id="0b25c-119">Stellen Sie sicher, dass Sie Sicherungen oder Kopien Ihrer Datenbanken erstellt haben, und nur mit großer Umsicht fortfahren.</span><span class="sxs-lookup"><span data-stu-id="0b25c-119">Make sure you have taken backups or copies of your databases and only then proceed with great care.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DetachShard">
      <MemberSignature Language="C#" Value="public void DetachShard (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DetachShard(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetachShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DetachShard (location As ShardLocation)" />
      <MemberSignature Language="F#" Value="member this.DetachShard : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation -&gt; unit" Usage="recoveryManager.DetachShard location" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="0b25c-120">Der Speicherort des betreffenden Shards getrennt wird.</span><span class="sxs-lookup"><span data-stu-id="0b25c-120">Location of the shard being detached.</span></span></param>
        <summary>
            <span data-ttu-id="0b25c-121">Trennt den angegebenen Shard aus der shardzuordnungs-Manager.</span><span class="sxs-lookup"><span data-stu-id="0b25c-121">Detaches the given shard from the shard map manager.</span></span> <span data-ttu-id="0b25c-122">Auf den Shard zu löschenden zeigen Mappings werden von dieser Methode automatisch entfernt werden.</span><span class="sxs-lookup"><span data-stu-id="0b25c-122">Mappings pointing to the shard to be deleted will automatically be removed by this method.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="0b25c-123">Beachten Sie, dass diese Methode nicht behebbaren Datenverlust führen kann.</span><span class="sxs-lookup"><span data-stu-id="0b25c-123">Note that this method can cause unrecoverable data loss.</span></span> <span data-ttu-id="0b25c-124">Stellen Sie sicher, dass Sie Sicherungen oder Kopien Ihrer Datenbanken erstellt haben, und nur mit großer Umsicht fortfahren.</span><span class="sxs-lookup"><span data-stu-id="0b25c-124">Make sure you have taken backups or copies of your databases and only then proceed with great care.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DetachShard">
      <MemberSignature Language="C#" Value="public void DetachShard (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location, string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DetachShard(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location, string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetachShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DetachShard (location As ShardLocation, shardMapName As String)" />
      <MemberSignature Language="F#" Value="member this.DetachShard : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation * string -&gt; unit" Usage="recoveryManager.DetachShard (location, shardMapName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="0b25c-125">Der Speicherort des betreffenden Shards getrennt wird.</span><span class="sxs-lookup"><span data-stu-id="0b25c-125">Location of the shard being detached.</span></span></param>
        <param name="shardMapName"><span data-ttu-id="0b25c-126">Optionale Zeichenfolge, die auf den Namen der shardzuordnung filtern.</span><span class="sxs-lookup"><span data-stu-id="0b25c-126">Optional string to filter on shard map name.</span></span></param>
        <summary>
            <span data-ttu-id="0b25c-127">Trennt den angegebenen Shard aus der shardzuordnungs-Manager.</span><span class="sxs-lookup"><span data-stu-id="0b25c-127">Detaches the given shard from the shard map manager.</span></span> <span data-ttu-id="0b25c-128">Auf den Shard zu löschenden zeigen Mappings werden von dieser Methode automatisch entfernt werden.</span><span class="sxs-lookup"><span data-stu-id="0b25c-128">Mappings pointing to the shard to be deleted will automatically be removed by this method.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="0b25c-129">Beachten Sie, dass diese Methode nicht behebbaren Datenverlust führen kann.</span><span class="sxs-lookup"><span data-stu-id="0b25c-129">Note that this method can cause unrecoverable data loss.</span></span> <span data-ttu-id="0b25c-130">Stellen Sie sicher, dass Sie Sicherungen oder Kopien Ihrer Datenbanken erstellt haben, und nur mit großer Umsicht fortfahren.</span><span class="sxs-lookup"><span data-stu-id="0b25c-130">Make sure you have taken backups or copies of your databases and only then proceed with great care.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DetectMappingDifferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt; DetectMappingDifferences (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt; DetectMappingDifferences(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Function DetectMappingDifferences (location As ShardLocation) As IEnumerable(Of RecoveryToken)" />
      <MemberSignature Language="F#" Value="member this.DetectMappingDifferences : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation -&gt; seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt;" Usage="recoveryManager.DetectMappingDifferences location" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="0b25c-131">Speicherort des Shard für das Erkennen von Inkonsistenzen.</span><span class="sxs-lookup"><span data-stu-id="0b25c-131">Location of shard for which to detect inconsistencies.</span></span></param>
        <summary>
            <span data-ttu-id="0b25c-132">Listet die Unterschiede in den Zuordnungen zwischen der globalen Shard Map-Manager-Datenbank und der lokalen Shard-Datenbank in den angegebenen Shard-Speicherort.</span><span class="sxs-lookup"><span data-stu-id="0b25c-132">Enumerates differences in the mappings between the global shard map manager database and the local shard database in the specified shard location.</span></span>
            </summary>
        <returns><span data-ttu-id="0b25c-133">Auflistung von Token für die weitere Auflösung Aufgaben verwendet werden soll (siehe <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.ResolveMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution)" />).</span><span class="sxs-lookup"><span data-stu-id="0b25c-133">Collection of tokens to be used for further resolution tasks (see <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.ResolveMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution)" />).</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DetectMappingDifferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt; DetectMappingDifferences (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location, string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt; DetectMappingDifferences(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location, string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DetectMappingDifferences (location As ShardLocation, shardMapName As String) As IEnumerable(Of RecoveryToken)" />
      <MemberSignature Language="F#" Value="member this.DetectMappingDifferences : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation * string -&gt; seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt;" Usage="recoveryManager.DetectMappingDifferences (location, shardMapName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Maintainability", "CA1506:AvoidExcessiveClassCoupling")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Maintainability", "CA1502:AvoidExcessiveComplexity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="0b25c-134">Speicherort des Shard für das Erkennen von Inkonsistenzen.</span><span class="sxs-lookup"><span data-stu-id="0b25c-134">Location of shard for which to detect inconsistencies.</span></span></param>
        <param name="shardMapName"><span data-ttu-id="0b25c-135">Optionaler Parameter zum Angeben einer bestimmten shardzuordnung.</span><span class="sxs-lookup"><span data-stu-id="0b25c-135">Optional parameter to specify a particular shard map.</span></span></param>
        <summary>
            <span data-ttu-id="0b25c-136">Listet die Unterschiede in den Zuordnungen zwischen der globalen Shard Map-Manager-Datenbank und der lokalen Shard-Datenbank in den angegebenen Shard-Speicherort.</span><span class="sxs-lookup"><span data-stu-id="0b25c-136">Enumerates differences in the mappings between the global shard map manager database and the local shard database in the specified shard location.</span></span>
            </summary>
        <returns><span data-ttu-id="0b25c-137">Auflistung von Token für die weitere Auflösung Aufgaben verwendet werden soll (siehe <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.ResolveMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution)" />).</span><span class="sxs-lookup"><span data-stu-id="0b25c-137">Collection of tokens to be used for further resolution tasks (see <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.ResolveMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution)" />).</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMappingDifferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation&gt; GetMappingDifferences (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IDictionary`2&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation&gt; GetMappingDifferences(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMappingDifferences (token As RecoveryToken) As IDictionary(Of ShardRange, MappingLocation)" />
      <MemberSignature Language="F#" Value="member this.GetMappingDifferences : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken -&gt; System.Collections.Generic.IDictionary&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation&gt;" Usage="recoveryManager.GetMappingDifferences token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="0b25c-138">Wiederherstellungstoken Merry <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span><span class="sxs-lookup"><span data-stu-id="0b25c-138">Recovery token returned from <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span></span></param>
        <summary>
            <span data-ttu-id="0b25c-139">Gibt ein Wörterbuch von Bereichsposition-Schlüssel-Wert-Paaren zurück.</span><span class="sxs-lookup"><span data-stu-id="0b25c-139">Returns a dictionary of range-to-location key-value pairs.</span></span> <span data-ttu-id="0b25c-140">Der Speicherort zurückgegeben wird ein Enumerator, der angibt, ob eine bestimmte Bereich-(oder) vorhanden, nur in der lokalen shardzuordnung, nur in der globalen shardzuordnung oder beides handelt.</span><span class="sxs-lookup"><span data-stu-id="0b25c-140">The location returned is an enumerator stating whether a given range (or point) is present only in the local shard map, only in the global shard map, or both.</span></span> <span data-ttu-id="0b25c-141">Bereiche, die nicht in einer shardzuordnung enthalten darf keine Unterschiede enthalten, damit diese Bereiche nicht angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="0b25c-141">Ranges not contained in either shard map cannot contain differences so those ranges are not shown.</span></span>
            </summary>
        <returns><span data-ttu-id="0b25c-142">Der Satz von Bereichen und ihre entsprechenden <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation" />.</span><span class="sxs-lookup"><span data-stu-id="0b25c-142">The set of ranges and their corresponding <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation" />.</span></span></returns>
        <remarks>
            <span data-ttu-id="0b25c-143">Diese Methode setzt voraus, einen vorherigen Aufruf von <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" /> , der die Wiederherstellung tokenparameter bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="0b25c-143">This method assumes a previous call to <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" /> that provides the recovery token parameter.</span></span>
            <span data-ttu-id="0b25c-144">Das Ergebnis dieser Methode wird üblicherweise in nachfolgende Aufrufe verwendet, um die Inkonsistenzen aufzulösen, wie z. B. <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.ResolveMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution)" /> oder <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.RebuildMappingsOnShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,System.Collections.Generic.IEnumerable{Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange})" />.</span><span class="sxs-lookup"><span data-stu-id="0b25c-144">The result of this method is typically used in subsequent calls to resolve inconsistencies such as <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.ResolveMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution)" /> or <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.RebuildMappingsOnShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,System.Collections.Generic.IEnumerable{Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange})" />.</span></span> 
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShardInfo">
      <MemberSignature Language="C#" Value="public void GetShardInfo (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, out Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType mapType, out string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void GetShardInfo(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, [out] valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType&amp; mapType, [out] string&amp; shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetShardInfo(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType@,System.String@)" />
      <MemberSignature Language="VB.NET" Value="Public Sub GetShardInfo (token As RecoveryToken, ByRef mapType As ShardMapType, ByRef shardMapName As String)" />
      <MemberSignature Language="F#" Value="member this.GetShardInfo : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken *  *  -&gt; unit" Usage="recoveryManager.GetShardInfo (token, mapType, shardMapName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", MessageId="1#")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", MessageId="2#")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
        <Parameter Name="mapType" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType&amp;" RefType="out" />
        <Parameter Name="shardMapName" Type="System.String&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="0b25c-145">Wiederherstellungstoken Merry <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span><span class="sxs-lookup"><span data-stu-id="0b25c-145">Recovery token returned from <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span></span></param>
        <param name="mapType"><span data-ttu-id="0b25c-146">Der Ausgabetyp Shardmap (Bereichs- oder Listen).</span><span class="sxs-lookup"><span data-stu-id="0b25c-146">Output Shardmap type (Range or List).</span></span></param>
        <param name="shardMapName"><span data-ttu-id="0b25c-147">Der Ausgabename der shardzuordnung.</span><span class="sxs-lookup"><span data-stu-id="0b25c-147">Output name of shard map.</span></span></param>
        <summary>
            <span data-ttu-id="0b25c-148">Ruft Shard Map-Typ und Name auf Grundlage von zurückgegebene Token <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span><span class="sxs-lookup"><span data-stu-id="0b25c-148">Retrieves shard map type and name based on the token returned from <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShardInfo">
      <MemberSignature Language="C#" Value="public void GetShardInfo (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, out Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType mapType, out string shardMapName, out Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation shardLocation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void GetShardInfo(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, [out] valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType&amp; mapType, [out] string&amp; shardMapName, [out] class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&amp; shardLocation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetShardInfo(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType@,System.String@,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation@)" />
      <MemberSignature Language="VB.NET" Value="Public Sub GetShardInfo (token As RecoveryToken, ByRef mapType As ShardMapType, ByRef shardMapName As String, ByRef shardLocation As ShardLocation)" />
      <MemberSignature Language="F#" Value="member this.GetShardInfo : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken *  *  *  -&gt; unit" Usage="recoveryManager.GetShardInfo (token, mapType, shardMapName, shardLocation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", MessageId="3#")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", MessageId="1#")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", MessageId="2#")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
        <Parameter Name="mapType" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType&amp;" RefType="out" />
        <Parameter Name="shardMapName" Type="System.String&amp;" RefType="out" />
        <Parameter Name="shardLocation" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="0b25c-149">Wiederherstellungstoken Merry <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span><span class="sxs-lookup"><span data-stu-id="0b25c-149">Recovery token returned from <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span></span></param>
        <param name="mapType"><span data-ttu-id="0b25c-150">Ausgaben Shard Map-Typ (Bereichs- oder Listen).</span><span class="sxs-lookup"><span data-stu-id="0b25c-150">Outputs shard map type (Range or List).</span></span></param>
        <param name="shardMapName"><span data-ttu-id="0b25c-151">Namen der shardzuordnung Ausgaben.</span><span class="sxs-lookup"><span data-stu-id="0b25c-151">Outputs shard map name.</span></span></param>
        <param name="shardLocation"><span data-ttu-id="0b25c-152">Ausgaben Shard-Speicherort</span><span class="sxs-lookup"><span data-stu-id="0b25c-152">Outputs shard location</span></span></param>
        <summary>
            <span data-ttu-id="0b25c-153">Ruft Shard Typ, Name und Shard Standorte der Karte basiert auf dem Token Merry <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span><span class="sxs-lookup"><span data-stu-id="0b25c-153">Retrieves shard map type, name and shard location based on the token returned from <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShardLocation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation GetShardLocation (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation GetShardLocation(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetShardLocation(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetShardLocation (token As RecoveryToken) As ShardLocation" />
      <MemberSignature Language="F#" Value="member this.GetShardLocation : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" Usage="recoveryManager.GetShardLocation token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="0b25c-154">Wiederherstellungstoken zurückgegeben wird, aus<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" /></span><span class="sxs-lookup"><span data-stu-id="0b25c-154">Recovery token returned from <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" /></span></span></param>
        <summary>
            <span data-ttu-id="0b25c-155">Gibt der Shard-Speicherort, der die lokale shardzuordnung von verarbeiteten <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span><span class="sxs-lookup"><span data-stu-id="0b25c-155">Returns the shard location of the local shard map processed by <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="0b25c-156">Speicherort des betreffenden Shards auf den Satz der Zuordnung der Unterschiede festgestellt werden, entsprechende <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span><span class="sxs-lookup"><span data-stu-id="0b25c-156">Location of the shard corresponding to the set of mapping differences detected in <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShardMapName">
      <MemberSignature Language="C#" Value="public string GetShardMapName (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetShardMapName(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetShardMapName(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetShardMapName (token As RecoveryToken) As String" />
      <MemberSignature Language="F#" Value="member this.GetShardMapName : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken -&gt; string" Usage="recoveryManager.GetShardMapName token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="0b25c-157">Wiederherstellungstoken Merry <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span><span class="sxs-lookup"><span data-stu-id="0b25c-157">Recovery token returned from <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span></span></param>
        <summary>
            <span data-ttu-id="0b25c-158">Gibt den shardzuordnungsnamen von der shardzuordnung von verarbeiteten <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span><span class="sxs-lookup"><span data-stu-id="0b25c-158">Returns the shard map name of the shard map processed by <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="0b25c-159">Der Name des der shardzuordnung für das angegebene Recovery-Token.</span><span class="sxs-lookup"><span data-stu-id="0b25c-159">The name of the shard map for the given recovery token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShardMapType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType GetShardMapType (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType GetShardMapType(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetShardMapType(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetShardMapType (token As RecoveryToken) As ShardMapType" />
      <MemberSignature Language="F#" Value="member this.GetShardMapType : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType" Usage="recoveryManager.GetShardMapType token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="0b25c-160">Wiederherstellungstoken Merry <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span><span class="sxs-lookup"><span data-stu-id="0b25c-160">Recovery token returned from <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span></span></param>
        <summary>
            <span data-ttu-id="0b25c-161">Gibt der Shard-Map-Typ, von der shardzuordnung von verarbeiteten <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span><span class="sxs-lookup"><span data-stu-id="0b25c-161">Returns the shard map type of the shard map processed by <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="0b25c-162">Der Typ des Shard Zuordnung (Liste in Bereich, usw.) entspricht, mit dem Recovery-Token.</span><span class="sxs-lookup"><span data-stu-id="0b25c-162">The type of shard map (list, range, etc...) corresponding to the recovery token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RebuildMappingsOnShard">
      <MemberSignature Language="C#" Value="public void RebuildMappingsOnShard (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange&gt; ranges);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RebuildMappingsOnShard(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange&gt; ranges) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.RebuildMappingsOnShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,System.Collections.Generic.IEnumerable{Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RebuildMappingsOnShard (token As RecoveryToken, ranges As IEnumerable(Of ShardRange))" />
      <MemberSignature Language="F#" Value="member this.RebuildMappingsOnShard : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken * seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange&gt; -&gt; unit" Usage="recoveryManager.RebuildMappingsOnShard (token, ranges)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="1")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
        <Parameter Name="ranges" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange&gt;" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="0b25c-163">Das Recovery-Token von einem vorherigen Aufruf von <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span><span class="sxs-lookup"><span data-stu-id="0b25c-163">The recovery token from a previous call to <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span></span></param>
        <param name="ranges"><span data-ttu-id="0b25c-164">Der Satz von Bereichen an, um auf den lokalen Shard behalten Sie beim Neuerstellen der lokalen shardzuordnung.</span><span class="sxs-lookup"><span data-stu-id="0b25c-164">The set of ranges to keep on the local shard when rebuilding the local shard map.</span></span></param>
        <summary>
             <span data-ttu-id="0b25c-165">Erstellt eine shardzuordnung lokalen Bereich aus einer Liste von inkonsistenten Shard Bereiche von erkannten neu <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" /> und Zugriff auf die dann von <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken)" />.</span><span class="sxs-lookup"><span data-stu-id="0b25c-165">Rebuilds a local range shard map from a list of inconsistent shard ranges detected by <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" /> and then accessed by <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken)" />.</span></span>
             <span data-ttu-id="0b25c-166">Die resultierende lokalen Bereich shardzuordnung wird immer noch nicht mit der globalen shardzuordnung in den Shard-Map-Manager-Datenbank sein.</span><span class="sxs-lookup"><span data-stu-id="0b25c-166">The resulting local range shard map will always still be inconsistent with the global shard map in the shard map manager database.</span></span> <span data-ttu-id="0b25c-167">Ein nachfolgender Aufruf von <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.ResolveMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution)" /> ist erforderlich, um das System wieder in einen fehlerfreien Zustand zu versetzen.</span><span class="sxs-lookup"><span data-stu-id="0b25c-167">A subsequent call to <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.ResolveMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution)" /> is necessary to bring the system back to a healthy state.</span></span>
             </summary>
        <remarks>
             <span data-ttu-id="0b25c-168">Beachten Sie, dass diese Methode nicht behebbaren Datenverlust führen kann.</span><span class="sxs-lookup"><span data-stu-id="0b25c-168">Note that this method can cause unrecoverable data loss.</span></span> <span data-ttu-id="0b25c-169">Stellen Sie sicher, dass Sie Sicherungen oder Kopien Ihrer Datenbanken erstellt haben, und nur mit großer Umsicht fortfahren.</span><span class="sxs-lookup"><span data-stu-id="0b25c-169">Make sure you have taken backups or copies of your databases and only then proceed with great care.</span></span>
             
            <span data-ttu-id="0b25c-170">Nur Shard Bereichen mit Inkonsistenzen können mit dieser Methode neu erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="0b25c-170">Only shard ranges with inconsistencies can be rebuilt using this method.</span></span> <span data-ttu-id="0b25c-171">Alle Bereiche mit keine Inkonsistenzen zwischen den lokalen Shard und der globale shardzuordnung werden auf den lokalen Shard unverändert beibehalten werden und werden durch diesen Aufruf nicht betroffen.</span><span class="sxs-lookup"><span data-stu-id="0b25c-171">All ranges with no inconsistencies between the local shard and the global shard map will be kept intact on the local shard and are not affected by this call.</span></span>
             <span data-ttu-id="0b25c-172">Nachfolgende Änderungen an die nicht in Konflikt stehender Zuordnungen können später mithilfe der regulären Schnittstellen in den shardzuordnungs-Manager vorgenommen werden.</span><span class="sxs-lookup"><span data-stu-id="0b25c-172">Subsequent changes to the non-conflicting mappings can be made later using the regular interfaces in the shard map manager.</span></span> <span data-ttu-id="0b25c-173">Es ist nicht notwendig, den Wiederherstellungs-Manager zu verwenden, nicht in Konflikt stehender Zuordnungen ändern.</span><span class="sxs-lookup"><span data-stu-id="0b25c-173">It is not necessary to use the recovery manager to change non-conflicting mappings.</span></span>
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebuildMappingsOnShardMapManagerFromShards">
      <MemberSignature Language="C#" Value="public void RebuildMappingsOnShardMapManagerFromShards (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RebuildMappingsOnShardMapManagerFromShards(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.RebuildMappingsOnShardMapManagerFromShards(System.Collections.Generic.IEnumerable{Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RebuildMappingsOnShardMapManagerFromShards (shardLocations As IEnumerable(Of ShardLocation))" />
      <MemberSignature Language="F#" Value="member this.RebuildMappingsOnShardMapManagerFromShards : seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; -&gt; unit" Usage="recoveryManager.RebuildMappingsOnShardMapManagerFromShards shardLocations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shardLocations" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt;" />
      </Parameters>
      <Docs>
        <param name="shardLocations"><span data-ttu-id="0b25c-174">Die Auflistung der Shard-Positionen.</span><span class="sxs-lookup"><span data-stu-id="0b25c-174">Collection of shard locations.</span></span></param>
        <summary>
            <span data-ttu-id="0b25c-175">Rekonstruiert eine angegebene eine Sammlung von Shard-Speicherorte die shardzuordnungs-Manager basierend auf Informationen über die Zuordnung in den einzelnen Shards gespeichert.</span><span class="sxs-lookup"><span data-stu-id="0b25c-175">Given a collection of shard locations, reconstructs the shard map manager based on mapping information stored in the individual shards.</span></span> <span data-ttu-id="0b25c-176">Die angegebene Shards müssen bereits in der globalen shardzuordnung registriert werden.</span><span class="sxs-lookup"><span data-stu-id="0b25c-176">The specified shards need to be registered already in the global shard map.</span></span> <span data-ttu-id="0b25c-177">Diese Methode wird nur Zuordnungen neu erstellt.</span><span class="sxs-lookup"><span data-stu-id="0b25c-177">This method only rebuilds mappings.</span></span> <span data-ttu-id="0b25c-178">Es wird nicht Shard Mitgliedschaft in der globalen shardzuordnung neu erstellt.</span><span class="sxs-lookup"><span data-stu-id="0b25c-178">It does not rebuild shard membership within the global shard map.</span></span>
            <span data-ttu-id="0b25c-179">Wenn die Informationen in den einzelnen shardzuordnungen oder inkonsistent, ist das Verhalten nicht definiert.</span><span class="sxs-lookup"><span data-stu-id="0b25c-179">If the information in the individual shard maps is or becomes inconsistent, the behavior is undefined.</span></span>
            <span data-ttu-id="0b25c-180">Keine Sperren Cross Shard vorgenommen werden sind, wenn während der Ausführung dieser Methode alle Shards inkonsistent werden, der finalen Status der globalen shardzuordnung möglicherweise beschädigt.</span><span class="sxs-lookup"><span data-stu-id="0b25c-180">No cross shard locks are taken, so if any shards become inconsistent during the execution of this method, the final state of the global shard map may be corrupt.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="0b25c-181">Beachten Sie, dass diese Methode nicht behebbaren Datenverlust führen kann.</span><span class="sxs-lookup"><span data-stu-id="0b25c-181">Note that this method can cause unrecoverable data loss.</span></span> <span data-ttu-id="0b25c-182">Stellen Sie sicher, dass Sie Sicherungen oder Kopien Ihrer Datenbanken erstellt haben, und nur mit großer Umsicht fortfahren.</span><span class="sxs-lookup"><span data-stu-id="0b25c-182">Make sure you have taken backups or copies of your databases and only then proceed with great care.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebuildMappingsOnShardMapManagerFromShards">
      <MemberSignature Language="C#" Value="public void RebuildMappingsOnShardMapManagerFromShards (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations, string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RebuildMappingsOnShardMapManagerFromShards(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations, string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.RebuildMappingsOnShardMapManagerFromShards(System.Collections.Generic.IEnumerable{Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RebuildMappingsOnShardMapManagerFromShards (shardLocations As IEnumerable(Of ShardLocation), shardMapName As String)" />
      <MemberSignature Language="F#" Value="member this.RebuildMappingsOnShardMapManagerFromShards : seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; * string -&gt; unit" Usage="recoveryManager.RebuildMappingsOnShardMapManagerFromShards (shardLocations, shardMapName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shardLocations" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt;" />
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="shardLocations"><span data-ttu-id="0b25c-183">Die Auflistung der Shard-Positionen.</span><span class="sxs-lookup"><span data-stu-id="0b25c-183">Collection of shard locations.</span></span></param>
        <param name="shardMapName"><span data-ttu-id="0b25c-184">Optionaler Name des shardzuordnung.</span><span class="sxs-lookup"><span data-stu-id="0b25c-184">Optional name of shard map.</span></span> <span data-ttu-id="0b25c-185">Wenn nicht angegeben, wird versucht, die Wiederherstellung alle shardzuordnungen für jeden Shard vorhanden.</span><span class="sxs-lookup"><span data-stu-id="0b25c-185">If omitted, will attempt to recover from all shard maps present on each shard.</span></span></param>
        <summary>
            <span data-ttu-id="0b25c-186">Rekonstruiert eine angegebene eine Sammlung von Shard-Speicherorte die shardzuordnungs-Manager basierend auf Informationen über die Zuordnung in den einzelnen Shards gespeichert.</span><span class="sxs-lookup"><span data-stu-id="0b25c-186">Given a collection of shard locations, reconstructs the shard map manager based on mapping information stored in the individual shards.</span></span> <span data-ttu-id="0b25c-187">Die angegebene Shards müssen bereits in der globalen shardzuordnung registriert werden.</span><span class="sxs-lookup"><span data-stu-id="0b25c-187">The specified shards need to be registered already in the global shard map.</span></span> <span data-ttu-id="0b25c-188">Diese Methode wird nur Zuordnungen neu erstellt.</span><span class="sxs-lookup"><span data-stu-id="0b25c-188">This method only rebuilds mappings.</span></span> <span data-ttu-id="0b25c-189">Es wird nicht Shard Mitgliedschaft in der globalen shardzuordnung neu erstellt.</span><span class="sxs-lookup"><span data-stu-id="0b25c-189">It does not rebuild shard membership within the global shard map.</span></span>
            <span data-ttu-id="0b25c-190">Wenn die Informationen in den einzelnen shardzuordnungen oder inkonsistent, ist das Verhalten nicht definiert.</span><span class="sxs-lookup"><span data-stu-id="0b25c-190">If the information in the individual shard maps is or becomes inconsistent, the behavior is undefined.</span></span>
            <span data-ttu-id="0b25c-191">Keine Sperren Cross Shard vorgenommen werden sind, wenn während der Ausführung dieser Methode alle Shards inkonsistent werden, der finalen Status der globalen shardzuordnung möglicherweise beschädigt.</span><span class="sxs-lookup"><span data-stu-id="0b25c-191">No cross shard locks are taken, so if any shards become inconsistent during the execution of this method, the final state of the global shard map may be corrupt.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="0b25c-192">Beachten Sie, dass diese Methode nicht behebbaren Datenverlust führen kann.</span><span class="sxs-lookup"><span data-stu-id="0b25c-192">Note that this method can cause unrecoverable data loss.</span></span> <span data-ttu-id="0b25c-193">Stellen Sie sicher, dass Sie Sicherungen oder Kopien Ihrer Datenbanken erstellt haben, und nur mit großer Umsicht fortfahren.</span><span class="sxs-lookup"><span data-stu-id="0b25c-193">Make sure you have taken backups or copies of your databases and only then proceed with great care.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebuildMappingsOnShardsFromShardMapManager">
      <MemberSignature Language="C#" Value="public void RebuildMappingsOnShardsFromShardMapManager (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RebuildMappingsOnShardsFromShardMapManager(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.RebuildMappingsOnShardsFromShardMapManager(System.Collections.Generic.IEnumerable{Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RebuildMappingsOnShardsFromShardMapManager (shardLocations As IEnumerable(Of ShardLocation))" />
      <MemberSignature Language="F#" Value="member this.RebuildMappingsOnShardsFromShardMapManager : seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; -&gt; unit" Usage="recoveryManager.RebuildMappingsOnShardsFromShardMapManager shardLocations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shardLocations" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt;" />
      </Parameters>
      <Docs>
        <param name="shardLocations"><span data-ttu-id="0b25c-194">Die Auflistung der Shard-Positionen.</span><span class="sxs-lookup"><span data-stu-id="0b25c-194">Collection of shard locations.</span></span></param>
        <summary>
            <span data-ttu-id="0b25c-195">Erhält eine Auflistung von Shard-Speicherorte, Basis rekonstruiert, ordnet lokalen shard, auf der gespeicherten Zuordnungsinformationen in der globalen shardzuordnung.</span><span class="sxs-lookup"><span data-stu-id="0b25c-195">Given a collection of shard locations, reconstructs local shard maps based on the mapping information stored in the global shard map.</span></span> <span data-ttu-id="0b25c-196">Die angegebene Shards müssen bereits in der globalen shardzuordnung registriert werden.</span><span class="sxs-lookup"><span data-stu-id="0b25c-196">The specified shards need to be registered already in the global shard map.</span></span> <span data-ttu-id="0b25c-197">Diese Methode wird nur Zuordnungen neu erstellt.</span><span class="sxs-lookup"><span data-stu-id="0b25c-197">This method only rebuilds mappings.</span></span> <span data-ttu-id="0b25c-198">Es wird nicht Shard Mitgliedschaft in der globalen shardzuordnung neu erstellt.</span><span class="sxs-lookup"><span data-stu-id="0b25c-198">It does not rebuild shard membership within the global shard map.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="0b25c-199">Beachten Sie, dass diese Methode nicht behebbaren Datenverlust führen kann.</span><span class="sxs-lookup"><span data-stu-id="0b25c-199">Note that this method can cause unrecoverable data loss.</span></span> <span data-ttu-id="0b25c-200">Stellen Sie sicher, dass Sie Sicherungen oder Kopien Ihrer Datenbanken erstellt haben, und nur mit großer Umsicht fortfahren.</span><span class="sxs-lookup"><span data-stu-id="0b25c-200">Make sure you have taken backups or copies of your databases and only then proceed with great care.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebuildMappingsOnShardsFromShardMapManager">
      <MemberSignature Language="C#" Value="public void RebuildMappingsOnShardsFromShardMapManager (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations, string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RebuildMappingsOnShardsFromShardMapManager(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations, string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.RebuildMappingsOnShardsFromShardMapManager(System.Collections.Generic.IEnumerable{Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RebuildMappingsOnShardsFromShardMapManager (shardLocations As IEnumerable(Of ShardLocation), shardMapName As String)" />
      <MemberSignature Language="F#" Value="member this.RebuildMappingsOnShardsFromShardMapManager : seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; * string -&gt; unit" Usage="recoveryManager.RebuildMappingsOnShardsFromShardMapManager (shardLocations, shardMapName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shardLocations" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt;" />
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="shardLocations"><span data-ttu-id="0b25c-201">Die Auflistung der Shard-Positionen.</span><span class="sxs-lookup"><span data-stu-id="0b25c-201">Collection of shard locations.</span></span></param>
        <param name="shardMapName"><span data-ttu-id="0b25c-202">Optionaler Parameter, um nach den Namen der shardzuordnung zu filtern.</span><span class="sxs-lookup"><span data-stu-id="0b25c-202">Optional parameter to filter by shard map name.</span></span> <span data-ttu-id="0b25c-203">Wenn nicht angegeben, werden alle shardzuordnungen neu erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="0b25c-203">If omitted, all shard maps will be rebuilt.</span></span></param>
        <summary>
            <span data-ttu-id="0b25c-204">Erhält eine Auflistung von Shard-Speicherorte, Basis rekonstruiert, ordnet lokalen shard, auf der gespeicherten Zuordnungsinformationen in der globalen shardzuordnung.</span><span class="sxs-lookup"><span data-stu-id="0b25c-204">Given a collection of shard locations, reconstructs local shard maps based on the mapping information stored in the global shard map.</span></span> <span data-ttu-id="0b25c-205">Die angegebene Shards müssen bereits in der globalen shardzuordnung registriert werden.</span><span class="sxs-lookup"><span data-stu-id="0b25c-205">The specified shards need to be registered already in the global shard map.</span></span> <span data-ttu-id="0b25c-206">Diese Methode wird nur Zuordnungen neu erstellt.</span><span class="sxs-lookup"><span data-stu-id="0b25c-206">This method only rebuilds mappings.</span></span> <span data-ttu-id="0b25c-207">Es wird nicht Shard Mitgliedschaft in der globalen shardzuordnung neu erstellt.</span><span class="sxs-lookup"><span data-stu-id="0b25c-207">It does not rebuild shard membership within the global shard map.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="0b25c-208">Beachten Sie, dass diese Methode nicht behebbaren Datenverlust führen kann.</span><span class="sxs-lookup"><span data-stu-id="0b25c-208">Note that this method can cause unrecoverable data loss.</span></span> <span data-ttu-id="0b25c-209">Stellen Sie sicher, dass Sie Sicherungen oder Kopien Ihrer Datenbanken erstellt haben, und nur mit großer Umsicht fortfahren.</span><span class="sxs-lookup"><span data-stu-id="0b25c-209">Make sure you have taken backups or copies of your databases and only then proceed with great care.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveMappingDifferences">
      <MemberSignature Language="C#" Value="public void ResolveMappingDifferences (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution resolution);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ResolveMappingDifferences(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution resolution) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.ResolveMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ResolveMappingDifferences (token As RecoveryToken, resolution As MappingDifferenceResolution)" />
      <MemberSignature Language="F#" Value="member this.ResolveMappingDifferences : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution -&gt; unit" Usage="recoveryManager.ResolveMappingDifferences (token, resolution)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
        <Parameter Name="resolution" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="0b25c-210">Wiederherstellungstoken Merry <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span><span class="sxs-lookup"><span data-stu-id="0b25c-210">Recovery token returned from <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span></span></param>
        <param name="resolution"><span data-ttu-id="0b25c-211">Die Auflösungsstrategie für die Auflösung verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="0b25c-211">The resolution strategy to be used for resolution.</span></span></param>
        <summary>
            <span data-ttu-id="0b25c-212">Wählt einen von der shardzuordnungen (lokal oder global) als Quelle für Wahrheit aus, und schaltet Zuordnungen auf beide synchron shardzuordnungen.</span><span class="sxs-lookup"><span data-stu-id="0b25c-212">Selects one of the shard maps (either local or global) as a source of truth and brings mappings on both shard maps in sync.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="0b25c-213">Beachten Sie, dass diese Methode nicht behebbaren Datenverlust führen kann.</span><span class="sxs-lookup"><span data-stu-id="0b25c-213">Note that this method can cause unrecoverable data loss.</span></span> <span data-ttu-id="0b25c-214">Stellen Sie sicher, dass Sie Sicherungen oder Kopien Ihrer Datenbanken erstellt haben, und nur mit großer Umsicht fortfahren.</span><span class="sxs-lookup"><span data-stu-id="0b25c-214">Make sure you have taken backups or copies of your databases and only then proceed with great care.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>