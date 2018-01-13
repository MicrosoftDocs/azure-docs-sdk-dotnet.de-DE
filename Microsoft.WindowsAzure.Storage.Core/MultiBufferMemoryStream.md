<Type Name="MultiBufferMemoryStream" FullName="Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream">
  <TypeSignature Language="C#" Value="public class MultiBufferMemoryStream : System.IO.Stream" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MultiBufferMemoryStream extends System.IO.Stream" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream" />
  <TypeSignature Language="VB.NET" Value="Public Class MultiBufferMemoryStream&#xA;Inherits Stream" />
  <TypeSignature Language="F#" Value="type MultiBufferMemoryStream = class&#xA;    inherit Stream" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.IO.Stream</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erstellt einen mehrpufferstream, dessen Zusatzspeicher Arbeitsspeicher ist.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiBufferMemoryStream (Microsoft.WindowsAzure.Storage.IBufferManager bufferManager, int bufferSize = 65536);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.IBufferManager bufferManager, int32 bufferSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.#ctor(Microsoft.WindowsAzure.Storage.IBufferManager,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (bufferManager As IBufferManager, Optional bufferSize As Integer = 65536)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream : Microsoft.WindowsAzure.Storage.IBufferManager * int -&gt; Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream" Usage="new Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream (bufferManager, bufferSize)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="bufferManager" Type="Microsoft.WindowsAzure.Storage.IBufferManager" />
        <Parameter Name="bufferSize" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="bufferManager">Die <see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" /> zum Abrufen und Zurückgeben von Puffern für den Stream. Möglicherweise <c>null</c>.</param>
        <param name="bufferSize">Die Puffergröße für jeden Block zu verwenden. Die Standardgröße beträgt 64 KB. Beachten Sie, dass dieser Parameter ignoriert, wenn ein <see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" /> angegeben ist.</param>
        <summary>
             Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream" /> Klasse mit dem angegebenen Puffer-Manager.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFastCopyTo">
      <MemberSignature Language="C#" Value="public IAsyncResult BeginFastCopyTo (System.IO.Stream destination, Nullable&lt;DateTime&gt; expiryTime, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.IAsyncResult BeginFastCopyTo(class System.IO.Stream destination, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; expiryTime, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.BeginFastCopyTo(System.IO.Stream,System.Nullable{System.DateTime},System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function BeginFastCopyTo (destination As Stream, expiryTime As Nullable(Of DateTime), callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="member this.BeginFastCopyTo : System.IO.Stream * Nullable&lt;DateTime&gt; * AsyncCallback * obj -&gt; IAsyncResult" Usage="multiBufferMemoryStream.BeginFastCopyTo (destination, expiryTime, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="destination" Type="System.IO.Stream" />
        <Parameter Name="expiryTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="destination">Der Stream, in den der Inhalt des aktuellen Stream kopiert wird.</param>
        <param name="expiryTime">DateTime-Wert, der angibt, der Ablaufzeit.</param>
        <param name="callback">Ein optionaler asynchroner Rückruf, der aufgerufen werden, wenn der Kopiervorgang abgeschlossen ist.</param>
        <param name="state">Ein vom Benutzer bereitgestelltes Objekt, das dieser bestimmten asynchronen Datenbankkopie-Anforderung von anderen Anforderungen unterscheidet.</param>
        <summary>
            Startet einen asynchronen Vorgang, Fast kopieren.
            </summary>
        <returns>Ein "IAsyncResult", die die asynchrone Kopie zu darstellt, die möglicherweise noch aussteht.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRead">
      <MemberSignature Language="C#" Value="public override IAsyncResult BeginRead (byte[] buffer, int offset, int count, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.IAsyncResult BeginRead(unsigned int8[] buffer, int32 offset, int32 count, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.BeginRead(System.Byte[],System.Int32,System.Int32,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BeginRead (buffer As Byte(), offset As Integer, count As Integer, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.BeginRead : byte[] * int * int * AsyncCallback * obj -&gt; IAsyncResult" Usage="multiBufferMemoryStream.BeginRead (buffer, offset, count, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="buffer">Nach dem Beenden dieser Methode enthält der Puffer das angegebene Bytearray mit den Werten zwischen Offset und (Offset + Zähler - 1), die durch aus der aktuellen Quelle gelesene Bytes ersetzt wurden.</param>
        <param name="offset">Der nullbasierte Byteoffset im Puffer, ab dem die aus dem aktuellen Stream gelesenen Daten gespeichert werden.</param>
        <param name="count">Die maximale Anzahl der zu lesenden Bytes.</param>
        <param name="callback">Ein optionaler asynchroner Rückruf, der nach Abschluss des Lesevorgangs aufgerufen werden soll.</param>
        <param name="state">Ein vom Benutzer bereitgestelltes Objekt, das diese asynchrone Leseanforderung von anderen Anforderungen unterscheidet.</param>
        <summary>
            Beginnt einen asynchronen Lesevorgang.
            </summary>
        <returns>Ein "IAsyncResult", das den asynchronen Lesevorgang darstellt, der möglicherweise noch aussteht.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginWrite">
      <MemberSignature Language="C#" Value="public override IAsyncResult BeginWrite (byte[] buffer, int offset, int count, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.IAsyncResult BeginWrite(unsigned int8[] buffer, int32 offset, int32 count, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.BeginWrite(System.Byte[],System.Int32,System.Int32,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BeginWrite (buffer As Byte(), offset As Integer, count As Integer, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.BeginWrite : byte[] * int * int * AsyncCallback * obj -&gt; IAsyncResult" Usage="multiBufferMemoryStream.BeginWrite (buffer, offset, count, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="buffer">Der Puffer, aus dem Daten geschrieben werden sollen.</param>
        <param name="offset">Der nullbasierte Byteoffset im Puffer, ab dem Bytes in den aktuellen Stream kopiert werden soll.</param>
        <param name="count">Die Anzahl der zu schreibenden Bytes.</param>
        <param name="callback">Ein optionaler asynchroner Rückruf, der nach Abschluss des Schreibvorgangs aufgerufen wird.</param>
        <param name="state">Ein vom Benutzer bereitgestelltes Objekt, das diese asynchrone Schreibanforderung von anderen Anforderungen unterscheidet.</param>
        <summary>
            Beginnt einen asynchronen Schreibvorgang.
            </summary>
        <returns>Ein "IAsyncResult", das den asynchronen Schreibvorgang darstellt, der möglicherweise noch aussteht.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanRead">
      <MemberSignature Language="C#" Value="public override bool CanRead { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CanRead" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.CanRead" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property CanRead As Boolean" />
      <MemberSignature Language="F#" Value="member this.CanRead : bool" Usage="Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.CanRead" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert ab, der angibt, ob der aktuelle Stream Lesevorgänge unterstützt.
            </summary>
        <value>
          <c>"true"</c> , wenn der Stream Lesevorgänge unterstützt, andernfalls <c>"false"</c>.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanSeek">
      <MemberSignature Language="C#" Value="public override bool CanSeek { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CanSeek" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.CanSeek" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property CanSeek As Boolean" />
      <MemberSignature Language="F#" Value="member this.CanSeek : bool" Usage="Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.CanSeek" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert ab, der angibt, ob der aktuelle Stream Suchvorgänge unterstützt.
            </summary>
        <value>
          <c>"true"</c> , wenn der Stream Suchvorgänge unterstützt, andernfalls <c>"false"</c>.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanWrite">
      <MemberSignature Language="C#" Value="public override bool CanWrite { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CanWrite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.CanWrite" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property CanWrite As Boolean" />
      <MemberSignature Language="F#" Value="member this.CanWrite : bool" Usage="Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.CanWrite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert ab, der angibt, ob der aktuelle Stream Schreibvorgänge unterstützt.
            </summary>
        <value>
          <c>"true"</c> , wenn der Stream Schreibvorgänge unterstützt, andernfalls <c>"false"</c>.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputeMD5Hash">
      <MemberSignature Language="C#" Value="public string ComputeMD5Hash ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string ComputeMD5Hash() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.ComputeMD5Hash" />
      <MemberSignature Language="VB.NET" Value="Public Function ComputeMD5Hash () As String" />
      <MemberSignature Language="F#" Value="member this.ComputeMD5Hash : unit -&gt; string" Usage="multiBufferMemoryStream.ComputeMD5Hash " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Berechnet den Hashwert für diesen Datenstrom.
            </summary>
        <returns>Die Zeichenfolgendarstellung des berechneten Hashwerts.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected override void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="override this.Dispose : bool -&gt; unit" Usage="multiBufferMemoryStream.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing">true, um sowohl verwaltete als auch nicht verwaltete Ressourcen freizugeben, false, um nur nicht verwaltete Ressourcen freizugeben.</param>
        <summary>
            Gibt alle vom <see cref="T:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream" /> verwendeten Ressourcen frei.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndFastCopyTo">
      <MemberSignature Language="C#" Value="public void EndFastCopyTo (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void EndFastCopyTo(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.EndFastCopyTo(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Sub EndFastCopyTo (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="member this.EndFastCopyTo : IAsyncResult -&gt; unit" Usage="multiBufferMemoryStream.EndFastCopyTo asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Der Verweis auf die ausstehende asynchrone Anforderung, die beendet werden soll.</param>
        <summary>
            Beendet einen asynchronen Kopiervorgang an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndRead">
      <MemberSignature Language="C#" Value="public override int EndRead (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 EndRead(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.EndRead(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function EndRead (asyncResult As IAsyncResult) As Integer" />
      <MemberSignature Language="F#" Value="override this.EndRead : IAsyncResult -&gt; int" Usage="multiBufferMemoryStream.EndRead asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Der Verweis auf die ausstehende asynchrone Anforderung, die beendet werden soll.</param>
        <summary>
            Wartet, bis der ausstehende asynchrone Lesevorgang abgeschlossen ist.
            </summary>
        <returns>Die Gesamtanzahl der in den Puffer gelesenen Bytes. Dies kann weniger als die Anzahl der angeforderten Bytes sein, wenn diese Anzahl an Bytes derzeit nicht verfügbar ist, oder 0 (null), wenn das Streamende erreicht ist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndWrite">
      <MemberSignature Language="C#" Value="public override void EndWrite (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void EndWrite(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.EndWrite(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub EndWrite (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.EndWrite : IAsyncResult -&gt; unit" Usage="multiBufferMemoryStream.EndWrite asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Der Verweis auf die ausstehende asynchrone Anforderung, die beendet werden soll.</param>
        <summary>
            Beendet einen asynchronen Schreibvorgang.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FastCopyTo">
      <MemberSignature Language="C#" Value="public void FastCopyTo (System.IO.Stream destination, Nullable&lt;DateTime&gt; expiryTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void FastCopyTo(class System.IO.Stream destination, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; expiryTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.FastCopyTo(System.IO.Stream,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub FastCopyTo (destination As Stream, expiryTime As Nullable(Of DateTime))" />
      <MemberSignature Language="F#" Value="member this.FastCopyTo : System.IO.Stream * Nullable&lt;DateTime&gt; -&gt; unit" Usage="multiBufferMemoryStream.FastCopyTo (destination, expiryTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="destination" Type="System.IO.Stream" />
        <Parameter Name="expiryTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="destination">Der Stream, in den der Inhalt des aktuellen Stream kopiert wird.</param>
        <param name="expiryTime">Ein DateTime-Wert, der angibt, der Ablaufzeit.</param>
        <summary>
            Liest alle Bytes aus dem aktuellen Stream und schreibt sie in einen anderen Datenstrom. Diese Methode schreibt direkt auf den Zieldatenstrom, statt die Daten in einen temporären Puffer kopiert werden.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Flush">
      <MemberSignature Language="C#" Value="public override void Flush ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Flush() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.Flush" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Flush ()" />
      <MemberSignature Language="F#" Value="override this.Flush : unit -&gt; unit" Usage="multiBufferMemoryStream.Flush " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Jeder Vorgang wird nicht ausgeführt werden, da der Datenstrom ein Speicherstream ist.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Length">
      <MemberSignature Language="C#" Value="public override long Length { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Length" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.Length" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Length As Long" />
      <MemberSignature Language="F#" Value="member this.Length : int64" Usage="Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.Length" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Länge des Streams in Bytes ab.
            </summary>
        <value>Ein Long-Wert, der die Länge des Streams in Bytes darstellt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Position">
      <MemberSignature Language="C#" Value="public override long Position { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Position" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.Position" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property Position As Long" />
      <MemberSignature Language="F#" Value="member this.Position : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.Position" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Position im aktuellen Stream ab oder legt diese fest.
            </summary>
        <value>Die aktuelle Position innerhalb des Streams.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="public override int Read (byte[] buffer, int offset, int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 Read(unsigned int8[] buffer, int32 offset, int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.Read(System.Byte[],System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Read (buffer As Byte(), offset As Integer, count As Integer) As Integer" />
      <MemberSignature Language="F#" Value="override this.Read : byte[] * int * int -&gt; int" Usage="multiBufferMemoryStream.Read (buffer, offset, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="buffer">Nach dem Beenden dieser Methode enthält der Puffer das angegebene Bytearray mit den Werten zwischen Offset und (Offset + Zähler - 1), die durch aus der aktuellen Quelle gelesene Bytes ersetzt wurden.</param>
        <param name="offset">Der nullbasierte Byteoffset im Puffer, ab dem die aus dem aktuellen Stream gelesenen Daten gespeichert werden.</param>
        <param name="count">Die maximale Anzahl der zu lesenden Bytes.</param>
        <summary>
            Liest einen Byteblock aus dem aktuellen Stream und schreibt die Daten in einen Puffer.
            </summary>
        <returns>Die Gesamtanzahl der in den Puffer gelesenen Bytes. Dies kann weniger als die Anzahl der angeforderten Bytes sein, wenn diese Anzahl an Bytes derzeit nicht verfügbar ist, oder 0 (null), wenn das Streamende erreicht ist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Seek">
      <MemberSignature Language="C#" Value="public override long Seek (long offset, System.IO.SeekOrigin origin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int64 Seek(int64 offset, valuetype System.IO.SeekOrigin origin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.Seek(System.Int64,System.IO.SeekOrigin)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Seek (offset As Long, origin As SeekOrigin) As Long" />
      <MemberSignature Language="F#" Value="override this.Seek : int64 * System.IO.SeekOrigin -&gt; int64" Usage="multiBufferMemoryStream.Seek (offset, origin)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="offset" Type="System.Int64" />
        <Parameter Name="origin" Type="System.IO.SeekOrigin" />
      </Parameters>
      <Docs>
        <param name="offset">Ein Byteoffset relativ zum Ursprungsparameter.</param>
        <param name="origin">Ein Wert vom Typ System.IO.SeekOrigin, der angibt, das der Bezugspunkt ist verwendet, um die neue Position ermittelt wird.</param>
        <summary>
            Legt die Position im aktuellen Stream fest.
            </summary>
        <returns>Die neue Position innerhalb des aktuellen Streams.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">Wird ausgelöst, wenn <paramref name="offset" /> ist für "SeekOrigin" ungültig.</exception>
      </Docs>
    </Member>
    <Member MemberName="SetLength">
      <MemberSignature Language="C#" Value="public override void SetLength (long value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void SetLength(int64 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.SetLength(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub SetLength (value As Long)" />
      <MemberSignature Language="F#" Value="override this.SetLength : int64 -&gt; unit" Usage="multiBufferMemoryStream.SetLength value" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="value" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="value">Die gewünschte Länge des aktuellen Streams in Bytes.</param>
        <summary>
            Legt die Länge des aktuellen Streams fest.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Wenn die <paramref name="value" /> ist ein negativer Wert.</exception>
      </Docs>
    </Member>
    <Member MemberName="Write">
      <MemberSignature Language="C#" Value="public override void Write (byte[] buffer, int offset, int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Write(unsigned int8[] buffer, int32 offset, int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.Write(System.Byte[],System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Write (buffer As Byte(), offset As Integer, count As Integer)" />
      <MemberSignature Language="F#" Value="override this.Write : byte[] * int * int -&gt; unit" Usage="multiBufferMemoryStream.Write (buffer, offset, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="buffer">Der Puffer, aus dem Daten geschrieben werden sollen.</param>
        <param name="offset">Der nullbasierte Byteoffset im Puffer, ab dem Bytes in den aktuellen Stream kopiert werden soll.</param>
        <param name="count">Die Anzahl der zu schreibenden Bytes. </param>
        <summary>
            Schreibt einen Byteblock mit den aus einem Puffer gelesenen Daten in den aktuellen Stream.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>