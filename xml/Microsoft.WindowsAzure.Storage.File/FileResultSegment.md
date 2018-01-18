<Type Name="FileResultSegment" FullName="Microsoft.WindowsAzure.Storage.File.FileResultSegment">
  <TypeSignature Language="C#" Value="public sealed class FileResultSegment" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FileResultSegment extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.FileResultSegment" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FileResultSegment" />
  <TypeSignature Language="F#" Value="type FileResultSegment = class" />
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
            <span data-ttu-id="6f5b8-101">Stellt ein Segment dar <see cref="T:Microsoft.WindowsAzure.Storage.File.IListFileItem" /> -Ergebnissen mit fortsetzungsinformationen für paginierungsszenarien.</span><span class="sxs-lookup"><span data-stu-id="6f5b8-101">Represents a segment of <see cref="T:Microsoft.WindowsAzure.Storage.File.IListFileItem" /> results, with continuation information for pagination scenarios.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.File.FileContinuationToken ContinuationToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.File.FileContinuationToken ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileResultSegment.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContinuationToken As FileContinuationToken" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : Microsoft.WindowsAzure.Storage.File.FileContinuationToken" Usage="Microsoft.WindowsAzure.Storage.File.FileResultSegment.ContinuationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.FileContinuationToken</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6f5b8-102">Ruft das Fortsetzungstoken zum Abrufen des nächsten Segments von <see cref="T:Microsoft.WindowsAzure.Storage.File.IListFileItem" /> Ergebnisse.</span><span class="sxs-lookup"><span data-stu-id="6f5b8-102">Gets the continuation token used to retrieve the next segment of <see cref="T:Microsoft.WindowsAzure.Storage.File.IListFileItem" /> results.</span></span> <span data-ttu-id="6f5b8-103">Gibt <c>null</c> , wenn keine weiteren Ergebnisse vorhanden sind.</span><span class="sxs-lookup"><span data-stu-id="6f5b8-103">Returns <c>null</c> if there are no more results.</span></span>
            </summary>
        <value><span data-ttu-id="6f5b8-104">Das Fortsetzungstoken.</span><span class="sxs-lookup"><span data-stu-id="6f5b8-104">The continuation token.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Results">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.IListFileItem&gt; Results { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.File.IListFileItem&gt; Results" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileResultSegment.Results" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Results As IEnumerable(Of IListFileItem)" />
      <MemberSignature Language="F#" Value="member this.Results : seq&lt;Microsoft.WindowsAzure.Storage.File.IListFileItem&gt;" Usage="Microsoft.WindowsAzure.Storage.File.FileResultSegment.Results" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.IListFileItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6f5b8-105">Ruft eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.File.IListFileItem" /> Ergebnisse.</span><span class="sxs-lookup"><span data-stu-id="6f5b8-105">Gets an enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.File.IListFileItem" /> results.</span></span>
            </summary>
        <value><span data-ttu-id="6f5b8-106">Eine aufzählbare Auflistung von Ergebnissen.</span><span class="sxs-lookup"><span data-stu-id="6f5b8-106">An enumerable collection of results.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>