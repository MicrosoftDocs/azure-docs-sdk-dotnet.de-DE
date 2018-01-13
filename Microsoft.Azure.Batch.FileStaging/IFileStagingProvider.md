<Type Name="IFileStagingProvider" FullName="Microsoft.Azure.Batch.FileStaging.IFileStagingProvider">
  <TypeSignature Language="C#" Value="public interface IFileStagingProvider" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IFileStagingProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider" />
  <TypeSignature Language="VB.NET" Value="Public Interface IFileStagingProvider" />
  <TypeSignature Language="F#" Value="type IFileStagingProvider = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1086d-101">Stellt grundlegende Funktionen staging-Datei.</span><span class="sxs-lookup"><span data-stu-id="1086d-101">Provides basic file staging features.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateStagingArtifact">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IFileStagingArtifact CreateStagingArtifact ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Batch.IFileStagingArtifact CreateStagingArtifact() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider.CreateStagingArtifact" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateStagingArtifact () As IFileStagingArtifact" />
      <MemberSignature Language="F#" Value="abstract member CreateStagingArtifact : unit -&gt; Microsoft.Azure.Batch.IFileStagingArtifact" Usage="iFileStagingProvider.CreateStagingArtifact " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IFileStagingArtifact</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1086d-102">Gibt erfordert eine Instanz des IFileStagingArtifact mit was die Implementierung Werte.</span><span class="sxs-lookup"><span data-stu-id="1086d-102">Returns an instance of IFileStagingArtifact with whatever values the implementation requires.</span></span>
            <span data-ttu-id="1086d-103">Dies wird aufgerufen, die während des Stagings Datei, wenn ein staging Artefakt nicht anderweitig bereitgestellt wurde.</span><span class="sxs-lookup"><span data-stu-id="1086d-103">This will be called during file staging whenever a staging artifact has not been otherwise provided.</span></span>
            </summary>
        <returns><span data-ttu-id="1086d-104">Eine Instanz des IFileStagingArtifact mit beliebigen Werten erfordert die Implementierung.</span><span class="sxs-lookup"><span data-stu-id="1086d-104">An instance of IFileStagingArtifact with whatever values the implementation requires.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StagedFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ResourceFile&gt; StagedFiles { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.ResourceFile&gt; StagedFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider.StagedFiles" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StagedFiles As IEnumerable(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.StagedFiles : seq&lt;Microsoft.Azure.Batch.ResourceFile&gt;" Usage="Microsoft.Azure.Batch.FileStaging.IFileStagingProvider.StagedFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ResourceFile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1086d-105">Die Auflistung von ResourceFile-Objekten, die der Datei Staging ergeben.</span><span class="sxs-lookup"><span data-stu-id="1086d-105">The collection of ResourceFile objects that are the result of file staging.</span></span>   
            <span data-ttu-id="1086d-106">Muss von der IFileStagingProvider.StageFilesAsync()-Methode festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="1086d-106">Must be set by the IFileStagingProvider.StageFilesAsync() method.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StageFilesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StageFilesAsync (System.Collections.Generic.List&lt;Microsoft.Azure.Batch.FileStaging.IFileStagingProvider&gt; filesToStage, Microsoft.Azure.Batch.IFileStagingArtifact fileStagingArtifact);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task StageFilesAsync(class System.Collections.Generic.List`1&lt;class Microsoft.Azure.Batch.FileStaging.IFileStagingProvider&gt; filesToStage, class Microsoft.Azure.Batch.IFileStagingArtifact fileStagingArtifact) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider.StageFilesAsync(System.Collections.Generic.List{Microsoft.Azure.Batch.FileStaging.IFileStagingProvider},Microsoft.Azure.Batch.IFileStagingArtifact)" />
      <MemberSignature Language="VB.NET" Value="Public Function StageFilesAsync (filesToStage As List(Of IFileStagingProvider), fileStagingArtifact As IFileStagingArtifact) As Task" />
      <MemberSignature Language="F#" Value="abstract member StageFilesAsync : System.Collections.Generic.List&lt;Microsoft.Azure.Batch.FileStaging.IFileStagingProvider&gt; * Microsoft.Azure.Batch.IFileStagingArtifact -&gt; System.Threading.Tasks.Task" Usage="iFileStagingProvider.StageFilesAsync (filesToStage, fileStagingArtifact)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filesToStage" Type="System.Collections.Generic.List&lt;Microsoft.Azure.Batch.FileStaging.IFileStagingProvider&gt;" />
        <Parameter Name="fileStagingArtifact" Type="Microsoft.Azure.Batch.IFileStagingArtifact" />
      </Parameters>
      <Docs>
        <param name="filesToStage"><span data-ttu-id="1086d-107">Die Auflistung aller staging Dateiobjekte bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="1086d-107">Collection of all file staging objects to be staged.</span></span>  <span data-ttu-id="1086d-108">Alle Instanzen müssen den gleichen Implementierungstyp haben.</span><span class="sxs-lookup"><span data-stu-id="1086d-108">All instances must have the same implementation type.</span></span></param>
        <param name="fileStagingArtifact"><span data-ttu-id="1086d-109">IFileStagingProvider bestimmte staging-Artefakte, einschließlich Fehler/ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="1086d-109">IFileStagingProvider specific staging artifacts including error/progress.</span></span></param>
        <summary>
            <span data-ttu-id="1086d-110">Startet einen asynchronen Vorgang, um alle Dateien in der angegebenen Auflistung Stufe an.</span><span class="sxs-lookup"><span data-stu-id="1086d-110">Begins an asynchronous operation to stage all of the files in the given collection.</span></span>
            <span data-ttu-id="1086d-111">Wenn Datei Staging beginnt, werden alle Instanzen von IFileStagingProvider anhand ihres Typs Implementierung bucketized.</span><span class="sxs-lookup"><span data-stu-id="1086d-111">When file staging begins, all instances of IFileStagingProvider are bucketized by their implementation type.</span></span>
            <span data-ttu-id="1086d-112">Hierdurch wird eine Auflistung von Instanzen pro Implementierung.</span><span class="sxs-lookup"><span data-stu-id="1086d-112">This produces one collection of instances per implementation.</span></span>
            <span data-ttu-id="1086d-113">Jede Implementierung von IFileStagingProvider besitzt eine StageFilesAsync()-Methode.</span><span class="sxs-lookup"><span data-stu-id="1086d-113">Each implmentation of IFileStagingProvider has a StageFilesAsync() method.</span></span>  <span data-ttu-id="1086d-114">Diese Methode wird mit der rechten Auflistung, durch die oben genannten Bucketization Schritt Oulined einmal aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="1086d-114">That method is called once with the collection produced by the bucketization step oulined above.</span></span>
            </summary>
        <returns><span data-ttu-id="1086d-115">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="1086d-115">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit" Usage="iFileStagingProvider.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1086d-116">Führt die clientseitige Validierung für das aktuelle Objekt.</span><span class="sxs-lookup"><span data-stu-id="1086d-116">Performs client-side validation on the current object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>