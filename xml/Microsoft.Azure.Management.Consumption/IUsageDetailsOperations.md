<Type Name="IUsageDetailsOperations" FullName="Microsoft.Azure.Management.Consumption.IUsageDetailsOperations">
  <TypeSignature Language="C#" Value="public interface IUsageDetailsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IUsageDetailsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Consumption.IUsageDetailsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IUsageDetailsOperations" />
  <TypeSignature Language="F#" Value="type IUsageDetailsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="868ef-101">UsageDetailsOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="868ef-101">UsageDetailsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Consumption.IUsageDetailsOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;&gt;" Usage="iUsageDetailsOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="868ef-102">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="868ef-102">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="868ef-103">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="868ef-103">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="868ef-104">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="868ef-104">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="868ef-105">Listet die Verwendungsdetails für einen Bereich von Abrechnungszeitraum.</span><span class="sxs-lookup"><span data-stu-id="868ef-105">Lists the usage details for a scope by billing period.</span></span> <span data-ttu-id="868ef-106">Nutzungsdetails sind nur über diese API nur für am 1. Mai 2014 oder höher verfügbar.</span><span class="sxs-lookup"><span data-stu-id="868ef-106">Usage details are available via this API only for May 1, 2014 or later.</span></span>
            <see href="https://docs.microsoft.com/en-us/azure/billing/billing-enterprise-api" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Consumption.Models.ErrorResponseException">
            <span data-ttu-id="868ef-107">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="868ef-107">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="868ef-108">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="868ef-108">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="868ef-109">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="868ef-109">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;&gt; ListWithHttpMessagesAsync (string scope, string expand = null, string filter = null, string skiptoken = null, Nullable&lt;int&gt; top = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;&gt; ListWithHttpMessagesAsync(string scope, string expand, string filter, string skiptoken, valuetype System.Nullable`1&lt;int32&gt; top, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Consumption.IUsageDetailsOperations.ListWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * string * string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;&gt;" Usage="iUsageDetailsOperations.ListWithHttpMessagesAsync (scope, expand, filter, skiptoken, top, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="skiptoken" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            <span data-ttu-id="868ef-110">Der Bereich die Verwendungsdetails.</span><span class="sxs-lookup"><span data-stu-id="868ef-110">The scope of the usage details.</span></span> <span data-ttu-id="868ef-111">Der Bereich kann "/ Subscriptions / {SubscriptionId}" für ein Abonnement, oder "/ subscriptions/{subscriptionId}/providers/Microsoft.Billing/billingPeriods/{billingPeriodName}" für einen Abrechnungszyklus Perdiod.</span><span class="sxs-lookup"><span data-stu-id="868ef-111">The scope can be '/subscriptions/{subscriptionId}' for a subscription, or '/subscriptions/{subscriptionId}/providers/Microsoft.Billing/billingPeriods/{billingPeriodName}' for a billing perdiod.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="868ef-112">Kann verwendet werden, um die Eigenschaften / "AdditionalProperties" oder die Eigenschaften/MeterDetails in einer Liste von Nutzungsdetails zu erweitern.</span><span class="sxs-lookup"><span data-stu-id="868ef-112">May be used to expand the properties/additionalProperties or properties/meterDetails within a list of usage details.</span></span> <span data-ttu-id="868ef-113">Standardmäßig sind diese Felder nicht eingeschlossen, wenn Nutzungsdetails aufgelistet.</span><span class="sxs-lookup"><span data-stu-id="868ef-113">By default, these fields are not included when listing usage details.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="868ef-114">Kann verwendet werden UsageDetails Filtern von Eigenschaften/UsageEnd (Utc-Zeit), -Eigenschaften/UsageStart (Utc-Zeit), Eigenschaften / "ResourceGroup", Eigenschaften/InstanceName oder Eigenschaften/InstanceId.</span><span class="sxs-lookup"><span data-stu-id="868ef-114">May be used to filter usageDetails by properties/usageEnd (Utc time), properties/usageStart (Utc time), properties/resourceGroup, properties/instanceName or properties/instanceId.</span></span> <span data-ttu-id="868ef-115">Der Filter unterstützt "Eq", "Lt", 'Gt', 'le', "ge", und "und".</span><span class="sxs-lookup"><span data-stu-id="868ef-115">The filter supports 'eq', 'lt', 'gt', 'le', 'ge', and 'and'.</span></span> <span data-ttu-id="868ef-116">Es derzeit nicht unterstützt 'Ne', 'oder' oder 'nicht'.</span><span class="sxs-lookup"><span data-stu-id="868ef-116">It does not currently support 'ne', 'or', or 'not'.</span></span>
            </param>
        <param name="skiptoken">
            <span data-ttu-id="868ef-117">Skiptoken wird nur verwendet, wenn der vorherige Vorgang ein Teilergebnis zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="868ef-117">Skiptoken is only used if a previous operation returned a partial result.</span></span> <span data-ttu-id="868ef-118">Wenn eine vorherige Antwort ein "NextLink"-Element enthält, wird der Wert des Elements "NextLink" einen Skiptoken-Parameter enthalten, der einen Ausgangspunkt für die Verwendung für nachfolgende Aufrufe zu angibt.</span><span class="sxs-lookup"><span data-stu-id="868ef-118">If a previous response contains a nextLink element, the value of the nextLink element will include a skiptoken parameter that specifies a starting point to use for subsequent calls.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="868ef-119">Kann verwendet werden, um die Anzahl der Ergebnisse in den letzten N UsageDetails zu beschränken.</span><span class="sxs-lookup"><span data-stu-id="868ef-119">May be used to limit the number of results to the most recent N usageDetails.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="868ef-120">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="868ef-120">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="868ef-121">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="868ef-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="868ef-122">Listet die Verwendungsdetails für einen Bereich von Abrechnungszeitraum.</span><span class="sxs-lookup"><span data-stu-id="868ef-122">Lists the usage details for a scope by billing period.</span></span> <span data-ttu-id="868ef-123">Nutzungsdetails sind nur über diese API nur für am 1. Mai 2014 oder höher verfügbar.</span><span class="sxs-lookup"><span data-stu-id="868ef-123">Usage details are available via this API only for May 1, 2014 or later.</span></span>
            <see href="https://docs.microsoft.com/en-us/azure/billing/billing-enterprise-api" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Consumption.Models.ErrorResponseException">
            <span data-ttu-id="868ef-124">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="868ef-124">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="868ef-125">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="868ef-125">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="868ef-126">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="868ef-126">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>