<Type Name="SegmentTransferProgress" FullName="Microsoft.Azure.Management.DataLake.Store.SegmentTransferProgress">
  <TypeSignature Language="C#" Value="public class SegmentTransferProgress" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SegmentTransferProgress extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.SegmentTransferProgress" />
  <TypeSignature Language="VB.NET" Value="Public Class SegmentTransferProgress" />
  <TypeSignature Language="F#" Value="type SegmentTransferProgress = class" />
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
            Stellt eine Klasse, die zur Übertragung Statusmeldung auf ein Segment verwendet.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="IsFailed">
      <MemberSignature Language="C#" Value="public bool IsFailed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsFailed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.SegmentTransferProgress.IsFailed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsFailed As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsFailed : bool" Usage="Microsoft.Azure.Management.DataLake.Store.SegmentTransferProgress.IsFailed" />
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
            Ruft einen Wert, der angibt, ob die Übertragung fehlgeschlagen, oder nicht ist.
            </summary>
        <value>
          <c>"true"</c> Wenn diese Instanz fehlgeschlagen ist, andernfalls <c>"false"</c>.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Length">
      <MemberSignature Language="C#" Value="public long Length { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Length" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.SegmentTransferProgress.Length" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Length As Long" />
      <MemberSignature Language="F#" Value="member this.Length : int64" Usage="Microsoft.Azure.Management.DataLake.Store.SegmentTransferProgress.Length" />
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
            Ruft einen Wert, der angibt, der Segmentlänge in Bytes ab.
            </summary>
        <value>
            Die Länge.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SegmentNumber">
      <MemberSignature Language="C#" Value="public int SegmentNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 SegmentNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.SegmentTransferProgress.SegmentNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SegmentNumber As Integer" />
      <MemberSignature Language="F#" Value="member this.SegmentNumber : int" Usage="Microsoft.Azure.Management.DataLake.Store.SegmentTransferProgress.SegmentNumber" />
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
            Ruft einen Wert, der angibt, der Segmentnummer, der dieser Statusbericht bezieht, sich auf.
            </summary>
        <value>
            Die Segmentnummer.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferredByteCount">
      <MemberSignature Language="C#" Value="public long TransferredByteCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TransferredByteCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.SegmentTransferProgress.TransferredByteCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransferredByteCount As Long" />
      <MemberSignature Language="F#" Value="member this.TransferredByteCount : int64" Usage="Microsoft.Azure.Management.DataLake.Store.SegmentTransferProgress.TransferredByteCount" />
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
            Ruft einen Wert, der angibt, der Anzahl der Bytes, die bisher für dieses Segment übertragen.
            </summary>
        <value>
            Die Anzahl der übertragenen Bytes.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>