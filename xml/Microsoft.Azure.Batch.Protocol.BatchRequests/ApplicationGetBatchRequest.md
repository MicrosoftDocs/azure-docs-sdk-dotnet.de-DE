<Type Name="ApplicationGetBatchRequest" FullName="Microsoft.Azure.Batch.Protocol.BatchRequests.ApplicationGetBatchRequest">
  <TypeSignature Language="C#" Value="public class ApplicationGetBatchRequest : Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions,Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary,Microsoft.Azure.Batch.Protocol.Models.ApplicationGetHeaders&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGetBatchRequest extends Microsoft.Azure.Batch.Protocol.BatchRequest`2&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions, class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary, class Microsoft.Azure.Batch.Protocol.Models.ApplicationGetHeaders&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequests.ApplicationGetBatchRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGetBatchRequest&#xA;Inherits BatchRequest(Of ApplicationGetOptions, AzureOperationResponse(Of ApplicationSummary, ApplicationGetHeaders))" />
  <TypeSignature Language="F#" Value="type ApplicationGetBatchRequest = class&#xA;    inherit BatchRequest&lt;ApplicationGetOptions, AzureOperationResponse&lt;ApplicationSummary, ApplicationGetHeaders&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions,Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary,Microsoft.Azure.Batch.Protocol.Models.ApplicationGetHeaders&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TOptions">Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TResponse">Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary,Microsoft.Azure.Batch.Protocol.Models.ApplicationGetHeaders&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f0c05-101">Ein <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> für den ApplicationGet-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="f0c05-101">An <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> for the ApplicationGet operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGetBatchRequest (Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequests.ApplicationGetBatchRequest.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequests.ApplicationGetBatchRequest : Microsoft.Azure.Batch.Protocol.BatchServiceClient * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequests.ApplicationGetBatchRequest" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequests.ApplicationGetBatchRequest (serviceClient, cancellationToken)" />
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
        <param name="serviceClient"><span data-ttu-id="f0c05-102">Der Dienstclient verwendet.</span><span class="sxs-lookup"><span data-stu-id="f0c05-102">The service client to use.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f0c05-103">Ein <see cref="T:System.Threading.CancellationToken" /> Steuerung der Lebensdauer der Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f0c05-103">A <see cref="T:System.Threading.CancellationToken" /> controlling the request lifetime.</span></span></param>
        <summary>
            <span data-ttu-id="f0c05-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.ApplicationGetBatchRequest" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f0c05-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.ApplicationGetBatchRequest" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>