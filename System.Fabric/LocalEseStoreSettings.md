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
      <para>Stellt die optionalen Einstellungen für einen lokalen ESE-Speicher dar.</para>
    </summary>
    <remarks>
      <para>Weitere Informationen finden Sie unter HYPERLINK "http://msdn.microsoft.com/library/gg294139 (v=exchg.10).aspx" http://msdn.microsoft.com/library/gg294139 (v=exchg.10).aspx Dokumentation zur ESE-Parameter.</para>
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
          <para>Erstellt und initialisiert eine neue Instanz der <see cref="T:System.Fabric.LocalEseStoreSettings" />-Klasse.</para>
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
            Ruft ab oder legt einen Wert, der angibt, der minimale Dateigröße einer Datenbank für offline-Komprimierung während öffnen auftreten.
            </summary>
        <value>
            Gibt den Schwellenwert in MB an.
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
            Sie ordnet direkt JET_paramDatabasePageSize auf dem lokalen ESE-Speicher.
            </summary>
        <value>
            Gibt die Größe der Datenbank-Seite in KB zurück.
            </value>
        <remarks>
            Die Seitengröße für die angegebene Datenbank ist nur auf neu erstellte Datenbanken angewendet. Vorhandene Datenbanken werden weiterhin die Seitengrößen Datenbank verwenden, denen sie mit erstellt wurden, wenn diese Einstellung unterscheidet.
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
          <para>Abrufen oder festlegen den Dateipfad, der lokalen Speicher-Dateien enthält.</para>
        </summary>
        <value>
          <para>Der Pfad der Datei, der den lokalen Speicher-Dateien enthält.</para>
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
            Ruft ab oder legt einen Wert, der angibt, der minimalen logischen Größe einer Datenbank für die Onlinedefragmentierung Hintergrund erfolgen.
            </summary>
        <value>
            Gibt den Schwellenwert in MB an.
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
          <para>Ruft ab oder legt einen Wert, der angibt, ob die Funktion für inkrementelle Sicherung für die Verwendung aktiviert ist.</para>
        </summary>
        <value>
            Gibt <languageKeyword>"true"</languageKeyword> Wenn inkrementeller Sicherung aktiviert, andernfalls ist <languageKeywork>"false"</languageKeywork>.
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
            Ermöglicht das direkte Ersetzen des Werts (es werden keine Insert/Delete) während der Update-Vorgang. Sie ordnet JET_bitSetOverwriteLV auf dem lokalen ESE-Speicher.
            </summary>
        <value>
            Gibt <languageKeyword>"true"</languageKeyword> Wenn überschreiben auf Update aktiviert ist, andernfalls <languageKeywork>"false"</languageKeywork>.
            </value>
        <remarks>
            Aktivieren diese Einstellung ist hilfreich in Fällen, in denen bestimmte Zugriffsmuster ESE-Datenbankdatei auf dem Datenträger vergrößert werden, obwohl die Größe der logischen gleichen bleibt verursachen können. Angenommen, eine große Anzahl von Transaktionen, die erste Rollback oder eine Reihe von Updates, die von einigen Transaktionen vorgenommen wurden, während andere Transaktionen geöffnet bleiben, wie Updates auftreten. 
            
            Beachten Sie, dass die Aktivierung dieser Einstellung kann Version Store Verwendung und den Wert der erhöht <see cref="P:System.Fabric.LocalEseStoreSettings.MaxVerPages" /> möglicherweise erhöht werden.
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
            Ruft ab oder legt einen Wert, der angibt, der Maximalwert-Größe, die Updates mit dem Flag JET_bitSetIntrinsicLV erfolgt. Diese Einstellung auf einen nicht positiven Wert festgelegt, wird das ESE-Standard von 1024 Bytes verwenden.
            </summary>
        <value>
            Gibt den Schwellenwert in Bytes zurück.
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
        <param name="codePackageActivationContext">Der Aktivierungskontext, unter dem dieser Code ausgeführt wird. Aus abgerufenen <see cref="T:System.Fabric.FabricRuntime" />.</param>
        <param name="configPackageName">Der Name des Konfigurationspakets (angegeben in der Dienstmanifest), enthält die Einstellungen, die geladen werden.</param>
        <param name="sectionName">Der Name des Abschnitts in "Settings.xml" im Paket angegebene Konfiguration mit den Einstellungen geladen werden soll.</param>
        <summary>
            Bequeme Methode zum Erstellen einer Instanz dieser Klasse initialisiert mit Eigenschaftswerten, die im Anwendungspaket für die Konfiguration geladen.
            </summary>
        <returns>Das initialisierte Einstellungsobjekt.</returns>
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
          <para>Sie ordnet JET_paramLogBuffers auf dem lokalen ESE-Speicher. Es ist eine Konvertierung von KB auf 512 Bytes (Volume Sektorgröße) in der Zuordnung.</para>
        </summary>
        <value>
          <para>Die Protokollpuffergröße in KB.</para>
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
          <para>Sie ordnet direkt JET_paramLogFileSize auf dem lokalen ESE-Speicher.
            </para>
        </summary>
        <value>
          <para>Die Protokolldateigröße in KB.</para>
        </value>
        <remarks>
            Die Größe der angegebenen Protokolldatei wird nur auf neu erstellte Datenbanken angewendet. Vorhandene Datenbanken werden weiterhin die Größe der Protokolldateien zu verwenden, denen sie mit erstellt wurden, wenn diese Einstellung unterscheidet.
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
          <para>Wird direkt an den CmsecDurableCommit-Parameter auf die JetCommitTransaction2() ESE-API-Aufrufe, wenn lokale Commits ausgeführt werden.
            </para>
        </summary>
        <value>
          <para>Die permanente verzögerter Commit-Dauer.</para>
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
            Sie ordnet direkt JET_paramCacheSizeMax auf dem lokalen ESE-Speicher.
            </summary>
        <value>
            Gibt die maximale Cachegröße in MB an.
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
          <para>Sie ordnet direkt JET_paramMaxCursors auf dem lokalen ESE-Speicher.
            </para>
        </summary>
        <value>
          <para>Die maximale Anzahl der zulässigen Datenbank Cursor.</para>
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
            Ruft ab oder legt einen Wert, der angibt, der Häufigkeit der periodischen Onlinedefragmentierung fest.
            </summary>
        <value>
            Gibt die Häufigkeit in Minuten zurück.
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
          <para>Sie ordnet direkt JET_paramMaxVerPages auf dem lokalen ESE-Speicher.
            </para>
        </summary>
        <value>
          <para>Die maximale Anzahl der Seiten, die zulässige Version.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>