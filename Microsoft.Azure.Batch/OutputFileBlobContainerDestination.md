<Type Name="OutputFileBlobContainerDestination" FullName="Microsoft.Azure.Batch.OutputFileBlobContainerDestination">
  <TypeSignature Language="C#" Value="public class OutputFileBlobContainerDestination" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OutputFileBlobContainerDestination extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.OutputFileBlobContainerDestination" />
  <TypeSignature Language="VB.NET" Value="Public Class OutputFileBlobContainerDestination" />
  <TypeSignature Language="F#" Value="type OutputFileBlobContainerDestination = class&#xA;    interface ITransportObjectProvider&lt;OutputFileBlobContainerDestination&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            Gibt eine Datei hochladen Ziel innerhalb einer Azure-Blob-Speichercontainer.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutputFileBlobContainerDestination (string containerUrl, string path = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string containerUrl, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.OutputFileBlobContainerDestination.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (containerUrl As String, Optional path As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.OutputFileBlobContainerDestination : string * string -&gt; Microsoft.Azure.Batch.OutputFileBlobContainerDestination" Usage="new Microsoft.Azure.Batch.OutputFileBlobContainerDestination (containerUrl, path)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="containerUrl" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="containerUrl">Die URL des Containers im Azure-Blob-Speicher, um Dateien hochzuladen.</param>
        <param name="path">Der Ziel-Blob oder das virtuelle Verzeichnis in Azure Storage-Container, in dem die Dateien hochladen.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.OutputFileBlobContainerDestination" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerUrl">
      <MemberSignature Language="C#" Value="public string ContainerUrl { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.OutputFileBlobContainerDestination.ContainerUrl" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainerUrl As String" />
      <MemberSignature Language="F#" Value="member this.ContainerUrl : string" Usage="Microsoft.Azure.Batch.OutputFileBlobContainerDestination.ContainerUrl" />
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
            Ruft die URL des Containers im Azure-Blob-Speicher, um Dateien hochzuladen.
            </summary>
        <value>To be added.</value>
        <remarks>
            Die URL muss eine Shared Access Signature (SAS) ein, erteilen Schreibberechtigungen für den Container enthalten.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.OutputFileBlobContainerDestination.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.Azure.Batch.OutputFileBlobContainerDestination.Path" />
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
            Ruft ab, die Ziel-Blob oder das virtuelle Verzeichnis in Azure Storage-Container, in dem die Dateien hochladen.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>Wenn <see cref="P:Microsoft.Azure.Batch.OutputFile.FilePattern" /> bezieht sich auf eine bestimmte (d. h. er enthält keine Platzhalter), ist dies der Name des Blob, an dem diese Datei hochladen.</para>
          <para>Wenn <see cref="P:Microsoft.Azure.Batch.OutputFile.FilePattern" /> Platzhalterzeichen enthält (und möglicherweise mehrere Dateien aus diesem Grund überein), und klicken Sie dann diese dann dies der Name des virtuellen Blob-Verzeichnisses ist (die einzelnen blobnamen vorangestellt ist), in dem die Dateien hochladen.</para>
          <para>Wenn nicht angegeben, werden die Dateien in das Stammverzeichnis des Containers mit einem übereinstimmenden Dateinamen blobnamen hochgeladen.</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>