<Type Name="IIntegrationRuntimeNodesOperations" FullName="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations">
  <TypeSignature Language="C#" Value="public interface IIntegrationRuntimeNodesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IIntegrationRuntimeNodesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IIntegrationRuntimeNodesOperations" />
  <TypeSignature Language="F#" Value="type IIntegrationRuntimeNodesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b9cf7-101">IntegrationRuntimeNodesOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-101">IntegrationRuntimeNodesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string factoryName, string integrationRuntimeName, string nodeName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string factoryName, string integrationRuntimeName, string nodeName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iIntegrationRuntimeNodesOperations.DeleteWithHttpMessagesAsync (resourceGroupName, factoryName, integrationRuntimeName, nodeName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b9cf7-102">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-102">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="b9cf7-103">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-103">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="b9cf7-104">Die Integration Laufzeitklasse-Namen.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-104">The integration runtime name.</span></span>
            </param>
        <param name="nodeName">
            <span data-ttu-id="b9cf7-105">Der Name der Integration Common Language Runtime-Knoten.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-105">The integration runtime node name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b9cf7-106">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b9cf7-107">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b9cf7-108">Löscht einen selbst gehosteten Integration Common Language Runtime-Knoten.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-108">Deletes a self-hosted integration runtime node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="b9cf7-109">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b9cf7-110">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetIpAddressWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeIpAddress&gt;&gt; GetIpAddressWithHttpMessagesAsync (string resourceGroupName, string factoryName, string integrationRuntimeName, string nodeName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeIpAddress&gt;&gt; GetIpAddressWithHttpMessagesAsync(string resourceGroupName, string factoryName, string integrationRuntimeName, string nodeName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations.GetIpAddressWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetIpAddressWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeIpAddress&gt;&gt;" Usage="iIntegrationRuntimeNodesOperations.GetIpAddressWithHttpMessagesAsync (resourceGroupName, factoryName, integrationRuntimeName, nodeName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeIpAddress&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b9cf7-111">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-111">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="b9cf7-112">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-112">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="b9cf7-113">Die Integration Laufzeitklasse-Namen.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-113">The integration runtime name.</span></span>
            </param>
        <param name="nodeName">
            <span data-ttu-id="b9cf7-114">Der Name der Integration Common Language Runtime-Knoten.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-114">The integration runtime node name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b9cf7-115">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-115">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b9cf7-116">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b9cf7-117">Abgerufen Sie die IP-Adresse des Knotens für selbst gehostete Integration Laufzeit werden.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-117">Get the IP address of self-hosted integration runtime node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="b9cf7-118">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-118">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b9cf7-119">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-119">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b9cf7-120">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-120">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeNode&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string factoryName, string integrationRuntimeName, string nodeName, Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeNodeRequest updateIntegrationRuntimeNodeRequest, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeNode&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string factoryName, string integrationRuntimeName, string nodeName, class Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeNodeRequest updateIntegrationRuntimeNodeRequest, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations.UpdateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeNodeRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeNodeRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeNode&gt;&gt;" Usage="iIntegrationRuntimeNodesOperations.UpdateWithHttpMessagesAsync (resourceGroupName, factoryName, integrationRuntimeName, nodeName, updateIntegrationRuntimeNodeRequest, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeNode&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="updateIntegrationRuntimeNodeRequest" Type="Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeNodeRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b9cf7-121">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-121">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="b9cf7-122">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-122">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="b9cf7-123">Die Integration Laufzeitklasse-Namen.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-123">The integration runtime name.</span></span>
            </param>
        <param name="nodeName">
            <span data-ttu-id="b9cf7-124">Der Name der Integration Common Language Runtime-Knoten.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-124">The integration runtime node name.</span></span>
            </param>
        <param name="updateIntegrationRuntimeNodeRequest">
            <span data-ttu-id="b9cf7-125">Die Parameter für das Aktualisieren einer Integration Common Language Runtime-Knotens.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-125">The parameters for updating an integration runtime node.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b9cf7-126">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-126">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b9cf7-127">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b9cf7-128">Aktualisiert einen selbst gehosteten Integration Common Language Runtime-Knoten.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-128">Updates a self-hosted integration runtime node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="b9cf7-129">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-129">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b9cf7-130">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-130">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b9cf7-131">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="b9cf7-131">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>