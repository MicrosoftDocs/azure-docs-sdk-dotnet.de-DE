<Type Name="ResourceFile" FullName="Microsoft.Azure.Batch.ResourceFile">
  <TypeSignature Language="C#" Value="public class ResourceFile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceFile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ResourceFile" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceFile" />
  <TypeSignature Language="F#" Value="type ResourceFile = class&#xA;    interface ITransportObjectProvider&lt;ResourceFile&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Eine Datei aus dem Azure-Blob-Speicher auf einem Serverknoten z. B. Task ausführbare Dateien heruntergeladen und aufgabenbezogene Eingabedateien Daten.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceFile (string blobSource, string filePath, string fileMode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string blobSource, string filePath, string fileMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ResourceFile.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobSource As String, filePath As String, Optional fileMode As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.ResourceFile : string * string * string -&gt; Microsoft.Azure.Batch.ResourceFile" Usage="new Microsoft.Azure.Batch.ResourceFile (blobSource, filePath, fileMode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="blobSource" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="fileMode" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="blobSource">Die URL der Datei innerhalb des Azure-Blob-Speicher.</param>
        <param name="filePath">Der Speicherort, der zum Herunterladen der Datei, relativ zum Arbeitsverzeichnis für den Task.</param>
        <param name="fileMode">Die Datei Berechtigung Mode-Attribut im Oktalformat.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.ResourceFile" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobSource">
      <MemberSignature Language="C#" Value="public string BlobSource { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobSource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceFile.BlobSource" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BlobSource As String" />
      <MemberSignature Language="F#" Value="member this.BlobSource : string" Usage="Microsoft.Azure.Batch.ResourceFile.BlobSource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die URL der Datei innerhalb des Azure-Blob-Speicher ab.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese URL sollte eine shared Access Signature enthalten, wenn das Blob nicht öffentlich gelesen werden kann.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FileMode">
      <MemberSignature Language="C#" Value="public string FileMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FileMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceFile.FileMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FileMode As String" />
      <MemberSignature Language="F#" Value="member this.FileMode : string" Usage="Microsoft.Azure.Batch.ResourceFile.FileMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Datei Berechtigung Mode-Attribut im Oktalformat ab.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>Diese Eigenschaft ist nur anwendbar, wenn die Ressourcendatei auf einem Linux-Knoten heruntergeladen wird. Diese Eigenschaft wird ignoriert, wenn er für angegeben ist eine <see cref="T:Microsoft.Azure.Batch.ResourceFile" /> die wird zu einem Windows-Knoten heruntergeladen werden. Wenn diese Eigenschaft nicht für einen Linux-Knoten angegeben wird, ist der Standardwert 0770.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="FilePath">
      <MemberSignature Language="C#" Value="public string FilePath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceFile.FilePath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FilePath As String" />
      <MemberSignature Language="F#" Value="member this.FilePath : string" Usage="Microsoft.Azure.Batch.ResourceFile.FilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Speicherort, der zum Herunterladen der Datei, relativ zum Arbeitsverzeichnis für den Task ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>