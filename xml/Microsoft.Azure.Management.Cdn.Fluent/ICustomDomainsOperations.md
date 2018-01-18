<Type Name="ICustomDomainsOperations" FullName="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations">
  <TypeSignature Language="C#" Value="public interface ICustomDomainsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICustomDomainsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICustomDomainsOperations" />
  <TypeSignature Language="F#" Value="type ICustomDomainsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="63bd0-101">CustomDomainsOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="63bd0-101">CustomDomainsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; BeginCreateWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, string customDomainName, string hostName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; BeginCreateWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, string customDomainName, string hostName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations.BeginCreateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateWithHttpMessagesAsync : string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;" Usage="iCustomDomainsOperations.BeginCreateWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, customDomainName, hostName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="63bd0-102">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="63bd0-102">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="63bd0-103">Name des CDN-Profil, das in der Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="63bd0-103">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="63bd0-104">Der Name des Endpunkts unter dem Profil, das global eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="63bd0-104">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customDomainName">
            <span data-ttu-id="63bd0-105">Der Name der benutzerdefinierten Domäne innerhalb eines Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="63bd0-105">Name of the custom domain within an endpoint.</span></span>
            </param>
        <param name="hostName">
            <span data-ttu-id="63bd0-106">Der Hostname der benutzerdefinierten Domäne.</span><span class="sxs-lookup"><span data-stu-id="63bd0-106">The host name of the custom domain.</span></span> <span data-ttu-id="63bd0-107">Ein Domänenname muss sein.</span><span class="sxs-lookup"><span data-stu-id="63bd0-107">Must be a domain name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="63bd0-108">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="63bd0-108">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63bd0-109">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="63bd0-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63bd0-110">Erstellt eine neue benutzerdefinierte Domäne innerhalb eines Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="63bd0-110">Creates a new custom domain within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="63bd0-111">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="63bd0-111">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="63bd0-112">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="63bd0-112">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="63bd0-113">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="63bd0-113">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, string customDomainName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;" Usage="iCustomDomainsOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, customDomainName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="63bd0-114">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="63bd0-114">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="63bd0-115">Name des CDN-Profil, das in der Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="63bd0-115">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="63bd0-116">Der Name des Endpunkts unter dem Profil, das global eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="63bd0-116">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customDomainName">
            <span data-ttu-id="63bd0-117">Der Name der benutzerdefinierten Domäne innerhalb eines Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="63bd0-117">Name of the custom domain within an endpoint.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="63bd0-118">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="63bd0-118">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63bd0-119">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="63bd0-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63bd0-120">Löscht eine vorhandene benutzerdefinierte Domäne innerhalb eines Endpunkts an.</span><span class="sxs-lookup"><span data-stu-id="63bd0-120">Deletes an existing custom domain within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="63bd0-121">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="63bd0-121">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="63bd0-122">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="63bd0-122">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="63bd0-123">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="63bd0-123">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; CreateWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, string customDomainName, string hostName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; CreateWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, string customDomainName, string hostName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations.CreateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;" Usage="iCustomDomainsOperations.CreateWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, customDomainName, hostName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="63bd0-124">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="63bd0-124">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="63bd0-125">Name des CDN-Profil, das in der Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="63bd0-125">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="63bd0-126">Der Name des Endpunkts unter dem Profil, das global eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="63bd0-126">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customDomainName">
            <span data-ttu-id="63bd0-127">Der Name der benutzerdefinierten Domäne innerhalb eines Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="63bd0-127">Name of the custom domain within an endpoint.</span></span>
            </param>
        <param name="hostName">
            <span data-ttu-id="63bd0-128">Der Hostname der benutzerdefinierten Domäne.</span><span class="sxs-lookup"><span data-stu-id="63bd0-128">The host name of the custom domain.</span></span> <span data-ttu-id="63bd0-129">Ein Domänenname muss sein.</span><span class="sxs-lookup"><span data-stu-id="63bd0-129">Must be a domain name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="63bd0-130">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="63bd0-130">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63bd0-131">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="63bd0-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63bd0-132">Erstellt eine neue benutzerdefinierte Domäne innerhalb eines Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="63bd0-132">Creates a new custom domain within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="63bd0-133">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="63bd0-133">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="63bd0-134">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="63bd0-134">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="63bd0-135">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="63bd0-135">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, string customDomainName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;" Usage="iCustomDomainsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, customDomainName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="63bd0-136">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="63bd0-136">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="63bd0-137">Name des CDN-Profil, das in der Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="63bd0-137">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="63bd0-138">Der Name des Endpunkts unter dem Profil, das global eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="63bd0-138">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customDomainName">
            <span data-ttu-id="63bd0-139">Der Name der benutzerdefinierten Domäne innerhalb eines Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="63bd0-139">Name of the custom domain within an endpoint.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="63bd0-140">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="63bd0-140">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63bd0-141">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="63bd0-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63bd0-142">Löscht eine vorhandene benutzerdefinierte Domäne innerhalb eines Endpunkts an.</span><span class="sxs-lookup"><span data-stu-id="63bd0-142">Deletes an existing custom domain within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="63bd0-143">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="63bd0-143">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="63bd0-144">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="63bd0-144">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="63bd0-145">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="63bd0-145">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DisableCustomHttpsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; DisableCustomHttpsWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; DisableCustomHttpsWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, string customDomainName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations.DisableCustomHttpsWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DisableCustomHttpsWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;" Usage="iCustomDomainsOperations.DisableCustomHttpsWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, customDomainName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="63bd0-146">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="63bd0-146">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="63bd0-147">Name des CDN-Profil, das in der Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="63bd0-147">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="63bd0-148">Der Name des Endpunkts unter dem Profil, das global eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="63bd0-148">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customDomainName">
            <span data-ttu-id="63bd0-149">Der Name der benutzerdefinierten Domäne innerhalb eines Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="63bd0-149">Name of the custom domain within an endpoint.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="63bd0-150">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="63bd0-150">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63bd0-151">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="63bd0-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63bd0-152">Deaktivieren Sie die Https-Übermittlung der benutzerdefinierten Domäne.</span><span class="sxs-lookup"><span data-stu-id="63bd0-152">Disable https delivery of the custom domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="63bd0-153">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="63bd0-153">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="63bd0-154">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="63bd0-154">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="63bd0-155">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="63bd0-155">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="EnableCustomHttpsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; EnableCustomHttpsWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; EnableCustomHttpsWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, string customDomainName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations.EnableCustomHttpsWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EnableCustomHttpsWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;" Usage="iCustomDomainsOperations.EnableCustomHttpsWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, customDomainName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="63bd0-156">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="63bd0-156">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="63bd0-157">Name des CDN-Profil, das in der Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="63bd0-157">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="63bd0-158">Der Name des Endpunkts unter dem Profil, das global eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="63bd0-158">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customDomainName">
            <span data-ttu-id="63bd0-159">Der Name der benutzerdefinierten Domäne innerhalb eines Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="63bd0-159">Name of the custom domain within an endpoint.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="63bd0-160">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="63bd0-160">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63bd0-161">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="63bd0-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63bd0-162">Https-Übermittlung, der die benutzerdefinierte Domäne zu aktivieren.</span><span class="sxs-lookup"><span data-stu-id="63bd0-162">Enable https delivery of the custom domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="63bd0-163">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="63bd0-163">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="63bd0-164">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="63bd0-164">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="63bd0-165">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="63bd0-165">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, string customDomainName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;" Usage="iCustomDomainsOperations.GetWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, customDomainName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="63bd0-166">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="63bd0-166">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="63bd0-167">Name des CDN-Profil, das in der Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="63bd0-167">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="63bd0-168">Der Name des Endpunkts unter dem Profil, das global eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="63bd0-168">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customDomainName">
            <span data-ttu-id="63bd0-169">Der Name der benutzerdefinierten Domäne innerhalb eines Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="63bd0-169">Name of the custom domain within an endpoint.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="63bd0-170">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="63bd0-170">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63bd0-171">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="63bd0-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63bd0-172">Ruft die benutzerdefinierte Domäne einer vorhandenen innerhalb eines Endpunkts ab.</span><span class="sxs-lookup"><span data-stu-id="63bd0-172">Gets an exisitng custom domain within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="63bd0-173">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="63bd0-173">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="63bd0-174">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="63bd0-174">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="63bd0-175">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="63bd0-175">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByEndpointNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;&gt; ListByEndpointNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;&gt; ListByEndpointNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations.ListByEndpointNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByEndpointNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;&gt;" Usage="iCustomDomainsOperations.ListByEndpointNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="63bd0-176">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="63bd0-176">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="63bd0-177">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="63bd0-177">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63bd0-178">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="63bd0-178">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63bd0-179">Zeigt eine Liste aller vorhandenen benutzerdefinierten Domänen innerhalb eines Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="63bd0-179">Lists all of the existing custom domains within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="63bd0-180">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="63bd0-180">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="63bd0-181">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="63bd0-181">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="63bd0-182">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="63bd0-182">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByEndpointWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;&gt; ListByEndpointWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;&gt; ListByEndpointWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations.ListByEndpointWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByEndpointWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;&gt;" Usage="iCustomDomainsOperations.ListByEndpointWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="63bd0-183">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="63bd0-183">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="63bd0-184">Name des CDN-Profil, das in der Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="63bd0-184">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="63bd0-185">Der Name des Endpunkts unter dem Profil, das global eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="63bd0-185">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="63bd0-186">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="63bd0-186">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63bd0-187">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="63bd0-187">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63bd0-188">Zeigt eine Liste aller vorhandenen benutzerdefinierten Domänen innerhalb eines Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="63bd0-188">Lists all of the existing custom domains within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="63bd0-189">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="63bd0-189">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="63bd0-190">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="63bd0-190">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="63bd0-191">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="63bd0-191">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>