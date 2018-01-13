<Type Name="ReliableStateManagerReplicatorSettings" FullName="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings">
  <TypeSignature Language="C#" Value="public class ReliableStateManagerReplicatorSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ReliableStateManagerReplicatorSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class ReliableStateManagerReplicatorSettings" />
  <TypeSignature Language="F#" Value="type ReliableStateManagerReplicatorSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Einstellungen, die den Replikator konfigurieren
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReliableStateManagerReplicatorSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchAcknowledgementInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; BatchAcknowledgementInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; BatchAcknowledgementInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.BatchAcknowledgementInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property BatchAcknowledgementInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.BatchAcknowledgementInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.BatchAcknowledgementInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Zeitspanne, die der Replikator nach dem Empfang eines Vorgangs vor dem Zurücksenden einer Bestätigung wartet.
            Der Standardwert beträgt 5 Millisekunden.
            </summary>
        <value>Das Intervall für den Batch-Bestätigung.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckpointThresholdInMB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; CheckpointThresholdInMB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; CheckpointThresholdInMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.CheckpointThresholdInMB" />
      <MemberSignature Language="VB.NET" Value="Public Property CheckpointThresholdInMB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.CheckpointThresholdInMB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.CheckpointThresholdInMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Prüfpunkt-Schwellenwert fest. Ein Prüfpunkt wird initiiert, wenn die Protokollnutzung diesen Wert überschreitet.
            Standardwert ist 50.
            Die Einheit ist MB.
            </summary>
        <value>Der Prüfpunkt-Schwellenwert.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="reliableStateManagerReplicatorSettings.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">
            Zu überprüfende Objekt.
            </param>
        <summary>
            Bestimmt, ob die angegebenen ReplicatorSettings mit dem aktuellen Objekt identisch ist.
            </summary>
        <returns>
            Die <see cref="T:System.Boolean" />.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="reliableStateManagerReplicatorSettings.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Fungiert für diesen Typ als eine Hashfunktion.
            </summary>
        <returns>
            Die <see cref="T:System.Int32" /> , die den Hashcode darstellt.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitialCopyQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; InitialCopyQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; InitialCopyQueueSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.InitialCopyQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property InitialCopyQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.InitialCopyQueueSize : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.InitialCopyQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die ursprüngliche Größe der Vorgangswarteschlange Kopie innerhalb der Replicator die Kopiervorgänge enthält.
            Standardwert ist 64.
            Der Wert ist die Anzahl der Vorgänge in der Warteschlange der kopieren-Vorgang. Eine Potenz von 2 muss sein.
            </summary>
        <value>Die Warteschlangengröße Erstkopie.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitialPrimaryReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; InitialPrimaryReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; InitialPrimaryReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.InitialPrimaryReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property InitialPrimaryReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.InitialPrimaryReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.InitialPrimaryReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Größe der primären Erstreplikation.
            Standardwert ist 64.
            Der Wert ist die Anzahl der Vorgänge in der Warteschlange der primären Replikation. Eine Potenz von 2 muss sein.
            </summary>
        <value>Die Warteschlangengröße des ersten primären Replikation.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitialSecondaryReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; InitialSecondaryReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; InitialSecondaryReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.InitialSecondaryReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property InitialSecondaryReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.InitialSecondaryReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.InitialSecondaryReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert die Warteschlangengröße sekundären Erstreplikation.
            Standardwert ist 64.
            Der Wert ist die Anzahl der Vorgänge in der sekundären Replikationswarteschlange. Eine Potenz von 2 muss sein.
            </summary>
        <value>Die Warteschlangengröße sekundären Erstreplikation.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxAccumulatedBackupLogSizeInMB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxAccumulatedBackupLogSizeInMB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxAccumulatedBackupLogSizeInMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxAccumulatedBackupLogSizeInMB" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxAccumulatedBackupLogSizeInMB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxAccumulatedBackupLogSizeInMB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxAccumulatedBackupLogSizeInMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Größe für eine kumulierte Sicherungsprotokoll für Sicherungen. Eine inkrementelle Sicherung Anforderungen schlägt fehl, wenn die Sicherungsprotokolle, die von der Anforderung generiert bewirkt, dass die Gesamtmenge der Protokolle angesammelt einschließlich der letzten vollständigen Sicherung um MaxAccumulatedBackupLogSizeInMB größer werden.
            In einem solchen Fall muss der Benutzer eine vollständige Sicherung durchführen.
            Standardwert ist 800.
            Die Einheit ist MB.
            </summary>
        <value>Der größten Wert kumuliert Sicherungsprotokoll Größe in MB an.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxCopyQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxCopyQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxCopyQueueSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxCopyQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxCopyQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxCopyQueueSize : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxCopyQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Größe der Warteschlange Vorgang Kopie innerhalb Replikator, die Kopiervorgänge enthält.
            Standardwert ist 1024.
            Der Wert ist die maximale Anzahl von Vorgängen in der Warteschlange der kopieren-Vorgang. Eine Potenz von 2 muss sein.
            </summary>
        <value>Die Warteschlangengröße max kopieren.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxMetadataSizeInKB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxMetadataSizeInKB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxMetadataSizeInKB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxMetadataSizeInKB" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxMetadataSizeInKB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxMetadataSizeInKB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxMetadataSizeInKB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest die Menge des Speicherplatzes für zusätzliche persistenten Speicher reserviert der Replikator in Kilobyte angegeben, die dieses Replikat zugeordnet ist. Dieser Wert muss ein Vielfaches von 4 sein.
            Der Standardwert ist 4. Die Einheit ist KB.
            </summary>
        <value>Die Metadatengröße des Max.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPrimaryReplicationQueueMemorySize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxPrimaryReplicationQueueMemorySize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxPrimaryReplicationQueueMemorySize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxPrimaryReplicationQueueMemorySize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPrimaryReplicationQueueMemorySize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxPrimaryReplicationQueueMemorySize : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxPrimaryReplicationQueueMemorySize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Warteschlangengröße des Arbeitsspeichers max primären Replikation.
            Standardwert ist 0, d. h., es gibt keine Einschränkung Arbeitsspeicher.
            Die Einheit ist Bytes.
            </summary>
        <value>Die Speichergröße für den maximalen primäre Replikation Warteschlange.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPrimaryReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxPrimaryReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxPrimaryReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxPrimaryReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPrimaryReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxPrimaryReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxPrimaryReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Warteschlangengröße max primären Replikation.
            Standardwert ist 1024.
            Der Wert ist die maximale Anzahl von Vorgängen in der Warteschlange der primären Replikation. Eine Potenz von 2 muss sein.
            </summary>
        <value>Die Warteschlangengröße max primären Replikation.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRecordSizeInKB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxRecordSizeInKB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxRecordSizeInKB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxRecordSizeInKB" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxRecordSizeInKB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxRecordSizeInKB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxRecordSizeInKB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die größte Datensatzgröße auf die der Replikator angegebenen in KB für das Protokoll schreiben kann, die dieses Replikat zugeordnet ist. Dieser Wert muss ein Vielfaches von 4 und größer als oder gleich 128 sein.
            Der Standardwert ist 1024. Die Einheit ist KB.
            </summary>
        <value>Die maximale Datensatzgröße.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReplicationMessageSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxReplicationMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxReplicationMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxReplicationMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReplicationMessageSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxReplicationMessageSize : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxReplicationMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Größe der max-Replikation.
            Standardwert ist 50MB.
            Die Einheit ist Bytes.
            </summary>
        <value>Die Nachrichtengröße des max-Replikation.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSecondaryReplicationQueueMemorySize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxSecondaryReplicationQueueMemorySize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxSecondaryReplicationQueueMemorySize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxSecondaryReplicationQueueMemorySize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSecondaryReplicationQueueMemorySize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxSecondaryReplicationQueueMemorySize : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxSecondaryReplicationQueueMemorySize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Warteschlangengröße des Arbeitsspeichers max sekundären Replikation.
            Standardwert ist 0, d. h., es gibt keine Einschränkung Arbeitsspeicher.
            Die Einheit ist Bytes.
            </summary>
        <value>Die Warteschlangengröße max sekundäre Replikation.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSecondaryReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxSecondaryReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxSecondaryReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxSecondaryReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSecondaryReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxSecondaryReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxSecondaryReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Warteschlangengröße max sekundäre Replikation.
            Standardwert ist 2048.
            Der Wert ist die maximale Anzahl von Vorgängen in der sekundären Replikationswarteschlange. Eine Potenz von 2 muss sein.
            </summary>
        <value>Die Warteschlangengröße max sekundäre Replikation.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxStreamSizeInMB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxStreamSizeInMB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxStreamSizeInMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxStreamSizeInMB" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxStreamSizeInMB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxStreamSizeInMB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxStreamSizeInMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Veraltet
            </summary>
        <value>Die maximale Streamgröße.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxWriteQueueDepthInKB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxWriteQueueDepthInKB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxWriteQueueDepthInKB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxWriteQueueDepthInKB" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxWriteQueueDepthInKB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxWriteQueueDepthInKB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxWriteQueueDepthInKB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Schreib-Warteschlangentiefe, die die zentrale Protokollierung entsprechend den Angaben in KB für das Protokoll verwenden können, die dieses Replikat zugeordnet ist. Dieser Wert ist die maximale Anzahl von Bytes, die während der Updates für die zentrale Protokollierung ausstehend sein können. Der Wert kann 0 sein, damit die zentrale Protokollierung einen geeigneten Wert berechnet, oder ein Vielfaches von 4.
            Der Standardwert ist 0.
            Die Einheit ist KB.
            </summary>
        <value>Die maximalen Warteschlangentiefe geschrieben werden.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinLogSizeInMB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MinLogSizeInMB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MinLogSizeInMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MinLogSizeInMB" />
      <MemberSignature Language="VB.NET" Value="Public Property MinLogSizeInMB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MinLogSizeInMB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MinLogSizeInMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die minimale Größe. Durch das Abschneiden wird nicht initialisiert werden, wenn sie die Größe des Protokolls zu unter diesen Wert verringern würde.
            Standardwert ist 0.
            </summary>
        <value>Die minimale Größe.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OptimizeForLocalSSD">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; OptimizeForLocalSSD { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; OptimizeForLocalSSD" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.OptimizeForLocalSSD" />
      <MemberSignature Language="VB.NET" Value="Public Property OptimizeForLocalSSD As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.OptimizeForLocalSSD : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.OptimizeForLocalSSD" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Veraltet
            </summary>
        <value>Wenn die OptimizeForLocalSSD-Option aktiviert ist.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OptimizeLogForLowerDiskUsage">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; OptimizeLogForLowerDiskUsage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; OptimizeLogForLowerDiskUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.OptimizeLogForLowerDiskUsage" />
      <MemberSignature Language="VB.NET" Value="Public Property OptimizeLogForLowerDiskUsage As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.OptimizeLogForLowerDiskUsage : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.OptimizeLogForLowerDiskUsage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ein Flag fest, wenn "true" gibt an, dass das Protokoll auf eine Weise optimieren soll, in denen weniger Speicherplatz für das Protokoll auf Kosten der Leistung von e/a verwendet wird. Wenn "false" wird das Protokoll mehr Speicherplatz verwenden jedoch bieten eine bessere e/a-Leistung.
            Standardwert ist "true".
            </summary>
        <value>Wenn die OptimizeLogForLowerDiskUsage-Option aktiviert ist.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicatorAddress">
      <MemberSignature Language="C#" Value="public string ReplicatorAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicatorAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.ReplicatorAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicatorAddress As String" />
      <MemberSignature Language="F#" Value="member this.ReplicatorAddress : string with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.ReplicatorAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Adresse in der {Ip}: {Port}-Format, die bei der Kommunikation mit anderen Replikatoren dieser Replikator verwenden.
            Der Standardwert ist "Localhost:0", die einen dynamischen Port-Nummer in die Laufzeit auswählt.
            Wenn Replikator innerhalb eines Containers ausgeführt wird, sollten Sie versuchen, das Einrichten <see cref="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.ReplicatorListenAddress" /> und <see cref="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.ReplicatorPublishAddress" />.
            </summary>
        <value>Die Adresse Replikator.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicatorListenAddress">
      <MemberSignature Language="C#" Value="public string ReplicatorListenAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicatorListenAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.ReplicatorListenAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicatorListenAddress As String" />
      <MemberSignature Language="F#" Value="member this.ReplicatorListenAddress : string with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.ReplicatorListenAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Adresse in der {Ip}: {Port}-Format, die diese Replikator zum Empfangen von Informationen aus anderen Replikatoren verwenden.
            Der Standardwert ist "Localhost:0", die einen dynamischen Port-Nummer in die Laufzeit auswählt.
            {Ip} Teil der abhöradresse abgerufen werden kann, aus <see cref="P:System.Fabric.CodePackageActivationContext.ServiceListenAddress" />.
            </summary>
        <value>Die Adresse Replikator.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicatorPublishAddress">
      <MemberSignature Language="C#" Value="public string ReplicatorPublishAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicatorPublishAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.ReplicatorPublishAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicatorPublishAddress As String" />
      <MemberSignature Language="F#" Value="member this.ReplicatorPublishAddress : string with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.ReplicatorPublishAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Adresse in der {Ip}: {Port}-Format, die diese Replikator zum Senden von Informationen an andere Replikatoren verwenden.
            Der Standardwert ist "Localhost:0", die einen dynamischen Port-Nummer in die Laufzeit auswählt.
            {Ip} Teil der Publish-Adresse abgerufen werden kann, aus <see cref="P:System.Fabric.CodePackageActivationContext.ServicePublishAddress" />.
            </summary>
        <value>Die Adresse Replikator.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; RetryInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; RetryInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.RetryInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.RetryInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.RetryInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, wie lange der Replikator wartet, nachdem er überträgt eine Nachricht vom primären auf die sekundäre Datenbank für die sekundäre Datenbank zu bestätigen, dass er die Nachricht empfangen hat.
            Der Standardwert ist 5 Sekunden.
            </summary>
        <value>Das Wiederholungsintervall.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryClearAcknowledgedOperations">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; SecondaryClearAcknowledgedOperations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; SecondaryClearAcknowledgedOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.SecondaryClearAcknowledgedOperations" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryClearAcknowledgedOperations As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SecondaryClearAcknowledgedOperations : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.SecondaryClearAcknowledgedOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ein Flag fest, wenn "true" gibt an, sekundären Replikator sollten die Warteschlange im Arbeitsspeicher deaktivieren, nachdem bestätigt die Vorgänge mit dem primären Replikat (nachdem Sie geleert werden, die Vorgänge auf dem Datenträger).
            Der Standardwert ist „false“.
            Einstellungen für diese Option, um "TRUE" kann dazu führen, zusätzliche Datenträger-Lesevorgänge auf dem neuen primären beim Sichern von Replikaten nach einem Failover abfangen.
            </summary>
        <value>Wenn die SecondaryClearAcknowledgedOperations-Option aktiviert ist.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityCredentials">
      <MemberSignature Language="C#" Value="public System.Fabric.SecurityCredentials SecurityCredentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.SecurityCredentials SecurityCredentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.SecurityCredentials" />
      <MemberSignature Language="VB.NET" Value="Public Property SecurityCredentials As SecurityCredentials" />
      <MemberSignature Language="F#" Value="member this.SecurityCredentials : System.Fabric.SecurityCredentials with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.SecurityCredentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SecurityCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anmeldeinformationen für das Sichern des Datenverkehrs zwischen Replikatoren.
            </summary>
        <value>Die Anmeldeinformationen.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedLogId">
      <MemberSignature Language="C#" Value="public string SharedLogId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedLogId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.SharedLogId" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedLogId As String" />
      <MemberSignature Language="F#" Value="member this.SharedLogId : string with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.SharedLogId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den GUID-Bezeichner für den Protokoll-Container, der von einer Anzahl der Replikate auf dem Windows Fabric-Knoten einschließlich hindurchscheinen gemeinsam verwendet wird.
            Standardwert ist "" die der Replikator zum Verwenden der globalen freigegebenen Protokolldatei für den Knoten verursacht.
            </summary>
        <value>Die Id des freigegebenen Protokoll.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedLogPath">
      <MemberSignature Language="C#" Value="public string SharedLogPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedLogPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.SharedLogPath" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedLogPath As String" />
      <MemberSignature Language="F#" Value="member this.SharedLogPath : string with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.SharedLogPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den vollständigen Pfadnamen für den Protokoll-Container, der von einer Anzahl der Replikate auf dem Knoten, einschließlich dieser Datei gemeinsam verwendet wird.
            Standardwert ist "" die der Replikator zum Verwenden der globalen freigegebenen Protokolldatei für den Knoten verursacht.
            </summary>
        <value>Der Pfad des freigegebenen Protokolls.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SlowApiMonitoringDuration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; SlowApiMonitoringDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; SlowApiMonitoringDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.SlowApiMonitoringDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property SlowApiMonitoringDuration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.SlowApiMonitoringDuration : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.SlowApiMonitoringDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Das Intervall, nach dem Replikator Integritätsbericht Warnung sendet, dass die API nur langsam wird und länger als die erwartete Dauer dauert, festgelegt.
            Standardwert ist 5 Minuten.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThrottlingThresholdFactor">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ThrottlingThresholdFactor { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ThrottlingThresholdFactor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.ThrottlingThresholdFactor" />
      <MemberSignature Language="VB.NET" Value="Public Property ThrottlingThresholdFactor As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ThrottlingThresholdFactor : Nullable&lt;int&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.ThrottlingThresholdFactor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Schwellenwertfaktor für die Drosselung. Einschränkung, wird initiiert werden, wenn die Verwendung des diesen Wert überschreitet das Zeitlimit MinLogSizeInMB.
            Standardwert ist 3.
            </summary>
        <value>Den drosselungsschwellenwert.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="reliableStateManagerReplicatorSettings.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt eine Zeichenfolge zurück, die das aktuelle Objekt darstellt.
            </summary>
        <returns>
            Die <see cref="T:System.String" />.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TruncationThresholdFactor">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TruncationThresholdFactor { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TruncationThresholdFactor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.TruncationThresholdFactor" />
      <MemberSignature Language="VB.NET" Value="Public Property TruncationThresholdFactor As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TruncationThresholdFactor : Nullable&lt;int&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.TruncationThresholdFactor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Faktor für die Kürzung Schwellenwert. Durch das Abschneiden wird initiiert, wenn die Verwendung des diesen Wert überschreitet das Zeitlimit MinLogSizeInMB.
            Standardwert ist 2.
            </summary>
        <value>Der Schwellenwert abgeschnitten.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>