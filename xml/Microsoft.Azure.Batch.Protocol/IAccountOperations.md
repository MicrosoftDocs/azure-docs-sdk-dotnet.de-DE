<Type Name="IAccountOperations" FullName="Microsoft.Azure.Batch.Protocol.IAccountOperations">
  <TypeSignature Language="C#" Value="public interface IAccountOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAccountOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.IAccountOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAccountOperations" />
  <TypeSignature Language="F#" Value="type IAccountOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7ee8a-101">AccountOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="7ee8a-101">AccountOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListNodeAgentSkusNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt;,Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusHeaders&gt;&gt; ListNodeAgentSkusNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusNextOptions accountListNodeAgentSkusNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt;, class Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusHeaders&gt;&gt; ListNodeAgentSkusNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusNextOptions accountListNodeAgentSkusNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IAccountOperations.ListNodeAgentSkusNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNodeAgentSkusNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt;, Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusHeaders&gt;&gt;" Usage="iAccountOperations.ListNodeAgentSkusNextWithHttpMessagesAsync (nextPageLink, accountListNodeAgentSkusNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt;,Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="accountListNodeAgentSkusNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="7ee8a-102">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="7ee8a-102">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="accountListNodeAgentSkusNextOptions">
            <span data-ttu-id="7ee8a-103">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="7ee8a-103">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7ee8a-104">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="7ee8a-104">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ee8a-105">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7ee8a-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ee8a-106">Listet alle Knoten-Agent-SKUs von der Azure Batch-Dienst unterstützt.</span><span class="sxs-lookup"><span data-stu-id="7ee8a-106">Lists all node agent SKUs supported by the Azure Batch service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="7ee8a-107">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="7ee8a-107">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7ee8a-108">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="7ee8a-108">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7ee8a-109">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="7ee8a-109">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNodeAgentSkusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt;,Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusHeaders&gt;&gt; ListNodeAgentSkusWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusOptions accountListNodeAgentSkusOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt;, class Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusHeaders&gt;&gt; ListNodeAgentSkusWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusOptions accountListNodeAgentSkusOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IAccountOperations.ListNodeAgentSkusWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNodeAgentSkusWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt;, Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusHeaders&gt;&gt;" Usage="iAccountOperations.ListNodeAgentSkusWithHttpMessagesAsync (accountListNodeAgentSkusOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt;,Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountListNodeAgentSkusOptions" Type="Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountListNodeAgentSkusOptions">
            <span data-ttu-id="7ee8a-110">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="7ee8a-110">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7ee8a-111">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="7ee8a-111">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ee8a-112">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7ee8a-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ee8a-113">Listet alle Knoten-Agent-SKUs von der Azure Batch-Dienst unterstützt.</span><span class="sxs-lookup"><span data-stu-id="7ee8a-113">Lists all node agent SKUs supported by the Azure Batch service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="7ee8a-114">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="7ee8a-114">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7ee8a-115">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="7ee8a-115">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7ee8a-116">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="7ee8a-116">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>