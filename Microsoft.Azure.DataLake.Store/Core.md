<Type Name="Core" FullName="Microsoft.Azure.DataLake.Store.Core">
  <TypeSignature Language="C#" Value="public class Core" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Core extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.Core" />
  <TypeSignature Language="VB.NET" Value="Public Class Core" />
  <TypeSignature Language="F#" Value="type Core = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>0.1.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Core-Ebene. Enthält Methoden für die REST-APIs. Für jeden rest-api Befehl eine HTTP-Anforderung an Server gesendet.
            Wir haben sowohl "Async" und "Sync-Versionen von CREATE-, ANFÜGEN, öffnen, CONCURRENTAPPEND. Der Grund, wir haben, ist, wenn die Anwendung diese Vorgänge, die häufig explizite Threads verwenden, und Verwenden von Async durchführt-"await" intern nicht benötigten Threads im Threadpool erstellt und die Leistung wird beeinträchtigt, aufgrund der Kontextwechsel. Anwendung kann in Fällen Uploader und Downloadprogramm explizite Threads erstellen.
            Alle diese Vorgang auch aufrufen, Sync-Versionen MakeCall in WebTransport-Ebene.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Core ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Append">
      <MemberSignature Language="C#" Value="public static void Append (string path, string leaseId, string sessionId, Microsoft.Azure.DataLake.Store.SyncFlag flag, long offsetFile, byte[] dataBytes, int offset, int length, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Append(string path, string leaseId, string sessionId, valuetype Microsoft.Azure.DataLake.Store.SyncFlag flag, int64 offsetFile, unsigned int8[] dataBytes, int32 offset, int32 length, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.Append(System.String,System.String,System.String,Microsoft.Azure.DataLake.Store.SyncFlag,System.Int64,System.Byte[],System.Int32,System.Int32,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub Append (path As String, leaseId As String, sessionId As String, flag As SyncFlag, offsetFile As Long, dataBytes As Byte(), offset As Integer, length As Integer, client As AdlsClient, req As RequestOptions, resp As OperationResponse)" />
      <MemberSignature Language="F#" Value="static member Append : string * string * string * Microsoft.Azure.DataLake.Store.SyncFlag * int64 * byte[] * int * int * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse -&gt; unit" Usage="Microsoft.Azure.DataLake.Store.Core.Append (path, leaseId, sessionId, flag, offsetFile, dataBytes, offset, length, client, req, resp)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="leaseId" Type="System.String" />
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="flag" Type="Microsoft.Azure.DataLake.Store.SyncFlag" />
        <Parameter Name="offsetFile" Type="System.Int64" />
        <Parameter Name="dataBytes" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="length" Type="System.Int32" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
      </Parameters>
      <Docs>
        <param name="path">Pfad der Datei</param>
        <param name="leaseId">Zeichenfolge, die die Lease-ID enthält, wenn ein Client einer Lease für eine Datei kein anderer Client erhält kann Änderungen an der Datei vornehmen. </param>
        <param name="sessionId">UUID, die verwendet wird, um den Handler für Dateien (Datenstrom) einfach auf den Server zu erhalten.</param>
        <param name="flag">Übergeben Sie SyncFlag.DATA beim Schreiben von Bytes an Daten SyncFlag.METADATA übergeben, wenn Metadaten der Datei wie die Länge, die geändert Zeitpunkt aktualisiert werden, damit Sie mit den tatsächlichen Daten der Datei übereinstimmen muss. Nach dem Übergeben der SyncFlag.METADATA GetFileStatus und ListStatus gibt Sie konsistente Daten zurück.
                               Übergeben Sie SyncFlag.CLOSE, wenn keine weiteren Daten angefügt werden müssen, Dateimetadaten wird aktualisiert, Lease freigegeben und der Stream geschlossen ist.  </param>
        <param name="offsetFile">Offset in der Datei, an der Daten angefügt wird</param>
        <param name="dataBytes">Array von Bytes, die in die Datei geschrieben.</param>
        <param name="offset">Offset im Bytearray</param>
        <param name="length">Anzahl der Bytes vom Offset geschrieben.</param>
        <param name="client">ADLS-Client</param>
        <param name="req">Optionen zum Ändern des Verhaltens der HTTP-Anforderung </param>
        <param name="resp">Speichert die Antwort/Ausgabe der HTTP-Anforderung </param>
        <summary>
            Daten werden an Datei anfügen. Dies ist ein synchroner Vorgang.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task AppendAsync (string path, string leaseId, string sessionId, Microsoft.Azure.DataLake.Store.SyncFlag flag, long offsetFile, byte[] dataBytes, int offset, int length, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task AppendAsync(string path, string leaseId, string sessionId, valuetype Microsoft.Azure.DataLake.Store.SyncFlag flag, int64 offsetFile, unsigned int8[] dataBytes, int32 offset, int32 length, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.AppendAsync(System.String,System.String,System.String,Microsoft.Azure.DataLake.Store.SyncFlag,System.Int64,System.Byte[],System.Int32,System.Int32,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function AppendAsync (path As String, leaseId As String, sessionId As String, flag As SyncFlag, offsetFile As Long, dataBytes As Byte(), offset As Integer, length As Integer, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member AppendAsync : string * string * string * Microsoft.Azure.DataLake.Store.SyncFlag * int64 * byte[] * int * int * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.AppendAsync (path, leaseId, sessionId, flag, offsetFile, dataBytes, offset, length, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;AppendAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="leaseId" Type="System.String" />
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="flag" Type="Microsoft.Azure.DataLake.Store.SyncFlag" />
        <Parameter Name="offsetFile" Type="System.Int64" />
        <Parameter Name="dataBytes" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="length" Type="System.Int32" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Pfad der Datei</param>
        <param name="leaseId">Zeichenfolge, die die Lease-ID enthält, wenn ein Client einer Lease für eine Datei kein anderer Client erhält kann Änderungen an der Datei vornehmen. </param>
        <param name="sessionId">UUID, die verwendet wird, um den Handler für Dateien (Datenstrom) einfach auf den Server zu erhalten.</param>
        <param name="flag">Übergeben Sie SyncFlag.DATA beim Schreiben von Bytes an Daten SyncFlag.METADATA übergeben, wenn Metadaten der Datei wie die Länge, die geändert Zeitpunkt aktualisiert werden, damit Sie mit den tatsächlichen Daten der Datei übereinstimmen muss. Nach dem Übergeben der SyncFlag.METADATA GetFileStatus und ListStatus gibt Sie konsistente Daten zurück.
                               Übergeben Sie SyncFlag.CLOSE, wenn keine weiteren Daten angefügt werden müssen, Dateimetadaten wird aktualisiert, Lease freigegeben und der Stream geschlossen ist.  </param>
        <param name="offsetFile">Offset in der Datei, an der Daten angefügt wird</param>
        <param name="dataBytes">Array von Bytes, die in die Datei geschrieben.</param>
        <param name="offset">Offset im Bytearray</param>
        <param name="length">Anzahl der Bytes vom Offset geschrieben.</param>
        <param name="client">ADLS-Client</param>
        <param name="req">Optionen zum Ändern des Verhaltens der HTTP-Anforderung </param>
        <param name="resp">Speichert die Antwort/Ausgabe der HTTP-Anforderung </param>
        <param name="cancelToken">CancellationToken, um die Anforderung abzubrechen</param>
        <summary>
            Daten werden an Datei anfügen. Das ist ein asynchroner Vorgang.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckAccessSync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CheckAccessSync (string path, string rwx, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CheckAccessSync(string path, string rwx, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.CheckAccessSync(System.String,System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CheckAccessSync (path As String, rwx As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member CheckAccessSync : string * string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.CheckAccessSync (path, rwx, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;CheckAccessSync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="rwx" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Pfad der Datei oder des Verzeichnisses</param>
        <param name="rwx">Berechtigung zum Einchecken von "Rwx" in Form einer Zeichenfolge. Für Beispiel, wenn der Benutzer möchte, um festzustellen, ob sie gelesen hat, führen Sie die Berechtigung, wäre die Zeichenfolge R-x </param>
        <param name="client">ADLS-Client</param>
        <param name="req">Optionen zum Ändern des Verhaltens der HTTP-Anforderung </param>
        <param name="resp">Speichert die Antwort/Ausgabe der HTTP-Anforderung </param>
        <param name="cancelToken">CancellationToken, um die Anforderung abzubrechen</param>
        <summary>
            Überprüft, ob die Benutzergruppe der Zugriff des angegebenen Pfads angegeben wurde
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcatAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ConcatAsync (string path, System.Collections.Generic.List&lt;string&gt; sourceFiles, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ConcatAsync(string path, class System.Collections.Generic.List`1&lt;string&gt; sourceFiles, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.ConcatAsync(System.String,System.Collections.Generic.List{System.String},Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ConcatAsync (path As String, sourceFiles As List(Of String), client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member ConcatAsync : string * System.Collections.Generic.List&lt;string&gt; * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.ConcatAsync (path, sourceFiles, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;ConcatAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="sourceFiles" Type="System.Collections.Generic.List&lt;System.String&gt;" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Pfad des Ziels</param>
        <param name="sourceFiles">Liste mit Pfaden der der Quelldateien</param>
        <param name="client">ADLS-Client</param>
        <param name="req">Optionen zum Ändern des Verhaltens der HTTP-Anforderung </param>
        <param name="resp">Speichert die Antwort/Ausgabe der HTTP-Anforderung </param>
        <param name="cancelToken">CancellationToken, um die Anforderung abzubrechen</param>
        <summary>
            Verketten Sie die Quelldateien in eine Zieldatei. In der Standardeinstellung nicht löschen Quellverzeichnis abrufen
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcatAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ConcatAsync (string path, System.Collections.Generic.List&lt;string&gt; sourceFiles, bool deleteSourceDirectory, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ConcatAsync(string path, class System.Collections.Generic.List`1&lt;string&gt; sourceFiles, bool deleteSourceDirectory, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.ConcatAsync(System.String,System.Collections.Generic.List{System.String},System.Boolean,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ConcatAsync (path As String, sourceFiles As List(Of String), deleteSourceDirectory As Boolean, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member ConcatAsync : string * System.Collections.Generic.List&lt;string&gt; * bool * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.ConcatAsync (path, sourceFiles, deleteSourceDirectory, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;ConcatAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="sourceFiles" Type="System.Collections.Generic.List&lt;System.String&gt;" />
        <Parameter Name="deleteSourceDirectory" Type="System.Boolean" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Pfad des Ziels</param>
        <param name="sourceFiles">Liste mit Pfaden der der Quelldateien</param>
        <param name="deleteSourceDirectory">Bei "true" löscht dann das Quellverzeichnis, wenn alle Dateien unter es verkettet sind</param>
        <param name="client">ADLS-Client</param>
        <param name="req">Optionen zum Ändern des Verhaltens der HTTP-Anforderung </param>
        <param name="resp">Speichert die Antwort/Ausgabe der HTTP-Anforderung </param>
        <param name="cancelToken">CancellationToken, um die Anforderung abzubrechen</param>
        <summary>
            Verketten von Quelldateien in eine Zieldatei
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcurrentAppend">
      <MemberSignature Language="C#" Value="public static void ConcurrentAppend (string path, bool autoCreate, byte[] dataBytes, int offset, int length, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ConcurrentAppend(string path, bool autoCreate, unsigned int8[] dataBytes, int32 offset, int32 length, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.ConcurrentAppend(System.String,System.Boolean,System.Byte[],System.Int32,System.Int32,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub ConcurrentAppend (path As String, autoCreate As Boolean, dataBytes As Byte(), offset As Integer, length As Integer, client As AdlsClient, req As RequestOptions, resp As OperationResponse)" />
      <MemberSignature Language="F#" Value="static member ConcurrentAppend : string * bool * byte[] * int * int * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse -&gt; unit" Usage="Microsoft.Azure.DataLake.Store.Core.ConcurrentAppend (path, autoCreate, dataBytes, offset, length, client, req, resp)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="autoCreate" Type="System.Boolean" />
        <Parameter Name="dataBytes" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="length" Type="System.Int32" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
      </Parameters>
      <Docs>
        <param name="path">Pfad der Datei</param>
        <param name="autoCreate"></param>
        <param name="dataBytes">Array von Bytes, die in die Datei geschrieben.</param>
        <param name="offset">Offset im Bytearray</param>
        <param name="length">Anzahl der Bytes vom Offset geschrieben.</param>
        <param name="client">ADLS-Client</param>
        <param name="req">Optionen zum Ändern des Verhaltens der HTTP-Anforderung </param>
        <param name="resp">Speichert die Antwort/Ausgabe der HTTP-Anforderung </param>
        <summary>
            Führt gleichzeitige synchron an den Server angefügt. Der Offset, bei dem Anfügen treten richtet sich nach Server
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcurrentAppendAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ConcurrentAppendAsync (string path, bool autoCreate, byte[] dataBytes, int offset, int length, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ConcurrentAppendAsync(string path, bool autoCreate, unsigned int8[] dataBytes, int32 offset, int32 length, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.ConcurrentAppendAsync(System.String,System.Boolean,System.Byte[],System.Int32,System.Int32,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ConcurrentAppendAsync (path As String, autoCreate As Boolean, dataBytes As Byte(), offset As Integer, length As Integer, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member ConcurrentAppendAsync : string * bool * byte[] * int * int * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.ConcurrentAppendAsync (path, autoCreate, dataBytes, offset, length, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;ConcurrentAppendAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="autoCreate" Type="System.Boolean" />
        <Parameter Name="dataBytes" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="length" Type="System.Int32" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Pfad der Datei</param>
        <param name="autoCreate"></param>
        <param name="dataBytes">Array von Bytes, die in die Datei geschrieben.</param>
        <param name="offset">Offset im Bytearray</param>
        <param name="length">Anzahl der Bytes vom Offset geschrieben.</param>
        <param name="client">ADLS-Client</param>
        <param name="req">Optionen zum Ändern des Verhaltens der HTTP-Anforderung </param>
        <param name="resp">Speichert die Antwort/Ausgabe der HTTP-Anforderung </param>
        <param name="cancelToken">CancellationToken, um die Anforderung abzubrechen</param>
        <summary>
            Führt gleichzeitige asynchron an den Server angefügt. Der Offset, bei dem Anfügen treten richtet sich nach Server
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static void Create (string path, bool overwrite, string octalPermission, string leaseId, string sessionId, bool createParent, Microsoft.Azure.DataLake.Store.SyncFlag flag, byte[] dataBytes, int offset, int length, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Create(string path, bool overwrite, string octalPermission, string leaseId, string sessionId, bool createParent, valuetype Microsoft.Azure.DataLake.Store.SyncFlag flag, unsigned int8[] dataBytes, int32 offset, int32 length, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.Create(System.String,System.Boolean,System.String,System.String,System.String,System.Boolean,Microsoft.Azure.DataLake.Store.SyncFlag,System.Byte[],System.Int32,System.Int32,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub Create (path As String, overwrite As Boolean, octalPermission As String, leaseId As String, sessionId As String, createParent As Boolean, flag As SyncFlag, dataBytes As Byte(), offset As Integer, length As Integer, client As AdlsClient, req As RequestOptions, resp As OperationResponse)" />
      <MemberSignature Language="F#" Value="static member Create : string * bool * string * string * string * bool * Microsoft.Azure.DataLake.Store.SyncFlag * byte[] * int * int * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse -&gt; unit" Usage="Microsoft.Azure.DataLake.Store.Core.Create (path, overwrite, octalPermission, leaseId, sessionId, createParent, flag, dataBytes, offset, length, client, req, resp)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="overwrite" Type="System.Boolean" />
        <Parameter Name="octalPermission" Type="System.String" />
        <Parameter Name="leaseId" Type="System.String" />
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="createParent" Type="System.Boolean" />
        <Parameter Name="flag" Type="Microsoft.Azure.DataLake.Store.SyncFlag" />
        <Parameter Name="dataBytes" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="length" Type="System.Int32" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
      </Parameters>
      <Docs>
        <param name="path">Pfad der Datei</param>
        <param name="overwrite">Wird die vorhandene Datei überschrieben, wenn das Flag auf "true" festgelegt ist</param>
        <param name="octalPermission">Oktale Berechtigungszeichenfolge</param>
        <param name="leaseId">Zeichenfolge, die die Lease-ID enthält, wenn ein Client einer Lease für eine Datei kein anderer Client erhält kann Änderungen an der Datei vornehmen. </param>
        <param name="sessionId">UUID, die verwendet wird, um den Handler für Dateien (Datenstrom) einfach auf den Server zu erhalten.</param>
        <param name="createParent">Bei "true" wird eine nicht vorhandene übergeordnete Verzeichnisse erstellt.</param>
        <param name="flag">Übergeben Sie SyncFlag.DATA beim Schreiben von Bytes an Daten SyncFlag.METADATA übergeben, wenn Metadaten der Datei wie die Länge, die geändert Zeitpunkt aktualisiert werden, damit Sie mit den tatsächlichen Daten der Datei übereinstimmen muss. Nach dem Übergeben der SyncFlag.METADATA GetFileStatus und ListStatus gibt Sie konsistente Daten zurück.
                               Übergeben Sie SyncFlag.CLOSE, wenn keine weiteren Daten angefügt werden müssen, Dateimetadaten wird aktualisiert, Lease freigegeben und der Stream geschlossen ist.  </param>
        <param name="dataBytes">Array von Bytes, die in die Datei geschrieben.</param>
        <param name="offset">Offset im Bytearray</param>
        <param name="length">Anzahl der Bytes vom Offset geschrieben.</param>
        <param name="client">ADLS-Client</param>
        <param name="req">Optionen zum Ändern des Verhaltens der HTTP-Anforderung </param>
        <param name="resp">Speichert die Antwort/Ausgabe der HTTP-Anforderung </param>
        <summary>
            Erstellen Sie eine neue Datei. Dies ist ein synchroner Vorgang.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CreateAsync (string path, bool overwrite, string octalPermission, string leaseId, string sessionId, bool createParent, Microsoft.Azure.DataLake.Store.SyncFlag flag, byte[] dataBytes, int offset, int length, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CreateAsync(string path, bool overwrite, string octalPermission, string leaseId, string sessionId, bool createParent, valuetype Microsoft.Azure.DataLake.Store.SyncFlag flag, unsigned int8[] dataBytes, int32 offset, int32 length, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.CreateAsync(System.String,System.Boolean,System.String,System.String,System.String,System.Boolean,Microsoft.Azure.DataLake.Store.SyncFlag,System.Byte[],System.Int32,System.Int32,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (path As String, overwrite As Boolean, octalPermission As String, leaseId As String, sessionId As String, createParent As Boolean, flag As SyncFlag, dataBytes As Byte(), offset As Integer, length As Integer, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member CreateAsync : string * bool * string * string * string * bool * Microsoft.Azure.DataLake.Store.SyncFlag * byte[] * int * int * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.CreateAsync (path, overwrite, octalPermission, leaseId, sessionId, createParent, flag, dataBytes, offset, length, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;CreateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="overwrite" Type="System.Boolean" />
        <Parameter Name="octalPermission" Type="System.String" />
        <Parameter Name="leaseId" Type="System.String" />
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="createParent" Type="System.Boolean" />
        <Parameter Name="flag" Type="Microsoft.Azure.DataLake.Store.SyncFlag" />
        <Parameter Name="dataBytes" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="length" Type="System.Int32" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Pfad der Datei</param>
        <param name="overwrite">Wird die vorhandene Datei überschrieben, wenn das Flag auf "true" festgelegt ist</param>
        <param name="octalPermission">Oktale Berechtigungszeichenfolge</param>
        <param name="leaseId">Zeichenfolge, die die Lease-ID enthält, wenn ein Client einer Lease für eine Datei kein anderer Client erhält kann Änderungen an der Datei vornehmen. </param>
        <param name="sessionId">UUID, die verwendet wird, um den Handler für Dateien (Datenstrom) einfach auf den Server zu erhalten.</param>
        <param name="createParent">Bei "true" wird eine nicht vorhandene übergeordnete Verzeichnisse erstellt.</param>
        <param name="flag">Übergeben Sie SyncFlag.DATA beim Schreiben von Bytes an Daten SyncFlag.METADATA übergeben, wenn Metadaten der Datei wie die Länge, die geändert Zeitpunkt aktualisiert werden, damit Sie mit den tatsächlichen Daten der Datei übereinstimmen muss. Nach dem Übergeben der SyncFlag.METADATA GetFileStatus und ListStatus gibt Sie konsistente Daten zurück.
                               Übergeben Sie SyncFlag.CLOSE, wenn keine weiteren Daten angefügt werden müssen, Dateimetadaten wird aktualisiert, Lease freigegeben und der Stream geschlossen ist.  </param>
        <param name="dataBytes">Array von Bytes, die in die Datei geschrieben.</param>
        <param name="offset">Offset im Bytearray</param>
        <param name="length">Anzahl der Bytes vom Offset geschrieben.</param>
        <param name="client">ADLS-Client</param>
        <param name="req">Optionen zum Ändern des Verhaltens der HTTP-Anforderung </param>
        <param name="resp">Speichert die Antwort/Ausgabe der HTTP-Anforderung </param>
        <param name="cancelToken">CancellationToken, um die Anforderung abzubrechen</param>
        <summary>
            Erstellen Sie eine neue Datei. Das ist ein asynchroner Vorgang.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; DeleteAsync (string path, bool recursive, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteAsync(string path, bool recursive, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.DeleteAsync(System.String,System.Boolean,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DeleteAsync (path As String, recursive As Boolean, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : string * bool * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.DataLake.Store.Core.DeleteAsync (path, recursive, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;DeleteAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="recursive" Type="System.Boolean" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Pfad der Datei oder des Verzeichnisses</param>
        <param name="recursive"></param>
        <param name="client">ADLS-Client</param>
        <param name="req">Optionen zum Ändern des Verhaltens der HTTP-Anforderung </param>
        <param name="resp">Speichert die Antwort/Ausgabe der HTTP-Anforderung </param>
        <param name="cancelToken">CancellationToken, um die Anforderung abzubrechen</param>
        <summary>
            Löscht eine Datei oder ein Verzeichnis
            </summary>
        <returns>True, wenn der Löschvorgang erfolgreich ist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAclStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.Acl.AclStatus&gt; GetAclStatusAsync (string path, Nullable&lt;Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt; userIdFormat, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclStatus&gt; GetAclStatusAsync(string path, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt; userIdFormat, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.GetAclStatusAsync(System.String,System.Nullable{Microsoft.Azure.DataLake.Store.UserGroupRepresentation},Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetAclStatusAsync (path As String, userIdFormat As Nullable(Of UserGroupRepresentation), client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task(Of AclStatus)" />
      <MemberSignature Language="F#" Value="static member GetAclStatusAsync : string * Nullable&lt;Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt; * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.Acl.AclStatus&gt;" Usage="Microsoft.Azure.DataLake.Store.Core.GetAclStatusAsync (path, userIdFormat, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;GetAclStatusAsync&gt;d__32))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.Acl.AclStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="userIdFormat" Type="System.Nullable&lt;Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt;" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Pfad der Datei oder des Verzeichnisses</param>
        <param name="userIdFormat">Möglichkeit, die Benutzer/Gruppenobjekt darzustellen.</param>
        <param name="client">ADLS-Client</param>
        <param name="req">Optionen zum Ändern des Verhaltens der HTTP-Anforderung </param>
        <param name="resp">Speichert die Antwort/Ausgabe der HTTP-Anforderung </param>
        <param name="cancelToken">CancellationToken, um die Anforderung abzubrechen</param>
        <summary>
            Ruft die ACL-Eintrag-Liste, Besitzer-ID, Gruppen-ID, oktale Berechtigung und persistente Bit (nur für ein Verzeichnis), der das Dateiverzeichnis ab
            </summary>
        <returns>ACL-Informationen: ACL-Eintrag-Liste, Besitzer-ID gruppieren-ID, oktale Berechtigung und persistente Bit</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetContentSummaryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.ContentSummary&gt; GetContentSummaryAsync (string path, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.DataLake.Store.ContentSummary&gt; GetContentSummaryAsync(string path, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.GetContentSummaryAsync(System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetContentSummaryAsync (path As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task(Of ContentSummary)" />
      <MemberSignature Language="F#" Value="static member GetContentSummaryAsync : string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.ContentSummary&gt;" Usage="Microsoft.Azure.DataLake.Store.Core.GetContentSummaryAsync (path, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;GetContentSummaryAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.ContentSummary&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Pfad des Verzeichnisses oder der Datei</param>
        <param name="client">ADLS-Client</param>
        <param name="req">Optionen zum Ändern des Verhaltens der HTTP-Anforderung </param>
        <param name="resp">Speichert die Antwort/Ausgabe der HTTP-Anforderung </param>
        <param name="cancelToken">CancellationToken, um die Anforderung abzubrechen</param>
        <summary>
            Ruft Content Zusammenfassung einer Datei oder das Verzeichnis ab
            </summary>
        <returns>ContentSummary des Pfads</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFileStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt; GetFileStatusAsync (string path, Nullable&lt;Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt; userIdFormat, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.DataLake.Store.DirectoryEntry&gt; GetFileStatusAsync(string path, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt; userIdFormat, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.GetFileStatusAsync(System.String,System.Nullable{Microsoft.Azure.DataLake.Store.UserGroupRepresentation},Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFileStatusAsync (path As String, userIdFormat As Nullable(Of UserGroupRepresentation), client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task(Of DirectoryEntry)" />
      <MemberSignature Language="F#" Value="static member GetFileStatusAsync : string * Nullable&lt;Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt; * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt;" Usage="Microsoft.Azure.DataLake.Store.Core.GetFileStatusAsync (path, userIdFormat, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;GetFileStatusAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="userIdFormat" Type="System.Nullable&lt;Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt;" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Pfad der Datei oder des Verzeichnisses</param>
        <param name="userIdFormat">Wie werden die Benutzer oder Gruppe Objekt dargestellt</param>
        <param name="client">ADLS-Client</param>
        <param name="req">Optionen zum Ändern des Verhaltens der HTTP-Anforderung </param>
        <param name="resp">Speichert die Antwort/Ausgabe der HTTP-Anforderung </param>
        <param name="cancelToken">CancellationToken, um die Anforderung abzubrechen</param>
        <summary>
            Ruft Metadaten, z. B. vollständiger Pfad, Typ (Datei oder Verzeichnis), Gruppe, Benutzer, Berechtigungen, Länge, der letzten Zugriffszeit, Uhrzeit der letzten Änderung, Ablaufzeit Acl Bit Replikation Faktor
            </summary>
        <returns>Gibt die Metadaten der Datei oder des Verzeichnisses zurück</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt;&gt; ListStatusAsync (string path, string listAfter, string listBefore, int listSize, Nullable&lt;Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt; userIdFormat, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.DirectoryEntry&gt;&gt; ListStatusAsync(string path, string listAfter, string listBefore, int32 listSize, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt; userIdFormat, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.ListStatusAsync(System.String,System.String,System.String,System.Int32,System.Nullable{Microsoft.Azure.DataLake.Store.UserGroupRepresentation},Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ListStatusAsync (path As String, listAfter As String, listBefore As String, listSize As Integer, userIdFormat As Nullable(Of UserGroupRepresentation), client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task(Of List(Of DirectoryEntry))" />
      <MemberSignature Language="F#" Value="static member ListStatusAsync : string * string * string * int * Nullable&lt;Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt; * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt;&gt;" Usage="Microsoft.Azure.DataLake.Store.Core.ListStatusAsync (path, listAfter, listBefore, listSize, userIdFormat, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;ListStatusAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="listAfter" Type="System.String" />
        <Parameter Name="listBefore" Type="System.String" />
        <Parameter Name="listSize" Type="System.Int32" />
        <Parameter Name="userIdFormat" Type="System.Nullable&lt;Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt;" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Pfad des Verzeichnisses</param>
        <param name="listAfter">Dateiname nach der Liste der Dateien vom Server abgerufen werden sollen</param>
        <param name="listBefore">FileName bis zu dem Liste der Dateien vom Server abgerufen werden sollen</param>
        <param name="listSize">Die Listengröße vom Server abgerufen</param>
        <param name="userIdFormat">Wie werden die Benutzer oder Gruppe Objekt dargestellt</param>
        <param name="client">ADLS-Client</param>
        <param name="req">Optionen zum Ändern des Verhaltens der HTTP-Anforderung </param>
        <param name="resp">Speichert die Antwort/Ausgabe der HTTP-Anforderung </param>
        <param name="cancelToken">CancellationToken, um die Anforderung abzubrechen</param>
        <summary>
            Listet die Unterverzeichnisse oder in einem Verzeichnis enthaltenen Dateien
            </summary>
        <returns>Liste der directoryentries</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MkdirsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; MkdirsAsync (string path, string octalPermission, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; MkdirsAsync(string path, string octalPermission, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.MkdirsAsync(System.String,System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function MkdirsAsync (path As String, octalPermission As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="static member MkdirsAsync : string * string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.DataLake.Store.Core.MkdirsAsync (path, octalPermission, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;MkdirsAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="octalPermission" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Pfad des Verzeichnisses</param>
        <param name="octalPermission">Oktale Berechtigung</param>
        <param name="client">ADLS-Client</param>
        <param name="req">Optionen zum Ändern des Verhaltens der HTTP-Anforderung </param>
        <param name="resp">Speichert die Antwort/Ausgabe der HTTP-Anforderung </param>
        <param name="cancelToken">CancellationToken, um die Anforderung abzubrechen</param>
        <summary>
            Erstellt ein Verzeichnis. 
            </summary>
        <returns>"true", wenn sie das Verzeichnis andernfalls "false" wird erstellt</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModifyAclEntriesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ModifyAclEntriesAsync (string path, System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpecList, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ModifyAclEntriesAsync(string path, class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpecList, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.ModifyAclEntriesAsync(System.String,System.Collections.Generic.List{Microsoft.Azure.DataLake.Store.Acl.AclEntry},Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ModifyAclEntriesAsync (path As String, aclSpecList As List(Of AclEntry), client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member ModifyAclEntriesAsync : string * System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.ModifyAclEntriesAsync (path, aclSpecList, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;ModifyAclEntriesAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclSpecList" Type="System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Pfad der Datei oder des Verzeichnisses</param>
        <param name="aclSpecList">Liste der Acl-Einträge zu ändern</param>
        <param name="client">ADLS-Client</param>
        <param name="req">Optionen zum Ändern des Verhaltens der HTTP-Anforderung </param>
        <param name="resp">Speichert die Antwort/Ausgabe der HTTP-Anforderung </param>
        <param name="cancelToken">CancellationToken, um die Anforderung abzubrechen</param>
        <summary>
            Ändert die Acl-Einträge einer Datei oder ein Verzeichnis mit die angegebene ACL-Liste. Er führt die vorhandenen ACL zusammen mit angegebene Liste aufzulisten.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModifyAclEntriesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ModifyAclEntriesAsync (string path, string aclSpec, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ModifyAclEntriesAsync(string path, string aclSpec, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.ModifyAclEntriesAsync(System.String,System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ModifyAclEntriesAsync (path As String, aclSpec As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member ModifyAclEntriesAsync : string * string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.ModifyAclEntriesAsync (path, aclSpec, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;ModifyAclEntriesAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclSpec" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Pfad der Datei oder des Verzeichnisses</param>
        <param name="aclSpec">AclSpec-Zeichenfolge, die ACL-Einträge durch Komma getrennt enthält </param>
        <param name="client">ADLS-Client</param>
        <param name="req">Optionen zum Ändern des Verhaltens der HTTP-Anforderung </param>
        <param name="resp">Speichert die Antwort/Ausgabe der HTTP-Anforderung </param>
        <param name="cancelToken">CancellationToken, um die Anforderung abzubrechen</param>
        <summary>
            Ändert die Acl-Einträge einer Datei oder ein Verzeichnis mit die angegebene ACL-Liste. Er führt die vorhandenen ACL zusammen mit angegebene Liste aufzulisten.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Open">
      <MemberSignature Language="C#" Value="public static int Open (string path, string sessionId, long offsetFile, byte[] buffer, int offset, int lengthFile, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig int32 Open(string path, string sessionId, int64 offsetFile, unsigned int8[] buffer, int32 offset, int32 lengthFile, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.Open(System.String,System.String,System.Int64,System.Byte[],System.Int32,System.Int32,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Open (path As String, sessionId As String, offsetFile As Long, buffer As Byte(), offset As Integer, lengthFile As Integer, client As AdlsClient, req As RequestOptions, resp As OperationResponse) As Integer" />
      <MemberSignature Language="F#" Value="static member Open : string * string * int64 * byte[] * int * int * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse -&gt; int" Usage="Microsoft.Azure.DataLake.Store.Core.Open (path, sessionId, offsetFile, buffer, offset, lengthFile, client, req, resp)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="offsetFile" Type="System.Int64" />
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="lengthFile" Type="System.Int32" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
      </Parameters>
      <Docs>
        <param name="path">Pfad der Datei</param>
        <param name="sessionId">UUID, die verwendet wird, um den Handler für Dateien (Datenstrom) einfach auf den Server zu erhalten.</param>
        <param name="offsetFile">Offset in der Datei, bei der Daten aus gelesen werden</param>
        <param name="buffer"> Puffer, in dem gelesenen Daten gespeichert werden soll</param>
        <param name="offset">Offset im Puffer, in dem Daten gelesen werden</param>
        <param name="lengthFile">Länge der Daten gelesen werden</param>
        <param name="client">ADLS-Client</param>
        <param name="req">Optionen zum Ändern des Verhaltens der HTTP-Anforderung </param>
        <param name="resp">Speichert die Antwort/Ausgabe der HTTP-Anforderung </param>
        <summary>
            Liest eine Datei vom Server an. Dies ist die synchrone Operation.
            </summary>
        <returns>Anzahl der gelesenen bytes</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;int&gt; OpenAsync (string path, string sessionId, long offsetFile, byte[] buffer, int offset, int lengthFile, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;int32&gt; OpenAsync(string path, string sessionId, int64 offsetFile, unsigned int8[] buffer, int32 offset, int32 lengthFile, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.OpenAsync(System.String,System.String,System.Int64,System.Byte[],System.Int32,System.Int32,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OpenAsync (path As String, sessionId As String, offsetFile As Long, buffer As Byte(), offset As Integer, lengthFile As Integer, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task(Of Integer)" />
      <MemberSignature Language="F#" Value="static member OpenAsync : string * string * int64 * byte[] * int * int * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="Microsoft.Azure.DataLake.Store.Core.OpenAsync (path, sessionId, offsetFile, buffer, offset, lengthFile, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;OpenAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="offsetFile" Type="System.Int64" />
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="lengthFile" Type="System.Int32" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Pfad der Datei</param>
        <param name="sessionId">UUID, die verwendet wird, um den Handler für Dateien (Datenstrom) einfach auf den Server zu erhalten.</param>
        <param name="offsetFile">Offset in der Datei, bei der Daten aus gelesen werden</param>
        <param name="buffer"> Puffer, in dem gelesenen Daten gespeichert werden soll</param>
        <param name="offset">Offset im Puffer, in dem Daten gelesen werden</param>
        <param name="lengthFile">Länge der Daten gelesen werden</param>
        <param name="client">ADLS-Client</param>
        <param name="req">Optionen zum Ändern des Verhaltens der HTTP-Anforderung </param>
        <param name="resp">Speichert die Antwort/Ausgabe der HTTP-Anforderung </param>
        <param name="cancelToken">CancellationToken, um die Anforderung abzubrechen</param>
        <summary>
            Liest eine Datei vom Server an. Das ist ein asynchroner Vorgang.
            </summary>
        <returns>Anzahl der gelesenen bytes</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAclAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RemoveAclAsync (string path, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RemoveAclAsync(string path, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.RemoveAclAsync(System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function RemoveAclAsync (path As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member RemoveAclAsync : string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.RemoveAclAsync (path, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;RemoveAclAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Pfad der Datei oder des Verzeichnisses</param>
        <param name="client">ADLS-Client</param>
        <param name="req">Optionen zum Ändern des Verhaltens der HTTP-Anforderung </param>
        <param name="resp">Speichert die Antwort/Ausgabe der HTTP-Anforderung </param>
        <param name="cancelToken">CancellationToken, um die Anforderung abzubrechen</param>
        <summary>
            Entfernt alle Acl-Einträge für eine Datei oder ein Verzeichnis an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAclEntriesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RemoveAclEntriesAsync (string path, System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpecList, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RemoveAclEntriesAsync(string path, class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpecList, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.RemoveAclEntriesAsync(System.String,System.Collections.Generic.List{Microsoft.Azure.DataLake.Store.Acl.AclEntry},Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function RemoveAclEntriesAsync (path As String, aclSpecList As List(Of AclEntry), client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member RemoveAclEntriesAsync : string * System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.RemoveAclEntriesAsync (path, aclSpecList, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;RemoveAclEntriesAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclSpecList" Type="System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Pfad der Datei oder des Verzeichnisses</param>
        <param name="aclSpecList">Liste der zu entfernenden Acl-Einträge</param>
        <param name="client">ADLS-Client</param>
        <param name="req">Optionen zum Ändern des Verhaltens der HTTP-Anforderung </param>
        <param name="resp">Speichert die Antwort/Ausgabe der HTTP-Anforderung </param>
        <param name="cancelToken">CancellationToken, um die Anforderung abzubrechen</param>
        <summary>
            Entfernt den angegebenen Acl-Einträge für eine Datei oder ein Verzeichnis.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAclEntriesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RemoveAclEntriesAsync (string path, string aclSpec, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RemoveAclEntriesAsync(string path, string aclSpec, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.RemoveAclEntriesAsync(System.String,System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function RemoveAclEntriesAsync (path As String, aclSpec As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member RemoveAclEntriesAsync : string * string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.RemoveAclEntriesAsync (path, aclSpec, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;RemoveAclEntriesAsync&gt;d__28))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclSpec" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Pfad der Datei oder des Verzeichnisses</param>
        <param name="aclSpec">Zeichenfolge, die zu entfernenden Acl-Einträge enthält.</param>
        <param name="client">ADLS-Client</param>
        <param name="req">Optionen zum Ändern des Verhaltens der HTTP-Anforderung </param>
        <param name="resp">Speichert die Antwort/Ausgabe der HTTP-Anforderung </param>
        <param name="cancelToken">CancellationToken, um die Anforderung abzubrechen</param>
        <summary>
            Entfernt den angegebenen Acl-Einträge für eine Datei oder ein Verzeichnis.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDefaultAclAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RemoveDefaultAclAsync (string path, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RemoveDefaultAclAsync(string path, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.RemoveDefaultAclAsync(System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function RemoveDefaultAclAsync (path As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member RemoveDefaultAclAsync : string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.RemoveDefaultAclAsync (path, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;RemoveDefaultAclAsync&gt;d__30))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Pfad der Datei oder des Verzeichnisses</param>
        <param name="client">ADLS-Client</param>
        <param name="req">Optionen zum Ändern des Verhaltens der HTTP-Anforderung </param>
        <param name="resp">Speichert die Antwort/Ausgabe der HTTP-Anforderung </param>
        <param name="cancelToken">CancellationToken, um die Anforderung abzubrechen</param>
        <summary>
            Entfernt alle Acl-Einträge des AclScope-Standard für eine Datei oder ein Verzeichnis an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenameAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; RenameAsync (string path, string destination, bool overwrite, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; RenameAsync(string path, string destination, bool overwrite, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.RenameAsync(System.String,System.String,System.Boolean,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function RenameAsync (path As String, destination As String, overwrite As Boolean, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="static member RenameAsync : string * string * bool * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.DataLake.Store.Core.RenameAsync (path, destination, overwrite, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;RenameAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="destination" Type="System.String" />
        <Parameter Name="overwrite" Type="System.Boolean" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Pfad der Quelldatei oder des Verzeichnisses</param>
        <param name="destination">Zielpfad</param>
        <param name="overwrite">Für die Datei: Wenn "true" klicken Sie dann die Zieldatei überschreibt, sofern für Verzeichnis vorhanden: Wenn das Zielverzeichnis vorhanden ist, hat dieses Flag keine. Da es die Quelle eine Ebene unter Ziel versetzt.
                                    Wenn ein Unterverzeichnis mit demselben Namen wie eine Ebene unter der Zielpfad der Datenquelle vorhanden ist, hat dieses Flag keine verwenden. Benennen Sie ein Fehler auftritt  </param>
        <param name="client">ADLS-Client</param>
        <param name="req">Optionen zum Ändern des Verhaltens der HTTP-Anforderung </param>
        <param name="resp">Speichert die Antwort/Ausgabe der HTTP-Anforderung </param>
        <param name="cancelToken">CancellationToken, um die Anforderung abzubrechen</param>
        <summary>
            Benennt einen Pfad an.
            Zum Umbenennen des Verzeichnisses: Wenn das Ziel vorhanden ist, dann er die Quelle eine Ebene unter dem Ziel legt.
            </summary>
        <returns>True, wenn die Umbenennung erfolgreich, andernfalls "false" ist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAclAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SetAclAsync (string path, System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpecList, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SetAclAsync(string path, class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpecList, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.SetAclAsync(System.String,System.Collections.Generic.List{Microsoft.Azure.DataLake.Store.Acl.AclEntry},Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SetAclAsync (path As String, aclSpecList As List(Of AclEntry), client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member SetAclAsync : string * System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.SetAclAsync (path, aclSpecList, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;SetAclAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclSpecList" Type="System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Pfad der Datei oder des Verzeichnisses</param>
        <param name="aclSpecList">Liste der Acl-Einträge festlegen </param>
        <param name="client">ADLS-Client</param>
        <param name="req">Optionen zum Ändern des Verhaltens der HTTP-Anforderung </param>
        <param name="resp">Speichert die Antwort/Ausgabe der HTTP-Anforderung </param>
        <param name="cancelToken">CancellationToken, um die Anforderung abzubrechen</param>
        <summary>
            Legt die Acl-Einträge für eine Datei oder ein Verzeichnis fest. Es werden die vorhandenen Acl-Einträge für den Pfad.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAclAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SetAclAsync (string path, string aclSpec, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SetAclAsync(string path, string aclSpec, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.SetAclAsync(System.String,System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SetAclAsync (path As String, aclSpec As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member SetAclAsync : string * string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.SetAclAsync (path, aclSpec, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;SetAclAsync&gt;d__26))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclSpec" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Pfad der Datei oder des Verzeichnisses</param>
        <param name="aclSpec">AclSpec-Zeichenfolge, die ACL-Einträge durch Komma getrennt enthält </param>
        <param name="client">ADLS-Client</param>
        <param name="req">Optionen zum Ändern des Verhaltens der HTTP-Anforderung </param>
        <param name="resp">Speichert die Antwort/Ausgabe der HTTP-Anforderung </param>
        <param name="cancelToken">CancellationToken, um die Anforderung abzubrechen</param>
        <summary>
            Legt die Acl-Einträge für eine Datei oder ein Verzeichnis fest. Es werden die vorhandenen Acl-Einträge für den Pfad.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetExpiryTimeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SetExpiryTimeAsync (string path, Microsoft.Azure.DataLake.Store.ExpiryOption opt, long expiryTime, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SetExpiryTimeAsync(string path, valuetype Microsoft.Azure.DataLake.Store.ExpiryOption opt, int64 expiryTime, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.SetExpiryTimeAsync(System.String,Microsoft.Azure.DataLake.Store.ExpiryOption,System.Int64,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SetExpiryTimeAsync (path As String, opt As ExpiryOption, expiryTime As Long, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member SetExpiryTimeAsync : string * Microsoft.Azure.DataLake.Store.ExpiryOption * int64 * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.SetExpiryTimeAsync (path, opt, expiryTime, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;SetExpiryTimeAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="opt" Type="Microsoft.Azure.DataLake.Store.ExpiryOption" />
        <Parameter Name="expiryTime" Type="System.Int64" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Pfad der Datei</param>
        <param name="opt">Andere Art von Ablauf-Methode, z. B.: nie ablaufen soll, relativ zum jetzt usw., die definiert, wie Sie ExpiryTime auswerten</param>
        <param name="expiryTime">Nach Ablauf der Zeitwert. Der Interepreation abhängig ist, auf welche Benutzer ExpiryOption übergibt</param>
        <param name="client">ADLS-Client</param>
        <param name="req">Optionen zum Ändern des Verhaltens der HTTP-Anforderung </param>
        <param name="resp">Speichert die Antwort/Ausgabe der HTTP-Anforderung </param>
        <param name="cancelToken">CancellationToken, um die Anforderung abzubrechen</param>
        <summary>
            Legen Sie die Ablaufzeit
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetOwnerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SetOwnerAsync (string path, string user, string group, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SetOwnerAsync(string path, string user, string group, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.SetOwnerAsync(System.String,System.String,System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SetOwnerAsync (path As String, user As String, group As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member SetOwnerAsync : string * string * string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.SetOwnerAsync (path, user, group, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;SetOwnerAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="user" Type="System.String" />
        <Parameter Name="group" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Pfad der Datei oder eines Verzeichnisses</param>
        <param name="user">Besitzer-Id des Pfads</param>
        <param name="group">Gruppen-Id des Pfads</param>
        <param name="client">ADLS-Client</param>
        <param name="req">Optionen zum Ändern des Verhaltens der HTTP-Anforderung </param>
        <param name="resp">Speichert die Antwort/Ausgabe der HTTP-Anforderung </param>
        <param name="cancelToken">CancellationToken, um die Anforderung abzubrechen</param>
        <summary>
            Legt den Besitzer oder / und des Pfads
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SetPermissionAsync (string path, string permission, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SetPermissionAsync(string path, string permission, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.SetPermissionAsync(System.String,System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SetPermissionAsync (path As String, permission As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member SetPermissionAsync : string * string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.SetPermissionAsync (path, permission, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;SetPermissionAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="permission" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Pfad der Datei oder des Verzeichnisses</param>
        <param name="permission">Berechtigung für das Einchecken oktale Unix-Format. Z. B., ob der Benutzer möchte, um festzustellen, ob der Besitzer gelesen hat schreiben execute-Berechtigung, alle Gruppen über die Schreibberechtigung Lese- und andere hat, dass die Berechtigung der Zeichenfolge 741 wäre lesen </param>
        <param name="client">ADLS-Client</param>
        <param name="req">Optionen zum Ändern des Verhaltens der HTTP-Anforderung </param>
        <param name="resp">Speichert die Antwort/Ausgabe der HTTP-Anforderung </param>
        <param name="cancelToken">CancellationToken, um die Anforderung abzubrechen</param>
        <summary>
            Die Berechtigungssätze des angegebenen Pfads.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>