<Type Name="PoolEnableAutoScaleBatchRequest" FullName="Microsoft.Azure.Batch.Protocol.BatchRequests.PoolEnableAutoScaleBatchRequest">
  <TypeSignature Language="C#" Value="public class PoolEnableAutoScaleBatchRequest : Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter,Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions,Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolEnableAutoScaleBatchRequest extends Microsoft.Azure.Batch.Protocol.BatchRequest`3&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions, class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequests.PoolEnableAutoScaleBatchRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolEnableAutoScaleBatchRequest&#xA;Inherits BatchRequest(Of PoolEnableAutoScaleParameter, PoolEnableAutoScaleOptions, AzureOperationHeaderResponse(Of PoolEnableAutoScaleHeaders))" />
  <TypeSignature Language="F#" Value="type PoolEnableAutoScaleBatchRequest = class&#xA;    inherit BatchRequest&lt;PoolEnableAutoScaleParameter, PoolEnableAutoScaleOptions, AzureOperationHeaderResponse&lt;PoolEnableAutoScaleHeaders&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter,Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions,Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TBody">Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TOptions">Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TResponse">Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a3931-101">Ein <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> für den PoolEnableAutoScale-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="a3931-101">An <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> for the PoolEnableAutoScale operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolEnableAutoScaleBatchRequest (Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, class Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequests.PoolEnableAutoScaleBatchRequest.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequests.PoolEnableAutoScaleBatchRequest : Microsoft.Azure.Batch.Protocol.BatchServiceClient * Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequests.PoolEnableAutoScaleBatchRequest" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequests.PoolEnableAutoScaleBatchRequest (serviceClient, parameters, cancellationToken)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceClient" Type="Microsoft.Azure.Batch.Protocol.BatchServiceClient" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceClient"><span data-ttu-id="a3931-102">Der Dienstclient verwendet.</span><span class="sxs-lookup"><span data-stu-id="a3931-102">The service client to use.</span></span></param>
        <param name="parameters"><span data-ttu-id="a3931-103">Die Parameter zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="a3931-103">The parameters to use.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="a3931-104">Ein <see cref="T:System.Threading.CancellationToken" /> Steuerung der Lebensdauer der Anforderung.</span><span class="sxs-lookup"><span data-stu-id="a3931-104">A <see cref="T:System.Threading.CancellationToken" /> controlling the request lifetime.</span></span></param>
        <summary>
            <span data-ttu-id="a3931-105">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.PoolEnableAutoScaleBatchRequest" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a3931-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.PoolEnableAutoScaleBatchRequest" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>