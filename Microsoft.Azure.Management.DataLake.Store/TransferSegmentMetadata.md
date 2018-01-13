<Type Name="TransferSegmentMetadata" FullName="Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata">
  <TypeSignature Language="C#" Value="public class TransferSegmentMetadata" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransferSegmentMetadata extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata" />
  <TypeSignature Language="VB.NET" Value="Public Class TransferSegmentMetadata" />
  <TypeSignature Language="F#" Value="type TransferSegmentMetadata = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.DebuggerDisplay("Segment {SegmentNumber}, Length = {Length}, Status = {Status}")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Die Metadaten für eine bestimmte Dateisegment darstellt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CalculateSegmentCount">
      <MemberSignature Language="C#" Value="public static int CalculateSegmentCount (long fileLength);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig int32 CalculateSegmentCount(int64 fileLength) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata.CalculateSegmentCount(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CalculateSegmentCount (fileLength As Long) As Integer" />
      <MemberSignature Language="F#" Value="static member CalculateSegmentCount : int64 -&gt; int" Usage="Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata.CalculateSegmentCount fileLength" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fileLength" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="fileLength">Die Länge der Datei in Bytes.</param>
        <summary>
            Berechnet die Anzahl der Segmente, denen in eine Datei mit der angegebenen Länge aufgeteilt werden soll.
            Die Methode, um dies zu berechnen basiert auf einige empirischen Messungen, die sowohl die Anzahl der Segmente und die Länge der einzelnen Segmente Eingabedatei wächst der fortschreitenden ermöglicht.
            Beide werden in einem logarithmische Muster zunehmender Länge der Datei.
            Die Formel ist etwa dieser:
            * Multiplikator = Min (100, 50 * 2 ^ Log10(FileLengthInGB))
            * SegmentCount = Max (1, Multiplikator * 2 ^ Log10(FileLengthInGB) im Wesentlichen wir vervierfachen die Anzahl der für die einzelnen Segmente Zehnfache Erhöhung der die Dateilänge mit bestimmten Abschlüssen. Die Formel dient zur Unterstützung sowohl für kleine Dateien als auch für sehr große Dateien (und nicht dazu, dass sehr kleine Segmentlängen oder sehr große Anzahl von Segmenten).
            </summary>
        <returns>
            Die Anzahl der Segmente für die Datei in Teilen. Gibt 0 zurück, wenn FileLength 0 ist.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">Dateilänge darf nicht negativ sein.</exception>
      </Docs>
    </Member>
    <Member MemberName="CalculateSegmentLength">
      <MemberSignature Language="C#" Value="public static long CalculateSegmentLength (long fileLength, int segmentCount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig int64 CalculateSegmentLength(int64 fileLength, int32 segmentCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata.CalculateSegmentLength(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CalculateSegmentLength (fileLength As Long, segmentCount As Integer) As Long" />
      <MemberSignature Language="F#" Value="static member CalculateSegmentLength : int64 * int -&gt; int64" Usage="Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata.CalculateSegmentLength (fileLength, segmentCount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fileLength" Type="System.Int64" />
        <Parameter Name="segmentCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="fileLength">Die Länge der Datei in Bytes.</param>
        <param name="segmentCount">Die Anzahl der Segmente für die Datei in Teilen.</param>
        <summary>
            Berechnet die Länge eines Segments normalen (nicht-Terminal) für eine Datei mit der angegebenen Länge, die in die angegebene Anzahl von Segmenten aufgeteilt wird.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">Anzahl der Segmente muss eine positive ganze Zahl sein.</exception>
      </Docs>
    </Member>
    <Member MemberName="Length">
      <MemberSignature Language="C#" Value="public long Length { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Length" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata.Length" />
      <MemberSignature Language="VB.NET" Value="Public Property Length As Long" />
      <MemberSignature Language="F#" Value="member this.Length : int64 with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata.Length" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Length")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, der Größe des Segments (in Bytes) fest.
            </summary>
        <value>
            Die Länge.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offset">
      <MemberSignature Language="C#" Value="public long Offset { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Offset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata.Offset" />
      <MemberSignature Language="VB.NET" Value="Public Property Offset As Long" />
      <MemberSignature Language="F#" Value="member this.Offset : int64 with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata.Offset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Offset")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, des Startoffset des Segments in der Datei fest.
            </summary>
        <value>
            Der Offset.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Path")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, des Stream-Pfads, die diesem Segment zugewiesen.
            </summary>
        <value>
            Der Pfad.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SegmentNumber">
      <MemberSignature Language="C#" Value="public int SegmentNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 SegmentNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata.SegmentNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property SegmentNumber As Integer" />
      <MemberSignature Language="F#" Value="member this.SegmentNumber : int with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata.SegmentNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Number")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, der Anzahl (Sequenz) des Segments in der Datei fest.
            </summary>
        <value>
            Die Segmentnummer.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As SegmentTransferStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, des aktuelle Upload-Status für dieses Segment.
            </summary>
        <value>
            Der Status.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>