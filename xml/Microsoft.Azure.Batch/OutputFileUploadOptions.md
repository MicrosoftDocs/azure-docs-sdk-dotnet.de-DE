<Type Name="OutputFileUploadOptions" FullName="Microsoft.Azure.Batch.OutputFileUploadOptions">
  <TypeSignature Language="C#" Value="public class OutputFileUploadOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OutputFileUploadOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.OutputFileUploadOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class OutputFileUploadOptions" />
  <TypeSignature Language="F#" Value="type OutputFileUploadOptions = class&#xA;    interface ITransportObjectProvider&lt;OutputFileUploadOptions&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="d72db-101">Details zu einer Ausgabedatei hochladen-Vorgangs, einschließlich unter welchen Bedingungen aus, um der Upload auszuführen.</span><span class="sxs-lookup"><span data-stu-id="d72db-101">Details about an output file upload operation, including under what conditions to perform the upload.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutputFileUploadOptions (Microsoft.Azure.Batch.Common.OutputFileUploadCondition uploadCondition);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Batch.Common.OutputFileUploadCondition uploadCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.OutputFileUploadOptions.#ctor(Microsoft.Azure.Batch.Common.OutputFileUploadCondition)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (uploadCondition As OutputFileUploadCondition)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.OutputFileUploadOptions : Microsoft.Azure.Batch.Common.OutputFileUploadCondition -&gt; Microsoft.Azure.Batch.OutputFileUploadOptions" Usage="new Microsoft.Azure.Batch.OutputFileUploadOptions uploadCondition" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="uploadCondition" Type="Microsoft.Azure.Batch.Common.OutputFileUploadCondition" />
      </Parameters>
      <Docs>
        <param name="uploadCondition"><span data-ttu-id="d72db-102">Die Bedingungen, unter denen die Dateien hochgeladen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="d72db-102">The conditions under which the file(s) should be uploaded.</span></span></param>
        <summary>
            <span data-ttu-id="d72db-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.OutputFileUploadOptions" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d72db-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.OutputFileUploadOptions" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadCondition">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.OutputFileUploadCondition UploadCondition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Common.OutputFileUploadCondition UploadCondition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.OutputFileUploadOptions.UploadCondition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UploadCondition As OutputFileUploadCondition" />
      <MemberSignature Language="F#" Value="member this.UploadCondition : Microsoft.Azure.Batch.Common.OutputFileUploadCondition" Usage="Microsoft.Azure.Batch.OutputFileUploadOptions.UploadCondition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.OutputFileUploadCondition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d72db-104">Ruft die Bedingungen, unter denen die Dateien hochgeladen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="d72db-104">Gets the conditions under which the file(s) should be uploaded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>