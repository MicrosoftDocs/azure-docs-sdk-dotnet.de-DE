<Type Name="TransferFolderProgress" FullName="Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress">
  <TypeSignature Language="C#" Value="public class TransferFolderProgress" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransferFolderProgress extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress" />
  <TypeSignature Language="VB.NET" Value="Public Class TransferFolderProgress" />
  <TypeSignature Language="F#" Value="type TransferFolderProgress = class" />
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
            Meldet den Status einer Übertragung für einen Ordner.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FailedFileCount">
      <MemberSignature Language="C#" Value="public long FailedFileCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 FailedFileCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress.FailedFileCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailedFileCount As Long" />
      <MemberSignature Language="F#" Value="member this.FailedFileCount : int64" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress.FailedFileCount" />
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
            Ruft die Anzahl der Dateien, die Fehler ab.
            </summary>
        <value>
            Die Anzahl der fehlerhaften Dateien.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSegmentProgress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Store.TransferProgress GetSegmentProgress (int segmentNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Management.DataLake.Store.TransferProgress GetSegmentProgress(int32 segmentNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress.GetSegmentProgress(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSegmentProgress (segmentNumber As Integer) As TransferProgress" />
      <MemberSignature Language="F#" Value="member this.GetSegmentProgress : int -&gt; Microsoft.Azure.Management.DataLake.Store.TransferProgress" Usage="transferFolderProgress.GetSegmentProgress segmentNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.TransferProgress</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="segmentNumber" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="segmentNumber">Die Sequenznummer der Datei zum Abrufen von Informationen für</param>
        <summary>
            Ruft den Status der Übertragung für eine bestimmte Datei ab.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalFileCount">
      <MemberSignature Language="C#" Value="public int TotalFileCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 TotalFileCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress.TotalFileCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalFileCount As Integer" />
      <MemberSignature Language="F#" Value="member this.TotalFileCount : int" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress.TotalFileCount" />
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
            Ruft die Anzahl der insgesamt Dateien ab.
            </summary>
        <value>
            Die Anzahl der Dateien insgesamt.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalFileLength">
      <MemberSignature Language="C#" Value="public long TotalFileLength { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalFileLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress.TotalFileLength" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalFileLength As Long" />
      <MemberSignature Language="F#" Value="member this.TotalFileLength : int64" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress.TotalFileLength" />
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
    <Member MemberName="TransferredByteCount">
      <MemberSignature Language="C#" Value="public long TransferredByteCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TransferredByteCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress.TransferredByteCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransferredByteCount As Long" />
      <MemberSignature Language="F#" Value="member this.TransferredByteCount : int64" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress.TransferredByteCount" />
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
    <Member MemberName="TransferredFileCount">
      <MemberSignature Language="C#" Value="public long TransferredFileCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TransferredFileCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress.TransferredFileCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransferredFileCount As Long" />
      <MemberSignature Language="F#" Value="member this.TransferredFileCount : int64" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress.TransferredFileCount" />
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
            Ruft die Anzahl der übertragenen Dateien ab.
            </summary>
        <value>
            Die Anzahl der übertragenen Dateien.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>