<Type Name="SingleEntryTransferStatus" FullName="Microsoft.Azure.DataLake.Store.FileTransfer.SingleEntryTransferStatus">
  <TypeSignature Language="C#" Value="public class SingleEntryTransferStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SingleEntryTransferStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.FileTransfer.SingleEntryTransferStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class SingleEntryTransferStatus" />
  <TypeSignature Language="F#" Value="type SingleEntryTransferStatus = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="211f0-101">Enthält das Ergebnis der Übertragung von Datei "oder" Segment "oder" Directory Übertragung</span><span class="sxs-lookup"><span data-stu-id="211f0-101">Contains the transfer result of each file or chunk or directory transfer</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="EntryName">
      <MemberSignature Language="C#" Value="public string EntryName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EntryName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.FileTransfer.SingleEntryTransferStatus.EntryName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EntryName As String" />
      <MemberSignature Language="F#" Value="member this.EntryName : string" Usage="Microsoft.Azure.DataLake.Store.FileTransfer.SingleEntryTransferStatus.EntryName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="211f0-102">Name des Segments oder der Datei oder des Verzeichnisses</span><span class="sxs-lookup"><span data-stu-id="211f0-102">Name of the chunk or file or directory</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntrySize">
      <MemberSignature Language="C#" Value="public long EntrySize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 EntrySize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.FileTransfer.SingleEntryTransferStatus.EntrySize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EntrySize As Long" />
      <MemberSignature Language="F#" Value="member this.EntrySize : int64" Usage="Microsoft.Azure.DataLake.Store.FileTransfer.SingleEntryTransferStatus.EntrySize" />
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
            <span data-ttu-id="211f0-103">Größe des Segments oder der Datei</span><span class="sxs-lookup"><span data-stu-id="211f0-103">Size of the chunk or file</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Errors">
      <MemberSignature Language="C#" Value="public string Errors { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Errors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.FileTransfer.SingleEntryTransferStatus.Errors" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Errors As String" />
      <MemberSignature Language="F#" Value="member this.Errors : string" Usage="Microsoft.Azure.DataLake.Store.FileTransfer.SingleEntryTransferStatus.Errors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="211f0-104">Alle Fehler, wenn die Übertragung nicht erfolgreich war.</span><span class="sxs-lookup"><span data-stu-id="211f0-104">Any errors if the transfer was not successful</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.DataLake.Store.FileTransfer.SingleChunkStatus Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.DataLake.Store.FileTransfer.SingleChunkStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.FileTransfer.SingleEntryTransferStatus.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As SingleChunkStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.DataLake.Store.FileTransfer.SingleChunkStatus" Usage="Microsoft.Azure.DataLake.Store.FileTransfer.SingleEntryTransferStatus.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.FileTransfer.SingleChunkStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="211f0-105">Status der Übertragung: erfolgreich oder fehlgeschlagen oder übersprungen, wenn wir hart möchten, um das Ziel zu überschreiben, falls vorhanden</span><span class="sxs-lookup"><span data-stu-id="211f0-105">Status of the transfer: Successful or failed or skipped if we didnt want to overwrite the destination if it exists</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.FileTransfer.SingleEntryTransferStatus.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="singleEntryTransferStatus.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.DataLake.Store.FileTransfer.EntryType Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.DataLake.Store.FileTransfer.EntryType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.FileTransfer.SingleEntryTransferStatus.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As EntryType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.DataLake.Store.FileTransfer.EntryType" Usage="Microsoft.Azure.DataLake.Store.FileTransfer.SingleEntryTransferStatus.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.FileTransfer.EntryType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="211f0-106">Art des Eintrags: Datei, Block oder ein Verzeichnis</span><span class="sxs-lookup"><span data-stu-id="211f0-106">Type of entry: File, chunk or directory</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>