<Type Name="MockAdlsInputStream" FullName="Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsInputStream">
  <TypeSignature Language="C#" Value="public sealed class MockAdlsInputStream : Microsoft.Azure.DataLake.Store.AdlsInputStream" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MockAdlsInputStream extends Microsoft.Azure.DataLake.Store.AdlsInputStream" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsInputStream" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MockAdlsInputStream&#xA;Inherits AdlsInputStream" />
  <TypeSignature Language="F#" Value="type MockAdlsInputStream = class&#xA;    inherit AdlsInputStream" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.DataLake.Store.AdlsInputStream</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Modellieren der Adls-Eingabe-Datenstrom für Komponententest
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected override void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsInputStream.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="override this.Dispose : bool -&gt; unit" Usage="mockAdlsInputStream.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing">"true", um sowohl verwaltete als auch nicht verwaltete Ressourcen freizugeben; "false", um ausschließlich nicht verwaltete Ressourcen freizugeben.</param>
        <summary>
            Die vom Stream nicht verwalteten Ressourcen frei, und optional die verwalteten Ressourcen frei. Für diese Implementierung wir den zugrunde liegenden Stream nicht löschen, da wir den Stream für Lese- und Schreibberechtigungen verwenden.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Length">
      <MemberSignature Language="C#" Value="public override long Length { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Length" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsInputStream.Length" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Length As Long" />
      <MemberSignature Language="F#" Value="member this.Length : int64" Usage="Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsInputStream.Length" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Länge des Streams kann nicht festgelegt werden, nur abgerufen
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Position">
      <MemberSignature Language="C#" Value="public override long Position { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Position" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsInputStream.Position" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property Position As Long" />
      <MemberSignature Language="F#" Value="member this.Position : int64 with get, set" Usage="Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsInputStream.Position" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Position im Stream von Anfang
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="public override int Read (byte[] output, int offset, int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 Read(unsigned int8[] output, int32 offset, int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsInputStream.Read(System.Byte[],System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Read (output As Byte(), offset As Integer, count As Integer) As Integer" />
      <MemberSignature Language="F#" Value="override this.Read : byte[] * int * int -&gt; int" Usage="mockAdlsInputStream.Read (output, offset, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="output" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="output">Ausgabebytearrays</param>
        <param name="offset">Offset, bei dem Daten im Ausgabearray eingefügt werden soll</param>
        <param name="count">Anzahl gelesener bytes</param>
        <summary>
            Liest eine Folge von Bytes aus dem aktuellen zugrunde liegenden Stream und erhöht die Position im Stream um die Anzahl der Bytes, die synchronen Lesevorgang.
            </summary>
        <returns>Anzahl der gelesenen bytes</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task&lt;int&gt; ReadAsync (byte[] output, int offset, int count, System.Threading.CancellationToken cancelToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task`1&lt;int32&gt; ReadAsync(unsigned int8[] output, int32 offset, int32 count, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsInputStream.ReadAsync(System.Byte[],System.Int32,System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ReadAsync (output As Byte(), offset As Integer, count As Integer, cancelToken As CancellationToken) As Task(Of Integer)" />
      <MemberSignature Language="F#" Value="override this.ReadAsync : byte[] * int * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="mockAdlsInputStream.ReadAsync (output, offset, count, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsInputStream/&lt;ReadAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="output" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="output">Ausgabebytearrays</param>
        <param name="offset">Offset, bei dem Daten im Ausgabearray eingefügt werden soll</param>
        <param name="count">Anzahl gelesener bytes</param>
        <param name="cancelToken">Abbruchtoken</param>
        <summary>
            Liest eine Folge von Bytes aus dem aktuellen zugrunde liegenden Stream und erhöht die Position im Stream um die Anzahl der Bytes, die asynchronen Lesevorgang.
            </summary>
        <returns>Anzahl der gelesenen bytes</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Seek">
      <MemberSignature Language="C#" Value="public override long Seek (long offset, System.IO.SeekOrigin origin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int64 Seek(int64 offset, valuetype System.IO.SeekOrigin origin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsInputStream.Seek(System.Int64,System.IO.SeekOrigin)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Seek (offset As Long, origin As SeekOrigin) As Long" />
      <MemberSignature Language="F#" Value="override this.Seek : int64 * System.IO.SeekOrigin -&gt; int64" Usage="mockAdlsInputStream.Seek (offset, origin)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="offset" Type="System.Int64" />
        <Parameter Name="origin" Type="System.IO.SeekOrigin" />
      </Parameters>
      <Docs>
        <param name="offset">Byte-Offset relativ zum Ursprungsparameter</param>
        <param name="origin">Ein Wert vom Typ "SeekOrigin", der angibt, das der Bezugspunkt ist verwendet, um die neue Position ermittelt wird.</param>
        <summary>
            Aktualisiert die Position des zugrunde liegenden Datenstrom auf Grundlage von "SeekOrigin"
            </summary>
        <returns>Aktuelle neue Position im stream</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>