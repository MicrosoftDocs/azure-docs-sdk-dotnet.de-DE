<Type Name="TransferParameters" FullName="Microsoft.Azure.Management.DataLake.Store.TransferParameters">
  <TypeSignature Language="C#" Value="public class TransferParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransferParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.TransferParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class TransferParameters" />
  <TypeSignature Language="F#" Value="type TransferParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt die Parameter für die DataLakeStoreTransferClient.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferParameters (string inputFilePath, string targetStreamPath, string accountName, int perFileThreadCount = -1, int concurrentFileCount = -1, bool isOverwrite = false, bool isResume = false, bool isBinary = true, bool isRecursive = false, bool isDownload = false, long maxSegmentLength = 268435456, string localMetadataLocation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string inputFilePath, string targetStreamPath, string accountName, int32 perFileThreadCount, int32 concurrentFileCount, bool isOverwrite, bool isResume, bool isBinary, bool isRecursive, bool isDownload, int64 maxSegmentLength, string localMetadataLocation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TransferParameters.#ctor(System.String,System.String,System.String,System.Int32,System.Int32,System.Boolean,System.Boolean,System.Boolean,System.Boolean,System.Boolean,System.Int64,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (inputFilePath As String, targetStreamPath As String, accountName As String, Optional perFileThreadCount As Integer = -1, Optional concurrentFileCount As Integer = -1, Optional isOverwrite As Boolean = false, Optional isResume As Boolean = false, Optional isBinary As Boolean = true, Optional isRecursive As Boolean = false, Optional isDownload As Boolean = false, Optional maxSegmentLength As Long = 268435456, Optional localMetadataLocation As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.TransferParameters : string * string * string * int * int * bool * bool * bool * bool * bool * int64 * string -&gt; Microsoft.Azure.Management.DataLake.Store.TransferParameters" Usage="new Microsoft.Azure.Management.DataLake.Store.TransferParameters (inputFilePath, targetStreamPath, accountName, perFileThreadCount, concurrentFileCount, isOverwrite, isResume, isBinary, isRecursive, isDownload, maxSegmentLength, localMetadataLocation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="inputFilePath" Type="System.String" />
        <Parameter Name="targetStreamPath" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="perFileThreadCount" Type="System.Int32" />
        <Parameter Name="concurrentFileCount" Type="System.Int32" />
        <Parameter Name="isOverwrite" Type="System.Boolean" />
        <Parameter Name="isResume" Type="System.Boolean" />
        <Parameter Name="isBinary" Type="System.Boolean" />
        <Parameter Name="isRecursive" Type="System.Boolean" />
        <Parameter Name="isDownload" Type="System.Boolean" />
        <Parameter Name="maxSegmentLength" Type="System.Int64" />
        <Parameter Name="localMetadataLocation" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="inputFilePath">Der vollständige Pfad zur Datei oder zum Zielordner übertragen werden.</param>
        <param name="targetStreamPath">Der vollständige Stream-Pfad, in dem die Datei oder den Ordner übertragen werden sollen.</param>
        <param name="accountName">Der Name des Kontos zu übertragen.</param>
        <param name="perFileThreadCount">Die pro Datei Thread-Anzahl, die angibt, der Anzahl der Dateisegmente parallel zu übertragen. Diese Zahl ist für eine optimale Leistung bei FILE_SIZE/MaxSegmentLength Obergrenze.</param>
        <param name="concurrentFileCount">Die parallele Dateianzahl, der angibt, der Anzahl der Dateien während der Übertragung Ordner parallel zu übertragen. Dieser Parameter wird für einzelne dateiübertragungen ignoriert. Standard ist 5 für Ordner Übertragungen</param>
        <param name="isOverwrite">(Optional) Ob der Zieldatenstrom oder nicht überschrieben werden soll.</param>
        <param name="isResume">(Optional) Gibt an, ob eine zuvor unterbrochene Übertragung fortsetzen.</param>
        <param name="isBinary">(Optional) Gibt an, ob die Eingabedatei als Binärdatei (True) behandelt werden soll, oder ob richten Sie die Übertragung von Nachrichtenblöcken datensatzbegrenzungen (False).</param>
        <param name="isRecursive">(Optional) Gibt an, ob die Quelle Ordner rekursiv oder nicht übertragen werden soll. Bei "true", wird das Quellverzeichnis übertragen, und alle untergeordneten Verzeichnissen, die Verzeichnisstruktur beibehalten.</param>
        <param name="isDownload">(Optional) bei Festlegung auf <c>"true"</c> [ist Download] anstelle einer Übertragung-Szenario. Die Standardeinstellung ist "false".</param>
        <param name="maxSegmentLength">Maximale Länge der einzelnen Segmente. Der Standardwert ist 256mb, wodurch eine optimale Leistung zu erhalten. Ändern Sie auf eigenes Risiko.</param>
        <param name="localMetadataLocation">(Optional) Gibt den Verzeichnispfad an, wo Sie die lokale Übertragung Metadaten-Datei zu speichern, während die Übertragung ausgeführt wird. Dieser Speicherort muss beschreibbar aus dieser Anwendung handeln. Standardspeicherort: SpecialFolder.LocalApplicationData.</param>
        <summary>
            Erstellt einen neuen Satz von Parametern für die DataLakeStoreTransferClient an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountName">
      <MemberSignature Language="C#" Value="public string AccountName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.AccountName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountName As String" />
      <MemberSignature Language="F#" Value="member this.AccountName : string" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.AccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert, der angibt, der des Namens des Kontos, das auf übertragen oder Herunterladen aus.
            </summary>
        <value>
            Der Name des Kontos.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcurrentFileCount">
      <MemberSignature Language="C#" Value="public int ConcurrentFileCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ConcurrentFileCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.ConcurrentFileCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConcurrentFileCount As Integer" />
      <MemberSignature Language="F#" Value="member this.ConcurrentFileCount : int" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.ConcurrentFileCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl der parallel-Dateien, die angibt, wie viele Dateien in einem Ordner übertragen oder parallel heruntergeladen werden
            </summary>
        <value>
            Die Anzahl der Dateien für die Übertragung oder Download auf einmal.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delimiter">
      <MemberSignature Language="C#" Value="public string Delimiter { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Delimiter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.Delimiter" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Delimiter As String" />
      <MemberSignature Language="F#" Value="member this.Delimiter : string" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.Delimiter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert, der angibt, des Trennzeichens Datensatz Grenze für die Datei ab, sofern vorhanden.
            </summary>
        <value>
            Das Trennzeichen Datensatz Grenze
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileEncoding">
      <MemberSignature Language="C#" Value="public System.Text.Encoding FileEncoding { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Text.Encoding FileEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.FileEncoding" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FileEncoding As Encoding" />
      <MemberSignature Language="F#" Value="member this.FileEncoding : System.Text.Encoding" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.FileEncoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Text.Encoding</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert, der angibt, die Codierung der übertragenen Datei.
            </summary>
        <value>
            Die dateicodierung.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InputFilePath">
      <MemberSignature Language="C#" Value="public string InputFilePath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InputFilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.InputFilePath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InputFilePath As String" />
      <MemberSignature Language="F#" Value="member this.InputFilePath : string" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.InputFilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert, der angibt, des vollständigen Pfads zur Datei oder zum Zielordner übertragen werden.
            </summary>
        <value>
            Der Pfad der Eingabedatei.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBinary">
      <MemberSignature Language="C#" Value="public bool IsBinary { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsBinary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsBinary" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsBinary As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsBinary : bool" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsBinary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert, der angibt, ob die Eingabedatei als binärer (True) oder eine durch Trennzeichen getrennten Eingabe ("false") behandelt werden sollen.
            </summary>
        <value>
          <c>"true"</c> Wenn diese Instanz binär ist, andernfalls ist <c>"false"</c>.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDownload">
      <MemberSignature Language="C#" Value="public bool IsDownload { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDownload" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsDownload" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDownload As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDownload : bool" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsDownload" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert, der angibt, ob diese Instanz mit dem lokalen Computer statt übertragen heruntergeladen wird.
            </summary>
        <value>
          <c>"true"</c> Wenn diese Instanz Download; andernfalls <c>"false"</c>.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsOverwrite">
      <MemberSignature Language="C#" Value="public bool IsOverwrite { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsOverwrite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsOverwrite" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsOverwrite As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsOverwrite : bool" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsOverwrite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert, der angibt, ob der Zieldatenstrom zu überschreiben, wenn sie bereits vorhanden ist.
            </summary>
        <value>
          <c>"true"</c> dieser Instanz überschrieben werden; andernfalls <c>"false"</c>.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRecursive">
      <MemberSignature Language="C#" Value="public bool IsRecursive { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsRecursive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsRecursive" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsRecursive As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsRecursive : bool" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsRecursive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert, der angibt, ob die Übertragung Ordner rekursiv Übertragung Quellordner sollten. Dies gilt nur für Ordner übertragen und wird für die Übertragung von Dateien ignoriert.
            </summary>
        <value>
          <c>"true"</c> Wenn diese Instanz rekursive; andernfalls <c>"false"</c>.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsResume">
      <MemberSignature Language="C#" Value="public bool IsResume { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsResume" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsResume" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsResume As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsResume : bool" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsResume" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert, der angibt, ob eine zuvor unterbrochene Übertragung fortsetzen.
            </summary>
        <value>
          <c>"true"</c> Wenn diese Instanz fortsetzen; andernfalls <c>"false"</c>.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalMetadataLocation">
      <MemberSignature Language="C#" Value="public string LocalMetadataLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalMetadataLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.LocalMetadataLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LocalMetadataLocation As String" />
      <MemberSignature Language="F#" Value="member this.LocalMetadataLocation : string" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.LocalMetadataLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert ab dem Verzeichnispfad, wo Sie die Metadaten für die Übertragung zu speichern.
            </summary>
        <value>
            Der lokalen Metadaten-Speicherort.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSegementLength">
      <MemberSignature Language="C#" Value="public long MaxSegementLength { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxSegementLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.MaxSegementLength" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxSegementLength As Long" />
      <MemberSignature Language="F#" Value="member this.MaxSegementLength : int64" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.MaxSegementLength" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die maximale Länge jedes Segments ab.
            </summary>
        <value>
            Die maximale Länge jedes Segments.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PerFileThreadCount">
      <MemberSignature Language="C#" Value="public int PerFileThreadCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PerFileThreadCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.PerFileThreadCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PerFileThreadCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PerFileThreadCount : int" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.PerFileThreadCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert, der angibt, der maximalen Anzahl von parallelen Threads zur Verwendung einer einzelnen übertragen oder herunterladen.
            </summary>
        <value>
            Die Thread-Anzahl der Dateien.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetStreamPath">
      <MemberSignature Language="C#" Value="public string TargetStreamPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetStreamPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.TargetStreamPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetStreamPath As String" />
      <MemberSignature Language="F#" Value="member this.TargetStreamPath : string" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.TargetStreamPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert, der angibt, des vollständige Stream-Pfads, in dem die Datei übertragen werden sollen.
            </summary>
        <value>
            Der Zielpfad Stream.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>