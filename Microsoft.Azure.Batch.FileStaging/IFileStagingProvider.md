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
            Stellt grundlegende Funktionen staging-Datei.
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
            Gibt erfordert eine Instanz des IFileStagingArtifact mit was die Implementierung Werte.
            Dies wird aufgerufen, die während des Stagings Datei, wenn ein staging Artefakt nicht anderweitig bereitgestellt wurde.
            </summary>
        <returns>Eine Instanz des IFileStagingArtifact mit beliebigen Werten erfordert die Implementierung.</returns>
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
            Die Auflistung von ResourceFile-Objekten, die der Datei Staging ergeben.   
            Muss von der IFileStagingProvider.StageFilesAsync()-Methode festgelegt werden.
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
        <param name="filesToStage">Die Auflistung aller staging Dateiobjekte bereitgestellt werden.  Alle Instanzen müssen den gleichen Implementierungstyp haben.</param>
        <param name="fileStagingArtifact">IFileStagingProvider bestimmte staging-Artefakte, einschließlich Fehler/ausgeführt.</param>
        <summary>
            Startet einen asynchronen Vorgang, um alle Dateien in der angegebenen Auflistung Stufe an.
            Wenn Datei Staging beginnt, werden alle Instanzen von IFileStagingProvider anhand ihres Typs Implementierung bucketized.
            Hierdurch wird eine Auflistung von Instanzen pro Implementierung.
            Jede Implementierung von IFileStagingProvider besitzt eine StageFilesAsync()-Methode.  Diese Methode wird mit der rechten Auflistung, durch die oben genannten Bucketization Schritt Oulined einmal aufgerufen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
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
            Führt die clientseitige Validierung für das aktuelle Objekt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>