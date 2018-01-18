<Type Name="ActivityLogsOperationsExtensions" FullName="Microsoft.Azure.Management.Monitor.ActivityLogsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ActivityLogsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ActivityLogsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.ActivityLogsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ActivityLogsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ActivityLogsOperationsExtensions = class" />
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
            <span data-ttu-id="ca0f4-101">Erweiterungsmethoden für ActivityLogsOperations.</span><span class="sxs-lookup"><span data-stu-id="ca0f4-101">Extension methods for ActivityLogsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt; List (this Microsoft.Azure.Management.Monitor.IActivityLogsOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt; odataQuery = null, string select = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Monitor.Models.EventData&gt; List(class Microsoft.Azure.Management.Monitor.IActivityLogsOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Monitor.Models.EventData&gt; odataQuery, string select) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.ActivityLogsOperationsExtensions.List(Microsoft.Azure.Management.Monitor.IActivityLogsOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Monitor.Models.EventData},System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IActivityLogsOperations, Optional odataQuery As ODataQuery(Of EventData) = null, Optional select As String = null) As IPage(Of EventData)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Monitor.IActivityLogsOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt; * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;" Usage="Microsoft.Azure.Management.Monitor.ActivityLogsOperationsExtensions.List (operations, odataQuery, select)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.IActivityLogsOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;" />
        <Parameter Name="select" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ca0f4-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ca0f4-102">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="ca0f4-103">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="ca0f4-103">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="ca0f4-104">Wird verwendet, um Ereignisse mit dem nur die angegebenen Eigenschaften abzurufen. &lt;Br&gt;der **$select** Argument ist eine durch Trennzeichen getrennte Liste von Eigenschaftennamen, die zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="ca0f4-104">Used to fetch events with only the given properties.&lt;br&gt;The **$select** argument is a comma separated list of property names to be returned.</span></span> <span data-ttu-id="ca0f4-105">Mögliche Werte sind: *Autorisierung*, *Ansprüche*, *CorrelationId*, *Beschreibung*, *EventDataId*, *EventName*, *EventTimestamp*, *HttpRequest*, *Ebene*, *OperationId*, *OperationName*, *Eigenschaften*, *ResourceGroupName*, *ResourceProviderName*, *ResourceId*, *Status*, *SubmissionTimestamp*, *Unterstatus*, *"subscriptionId"*</span><span class="sxs-lookup"><span data-stu-id="ca0f4-105">Possible values are: *authorization*, *claims*, *correlationId*, *description*, *eventDataId*, *eventName*, *eventTimestamp*, *httpRequest*, *level*, *operationId*, *operationName*, *properties*, *resourceGroupName*, *resourceProviderName*, *resourceId*, *status*, *submissionTimestamp*, *subStatus*, *subscriptionId*</span></span>
            </param>
        <summary>
            <span data-ttu-id="ca0f4-106">Gibt eine Liste der Datensätze aus den Aktivitätsprotokollen.</span><span class="sxs-lookup"><span data-stu-id="ca0f4-106">Provides the list of records from the activity logs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;&gt; ListAsync (this Microsoft.Azure.Management.Monitor.IActivityLogsOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt; odataQuery = null, string select = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Monitor.Models.EventData&gt;&gt; ListAsync(class Microsoft.Azure.Management.Monitor.IActivityLogsOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Monitor.Models.EventData&gt; odataQuery, string select, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.ActivityLogsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Monitor.IActivityLogsOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Monitor.Models.EventData},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Monitor.IActivityLogsOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;&gt;" Usage="Microsoft.Azure.Management.Monitor.ActivityLogsOperationsExtensions.ListAsync (operations, odataQuery, select, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.ActivityLogsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.IActivityLogsOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ca0f4-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ca0f4-107">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="ca0f4-108">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="ca0f4-108">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="ca0f4-109">Wird verwendet, um Ereignisse mit dem nur die angegebenen Eigenschaften abzurufen. &lt;Br&gt;der **$select** Argument ist eine durch Trennzeichen getrennte Liste von Eigenschaftennamen, die zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="ca0f4-109">Used to fetch events with only the given properties.&lt;br&gt;The **$select** argument is a comma separated list of property names to be returned.</span></span> <span data-ttu-id="ca0f4-110">Mögliche Werte sind: *Autorisierung*, *Ansprüche*, *CorrelationId*, *Beschreibung*, *EventDataId*, *EventName*, *EventTimestamp*, *HttpRequest*, *Ebene*, *OperationId*, *OperationName*, *Eigenschaften*, *ResourceGroupName*, *ResourceProviderName*, *ResourceId*, *Status*, *SubmissionTimestamp*, *Unterstatus*, *"subscriptionId"*</span><span class="sxs-lookup"><span data-stu-id="ca0f4-110">Possible values are: *authorization*, *claims*, *correlationId*, *description*, *eventDataId*, *eventName*, *eventTimestamp*, *httpRequest*, *level*, *operationId*, *operationName*, *properties*, *resourceGroupName*, *resourceProviderName*, *resourceId*, *status*, *submissionTimestamp*, *subStatus*, *subscriptionId*</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ca0f4-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ca0f4-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ca0f4-112">Gibt eine Liste der Datensätze aus den Aktivitätsprotokollen.</span><span class="sxs-lookup"><span data-stu-id="ca0f4-112">Provides the list of records from the activity logs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt; ListNext (this Microsoft.Azure.Management.Monitor.IActivityLogsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Monitor.Models.EventData&gt; ListNext(class Microsoft.Azure.Management.Monitor.IActivityLogsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.ActivityLogsOperationsExtensions.ListNext(Microsoft.Azure.Management.Monitor.IActivityLogsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IActivityLogsOperations, nextPageLink As String) As IPage(Of EventData)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Monitor.IActivityLogsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;" Usage="Microsoft.Azure.Management.Monitor.ActivityLogsOperationsExtensions.ListNext (operations, nextPageLink)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.IActivityLogsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ca0f4-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ca0f4-113">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="ca0f4-114">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="ca0f4-114">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ca0f4-115">Gibt eine Liste der Datensätze aus den Aktivitätsprotokollen.</span><span class="sxs-lookup"><span data-stu-id="ca0f4-115">Provides the list of records from the activity logs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Monitor.IActivityLogsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Monitor.Models.EventData&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Monitor.IActivityLogsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.ActivityLogsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Monitor.IActivityLogsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Monitor.IActivityLogsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;&gt;" Usage="Microsoft.Azure.Management.Monitor.ActivityLogsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.ActivityLogsOperationsExtensions/&lt;ListNextAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.IActivityLogsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ca0f4-116">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ca0f4-116">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="ca0f4-117">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="ca0f4-117">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ca0f4-118">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ca0f4-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ca0f4-119">Gibt eine Liste der Datensätze aus den Aktivitätsprotokollen.</span><span class="sxs-lookup"><span data-stu-id="ca0f4-119">Provides the list of records from the activity logs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>