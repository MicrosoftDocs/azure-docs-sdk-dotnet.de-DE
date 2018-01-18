<Type Name="LocalEseStoreSettings" FullName="System.Fabric.LocalEseStoreSettings">
  <TypeSignature Language="C#" Value="public sealed class LocalEseStoreSettings : System.Fabric.LocalStoreSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit LocalEseStoreSettings extends System.Fabric.LocalStoreSettings" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.LocalEseStoreSettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class LocalEseStoreSettings&#xA;Inherits LocalStoreSettings" />
  <TypeSignature Language="F#" Value="type LocalEseStoreSettings = class&#xA;    inherit LocalStoreSettings" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.LocalStoreSettings</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="1fa03-101">Stellt die optionalen Einstellungen für einen lokalen ESE-Speicher dar.</span><span class="sxs-lookup"><span data-stu-id="1fa03-101">Represents the optional settings for a local ESE store.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="1fa03-102">Weitere Informationen finden Sie unter HYPERLINK "http://msdn.microsoft.com/library/gg294139 (v=exchg.10).aspx" http://msdn.microsoft.com/library/gg294139 (v=exchg.10).aspx Dokumentation zur ESE-Parameter.</span><span class="sxs-lookup"><span data-stu-id="1fa03-102">Please see  HYPERLINK "http://msdn.microsoft.com/library/gg294139(v=exchg.10).aspx" http://msdn.microsoft.com/library/gg294139(v=exchg.10).aspx for documentation on ESE parameters.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LocalEseStoreSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.LocalEseStoreSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="1fa03-103">Erstellt und initialisiert eine neue Instanz der <see cref="T:System.Fabric.LocalEseStoreSettings" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1fa03-103">Creates and initializes a new instance of the <see cref="T:System.Fabric.LocalEseStoreSettings" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompactionThresholdInMB">
      <MemberSignature Language="C#" Value="public int CompactionThresholdInMB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 CompactionThresholdInMB" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalEseStoreSettings.CompactionThresholdInMB" />
      <MemberSignature Language="VB.NET" Value="Public Property CompactionThresholdInMB As Integer" />
      <MemberSignature Language="F#" Value="member this.CompactionThresholdInMB : int with get, set" Usage="System.Fabric.LocalEseStoreSettings.CompactionThresholdInMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1fa03-104">Ruft ab oder legt einen Wert, der angibt, der minimale Dateigröße einer Datenbank für offline-Komprimierung während öffnen auftreten.</span><span class="sxs-lookup"><span data-stu-id="1fa03-104">Gets or sets a value indicating the minimum file size of a database for offline compaction to occur during open.</span></span>
            </summary>
        <value>
            <span data-ttu-id="1fa03-105">Gibt den Schwellenwert in MB an.</span><span class="sxs-lookup"><span data-stu-id="1fa03-105">Returns the threshold in MB.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabasePageSizeInKB">
      <MemberSignature Language="C#" Value="public int DatabasePageSizeInKB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DatabasePageSizeInKB" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalEseStoreSettings.DatabasePageSizeInKB" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabasePageSizeInKB As Integer" />
      <MemberSignature Language="F#" Value="member this.DatabasePageSizeInKB : int with get, set" Usage="System.Fabric.LocalEseStoreSettings.DatabasePageSizeInKB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1fa03-106">Sie ordnet direkt JET_paramDatabasePageSize auf dem lokalen ESE-Speicher.</span><span class="sxs-lookup"><span data-stu-id="1fa03-106">Maps directly to JET_paramDatabasePageSize on the local ESE store.</span></span>
            </summary>
        <value>
            <span data-ttu-id="1fa03-107">Gibt die Größe der Datenbank-Seite in KB zurück.</span><span class="sxs-lookup"><span data-stu-id="1fa03-107">Returns the database page size in KB.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="1fa03-108">Die Seitengröße für die angegebene Datenbank ist nur auf neu erstellte Datenbanken angewendet.</span><span class="sxs-lookup"><span data-stu-id="1fa03-108">The specified database page size is only applied to newly created databases.</span></span> <span data-ttu-id="1fa03-109">Vorhandene Datenbanken werden weiterhin die Seitengrößen Datenbank verwenden, denen sie mit erstellt wurden, wenn diese Einstellung unterscheidet.</span><span class="sxs-lookup"><span data-stu-id="1fa03-109">Existing databases will continue to use the database page sizes they were created with if different from this setting.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DbFolderPath">
      <MemberSignature Language="C#" Value="public string DbFolderPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DbFolderPath" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalEseStoreSettings.DbFolderPath" />
      <MemberSignature Language="VB.NET" Value="Public Property DbFolderPath As String" />
      <MemberSignature Language="F#" Value="member this.DbFolderPath : string with get, set" Usage="System.Fabric.LocalEseStoreSettings.DbFolderPath" />
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
          <para><span data-ttu-id="1fa03-110">Abrufen oder festlegen den Dateipfad, der lokalen Speicher-Dateien enthält.</span><span class="sxs-lookup"><span data-stu-id="1fa03-110">Gets or sets the file path that contains the local store files.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="1fa03-111">Der Pfad der Datei, der den lokalen Speicher-Dateien enthält.</span><span class="sxs-lookup"><span data-stu-id="1fa03-111">The file path that contains the local store files.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefragThresholdInMB">
      <MemberSignature Language="C#" Value="public int DefragThresholdInMB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DefragThresholdInMB" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalEseStoreSettings.DefragThresholdInMB" />
      <MemberSignature Language="VB.NET" Value="Public Property DefragThresholdInMB As Integer" />
      <MemberSignature Language="F#" Value="member this.DefragThresholdInMB : int with get, set" Usage="System.Fabric.LocalEseStoreSettings.DefragThresholdInMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1fa03-112">Ruft ab oder legt einen Wert, der angibt, der minimalen logischen Größe einer Datenbank für die Onlinedefragmentierung Hintergrund erfolgen.</span><span class="sxs-lookup"><span data-stu-id="1fa03-112">Gets or sets a value indicating the minimum logical size of a database for online defragmentation to occur the background.</span></span>
            </summary>
        <value>
            <span data-ttu-id="1fa03-113">Gibt den Schwellenwert in MB an.</span><span class="sxs-lookup"><span data-stu-id="1fa03-113">Returns the threshold in MB.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableIncrementalBackup">
      <MemberSignature Language="C#" Value="public bool EnableIncrementalBackup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableIncrementalBackup" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalEseStoreSettings.EnableIncrementalBackup" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableIncrementalBackup As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableIncrementalBackup : bool with get, set" Usage="System.Fabric.LocalEseStoreSettings.EnableIncrementalBackup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="1fa03-114">Ruft ab oder legt einen Wert, der angibt, ob die Funktion für inkrementelle Sicherung für die Verwendung aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="1fa03-114">Gets or sets a value indicating whether the incremental backup feature is enabled for use.</span></span></para>
        </summary>
        <value>
            <span data-ttu-id="1fa03-115">Gibt <languageKeyword>"true"</languageKeyword> Wenn inkrementeller Sicherung aktiviert, andernfalls ist <languageKeywork>"false"</languageKeywork>.</span><span class="sxs-lookup"><span data-stu-id="1fa03-115">Returns <languageKeyword>true</languageKeyword> if incremental backup is enabled; otherwise, <languageKeywork>false</languageKeywork>.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableOverwriteOnUpdate">
      <MemberSignature Language="C#" Value="public bool EnableOverwriteOnUpdate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableOverwriteOnUpdate" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalEseStoreSettings.EnableOverwriteOnUpdate" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableOverwriteOnUpdate As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableOverwriteOnUpdate : bool with get, set" Usage="System.Fabric.LocalEseStoreSettings.EnableOverwriteOnUpdate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1fa03-116">Ermöglicht das direkte Ersetzen des Werts (es werden keine Insert/Delete) während der Update-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="1fa03-116">Enables in-place replace of value (versus insert/delete) during update operation.</span></span> <span data-ttu-id="1fa03-117">Sie ordnet JET_bitSetOverwriteLV auf dem lokalen ESE-Speicher.</span><span class="sxs-lookup"><span data-stu-id="1fa03-117">Maps to JET_bitSetOverwriteLV on the local ESE store.</span></span>
            </summary>
        <value>
            <span data-ttu-id="1fa03-118">Gibt <languageKeyword>"true"</languageKeyword> Wenn überschreiben auf Update aktiviert ist, andernfalls <languageKeywork>"false"</languageKeywork>.</span><span class="sxs-lookup"><span data-stu-id="1fa03-118">Returns <languageKeyword>true</languageKeyword> if overwrite on update is enabled; otherwise, <languageKeywork>false</languageKeywork>.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="1fa03-119">Aktivieren diese Einstellung ist hilfreich in Fällen, in denen bestimmte Zugriffsmuster ESE-Datenbankdatei auf dem Datenträger vergrößert werden, obwohl die Größe der logischen gleichen bleibt verursachen können.</span><span class="sxs-lookup"><span data-stu-id="1fa03-119">Enabling this setting is useful in cases where certain access patterns can cause the ESE database file to grow on disk even though the logical data size remains same.</span></span> <span data-ttu-id="1fa03-120">Angenommen, eine große Anzahl von Transaktionen, die erste Rollback oder eine Reihe von Updates, die von einigen Transaktionen vorgenommen wurden, während andere Transaktionen geöffnet bleiben, wie Updates auftreten.</span><span class="sxs-lookup"><span data-stu-id="1fa03-120">For example, a large number of transactions getting rolled back or a series of updates made by some transactions while other transactions remain open as updates are happening.</span></span> 
            
            <span data-ttu-id="1fa03-121">Beachten Sie, dass die Aktivierung dieser Einstellung kann Version Store Verwendung und den Wert der erhöht <see cref="P:System.Fabric.LocalEseStoreSettings.MaxVerPages" /> möglicherweise erhöht werden.</span><span class="sxs-lookup"><span data-stu-id="1fa03-121">Note that enabling this setting may increase version store usage and the value of <see cref="P:System.Fabric.LocalEseStoreSettings.MaxVerPages" /> may need to be increased.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="IntrinsicValueThresholdInBytes">
      <MemberSignature Language="C#" Value="public int IntrinsicValueThresholdInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 IntrinsicValueThresholdInBytes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalEseStoreSettings.IntrinsicValueThresholdInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property IntrinsicValueThresholdInBytes As Integer" />
      <MemberSignature Language="F#" Value="member this.IntrinsicValueThresholdInBytes : int with get, set" Usage="System.Fabric.LocalEseStoreSettings.IntrinsicValueThresholdInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1fa03-122">Ruft ab oder legt einen Wert, der angibt, der Maximalwert-Größe, die Updates mit dem Flag JET_bitSetIntrinsicLV erfolgt.</span><span class="sxs-lookup"><span data-stu-id="1fa03-122">Gets or sets a value indicating the maximum value size at which updates will occur with the JET_bitSetIntrinsicLV flag.</span></span> <span data-ttu-id="1fa03-123">Diese Einstellung auf einen nicht positiven Wert festgelegt, wird das ESE-Standard von 1024 Bytes verwenden.</span><span class="sxs-lookup"><span data-stu-id="1fa03-123">Setting this to a non-positive value will use the ESE default of 1024 bytes.</span></span>
            </summary>
        <value>
            <span data-ttu-id="1fa03-124">Gibt den Schwellenwert in Bytes zurück.</span><span class="sxs-lookup"><span data-stu-id="1fa03-124">Returns the threshold in bytes.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadFrom">
      <MemberSignature Language="C#" Value="public static System.Fabric.LocalEseStoreSettings LoadFrom (System.Fabric.CodePackageActivationContext codePackageActivationContext, string configPackageName, string sectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.LocalEseStoreSettings LoadFrom(class System.Fabric.CodePackageActivationContext codePackageActivationContext, string configPackageName, string sectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.LocalEseStoreSettings.LoadFrom(System.Fabric.CodePackageActivationContext,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member LoadFrom : System.Fabric.CodePackageActivationContext * string * string -&gt; System.Fabric.LocalEseStoreSettings" Usage="System.Fabric.LocalEseStoreSettings.LoadFrom (codePackageActivationContext, configPackageName, sectionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.LocalEseStoreSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="codePackageActivationContext" Type="System.Fabric.CodePackageActivationContext" />
        <Parameter Name="configPackageName" Type="System.String" />
        <Parameter Name="sectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="codePackageActivationContext"><span data-ttu-id="1fa03-125">Der Aktivierungskontext, unter dem dieser Code ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="1fa03-125">The activation context under which this code is running.</span></span> <span data-ttu-id="1fa03-126">Aus abgerufenen <see cref="T:System.Fabric.FabricRuntime" />.</span><span class="sxs-lookup"><span data-stu-id="1fa03-126">Retrieved from <see cref="T:System.Fabric.FabricRuntime" />.</span></span></param>
        <param name="configPackageName"><span data-ttu-id="1fa03-127">Der Name des Konfigurationspakets (angegeben in der Dienstmanifest), enthält die Einstellungen, die geladen werden.</span><span class="sxs-lookup"><span data-stu-id="1fa03-127">The name of the configuration package (specified in the Service Manifest) containing the settings to load.</span></span></param>
        <param name="sectionName"><span data-ttu-id="1fa03-128">Der Name des Abschnitts in "Settings.xml" im Paket angegebene Konfiguration mit den Einstellungen geladen werden soll.</span><span class="sxs-lookup"><span data-stu-id="1fa03-128">The name of the section in Settings.xml within the specified configuration package containing the settings to load.</span></span></param>
        <summary>
            <span data-ttu-id="1fa03-129">Bequeme Methode zum Erstellen einer Instanz dieser Klasse initialisiert mit Eigenschaftswerten, die im Anwendungspaket für die Konfiguration geladen.</span><span class="sxs-lookup"><span data-stu-id="1fa03-129">Convenience method to create an instance of this class initialized with property values loaded from the application configuration package.</span></span>
            </summary>
        <returns><span data-ttu-id="1fa03-130">Das initialisierte Einstellungsobjekt.</span><span class="sxs-lookup"><span data-stu-id="1fa03-130">The initialized settings object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogBufferSizeInKB">
      <MemberSignature Language="C#" Value="public int LogBufferSizeInKB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LogBufferSizeInKB" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalEseStoreSettings.LogBufferSizeInKB" />
      <MemberSignature Language="VB.NET" Value="Public Property LogBufferSizeInKB As Integer" />
      <MemberSignature Language="F#" Value="member this.LogBufferSizeInKB : int with get, set" Usage="System.Fabric.LocalEseStoreSettings.LogBufferSizeInKB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="1fa03-131">Sie ordnet JET_paramLogBuffers auf dem lokalen ESE-Speicher.</span><span class="sxs-lookup"><span data-stu-id="1fa03-131">Maps to JET_paramLogBuffers on the local ESE store.</span></span> <span data-ttu-id="1fa03-132">Es ist eine Konvertierung von KB auf 512 Bytes (Volume Sektorgröße) in der Zuordnung.</span><span class="sxs-lookup"><span data-stu-id="1fa03-132">There is a conversion from KB to 512 bytes (volume sector size) in the mapping.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="1fa03-133">Die Protokollpuffergröße in KB.</span><span class="sxs-lookup"><span data-stu-id="1fa03-133">The log buffer size in KB.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogFileSizeInKB">
      <MemberSignature Language="C#" Value="public int LogFileSizeInKB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LogFileSizeInKB" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalEseStoreSettings.LogFileSizeInKB" />
      <MemberSignature Language="VB.NET" Value="Public Property LogFileSizeInKB As Integer" />
      <MemberSignature Language="F#" Value="member this.LogFileSizeInKB : int with get, set" Usage="System.Fabric.LocalEseStoreSettings.LogFileSizeInKB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="1fa03-134">Sie ordnet direkt JET_paramLogFileSize auf dem lokalen ESE-Speicher.</span><span class="sxs-lookup"><span data-stu-id="1fa03-134">Maps directly to JET_paramLogFileSize on the local ESE store.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="1fa03-135">Die Protokolldateigröße in KB.</span><span class="sxs-lookup"><span data-stu-id="1fa03-135">The log file size in KB.</span></span></para>
        </value>
        <remarks>
            <span data-ttu-id="1fa03-136">Die Größe der angegebenen Protokolldatei wird nur auf neu erstellte Datenbanken angewendet.</span><span class="sxs-lookup"><span data-stu-id="1fa03-136">The specified log file size is only applied to newly created databases.</span></span> <span data-ttu-id="1fa03-137">Vorhandene Datenbanken werden weiterhin die Größe der Protokolldateien zu verwenden, denen sie mit erstellt wurden, wenn diese Einstellung unterscheidet.</span><span class="sxs-lookup"><span data-stu-id="1fa03-137">Existing databases will continue to use the log file sizes they were created with if different from this setting.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxAsyncCommitDelay">
      <MemberSignature Language="C#" Value="public TimeSpan MaxAsyncCommitDelay { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaxAsyncCommitDelay" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalEseStoreSettings.MaxAsyncCommitDelay" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxAsyncCommitDelay As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaxAsyncCommitDelay : TimeSpan with get, set" Usage="System.Fabric.LocalEseStoreSettings.MaxAsyncCommitDelay" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="1fa03-138">Wird direkt an den CmsecDurableCommit-Parameter auf die JetCommitTransaction2() ESE-API-Aufrufe, wenn lokale Commits ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="1fa03-138">Maps directly to the cmsecDurableCommit parameter on the JetCommitTransaction2() ESE API calls when local commits are performed.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="1fa03-139">Die permanente verzögerter Commit-Dauer.</span><span class="sxs-lookup"><span data-stu-id="1fa03-139">The durable lazy commit duration.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxCacheSizeInMB">
      <MemberSignature Language="C#" Value="public int MaxCacheSizeInMB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxCacheSizeInMB" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalEseStoreSettings.MaxCacheSizeInMB" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxCacheSizeInMB As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxCacheSizeInMB : int with get, set" Usage="System.Fabric.LocalEseStoreSettings.MaxCacheSizeInMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1fa03-140">Sie ordnet direkt JET_paramCacheSizeMax auf dem lokalen ESE-Speicher.</span><span class="sxs-lookup"><span data-stu-id="1fa03-140">Maps directly to JET_paramCacheSizeMax on the local ESE store.</span></span>
            </summary>
        <value>
            <span data-ttu-id="1fa03-141">Gibt die maximale Cachegröße in MB an.</span><span class="sxs-lookup"><span data-stu-id="1fa03-141">Returns the maximum database cache size in MB.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxCursors">
      <MemberSignature Language="C#" Value="public int MaxCursors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxCursors" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalEseStoreSettings.MaxCursors" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxCursors As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxCursors : int with get, set" Usage="System.Fabric.LocalEseStoreSettings.MaxCursors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="1fa03-142">Sie ordnet direkt JET_paramMaxCursors auf dem lokalen ESE-Speicher.</span><span class="sxs-lookup"><span data-stu-id="1fa03-142">Maps directly to JET_paramMaxCursors on the local ESE store.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="1fa03-143">Die maximale Anzahl der zulässigen Datenbank Cursor.</span><span class="sxs-lookup"><span data-stu-id="1fa03-143">The maximum number of allowed database cursors.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDefragFrequencyInMinutes">
      <MemberSignature Language="C#" Value="public int MaxDefragFrequencyInMinutes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxDefragFrequencyInMinutes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalEseStoreSettings.MaxDefragFrequencyInMinutes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDefragFrequencyInMinutes As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxDefragFrequencyInMinutes : int with get, set" Usage="System.Fabric.LocalEseStoreSettings.MaxDefragFrequencyInMinutes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1fa03-144">Ruft ab oder legt einen Wert, der angibt, der Häufigkeit der periodischen Onlinedefragmentierung fest.</span><span class="sxs-lookup"><span data-stu-id="1fa03-144">Gets or sets a value indicating the frequency of periodic online defragmentation.</span></span>
            </summary>
        <value>
            <span data-ttu-id="1fa03-145">Gibt die Häufigkeit in Minuten zurück.</span><span class="sxs-lookup"><span data-stu-id="1fa03-145">Returns the frequency in minutes.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxVerPages">
      <MemberSignature Language="C#" Value="public int MaxVerPages { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxVerPages" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalEseStoreSettings.MaxVerPages" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxVerPages As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxVerPages : int with get, set" Usage="System.Fabric.LocalEseStoreSettings.MaxVerPages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="1fa03-146">Sie ordnet direkt JET_paramMaxVerPages auf dem lokalen ESE-Speicher.</span><span class="sxs-lookup"><span data-stu-id="1fa03-146">Maps directly to JET_paramMaxVerPages on the local ESE store.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="1fa03-147">Die maximale Anzahl der Seiten, die zulässige Version.</span><span class="sxs-lookup"><span data-stu-id="1fa03-147">The maximum number of allowed version pages.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>