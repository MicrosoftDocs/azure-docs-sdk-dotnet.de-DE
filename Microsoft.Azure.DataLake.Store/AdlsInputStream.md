<Type Name="AdlsInputStream" FullName="Microsoft.Azure.DataLake.Store.AdlsInputStream">
  <TypeSignature Language="C#" Value="public class AdlsInputStream : System.IO.Stream" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AdlsInputStream extends System.IO.Stream" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.AdlsInputStream" />
  <TypeSignature Language="VB.NET" Value="Public Class AdlsInputStream&#xA;Inherits Stream" />
  <TypeSignature Language="F#" Value="type AdlsInputStream = class&#xA;    inherit Stream" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>0.1.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.IO.Stream</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ADLS-Eingabe-Datenstrom, der Daten aus einer Datei auf Data Lake liest. Er liest in einem Massenvorgang Daten vom Server auf einen Puffer und Wiederherstellungsprozessen gepufferte Ausgabe an den Client gemäß der Anforderung.
            Daten können asynchron/synchron gelesen werden. Daten können nacheinander oder von beliebigen Punkt in der Datei gelesen werden. Gelesen wurde, bis der Transportschicht vollständig synchron ist. ReadAsync ist vollständig synchron ist, bis der Transportschicht. 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected AdlsInputStream ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Nur für imitieren Zweck. Für imitieren Zweck können Sie von dieser Klasse erben und die Methoden überschreiben
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanRead">
      <MemberSignature Language="C#" Value="public override bool CanRead { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CanRead" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.AdlsInputStream.CanRead" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property CanRead As Boolean" />
      <MemberSignature Language="F#" Value="member this.CanRead : bool" Usage="Microsoft.Azure.DataLake.Store.AdlsInputStream.CanRead" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, ob Daten von Stream gelesen werden kann
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanSeek">
      <MemberSignature Language="C#" Value="public override bool CanSeek { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CanSeek" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.AdlsInputStream.CanSeek" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property CanSeek As Boolean" />
      <MemberSignature Language="F#" Value="member this.CanSeek : bool" Usage="Microsoft.Azure.DataLake.Store.AdlsInputStream.CanSeek" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, ob der Stream Daten durchsucht werden kann
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanWrite">
      <MemberSignature Language="C#" Value="public override bool CanWrite { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CanWrite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.AdlsInputStream.CanWrite" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property CanWrite As Boolean" />
      <MemberSignature Language="F#" Value="member this.CanWrite : bool" Usage="Microsoft.Azure.DataLake.Store.AdlsInputStream.CanWrite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, ob der Stream Daten schreiben
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected override void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="override this.Dispose : bool -&gt; unit" Usage="adlsInputStream.Dispose disposing" />
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
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing">"true", um sowohl verwaltete als auch nicht verwaltete Ressourcen freizugeben; "false", um ausschließlich nicht verwaltete Ressourcen freizugeben.</param>
        <summary>
            Die vom Stream nicht verwalteten Ressourcen frei und gibt optional die verwalteten Ressourcen frei
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Flush">
      <MemberSignature Language="C#" Value="public override void Flush ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Flush() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.Flush" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Flush ()" />
      <MemberSignature Language="F#" Value="override this.Flush : unit -&gt; unit" Usage="adlsInputStream.Flush " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Nicht unterstützt
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Length">
      <MemberSignature Language="C#" Value="public override long Length { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Length" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.AdlsInputStream.Length" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Length As Long" />
      <MemberSignature Language="F#" Value="member this.Length : int64" Usage="Microsoft.Azure.DataLake.Store.AdlsInputStream.Length" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gesamtlänge der Datei
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Position">
      <MemberSignature Language="C#" Value="public override long Position { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Position" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.AdlsInputStream.Position" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property Position As Long" />
      <MemberSignature Language="F#" Value="member this.Position : int64 with get, set" Usage="Microsoft.Azure.DataLake.Store.AdlsInputStream.Position" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.Read(System.Byte[],System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Read (output As Byte(), offset As Integer, count As Integer) As Integer" />
      <MemberSignature Language="F#" Value="override this.Read : byte[] * int * int -&gt; int" Usage="adlsInputStream.Read (output, offset, count)" />
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
        <Parameter Name="output" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="output">Ausgabebytearrays</param>
        <param name="offset">Offset, bei dem Daten im Ausgabearray eingefügt werden soll</param>
        <param name="count">Anzahl gelesener bytes</param>
        <summary>
            Liest eine Folge von Bytes aus dem aktuellen Stream und erhöht die Position im Stream um die Anzahl der Bytes, die synchronen Lesevorgang.
            </summary>
        <returns>Anzahl der gelesenen bytes</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="public int Read (long position, byte[] output, int offset, int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance int32 Read(int64 position, unsigned int8[] output, int32 offset, int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.Read(System.Int64,System.Byte[],System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function Read (position As Long, output As Byte(), offset As Integer, count As Integer) As Integer" />
      <MemberSignature Language="F#" Value="override this.Read : int64 * byte[] * int * int -&gt; int" Usage="adlsInputStream.Read (position, output, offset, count)" />
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
        <Parameter Name="position" Type="System.Int64" />
        <Parameter Name="output" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="position">Position in der Datei aus, in dem sie beginnen soll, Lesen von Daten</param>
        <param name="output">Ausgabebytearrays</param>
        <param name="offset">Offset, bei dem Daten im Ausgabearray eingefügt werden soll</param>
        <param name="count">Anzahl gelesener bytes</param>
        <summary>
            Liest eine Folge von Bytes direkt vom Server an. Es wird nichts in den Stream nicht aktualisiert.
            </summary>
        <returns>Anzahl der gelesenen bytes</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task&lt;int&gt; ReadAsync (byte[] output, int offset, int count, System.Threading.CancellationToken cancelToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task`1&lt;int32&gt; ReadAsync(unsigned int8[] output, int32 offset, int32 count, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.ReadAsync(System.Byte[],System.Int32,System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ReadAsync (output As Byte(), offset As Integer, count As Integer, cancelToken As CancellationToken) As Task(Of Integer)" />
      <MemberSignature Language="F#" Value="override this.ReadAsync : byte[] * int * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="adlsInputStream.ReadAsync (output, offset, count, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.AdlsInputStream/&lt;ReadAsync&gt;d__49))</AttributeName>
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
            Liest eine Folge von Bytes aus dem aktuellen Stream und erhöht die Position im Stream um die Anzahl der Bytes, die asynchronen Lesevorgang.
            </summary>
        <returns>Anzahl der gelesenen bytes</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;int&gt; ReadAsync (long position, byte[] output, int offset, int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int32&gt; ReadAsync(int64 position, unsigned int8[] output, int32 offset, int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.ReadAsync(System.Int64,System.Byte[],System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadAsync (position As Long, output As Byte(), offset As Integer, count As Integer) As Task(Of Integer)" />
      <MemberSignature Language="F#" Value="override this.ReadAsync : int64 * byte[] * int * int -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="adlsInputStream.ReadAsync (position, output, offset, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.AdlsInputStream/&lt;ReadAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="position" Type="System.Int64" />
        <Parameter Name="output" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="position">Position in der Datei aus, in dem sie beginnen soll, Lesen von Daten</param>
        <param name="output">Ausgabebytearrays</param>
        <param name="offset">Offset, bei dem Daten im Ausgabearray eingefügt werden soll</param>
        <param name="count">Anzahl gelesener bytes</param>
        <summary>
            Liest eine Folge von Bytes direkt vom Server an. Es wird nichts in den Stream nicht aktualisiert.
            </summary>
        <returns>Anzahl der gelesenen bytes</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Seek">
      <MemberSignature Language="C#" Value="public override long Seek (long offset, System.IO.SeekOrigin origin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int64 Seek(int64 offset, valuetype System.IO.SeekOrigin origin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.Seek(System.Int64,System.IO.SeekOrigin)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Seek (offset As Long, origin As SeekOrigin) As Long" />
      <MemberSignature Language="F#" Value="override this.Seek : int64 * System.IO.SeekOrigin -&gt; int64" Usage="adlsInputStream.Seek (offset, origin)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
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
            Aktualisiert die Position des Streams basierend auf "SeekOrigin"
            </summary>
        <returns>Aktuelle neue Position im stream</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetLength">
      <MemberSignature Language="C#" Value="public override void SetLength (long value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void SetLength(int64 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.SetLength(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub SetLength (value As Long)" />
      <MemberSignature Language="F#" Value="override this.SetLength : int64 -&gt; unit" Usage="adlsInputStream.SetLength value" />
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
        <Parameter Name="value" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="value"></param>
        <summary>
            Nicht unterstützt
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Write">
      <MemberSignature Language="C#" Value="public override void Write (byte[] buffer, int offset, int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Write(unsigned int8[] buffer, int32 offset, int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.Write(System.Byte[],System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Write (buffer As Byte(), offset As Integer, count As Integer)" />
      <MemberSignature Language="F#" Value="override this.Write : byte[] * int * int -&gt; unit" Usage="adlsInputStream.Write (buffer, offset, count)" />
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
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="buffer"></param>
        <param name="offset"></param>
        <param name="count"></param>
        <summary>
            Nicht unterstützt
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>