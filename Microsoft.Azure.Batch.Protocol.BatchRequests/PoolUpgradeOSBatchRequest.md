<Type Name="PoolUpgradeOSBatchRequest" FullName="Microsoft.Azure.Batch.Protocol.BatchRequests.PoolUpgradeOSBatchRequest">
  <TypeSignature Language="C#" Value="public class PoolUpgradeOSBatchRequest : Microsoft.Azure.Batch.Protocol.BatchRequest&lt;string,Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions,Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolUpgradeOSBatchRequest extends Microsoft.Azure.Batch.Protocol.BatchRequest`3&lt;string, class Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions, class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequests.PoolUpgradeOSBatchRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolUpgradeOSBatchRequest&#xA;Inherits BatchRequest(Of String, PoolUpgradeOSOptions, AzureOperationHeaderResponse(Of PoolUpgradeOSHeaders))" />
  <TypeSignature Language="F#" Value="type PoolUpgradeOSBatchRequest = class&#xA;    inherit BatchRequest&lt;string, PoolUpgradeOSOptions, AzureOperationHeaderResponse&lt;PoolUpgradeOSHeaders&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.BatchRequest&lt;System.String,Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions,Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TBody">System.String</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TOptions">Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TResponse">Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f7f1e-101">Ein <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> für den PoolUpgradeOS-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="f7f1e-101">An <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> for the PoolUpgradeOS operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolUpgradeOSBatchRequest (Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, string parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, string parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequests.PoolUpgradeOSBatchRequest.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequests.PoolUpgradeOSBatchRequest : Microsoft.Azure.Batch.Protocol.BatchServiceClient * string * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequests.PoolUpgradeOSBatchRequest" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequests.PoolUpgradeOSBatchRequest (serviceClient, parameters, cancellationToken)" />
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
        <param name="serviceClient"><span data-ttu-id="f7f1e-102">Der Dienstclient verwendet.</span><span class="sxs-lookup"><span data-stu-id="f7f1e-102">The service client to use.</span></span></param>
        <param name="parameters"><span data-ttu-id="f7f1e-103">Die Parameter zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="f7f1e-103">The parameters to use.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f7f1e-104">Ein <see cref="T:System.Threading.CancellationToken" /> Steuerung der Lebensdauer der Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f7f1e-104">A <see cref="T:System.Threading.CancellationToken" /> controlling the request lifetime.</span></span></param>
        <summary>
            <span data-ttu-id="f7f1e-105">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.PoolUpgradeOSBatchRequest" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f7f1e-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.PoolUpgradeOSBatchRequest" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>