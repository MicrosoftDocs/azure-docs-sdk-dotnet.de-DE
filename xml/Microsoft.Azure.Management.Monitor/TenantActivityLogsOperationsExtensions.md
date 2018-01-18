<Type Name="TenantActivityLogsOperationsExtensions" FullName="Microsoft.Azure.Management.Monitor.TenantActivityLogsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class TenantActivityLogsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TenantActivityLogsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.TenantActivityLogsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TenantActivityLogsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type TenantActivityLogsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0ccbd-101">Erweiterungsmethoden für TenantActivityLogsOperations.</span><span class="sxs-lookup"><span data-stu-id="0ccbd-101">Extension methods for TenantActivityLogsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt; List (this Microsoft.Azure.Management.Monitor.ITenantActivityLogsOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt; odataQuery = null, string select = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Monitor.Models.EventData&gt; List(class Microsoft.Azure.Management.Monitor.ITenantActivityLogsOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Monitor.Models.EventData&gt; odataQuery, string select) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.TenantActivityLogsOperationsExtensions.List(Microsoft.Azure.Management.Monitor.ITenantActivityLogsOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Monitor.Models.EventData},System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ITenantActivityLogsOperations, Optional odataQuery As ODataQuery(Of EventData) = null, Optional select As String = null) As IPage(Of EventData)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Monitor.ITenantActivityLogsOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt; * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;" Usage="Microsoft.Azure.Management.Monitor.TenantActivityLogsOperationsExtensions.List (operations, odataQuery, select)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.ITenantActivityLogsOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;" />
        <Parameter Name="select" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ccbd-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0ccbd-102">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="0ccbd-103">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="0ccbd-103">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="0ccbd-104">Wird verwendet, um Ereignisse mit dem nur die angegebenen Eigenschaften abzurufen. &lt;Br&gt;der **$select** Argument ist eine durch Trennzeichen getrennte Liste von Eigenschaftennamen, die zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="0ccbd-104">Used to fetch events with only the given properties.&lt;br&gt;The **$select** argument is a comma separated list of property names to be returned.</span></span> <span data-ttu-id="0ccbd-105">Mögliche Werte sind: *Autorisierung*, *Ansprüche*, *CorrelationId*, *Beschreibung*, *EventDataId*, *EventName*, *EventTimestamp*, *HttpRequest*, *Ebene*, *OperationId*, *OperationName*, *Eigenschaften*, *ResourceGroupName*, *ResourceProviderName*, *ResourceId*, *Status*, *SubmissionTimestamp*, *Unterstatus*, *"subscriptionId"*</span><span class="sxs-lookup"><span data-stu-id="0ccbd-105">Possible values are: *authorization*, *claims*, *correlationId*, *description*, *eventDataId*, *eventName*, *eventTimestamp*, *httpRequest*, *level*, *operationId*, *operationName*, *properties*, *resourceGroupName*, *resourceProviderName*, *resourceId*, *status*, *submissionTimestamp*, *subStatus*, *subscriptionId*</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ccbd-106">Ruft die Aktivitätsprotokolle für den Mandanten ab. &lt;Br&gt;alle Komponenten, die gilt für die API die Aktivitätsprotokolle abgerufen, für das Abonnement für diese API (der Parameter, $filter, usw.). &lt;Br&gt;aufpassen sieht, dass diese API ist Punkte *nicht* Abrufen der Protokolle auf die einzelnen Abonnements für den Mandanten aber nur Flächen die Protokolle, die auf Mandantenebene generiert wurden.</span><span class="sxs-lookup"><span data-stu-id="0ccbd-106">Gets the Activity Logs for the Tenant.&lt;br&gt;Everything that is applicable to the API to get the Activity Logs for the subscription is applicable to this API (the parameters, $filter, etc.).&lt;br&gt;One thing to point out here is that this API does *not* retrieve the logs at the individual subscription of the tenant but only surfaces the logs that were generated at the tenant level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;&gt; ListAsync (this Microsoft.Azure.Management.Monitor.ITenantActivityLogsOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt; odataQuery = null, string select = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Monitor.Models.EventData&gt;&gt; ListAsync(class Microsoft.Azure.Management.Monitor.ITenantActivityLogsOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Monitor.Models.EventData&gt; odataQuery, string select, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.TenantActivityLogsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Monitor.ITenantActivityLogsOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Monitor.Models.EventData},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Monitor.ITenantActivityLogsOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;&gt;" Usage="Microsoft.Azure.Management.Monitor.TenantActivityLogsOperationsExtensions.ListAsync (operations, odataQuery, select, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.TenantActivityLogsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.ITenantActivityLogsOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ccbd-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0ccbd-107">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="0ccbd-108">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="0ccbd-108">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="0ccbd-109">Wird verwendet, um Ereignisse mit dem nur die angegebenen Eigenschaften abzurufen. &lt;Br&gt;der **$select** Argument ist eine durch Trennzeichen getrennte Liste von Eigenschaftennamen, die zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="0ccbd-109">Used to fetch events with only the given properties.&lt;br&gt;The **$select** argument is a comma separated list of property names to be returned.</span></span> <span data-ttu-id="0ccbd-110">Mögliche Werte sind: *Autorisierung*, *Ansprüche*, *CorrelationId*, *Beschreibung*, *EventDataId*, *EventName*, *EventTimestamp*, *HttpRequest*, *Ebene*, *OperationId*, *OperationName*, *Eigenschaften*, *ResourceGroupName*, *ResourceProviderName*, *ResourceId*, *Status*, *SubmissionTimestamp*, *Unterstatus*, *"subscriptionId"*</span><span class="sxs-lookup"><span data-stu-id="0ccbd-110">Possible values are: *authorization*, *claims*, *correlationId*, *description*, *eventDataId*, *eventName*, *eventTimestamp*, *httpRequest*, *level*, *operationId*, *operationName*, *properties*, *resourceGroupName*, *resourceProviderName*, *resourceId*, *status*, *submissionTimestamp*, *subStatus*, *subscriptionId*</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ccbd-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0ccbd-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ccbd-112">Ruft die Aktivitätsprotokolle für den Mandanten ab. &lt;Br&gt;alle Komponenten, die gilt für die API die Aktivitätsprotokolle abgerufen, für das Abonnement für diese API (der Parameter, $filter, usw.). &lt;Br&gt;aufpassen sieht, dass diese API ist Punkte *nicht* Abrufen der Protokolle auf die einzelnen Abonnements für den Mandanten aber nur Flächen die Protokolle, die auf Mandantenebene generiert wurden.</span><span class="sxs-lookup"><span data-stu-id="0ccbd-112">Gets the Activity Logs for the Tenant.&lt;br&gt;Everything that is applicable to the API to get the Activity Logs for the subscription is applicable to this API (the parameters, $filter, etc.).&lt;br&gt;One thing to point out here is that this API does *not* retrieve the logs at the individual subscription of the tenant but only surfaces the logs that were generated at the tenant level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt; ListNext (this Microsoft.Azure.Management.Monitor.ITenantActivityLogsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Monitor.Models.EventData&gt; ListNext(class Microsoft.Azure.Management.Monitor.ITenantActivityLogsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.TenantActivityLogsOperationsExtensions.ListNext(Microsoft.Azure.Management.Monitor.ITenantActivityLogsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As ITenantActivityLogsOperations, nextPageLink As String) As IPage(Of EventData)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Monitor.ITenantActivityLogsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;" Usage="Microsoft.Azure.Management.Monitor.TenantActivityLogsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.ITenantActivityLogsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ccbd-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0ccbd-113">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="0ccbd-114">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0ccbd-114">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ccbd-115">Ruft die Aktivitätsprotokolle für den Mandanten ab. &lt;Br&gt;alle Komponenten, die gilt für die API die Aktivitätsprotokolle abgerufen, für das Abonnement für diese API (der Parameter, $filter, usw.). &lt;Br&gt;aufpassen sieht, dass diese API ist Punkte *nicht* Abrufen der Protokolle auf die einzelnen Abonnements für den Mandanten aber nur Flächen die Protokolle, die auf Mandantenebene generiert wurden.</span><span class="sxs-lookup"><span data-stu-id="0ccbd-115">Gets the Activity Logs for the Tenant.&lt;br&gt;Everything that is applicable to the API to get the Activity Logs for the subscription is applicable to this API (the parameters, $filter, etc.).&lt;br&gt;One thing to point out here is that this API does *not* retrieve the logs at the individual subscription of the tenant but only surfaces the logs that were generated at the tenant level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Monitor.ITenantActivityLogsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Monitor.Models.EventData&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Monitor.ITenantActivityLogsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.TenantActivityLogsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Monitor.ITenantActivityLogsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Monitor.ITenantActivityLogsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;&gt;" Usage="Microsoft.Azure.Management.Monitor.TenantActivityLogsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.TenantActivityLogsOperationsExtensions/&lt;ListNextAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.ITenantActivityLogsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ccbd-116">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0ccbd-116">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="0ccbd-117">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0ccbd-117">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ccbd-118">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0ccbd-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ccbd-119">Ruft die Aktivitätsprotokolle für den Mandanten ab. &lt;Br&gt;alle Komponenten, die gilt für die API die Aktivitätsprotokolle abgerufen, für das Abonnement für diese API (der Parameter, $filter, usw.). &lt;Br&gt;aufpassen sieht, dass diese API ist Punkte *nicht* Abrufen der Protokolle auf die einzelnen Abonnements für den Mandanten aber nur Flächen die Protokolle, die auf Mandantenebene generiert wurden.</span><span class="sxs-lookup"><span data-stu-id="0ccbd-119">Gets the Activity Logs for the Tenant.&lt;br&gt;Everything that is applicable to the API to get the Activity Logs for the subscription is applicable to this API (the parameters, $filter, etc.).&lt;br&gt;One thing to point out here is that this API does *not* retrieve the logs at the individual subscription of the tenant but only surfaces the logs that were generated at the tenant level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>