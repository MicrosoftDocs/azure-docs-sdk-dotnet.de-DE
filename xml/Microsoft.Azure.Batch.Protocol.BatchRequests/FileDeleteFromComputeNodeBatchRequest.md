<Type Name="FileDeleteFromComputeNodeBatchRequest" FullName="Microsoft.Azure.Batch.Protocol.BatchRequests.FileDeleteFromComputeNodeBatchRequest">
  <TypeSignature Language="C#" Value="public class FileDeleteFromComputeNodeBatchRequest : Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Nullable&lt;bool&gt;,Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions,Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeHeaders&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileDeleteFromComputeNodeBatchRequest extends Microsoft.Azure.Batch.Protocol.BatchRequest`3&lt;valuetype System.Nullable`1&lt;bool&gt;, class Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions, class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeHeaders&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequests.FileDeleteFromComputeNodeBatchRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class FileDeleteFromComputeNodeBatchRequest&#xA;Inherits BatchRequest(Of Nullable(Of Boolean), FileDeleteFromComputeNodeOptions, AzureOperationHeaderResponse(Of FileDeleteFromComputeNodeHeaders))" />
  <TypeSignature Language="F#" Value="type FileDeleteFromComputeNodeBatchRequest = class&#xA;    inherit BatchRequest&lt;Nullable&lt;bool&gt;, FileDeleteFromComputeNodeOptions, AzureOperationHeaderResponse&lt;FileDeleteFromComputeNodeHeaders&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.BatchRequest&lt;System.Nullable&lt;System.Boolean&gt;,Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions,Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeHeaders&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TBody">System.Nullable&lt;System.Boolean&gt;</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TOptions">Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TResponse">Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeHeaders&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ab2f1-101">Ein <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> für den FileDeleteFromComputeNode-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ab2f1-101">An <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> for the FileDeleteFromComputeNode operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileDeleteFromComputeNodeBatchRequest (Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, Nullable&lt;bool&gt; parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, valuetype System.Nullable`1&lt;bool&gt; parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequests.FileDeleteFromComputeNodeBatchRequest.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequests.FileDeleteFromComputeNodeBatchRequest : Microsoft.Azure.Batch.Protocol.BatchServiceClient * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequests.FileDeleteFromComputeNodeBatchRequest" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequests.FileDeleteFromComputeNodeBatchRequest (serviceClient, parameters, cancellationToken)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceClient" Type="Microsoft.Azure.Batch.Protocol.BatchServiceClient" />
        <Parameter Name="parameters" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceClient"><span data-ttu-id="ab2f1-102">Der Dienstclient verwendet.</span><span class="sxs-lookup"><span data-stu-id="ab2f1-102">The service client to use.</span></span></param>
        <param name="parameters"><span data-ttu-id="ab2f1-103">Die Parameter zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="ab2f1-103">The parameters to use.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="ab2f1-104">Ein <see cref="T:System.Threading.CancellationToken" /> Steuerung der Lebensdauer der Anforderung.</span><span class="sxs-lookup"><span data-stu-id="ab2f1-104">A <see cref="T:System.Threading.CancellationToken" /> controlling the request lifetime.</span></span></param>
        <summary>
            <span data-ttu-id="ab2f1-105">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.FileDeleteFromComputeNodeBatchRequest" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ab2f1-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.FileDeleteFromComputeNodeBatchRequest" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>