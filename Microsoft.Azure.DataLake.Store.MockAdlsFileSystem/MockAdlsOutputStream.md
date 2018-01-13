<Type Name="MockAdlsOutputStream" FullName="Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsOutputStream">
  <TypeSignature Language="C#" Value="public sealed class MockAdlsOutputStream : Microsoft.Azure.DataLake.Store.AdlsOutputStream" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MockAdlsOutputStream extends Microsoft.Azure.DataLake.Store.AdlsOutputStream" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsOutputStream" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MockAdlsOutputStream&#xA;Inherits AdlsOutputStream" />
  <TypeSignature Language="F#" Value="type MockAdlsOutputStream = class&#xA;    inherit AdlsOutputStream" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.DataLake.Store.AdlsOutputStream</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Modellieren der Adls-Ausgabedatenstrom für Komponententest
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected override void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsOutputStream.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="override this.Dispose : bool -&gt; unit" Usage="mockAdlsOutputStream.Dispose disposing" />
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
    <Member MemberName="Flush">
      <MemberSignature Language="C#" Value="public override void Flush ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Flush() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsOutputStream.Flush" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Flush ()" />
      <MemberSignature Language="F#" Value="override this.Flush : unit -&gt; unit" Usage="mockAdlsOutputStream.Flush " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Synchrone Daten auf den zugrunde liegenden Stream aus Puffer geleert und aktualisiert die Metadaten
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FlushAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task FlushAsync (System.Threading.CancellationToken cancelToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task FlushAsync(valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsOutputStream.FlushAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function FlushAsync (cancelToken As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="override this.FlushAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="mockAdlsOutputStream.FlushAsync cancelToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsOutputStream/&lt;FlushAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancelToken">Abbruchtoken</param>
        <summary>
            Asynchron Daten vom Puffer auf den zugrunde liegenden Stream geleert und aktualisiert die Metadaten
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Position">
      <MemberSignature Language="C#" Value="public override long Position { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Position" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsOutputStream.Position" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property Position As Long" />
      <MemberSignature Language="F#" Value="member this.Position : int64 with get, set" Usage="Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsOutputStream.Position" />
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
            Set wird nicht unterstützt. Ruft die Position, in dem weitere Daten geschrieben werden
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Write">
      <MemberSignature Language="C#" Value="public override void Write (byte[] buffer, int offset, int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Write(unsigned int8[] buffer, int32 offset, int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsOutputStream.Write(System.Byte[],System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Write (buffer As Byte(), offset As Integer, count As Integer)" />
      <MemberSignature Language="F#" Value="override this.Write : byte[] * int * int -&gt; unit" Usage="mockAdlsOutputStream.Write (buffer, offset, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
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
        <param name="buffer">Eingabebytearray, die die zu schreibenden Daten enthält.</param>
        <param name="offset">Offset im Puffer</param>
        <param name="count">Die Anzahl der Bytes zu schreiben</param>
        <summary>
            Schreibt Daten in den internen Puffer. Wenn der Puffer voll werden dann in den zugrunde liegenden Stream schreibt.
            Er ist synchron.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task WriteAsync (byte[] buffer, int offset, int count, System.Threading.CancellationToken cancelToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task WriteAsync(unsigned int8[] buffer, int32 offset, int32 count, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsOutputStream.WriteAsync(System.Byte[],System.Int32,System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function WriteAsync (buffer As Byte(), offset As Integer, count As Integer, cancelToken As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="override this.WriteAsync : byte[] * int * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="mockAdlsOutputStream.WriteAsync (buffer, offset, count, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsOutputStream/&lt;WriteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="buffer">Eingabebytearray, die die zu schreibenden Daten enthält.</param>
        <param name="offset">Offset im Puffer</param>
        <param name="count">Die Anzahl der Bytes zu schreiben</param>
        <param name="cancelToken">Abbruchtoken</param>
        <summary>
            Schreibt Daten in den internen Puffer. Wenn der Puffer voll werden dann in den zugrunde liegenden Stream schreibt.
            Geschieht dies asynchron
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>