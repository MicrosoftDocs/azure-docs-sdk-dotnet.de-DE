<Type Name="OutputFileDestination" FullName="Microsoft.Azure.Batch.OutputFileDestination">
  <TypeSignature Language="C#" Value="public class OutputFileDestination" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OutputFileDestination extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.OutputFileDestination" />
  <TypeSignature Language="VB.NET" Value="Public Class OutputFileDestination" />
  <TypeSignature Language="F#" Value="type OutputFileDestination = class&#xA;    interface ITransportObjectProvider&lt;OutputFileDestination&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="bb804-101">Das Ziel, auf dem eine Datei hochgeladen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="bb804-101">The destination to which a file should be uploaded.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutputFileDestination (Microsoft.Azure.Batch.OutputFileBlobContainerDestination container);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.OutputFileBlobContainerDestination container) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.OutputFileDestination.#ctor(Microsoft.Azure.Batch.OutputFileBlobContainerDestination)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (container As OutputFileBlobContainerDestination)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.OutputFileDestination : Microsoft.Azure.Batch.OutputFileBlobContainerDestination -&gt; Microsoft.Azure.Batch.OutputFileDestination" Usage="new Microsoft.Azure.Batch.OutputFileDestination container" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="container" Type="Microsoft.Azure.Batch.OutputFileBlobContainerDestination" />
      </Parameters>
      <Docs>
        <param name="container"><span data-ttu-id="bb804-102">Eine Position im Azure-Blob-Speicher in die Dateien hochgeladen werden.</span><span class="sxs-lookup"><span data-stu-id="bb804-102">A location in Azure blob storage to which files are uploaded.</span></span></param>
        <summary>
            <span data-ttu-id="bb804-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.OutputFileDestination" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bb804-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.OutputFileDestination" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Container">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.OutputFileBlobContainerDestination Container { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.OutputFileBlobContainerDestination Container" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.OutputFileDestination.Container" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Container As OutputFileBlobContainerDestination" />
      <MemberSignature Language="F#" Value="member this.Container : Microsoft.Azure.Batch.OutputFileBlobContainerDestination" Usage="Microsoft.Azure.Batch.OutputFileDestination.Container" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.OutputFileBlobContainerDestination</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bb804-104">Ruft einen Speicherort im Azure-Blob-Speicher in die Dateien hochgeladen werden.</span><span class="sxs-lookup"><span data-stu-id="bb804-104">Gets a location in Azure blob storage to which files are uploaded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>