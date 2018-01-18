<Type Name="FileGetFromComputeNodeBatchRequest" FullName="Microsoft.Azure.Batch.Protocol.BatchRequests.FileGetFromComputeNodeBatchRequest">
  <TypeSignature Language="C#" Value="public class FileGetFromComputeNodeBatchRequest : Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions,Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream,Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeHeaders&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileGetFromComputeNodeBatchRequest extends Microsoft.Azure.Batch.Protocol.BatchRequest`2&lt;class Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions, class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class System.IO.Stream, class Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeHeaders&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequests.FileGetFromComputeNodeBatchRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class FileGetFromComputeNodeBatchRequest&#xA;Inherits BatchRequest(Of FileGetFromComputeNodeOptions, AzureOperationResponse(Of Stream, FileGetFromComputeNodeHeaders))" />
  <TypeSignature Language="F#" Value="type FileGetFromComputeNodeBatchRequest = class&#xA;    inherit BatchRequest&lt;FileGetFromComputeNodeOptions, AzureOperationResponse&lt;Stream, FileGetFromComputeNodeHeaders&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions,Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream,Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeHeaders&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TOptions">Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TResponse">Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream,Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeHeaders&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7f1ca-101">Ein <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> für den FileGetFromComputeNode-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="7f1ca-101">An <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> for the FileGetFromComputeNode operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileGetFromComputeNodeBatchRequest (Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequests.FileGetFromComputeNodeBatchRequest.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequests.FileGetFromComputeNodeBatchRequest : Microsoft.Azure.Batch.Protocol.BatchServiceClient * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequests.FileGetFromComputeNodeBatchRequest" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequests.FileGetFromComputeNodeBatchRequest (serviceClient, cancellationToken)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceClient" Type="Microsoft.Azure.Batch.Protocol.BatchServiceClient" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceClient"><span data-ttu-id="7f1ca-102">Der Dienstclient verwendet.</span><span class="sxs-lookup"><span data-stu-id="7f1ca-102">The service client to use.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="7f1ca-103">Ein <see cref="T:System.Threading.CancellationToken" /> Steuerung der Lebensdauer der Anforderung.</span><span class="sxs-lookup"><span data-stu-id="7f1ca-103">A <see cref="T:System.Threading.CancellationToken" /> controlling the request lifetime.</span></span></param>
        <summary>
            <span data-ttu-id="7f1ca-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.FileGetFromComputeNodeBatchRequest" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7f1ca-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.FileGetFromComputeNodeBatchRequest" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>