<Type Name="TransferProgress" FullName="Microsoft.Azure.Management.DataLake.Store.TransferProgress">
  <TypeSignature Language="C#" Value="public class TransferProgress" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransferProgress extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.TransferProgress" />
  <TypeSignature Language="VB.NET" Value="Public Class TransferProgress" />
  <TypeSignature Language="F#" Value="type TransferProgress = class" />
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
            Meldet den Status einer Übertragung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetSegmentProgress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Store.SegmentTransferProgress GetSegmentProgress (int segmentNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Management.DataLake.Store.SegmentTransferProgress GetSegmentProgress(int32 segmentNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TransferProgress.GetSegmentProgress(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSegmentProgress (segmentNumber As Integer) As SegmentTransferProgress" />
      <MemberSignature Language="F#" Value="member this.GetSegmentProgress : int -&gt; Microsoft.Azure.Management.DataLake.Store.SegmentTransferProgress" Usage="transferProgress.GetSegmentProgress segmentNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.SegmentTransferProgress</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="segmentNumber" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="segmentNumber">Die Sequenznummer des Segments zum Abrufen von Informationen für</param>
        <summary>
            Ruft den Status der Übertragung für ein bestimmtes Segment ab.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalFileLength">
      <MemberSignature Language="C#" Value="public long TotalFileLength { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalFileLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferProgress.TotalFileLength" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalFileLength As Long" />
      <MemberSignature Language="F#" Value="member this.TotalFileLength : int64" Usage="Microsoft.Azure.Management.DataLake.Store.TransferProgress.TotalFileLength" />
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
            Ruft einen Wert, der angibt, der Gesamtlänge der Datei zu übertragen.
            </summary>
        <value>
            Die Gesamtlänge der Datei.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalSegmentCount">
      <MemberSignature Language="C#" Value="public int TotalSegmentCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 TotalSegmentCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferProgress.TotalSegmentCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalSegmentCount As Integer" />
      <MemberSignature Language="F#" Value="member this.TotalSegmentCount : int" Usage="Microsoft.Azure.Management.DataLake.Store.TransferProgress.TotalSegmentCount" />
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
            Ruft einen Wert, der angibt, der Gesamtanzahl der Segmente zu übertragen.
            </summary>
        <value>
            Die Segmentanzahl der insgesamt.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferredByteCount">
      <MemberSignature Language="C#" Value="public long TransferredByteCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TransferredByteCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferProgress.TransferredByteCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransferredByteCount As Long" />
      <MemberSignature Language="F#" Value="member this.TransferredByteCount : int64" Usage="Microsoft.Azure.Management.DataLake.Store.TransferProgress.TransferredByteCount" />
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
            Ruft einen Wert, der angibt, der Anzahl der Bytes, die bisher übertragen wurden.
            </summary>
        <value>
            Die Anzahl der übertragenen Bytes.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>