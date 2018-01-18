<Type Name="CertificateListBatchRequest" FullName="Microsoft.Azure.Batch.Protocol.BatchRequests.CertificateListBatchRequest">
  <TypeSignature Language="C#" Value="public class CertificateListBatchRequest : Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions,Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;,Microsoft.Azure.Batch.Protocol.Models.CertificateListHeaders&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateListBatchRequest extends Microsoft.Azure.Batch.Protocol.BatchRequest`2&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions, class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;, class Microsoft.Azure.Batch.Protocol.Models.CertificateListHeaders&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequests.CertificateListBatchRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateListBatchRequest&#xA;Inherits BatchRequest(Of CertificateListOptions, AzureOperationResponse(Of IPage(Of Certificate), CertificateListHeaders))" />
  <TypeSignature Language="F#" Value="type CertificateListBatchRequest = class&#xA;    inherit BatchRequest&lt;CertificateListOptions, AzureOperationResponse&lt;IPage&lt;Certificate&gt;, CertificateListHeaders&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions,Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;,Microsoft.Azure.Batch.Protocol.Models.CertificateListHeaders&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TOptions">Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TResponse">Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;,Microsoft.Azure.Batch.Protocol.Models.CertificateListHeaders&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3ea0c-101">Ein <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> für den CertificateList-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="3ea0c-101">An <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> for the CertificateList operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateListBatchRequest (Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequests.CertificateListBatchRequest.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequests.CertificateListBatchRequest : Microsoft.Azure.Batch.Protocol.BatchServiceClient * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequests.CertificateListBatchRequest" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequests.CertificateListBatchRequest (serviceClient, cancellationToken)" />
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
        <param name="serviceClient"><span data-ttu-id="3ea0c-102">Der Dienstclient verwendet.</span><span class="sxs-lookup"><span data-stu-id="3ea0c-102">The service client to use.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="3ea0c-103">Ein <see cref="T:System.Threading.CancellationToken" /> Steuerung der Lebensdauer der Anforderung.</span><span class="sxs-lookup"><span data-stu-id="3ea0c-103">A <see cref="T:System.Threading.CancellationToken" /> controlling the request lifetime.</span></span></param>
        <summary>
            <span data-ttu-id="3ea0c-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.CertificateListBatchRequest" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3ea0c-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.CertificateListBatchRequest" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>