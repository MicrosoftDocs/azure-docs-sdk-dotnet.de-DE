<Type Name="FileToStage" FullName="Microsoft.Azure.Batch.FileStaging.FileToStage">
  <TypeSignature Language="C#" Value="public sealed class FileToStage : Microsoft.Azure.Batch.FileStaging.IFileStagingProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FileToStage extends System.Object implements class Microsoft.Azure.Batch.FileStaging.IFileStagingProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.FileStaging.FileToStage" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FileToStage&#xA;Implements IFileStagingProvider" />
  <TypeSignature Language="F#" Value="type FileToStage = class&#xA;    interface IFileStagingProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch.FileStaging</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.FileStaging.IFileStagingProvider</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Für das Staging der Datei einer lokalen Datei in den blobspeicher bietet.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileToStage (string localFileToStage, Microsoft.Azure.Batch.FileStaging.StagingStorageAccount storageCredentials, string nodeFileName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string localFileToStage, class Microsoft.Azure.Batch.FileStaging.StagingStorageAccount storageCredentials, string nodeFileName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.FileStaging.FileToStage.#ctor(System.String,Microsoft.Azure.Batch.FileStaging.StagingStorageAccount,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (localFileToStage As String, storageCredentials As StagingStorageAccount, Optional nodeFileName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.FileStaging.FileToStage : string * Microsoft.Azure.Batch.FileStaging.StagingStorageAccount * string -&gt; Microsoft.Azure.Batch.FileStaging.FileToStage" Usage="new Microsoft.Azure.Batch.FileStaging.FileToStage (localFileToStage, storageCredentials, nodeFileName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.FileStaging</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="localFileToStage" Type="System.String" />
        <Parameter Name="storageCredentials" Type="Microsoft.Azure.Batch.FileStaging.StagingStorageAccount" />
        <Parameter Name="nodeFileName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="localFileToStage">Der Name der lokalen Datei.</param>
        <param name="storageCredentials">Die speicheranmeldeinformationen, die beim Erstellen des Standardcontainers verwendet werden.</param>
        <param name="nodeFileName">Optionale Name, der für die Datei auf den Computeknoten gewährt werden.  Wenn dieser Parameter null ist oder fehlt der Name auf den Computeknoten auf den Wert der von allen Pfadinformationen befreite LocalFileToStage festgelegt werden werden.</param>
        <summary>
            Gibt an, dass eine lokale Datei für den blob-Speicher bereitgestellt werden soll.  
            Das angegebene Konto wird Speicherkosten in Rechnung gestellt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateStagingArtifact">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IFileStagingArtifact CreateStagingArtifact ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Batch.IFileStagingArtifact CreateStagingArtifact() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.FileStaging.FileToStage.CreateStagingArtifact" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateStagingArtifact () As IFileStagingArtifact" />
      <MemberSignature Language="F#" Value="abstract member CreateStagingArtifact : unit -&gt; Microsoft.Azure.Batch.IFileStagingArtifact&#xA;override this.CreateStagingArtifact : unit -&gt; Microsoft.Azure.Batch.IFileStagingArtifact" Usage="fileToStage.CreateStagingArtifact " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider.CreateStagingArtifact</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.FileStaging</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IFileStagingArtifact</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Weitere Informationen finden Sie unter <see cref="M:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider.CreateStagingArtifact" />.
            </summary>
        <returns>Eine Instanz des IFileStagingArtifact mit Standardwerten.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exception">
      <MemberSignature Language="C#" Value="public Exception Exception { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception Exception" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.FileStaging.FileToStage.Exception" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Exception As Exception" />
      <MemberSignature Language="F#" Value="member this.Exception : Exception" Usage="Microsoft.Azure.Batch.FileStaging.FileToStage.Exception" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.FileStaging</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Ausnahme abgefangen ggf. beim Versuch, diese Datei Stufe an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalFileToStage">
      <MemberSignature Language="C#" Value="public string LocalFileToStage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalFileToStage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.FileStaging.FileToStage.LocalFileToStage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LocalFileToStage As String" />
      <MemberSignature Language="F#" Value="member this.LocalFileToStage : string" Usage="Microsoft.Azure.Batch.FileStaging.FileToStage.LocalFileToStage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.FileStaging</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Name der lokalen Datei, Phase, um Blob-Speicher
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeFileName">
      <MemberSignature Language="C#" Value="public string NodeFileName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeFileName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.FileStaging.FileToStage.NodeFileName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeFileName As String" />
      <MemberSignature Language="F#" Value="member this.NodeFileName : string" Usage="Microsoft.Azure.Batch.FileStaging.FileToStage.NodeFileName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.FileStaging</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Dateiname Ziel auf den Serverknoten, den den Blob-Inhalt heruntergeladen werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StagedFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ResourceFile&gt; StagedFiles { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.ResourceFile&gt; StagedFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.FileStaging.FileToStage.StagedFiles" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StagedFiles As IEnumerable(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.StagedFiles : seq&lt;Microsoft.Azure.Batch.ResourceFile&gt;" Usage="Microsoft.Azure.Batch.FileStaging.FileToStage.StagedFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.FileStaging</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ResourceFile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Instanzen von ResourcesFile angegebene Dateiname für die bereitgestellten lokalen Datei.
            Für diese Implementierung führt eine Sammlung mit nur ein Eintrag erfolgreich Datei Staging dieses Objekts.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StageFilesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StageFilesAsync (System.Collections.Generic.List&lt;Microsoft.Azure.Batch.FileStaging.IFileStagingProvider&gt; filesToStage, Microsoft.Azure.Batch.IFileStagingArtifact fileStagingArtifact);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task StageFilesAsync(class System.Collections.Generic.List`1&lt;class Microsoft.Azure.Batch.FileStaging.IFileStagingProvider&gt; filesToStage, class Microsoft.Azure.Batch.IFileStagingArtifact fileStagingArtifact) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.FileStaging.FileToStage.StageFilesAsync(System.Collections.Generic.List{Microsoft.Azure.Batch.FileStaging.IFileStagingProvider},Microsoft.Azure.Batch.IFileStagingArtifact)" />
      <MemberSignature Language="VB.NET" Value="Public Function StageFilesAsync (filesToStage As List(Of IFileStagingProvider), fileStagingArtifact As IFileStagingArtifact) As Task" />
      <MemberSignature Language="F#" Value="abstract member StageFilesAsync : System.Collections.Generic.List&lt;Microsoft.Azure.Batch.FileStaging.IFileStagingProvider&gt; * Microsoft.Azure.Batch.IFileStagingArtifact -&gt; System.Threading.Tasks.Task&#xA;override this.StageFilesAsync : System.Collections.Generic.List&lt;Microsoft.Azure.Batch.FileStaging.IFileStagingProvider&gt; * Microsoft.Azure.Batch.IFileStagingArtifact -&gt; System.Threading.Tasks.Task" Usage="fileToStage.StageFilesAsync (filesToStage, fileStagingArtifact)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider.StageFilesAsync(System.Collections.Generic.List{Microsoft.Azure.Batch.FileStaging.IFileStagingProvider},Microsoft.Azure.Batch.IFileStagingArtifact)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.FileStaging</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.FileStaging.FileToStage/&lt;StageFilesAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filesToStage" Type="System.Collections.Generic.List&lt;Microsoft.Azure.Batch.FileStaging.IFileStagingProvider&gt;" />
        <Parameter Name="fileStagingArtifact" Type="Microsoft.Azure.Batch.IFileStagingArtifact" />
      </Parameters>
      <Docs>
        <param name="filesToStage">Die Instanzen der IFileStagingProvider Phase.</param>
        <param name="fileStagingArtifact">IFileStagingProvider bestimmte staging-Artefakte, einschließlich Fehler/ausgeführt.</param>
        <summary>
            Weitere Informationen finden Sie unter <see cref="M:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider.StageFilesAsync(System.Collections.Generic.List{Microsoft.Azure.Batch.FileStaging.IFileStagingProvider},Microsoft.Azure.Batch.IFileStagingArtifact)" />.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.FileStaging.FileToStage.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="fileToStage.Validate " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider.Validate</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.FileStaging</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Weitere Informationen finden Sie unter <see cref="M:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider.Validate" />.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>