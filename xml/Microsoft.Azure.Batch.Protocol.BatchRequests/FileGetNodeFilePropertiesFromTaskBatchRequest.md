<Type Name="FileGetNodeFilePropertiesFromTaskBatchRequest" FullName="Microsoft.Azure.Batch.Protocol.BatchRequests.FileGetNodeFilePropertiesFromTaskBatchRequest">
  <TypeSignature Language="C#" Value="public class FileGetNodeFilePropertiesFromTaskBatchRequest : Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions,Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileGetNodeFilePropertiesFromTaskBatchRequest extends Microsoft.Azure.Batch.Protocol.BatchRequest`2&lt;class Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions, class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequests.FileGetNodeFilePropertiesFromTaskBatchRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class FileGetNodeFilePropertiesFromTaskBatchRequest&#xA;Inherits BatchRequest(Of FileGetPropertiesFromTaskOptions, AzureOperationHeaderResponse(Of FileGetPropertiesFromTaskHeaders))" />
  <TypeSignature Language="F#" Value="type FileGetNodeFilePropertiesFromTaskBatchRequest = class&#xA;    inherit BatchRequest&lt;FileGetPropertiesFromTaskOptions, AzureOperationHeaderResponse&lt;FileGetPropertiesFromTaskHeaders&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions,Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TOptions">Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TResponse">Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b1c3d-101">Ein <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> für den FileGetNodeFilePropertiesFromTask-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b1c3d-101">An <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> for the FileGetNodeFilePropertiesFromTask operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileGetNodeFilePropertiesFromTaskBatchRequest (Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequests.FileGetNodeFilePropertiesFromTaskBatchRequest.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequests.FileGetNodeFilePropertiesFromTaskBatchRequest : Microsoft.Azure.Batch.Protocol.BatchServiceClient * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequests.FileGetNodeFilePropertiesFromTaskBatchRequest" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequests.FileGetNodeFilePropertiesFromTaskBatchRequest (serviceClient, cancellationToken)" />
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
        <param name="serviceClient"><span data-ttu-id="b1c3d-102">Der Dienstclient verwendet.</span><span class="sxs-lookup"><span data-stu-id="b1c3d-102">The service client to use.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b1c3d-103">Ein <see cref="T:System.Threading.CancellationToken" /> Steuerung der Lebensdauer der Anforderung.</span><span class="sxs-lookup"><span data-stu-id="b1c3d-103">A <see cref="T:System.Threading.CancellationToken" /> controlling the request lifetime.</span></span></param>
        <summary>
            <span data-ttu-id="b1c3d-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.FileGetNodeFilePropertiesFromTaskBatchRequest" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b1c3d-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.FileGetNodeFilePropertiesFromTaskBatchRequest" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>