<Type Name="SyncMemoryStream" FullName="Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream">
  <TypeSignature Language="C#" Value="public class SyncMemoryStream : System.IO.MemoryStream" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SyncMemoryStream extends System.IO.MemoryStream" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream" />
  <TypeSignature Language="VB.NET" Value="Public Class SyncMemoryStream&#xA;Inherits MemoryStream" />
  <TypeSignature Language="F#" Value="type SyncMemoryStream = class&#xA;    inherit MemoryStream" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.IO.MemoryStream</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Diese Klasse bietet Außerkraftsetzungen von APM-Lese-/Schreibzugriff für Speicherstream zur Verbesserung der Leistung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncMemoryStream ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Klasse SyncMemoryStream mit einer erweiterbaren Kapazität, die mit 0 (null) initialisiert.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncMemoryStream (byte[] buffer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] buffer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream.#ctor(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (buffer As Byte())" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream : byte[] -&gt; Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream" Usage="new Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream buffer" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="buffer">Das Array vorzeichenloser Bytes, aus dem der aktuelle Stream erstellt werden soll.</param>
        <summary>
            Initialisiert eine neue, nicht veränderbare Größen Instanz der Klasse SyncMemoryStream basierend auf dem angegebenen Bytearray. 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncMemoryStream (byte[] buffer, int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] buffer, int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream.#ctor(System.Byte[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (buffer As Byte(), index As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream : byte[] * int -&gt; Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream" Usage="new Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream (buffer, index)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="buffer">Das Array vorzeichenloser Bytes, aus dem der aktuelle Stream erstellt werden soll.</param>
        <param name="index">Der Index in Puffer, an dem der Stream beginnt.</param>
        <summary>
            Initialisiert eine neue nicht veränderbare Größen Instanz der Klasse SyncMemoryStream anhand des angegebenen Bereichs (Indexes) eines Bytearrays. 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncMemoryStream (byte[] buffer, int index, int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] buffer, int32 index, int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream.#ctor(System.Byte[],System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (buffer As Byte(), index As Integer, count As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream : byte[] * int * int -&gt; Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream" Usage="new Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream (buffer, index, count)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="buffer">Das Array vorzeichenloser Bytes, aus dem der aktuelle Stream erstellt werden soll.</param>
        <param name="index">Der Index in Puffer, an dem der Stream beginnt.</param>
        <param name="count">Die Länge des Streams in Bytes.</param>
        <summary>
            Initialisiert eine neue nicht veränderbare Größen Instanz der Klasse SyncMemoryStream anhand des angegebenen Bereichs (Indexes) eines Bytearrays. 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRead">
      <MemberSignature Language="C#" Value="public override IAsyncResult BeginRead (byte[] buffer, int offset, int count, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.IAsyncResult BeginRead(unsigned int8[] buffer, int32 offset, int32 count, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream.BeginRead(System.Byte[],System.Int32,System.Int32,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BeginRead (buffer As Byte(), offset As Integer, count As Integer, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.BeginRead : byte[] * int * int * AsyncCallback * obj -&gt; IAsyncResult" Usage="syncMemoryStream.BeginRead (buffer, offset, count, callback, state)" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream.BeginWrite(System.Byte[],System.Int32,System.Int32,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BeginWrite (buffer As Byte(), offset As Integer, count As Integer, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.BeginWrite : byte[] * int * int * AsyncCallback * obj -&gt; IAsyncResult" Usage="syncMemoryStream.BeginWrite (buffer, offset, count, callback, state)" />
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
    <Member MemberName="EndRead">
      <MemberSignature Language="C#" Value="public override int EndRead (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 EndRead(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream.EndRead(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function EndRead (asyncResult As IAsyncResult) As Integer" />
      <MemberSignature Language="F#" Value="override this.EndRead : IAsyncResult -&gt; int" Usage="syncMemoryStream.EndRead asyncResult" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream.EndWrite(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub EndWrite (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.EndWrite : IAsyncResult -&gt; unit" Usage="syncMemoryStream.EndWrite asyncResult" />
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
  </Members>
</Type>