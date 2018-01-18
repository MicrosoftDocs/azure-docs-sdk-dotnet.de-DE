<Type Name="PoolEvaluateAutoScaleBatchRequest" FullName="Microsoft.Azure.Batch.Protocol.BatchRequests.PoolEvaluateAutoScaleBatchRequest">
  <TypeSignature Language="C#" Value="public class PoolEvaluateAutoScaleBatchRequest : Microsoft.Azure.Batch.Protocol.BatchRequest&lt;string,Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions,Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun,Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleHeaders&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolEvaluateAutoScaleBatchRequest extends Microsoft.Azure.Batch.Protocol.BatchRequest`3&lt;string, class Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions, class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun, class Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleHeaders&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequests.PoolEvaluateAutoScaleBatchRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolEvaluateAutoScaleBatchRequest&#xA;Inherits BatchRequest(Of String, PoolEvaluateAutoScaleOptions, AzureOperationResponse(Of AutoScaleRun, PoolEvaluateAutoScaleHeaders))" />
  <TypeSignature Language="F#" Value="type PoolEvaluateAutoScaleBatchRequest = class&#xA;    inherit BatchRequest&lt;string, PoolEvaluateAutoScaleOptions, AzureOperationResponse&lt;AutoScaleRun, PoolEvaluateAutoScaleHeaders&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.BatchRequest&lt;System.String,Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions,Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun,Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleHeaders&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TBody">System.String</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TOptions">Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TResponse">Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun,Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleHeaders&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2da64-101">Ein <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> für den PoolEvaluateAutoScale-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="2da64-101">An <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> for the PoolEvaluateAutoScale operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolEvaluateAutoScaleBatchRequest (Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, string parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, string parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequests.PoolEvaluateAutoScaleBatchRequest.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequests.PoolEvaluateAutoScaleBatchRequest : Microsoft.Azure.Batch.Protocol.BatchServiceClient * string * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequests.PoolEvaluateAutoScaleBatchRequest" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequests.PoolEvaluateAutoScaleBatchRequest (serviceClient, parameters, cancellationToken)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceClient" Type="Microsoft.Azure.Batch.Protocol.BatchServiceClient" />
        <Parameter Name="parameters" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceClient"><span data-ttu-id="2da64-102">Der Dienstclient verwendet.</span><span class="sxs-lookup"><span data-stu-id="2da64-102">The service client to use.</span></span></param>
        <param name="parameters"><span data-ttu-id="2da64-103">Die Parameter zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="2da64-103">The parameters to use.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2da64-104">Ein <see cref="T:System.Threading.CancellationToken" /> Steuerung der Lebensdauer der Anforderung.</span><span class="sxs-lookup"><span data-stu-id="2da64-104">A <see cref="T:System.Threading.CancellationToken" /> controlling the request lifetime.</span></span></param>
        <summary>
            <span data-ttu-id="2da64-105">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.PoolEvaluateAutoScaleBatchRequest" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2da64-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.PoolEvaluateAutoScaleBatchRequest" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>