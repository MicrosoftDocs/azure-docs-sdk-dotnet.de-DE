<Type Name="BlobResultSegment" FullName="Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment">
  <TypeSignature Language="C#" Value="public class BlobResultSegment" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BlobResultSegment extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" />
  <TypeSignature Language="VB.NET" Value="Public Class BlobResultSegment" />
  <TypeSignature Language="F#" Value="type BlobResultSegment = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6db03-101">Stellt ein Segment dar <see cref="T:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" /> -Ergebnissen mit fortsetzungsinformationen für paginierungsszenarien.</span><span class="sxs-lookup"><span data-stu-id="6db03-101">Represents a segment of <see cref="T:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" /> results, with continuation information for pagination scenarios.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken ContinuationToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContinuationToken As BlobContinuationToken" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment.ContinuationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6db03-102">Ruft das Fortsetzungstoken zum Abrufen des nächsten Segments von <see cref="T:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" /> Ergebnisse.</span><span class="sxs-lookup"><span data-stu-id="6db03-102">Gets the continuation token used to retrieve the next segment of <see cref="T:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" /> results.</span></span> <span data-ttu-id="6db03-103">Gibt <c>null</c> , wenn keine weiteren Ergebnisse vorhanden sind.</span><span class="sxs-lookup"><span data-stu-id="6db03-103">Returns <c>null</c> if there are no more results.</span></span>
            </summary>
        <value><span data-ttu-id="6db03-104">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="6db03-104">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Results">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.IListBlobItem&gt; Results { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.IListBlobItem&gt; Results" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment.Results" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Results As IEnumerable(Of IListBlobItem)" />
      <MemberSignature Language="F#" Value="member this.Results : seq&lt;Microsoft.WindowsAzure.Storage.Blob.IListBlobItem&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment.Results" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.IListBlobItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6db03-105">Ruft eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" /> Ergebnisse.</span><span class="sxs-lookup"><span data-stu-id="6db03-105">Gets an enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" /> results.</span></span>
            </summary>
        <value><span data-ttu-id="6db03-106">Eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="6db03-106">An enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" /> objects.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>