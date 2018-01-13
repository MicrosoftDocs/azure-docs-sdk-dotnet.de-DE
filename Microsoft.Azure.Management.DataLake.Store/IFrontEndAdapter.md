<Type Name="IFrontEndAdapter" FullName="Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter">
  <TypeSignature Language="C#" Value="public interface IFrontEndAdapter" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IFrontEndAdapter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter" />
  <TypeSignature Language="VB.NET" Value="Public Interface IFrontEndAdapter" />
  <TypeSignature Language="F#" Value="type IFrontEndAdapter = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Definiert die Vorgänge, die die DataLakeTransferClient aus dem Front-End benötigt werden, um ausgeführt werden
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AppendToStream">
      <MemberSignature Language="C#" Value="public void AppendToStream (string streamPath, byte[] data, long offset, int length);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void AppendToStream(string streamPath, unsigned int8[] data, int64 offset, int32 length) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.AppendToStream(System.String,System.Byte[],System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AppendToStream (streamPath As String, data As Byte(), offset As Long, length As Integer)" />
      <MemberSignature Language="F#" Value="abstract member AppendToStream : string * byte[] * int64 * int -&gt; unit" Usage="iFrontEndAdapter.AppendToStream (streamPath, data, offset, length)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="streamPath" Type="System.String" />
        <Parameter Name="data" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int64" />
        <Parameter Name="length" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="streamPath">Der relative Pfad in den Stream.</param>
        <param name="data">Ein Array von Bytes, die in den Stream angefügt werden.</param>
        <param name="offset">Der Offset, bei dem in den Stream angefügt werden soll.</param>
        <param name="length">Die Anzahl der Bytes, die angefügt werden soll (beginnend mit 0).</param>
        <summary>
            Fügt das angegebene Bytearray bis zum Ende einer angegebenen Datenstrom.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wenn die Daten an, die angefügt werden, null oder leer ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="Concatenate">
      <MemberSignature Language="C#" Value="public void Concatenate (string targetStreamPath, string[] inputStreamPaths, bool isDownload = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Concatenate(string targetStreamPath, string[] inputStreamPaths, bool isDownload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.Concatenate(System.String,System.String[],System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Concatenate (targetStreamPath As String, inputStreamPaths As String(), Optional isDownload As Boolean = false)" />
      <MemberSignature Language="F#" Value="abstract member Concatenate : string * string[] * bool -&gt; unit" Usage="iFrontEndAdapter.Concatenate (targetStreamPath, inputStreamPaths, isDownload)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="targetStreamPath" Type="System.String" />
        <Parameter Name="inputStreamPaths" Type="System.String[]" />
        <Parameter Name="isDownload" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="targetStreamPath">Der relative Pfad auf den Zieldatenstrom.</param>
        <param name="inputStreamPaths">Ein geordnetes Array von Pfaden, die der Eingabestreams.</param>
        <param name="isDownload">Wenn auf festgelegt <c>"true"</c> [ist Download], d. h., es wird die Datenströme auf dem lokalen Computer statt auf dem Server verketten.</param>
        <summary>
            Verkettet die angegebenen Eingabedatenströme (nacheinander) in den angegebenen Zieltyp Stream an.
            Am Ende dieses Vorgangs werden der Eingabestreams gelöscht werden.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateStream">
      <MemberSignature Language="C#" Value="public void CreateStream (string streamPath, bool overwrite, byte[] data, int byteCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CreateStream(string streamPath, bool overwrite, unsigned int8[] data, int32 byteCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.CreateStream(System.String,System.Boolean,System.Byte[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CreateStream (streamPath As String, overwrite As Boolean, data As Byte(), byteCount As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CreateStream : string * bool * byte[] * int -&gt; unit" Usage="iFrontEndAdapter.CreateStream (streamPath, overwrite, data, byteCount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="streamPath" Type="System.String" />
        <Parameter Name="overwrite" Type="System.Boolean" />
        <Parameter Name="data" Type="System.Byte[]" />
        <Parameter Name="byteCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="streamPath">Der relative Pfad in den Stream.</param>
        <param name="overwrite">Ob überschreiben einen vorhandenen Datenstrom.</param>
        <param name="data">Die Daten.</param>
        <param name="byteCount">Die Anzahl von Bytes.</param>
        <summary>
            Erstellt einen neuen, leeren Datenstrom im angegebenen Pfad.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteStream">
      <MemberSignature Language="C#" Value="public void DeleteStream (string streamPath, bool recurse = false, bool isDownload = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeleteStream(string streamPath, bool recurse, bool isDownload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.DeleteStream(System.String,System.Boolean,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteStream (streamPath As String, Optional recurse As Boolean = false, Optional isDownload As Boolean = false)" />
      <MemberSignature Language="F#" Value="abstract member DeleteStream : string * bool * bool -&gt; unit" Usage="iFrontEndAdapter.DeleteStream (streamPath, recurse, isDownload)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="streamPath" Type="System.String" />
        <Parameter Name="recurse" Type="System.Boolean" />
        <Parameter Name="isDownload" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="streamPath">Der relative Pfad in den Stream.</param>
        <param name="recurse">Wenn auf festgelegt <c>"true"</c> [Recurse]. Dies wird für nur die Ordner-Streams verwendet.</param>
        <param name="isDownload">Wenn auf festgelegt <c>"true"</c> [ist Download], d. h., es wird einen Datenstrom, auf dem lokalen Computer statt auf dem Server gelöscht.</param>
        <summary>
            Löscht einen vorhandenen Datenstrom im angegebenen Pfad.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStreamLength">
      <MemberSignature Language="C#" Value="public long GetStreamLength (string streamPath, bool isDownload = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int64 GetStreamLength(string streamPath, bool isDownload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.GetStreamLength(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetStreamLength (streamPath As String, Optional isDownload As Boolean = false) As Long" />
      <MemberSignature Language="F#" Value="abstract member GetStreamLength : string * bool -&gt; int64" Usage="iFrontEndAdapter.GetStreamLength (streamPath, isDownload)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="streamPath" Type="System.String" />
        <Parameter Name="isDownload" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="streamPath">Der relative Pfad in den Stream.</param>
        <param name="isDownload">Wenn auf festgelegt <c>"true"</c> [ist Download], d. h., es wird die Länge des Streams abrufen, auf dem lokalen Computer statt auf dem Server.</param>
        <summary>
            Ruft einen Wert, der angibt, der Länge des Streams in Bytes ab.
            </summary>
        <returns>Die Länge des Streams in Bytes.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDirectory">
      <MemberSignature Language="C#" Value="public bool IsDirectory (string streamPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsDirectory(string streamPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.IsDirectory(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function IsDirectory (streamPath As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsDirectory : string -&gt; bool" Usage="iFrontEndAdapter.IsDirectory streamPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="streamPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="streamPath">Der relative Pfad in den Stream.</param>
        <summary>
            Bestimmt, ob der Stream mit angegebenen Pfad auf dem Server ein Verzeichnis oder eine abschließende Datei ist.
            Dies wird ausschließlich für den Download verwendet.
            </summary>
        <returns>"True", wenn der Stream andernfalls "false" ein Verzeichnis ist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDirectory">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,long&gt; ListDirectory (string directoryPath, bool recursive);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IDictionary`2&lt;string, int64&gt; ListDirectory(string directoryPath, bool recursive) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.ListDirectory(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListDirectory (directoryPath As String, recursive As Boolean) As IDictionary(Of String, Long)" />
      <MemberSignature Language="F#" Value="abstract member ListDirectory : string * bool -&gt; System.Collections.Generic.IDictionary&lt;string, int64&gt;" Usage="iFrontEndAdapter.ListDirectory (directoryPath, recursive)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="directoryPath" Type="System.String" />
        <Parameter Name="recursive" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="directoryPath">Der Verzeichnispfad.</param>
        <param name="recursive">Wenn auf festgelegt <c>"true"</c> [rekursive].</param>
        <summary>
            Führt das angegebene Data Lake-Speicher-Verzeichnis.
            </summary>
        <returns>
            Die Liste der Zeichenfolge Pfade und die entsprechenden Dateigröße in Bytes.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadStream">
      <MemberSignature Language="C#" Value="public System.IO.Stream ReadStream (string streamPath, long offset, long length, bool isDownload = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.IO.Stream ReadStream(string streamPath, int64 offset, int64 length, bool isDownload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.ReadStream(System.String,System.Int64,System.Int64,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadStream (streamPath As String, offset As Long, length As Long, Optional isDownload As Boolean = false) As Stream" />
      <MemberSignature Language="F#" Value="abstract member ReadStream : string * int64 * int64 * bool -&gt; System.IO.Stream" Usage="iFrontEndAdapter.ReadStream (streamPath, offset, length, isDownload)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="streamPath" Type="System.String" />
        <Parameter Name="offset" Type="System.Int64" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="isDownload" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="streamPath">Der relative Pfad in den Stream.</param>
        <param name="offset">Der Offset, bei dem in den Stream angefügt werden soll.</param>
        <param name="length">Die Anzahl der Bytes, die angefügt werden soll (beginnend mit 0).</param>
        <param name="isDownload">Wenn auf festgelegt <c>"true"</c> [ist Download], d. h., es wird einen Datenstrom, auf dem Server zum Auslesen, anstatt den lokalen Computer geöffnet.</param>
        <summary>
            Öffnet einen Datenstrom zu lesen, die Angabe des Pfads der Proxyport stream
            </summary>
        <returns />
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wenn die Daten an, die angefügt werden, null oder leer ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="StreamExists">
      <MemberSignature Language="C#" Value="public bool StreamExists (string streamPath, bool isDownload = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool StreamExists(string streamPath, bool isDownload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.StreamExists(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function StreamExists (streamPath As String, Optional isDownload As Boolean = false) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member StreamExists : string * bool -&gt; bool" Usage="iFrontEndAdapter.StreamExists (streamPath, isDownload)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="streamPath" Type="System.String" />
        <Parameter Name="isDownload" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="streamPath">Der relative Pfad in den Stream.</param>
        <param name="isDownload">Wenn auf festgelegt <c>"true"</c> [ist Download], d. h., es testen, wenn der Datenstrom auf dem lokalen Computer statt auf dem Server vorhanden ist.</param>
        <summary>
            Bestimmt, ob der Stream mit dem angegebenen Pfad vorhanden.
            </summary>
        <returns>"True", wenn der Stream "false" vorhanden, andernfalls ist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>