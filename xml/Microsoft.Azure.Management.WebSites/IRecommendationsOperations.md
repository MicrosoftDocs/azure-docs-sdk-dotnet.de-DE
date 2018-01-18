<Type Name="IRecommendationsOperations" FullName="Microsoft.Azure.Management.WebSites.IRecommendationsOperations">
  <TypeSignature Language="C#" Value="public interface IRecommendationsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRecommendationsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.IRecommendationsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRecommendationsOperations" />
  <TypeSignature Language="F#" Value="type IRecommendationsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="74d05-101">RecommendationsOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="74d05-101">RecommendationsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DisableAllForWebAppWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DisableAllForWebAppWithHttpMessagesAsync (string resourceGroupName, string siteName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DisableAllForWebAppWithHttpMessagesAsync(string resourceGroupName, string siteName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IRecommendationsOperations.DisableAllForWebAppWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DisableAllForWebAppWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iRecommendationsOperations.DisableAllForWebAppWithHttpMessagesAsync (resourceGroupName, siteName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="74d05-102">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="74d05-102">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="74d05-103">Der Name der app.</span><span class="sxs-lookup"><span data-stu-id="74d05-103">Name of the app.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="74d05-104">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="74d05-104">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="74d05-105">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="74d05-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74d05-106">Deaktivieren Sie alle Empfehlungen für eine app an.</span><span class="sxs-lookup"><span data-stu-id="74d05-106">Disable all recommendations for an app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="74d05-107">Deaktivieren Sie alle Empfehlungen für eine app an.</span><span class="sxs-lookup"><span data-stu-id="74d05-107">Disable all recommendations for an app.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="74d05-108">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="74d05-108">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="74d05-109">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="74d05-109">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetRuleDetailsByWebAppWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.RecommendationRule&gt;&gt; GetRuleDetailsByWebAppWithHttpMessagesAsync (string resourceGroupName, string siteName, string name, Nullable&lt;bool&gt; updateSeen = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.RecommendationRule&gt;&gt; GetRuleDetailsByWebAppWithHttpMessagesAsync(string resourceGroupName, string siteName, string name, valuetype System.Nullable`1&lt;bool&gt; updateSeen, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IRecommendationsOperations.GetRuleDetailsByWebAppWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetRuleDetailsByWebAppWithHttpMessagesAsync : string * string * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.RecommendationRule&gt;&gt;" Usage="iRecommendationsOperations.GetRuleDetailsByWebAppWithHttpMessagesAsync (resourceGroupName, siteName, name, updateSeen, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.RecommendationRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="updateSeen" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="74d05-110">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="74d05-110">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="74d05-111">Der Name der app.</span><span class="sxs-lookup"><span data-stu-id="74d05-111">Name of the app.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="74d05-112">Der Name der Empfehlung.</span><span class="sxs-lookup"><span data-stu-id="74d05-112">Name of the recommendation.</span></span>
            </param>
        <param name="updateSeen">
            <span data-ttu-id="74d05-113">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; den letzten gesehen Zeitstempel des Objekts Empfehlung zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="74d05-113">Specify &lt;code&gt;true&lt;/code&gt; to update the last-seen timestamp of the recommendation object.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="74d05-114">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="74d05-114">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="74d05-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="74d05-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74d05-116">Eine Regel für die Empfehlung für eine app abrufen.</span><span class="sxs-lookup"><span data-stu-id="74d05-116">Get a recommendation rule for an app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="74d05-117">Eine Regel für die Empfehlung für eine app abrufen.</span><span class="sxs-lookup"><span data-stu-id="74d05-117">Get a recommendation rule for an app.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="74d05-118">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="74d05-118">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="74d05-119">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="74d05-119">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="74d05-120">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="74d05-120">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListHistoryForWebAppWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;&gt; ListHistoryForWebAppWithHttpMessagesAsync (string resourceGroupName, string siteName, string filter = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;&gt; ListHistoryForWebAppWithHttpMessagesAsync(string resourceGroupName, string siteName, string filter, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IRecommendationsOperations.ListHistoryForWebAppWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListHistoryForWebAppWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;&gt;" Usage="iRecommendationsOperations.ListHistoryForWebAppWithHttpMessagesAsync (resourceGroupName, siteName, filter, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="74d05-121">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="74d05-121">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="74d05-122">Der Name der app.</span><span class="sxs-lookup"><span data-stu-id="74d05-122">Name of the app.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="74d05-123">Filter wird mithilfe von OData-Syntax angegeben.</span><span class="sxs-lookup"><span data-stu-id="74d05-123">Filter is specified by using OData syntax.</span></span> <span data-ttu-id="74d05-124">Beispiel: $filter = Kanäle Eq "-Api" oder den Kanal Eq "Benachrichtigung" und "StartTime" Eq "2014-01-01T00:00:00Z" und EndTime-Eq "2014-12-31T23:59:59Z" und die Dauer der timegrain-Wert-Eq "[PT1H | PT1M | P1D]</span><span class="sxs-lookup"><span data-stu-id="74d05-124">Example: $filter=channels eq 'Api' or channel eq 'Notification' and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[PT1H|PT1M|P1D]</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="74d05-125">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="74d05-125">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="74d05-126">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="74d05-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74d05-127">Darüber hinaus Empfehlungen für eine app, die optional angegeben werden, indem Sie den Zeitbereich.</span><span class="sxs-lookup"><span data-stu-id="74d05-127">Get past recommendations for an app, optionally specified by the time range.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="74d05-128">Darüber hinaus Empfehlungen für eine app, die optional angegeben werden, indem Sie den Zeitbereich.</span><span class="sxs-lookup"><span data-stu-id="74d05-128">Get past recommendations for an app, optionally specified by the time range.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="74d05-129">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="74d05-129">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="74d05-130">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="74d05-130">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="74d05-131">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="74d05-131">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListRecommendedRulesForWebAppWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;&gt; ListRecommendedRulesForWebAppWithHttpMessagesAsync (string resourceGroupName, string siteName, Nullable&lt;bool&gt; featured = null, string filter = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;&gt; ListRecommendedRulesForWebAppWithHttpMessagesAsync(string resourceGroupName, string siteName, valuetype System.Nullable`1&lt;bool&gt; featured, string filter, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IRecommendationsOperations.ListRecommendedRulesForWebAppWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Boolean},System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListRecommendedRulesForWebAppWithHttpMessagesAsync : string * string * Nullable&lt;bool&gt; * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;&gt;" Usage="iRecommendationsOperations.ListRecommendedRulesForWebAppWithHttpMessagesAsync (resourceGroupName, siteName, featured, filter, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="featured" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="74d05-132">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="74d05-132">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="74d05-133">Der Name der app.</span><span class="sxs-lookup"><span data-stu-id="74d05-133">Name of the app.</span></span>
            </param>
        <param name="featured">
            <span data-ttu-id="74d05-134">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; nur die wichtigsten Empfehlungen zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="74d05-134">Specify &lt;code&gt;true&lt;/code&gt; to return only the most critical recommendations.</span></span> <span data-ttu-id="74d05-135">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;, wobei alle Empfehlungen zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="74d05-135">The default is &lt;code&gt;false&lt;/code&gt;, which returns all recommendations.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="74d05-136">Geben Sie nur die Kanäle, die im Filter angegebenen zurück.</span><span class="sxs-lookup"><span data-stu-id="74d05-136">Return only channels specified in the filter.</span></span> <span data-ttu-id="74d05-137">Filter wird mithilfe von OData-Syntax angegeben.</span><span class="sxs-lookup"><span data-stu-id="74d05-137">Filter is specified by using OData syntax.</span></span> <span data-ttu-id="74d05-138">Beispiel: $filter = Kanäle Eq "-Api" oder den Kanal Eq "Benachrichtigung"</span><span class="sxs-lookup"><span data-stu-id="74d05-138">Example: $filter=channels eq 'Api' or channel eq 'Notification'</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="74d05-139">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="74d05-139">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="74d05-140">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="74d05-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74d05-141">Rufen Sie aller Empfehlungen für eine app an ab.</span><span class="sxs-lookup"><span data-stu-id="74d05-141">Get all recommendations for an app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="74d05-142">Rufen Sie aller Empfehlungen für eine app an ab.</span><span class="sxs-lookup"><span data-stu-id="74d05-142">Get all recommendations for an app.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="74d05-143">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="74d05-143">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="74d05-144">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="74d05-144">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="74d05-145">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="74d05-145">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;&gt; ListWithHttpMessagesAsync (Nullable&lt;bool&gt; featured = null, string filter = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;&gt; ListWithHttpMessagesAsync(valuetype System.Nullable`1&lt;bool&gt; featured, string filter, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IRecommendationsOperations.ListWithHttpMessagesAsync(System.Nullable{System.Boolean},System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : Nullable&lt;bool&gt; * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;&gt;" Usage="iRecommendationsOperations.ListWithHttpMessagesAsync (featured, filter, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="featured" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="featured">
            <span data-ttu-id="74d05-146">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; nur die wichtigsten Empfehlungen zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="74d05-146">Specify &lt;code&gt;true&lt;/code&gt; to return only the most critical recommendations.</span></span> <span data-ttu-id="74d05-147">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;, wobei alle Empfehlungen zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="74d05-147">The default is &lt;code&gt;false&lt;/code&gt;, which returns all recommendations.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="74d05-148">Filter wird mithilfe von OData-Syntax angegeben.</span><span class="sxs-lookup"><span data-stu-id="74d05-148">Filter is specified by using OData syntax.</span></span> <span data-ttu-id="74d05-149">Beispiel: $filter = Kanäle Eq "-Api" oder den Kanal Eq "Benachrichtigung" und "StartTime" Eq "2014-01-01T00:00:00Z" und EndTime-Eq "2014-12-31T23:59:59Z" und die Dauer der timegrain-Wert-Eq "[PT1H | PT1M | P1D]</span><span class="sxs-lookup"><span data-stu-id="74d05-149">Example: $filter=channels eq 'Api' or channel eq 'Notification' and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[PT1H|PT1M|P1D]</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="74d05-150">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="74d05-150">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="74d05-151">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="74d05-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74d05-152">Liste aller Empfehlungen für ein Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="74d05-152">List all recommendations for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="74d05-153">Liste aller Empfehlungen für ein Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="74d05-153">List all recommendations for a subscription.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="74d05-154">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="74d05-154">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="74d05-155">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="74d05-155">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="74d05-156">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="74d05-156">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ResetAllFiltersForWebAppWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ResetAllFiltersForWebAppWithHttpMessagesAsync (string resourceGroupName, string siteName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ResetAllFiltersForWebAppWithHttpMessagesAsync(string resourceGroupName, string siteName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IRecommendationsOperations.ResetAllFiltersForWebAppWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResetAllFiltersForWebAppWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iRecommendationsOperations.ResetAllFiltersForWebAppWithHttpMessagesAsync (resourceGroupName, siteName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="74d05-157">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="74d05-157">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="74d05-158">Der Name der app.</span><span class="sxs-lookup"><span data-stu-id="74d05-158">Name of the app.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="74d05-159">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="74d05-159">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="74d05-160">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="74d05-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74d05-161">Alle Empfehlung opt-Out-Einstellungen für eine app zurücksetzen.</span><span class="sxs-lookup"><span data-stu-id="74d05-161">Reset all recommendation opt-out settings for an app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="74d05-162">Alle Empfehlung opt-Out-Einstellungen für eine app zurücksetzen.</span><span class="sxs-lookup"><span data-stu-id="74d05-162">Reset all recommendation opt-out settings for an app.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="74d05-163">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="74d05-163">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="74d05-164">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="74d05-164">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ResetAllFiltersWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ResetAllFiltersWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ResetAllFiltersWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IRecommendationsOperations.ResetAllFiltersWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResetAllFiltersWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iRecommendationsOperations.ResetAllFiltersWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="74d05-165">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="74d05-165">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="74d05-166">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="74d05-166">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74d05-167">Setzen Sie alle Empfehlung opt-Out-Einstellungen für ein Abonnement zurück.</span><span class="sxs-lookup"><span data-stu-id="74d05-167">Reset all recommendation opt-out settings for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="74d05-168">Setzen Sie alle Empfehlung opt-Out-Einstellungen für ein Abonnement zurück.</span><span class="sxs-lookup"><span data-stu-id="74d05-168">Reset all recommendation opt-out settings for a subscription.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="74d05-169">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="74d05-169">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="74d05-170">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="74d05-170">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>