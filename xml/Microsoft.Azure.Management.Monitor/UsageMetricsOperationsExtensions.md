<Type Name="UsageMetricsOperationsExtensions" FullName="Microsoft.Azure.Management.Monitor.UsageMetricsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class UsageMetricsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit UsageMetricsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.UsageMetricsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module UsageMetricsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type UsageMetricsOperationsExtensions = class" />
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
            <span data-ttu-id="a79ac-101">Erweiterungsmethoden für UsageMetricsOperations.</span><span class="sxs-lookup"><span data-stu-id="a79ac-101">Extension methods for UsageMetricsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt; List (this Microsoft.Azure.Management.Monitor.IUsageMetricsOperations operations, string resourceUri, string apiVersion, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt; List(class Microsoft.Azure.Management.Monitor.IUsageMetricsOperations operations, string resourceUri, string apiVersion, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.UsageMetricsOperationsExtensions.List(Microsoft.Azure.Management.Monitor.IUsageMetricsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Monitor.Models.UsageMetric})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IUsageMetricsOperations, resourceUri As String, apiVersion As String, Optional odataQuery As ODataQuery(Of UsageMetric) = null) As IEnumerable(Of UsageMetric)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Monitor.IUsageMetricsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt; -&gt; seq&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt;" Usage="Microsoft.Azure.Management.Monitor.UsageMetricsOperationsExtensions.List (operations, resourceUri, apiVersion, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.IUsageMetricsOperations" RefType="this" />
        <Parameter Name="resourceUri" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a79ac-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a79ac-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceUri">
            <span data-ttu-id="a79ac-103">Der Bezeichner der Ressource.</span><span class="sxs-lookup"><span data-stu-id="a79ac-103">The identifier of the resource.</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="a79ac-104">Client-API-Version.</span><span class="sxs-lookup"><span data-stu-id="a79ac-104">Client Api Version.</span></span> <span data-ttu-id="a79ac-105">Hinweis: Dies ist eine Eigenschaft des Clients, muss er explizit im Aufruf, und es ist kein Standardwert.</span><span class="sxs-lookup"><span data-stu-id="a79ac-105">NOTE: This is not a client property, it must be explicit in the call and there is no default value.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="a79ac-106">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="a79ac-106">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a79ac-107">Der List-Vorgang Listet die Nutzungsdaten für die Ressource. &lt;Br&gt;**Warnung**: Dieser Vorgang wird nicht *veraltet* in der nächsten Version.</span><span class="sxs-lookup"><span data-stu-id="a79ac-107">The List operation lists the usage metrics for the resource.&lt;br&gt;**WARNING**: This operation will be *deprecated* in the next release.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt;&gt; ListAsync (this Microsoft.Azure.Management.Monitor.IUsageMetricsOperations operations, string resourceUri, string apiVersion, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt;&gt; ListAsync(class Microsoft.Azure.Management.Monitor.IUsageMetricsOperations operations, string resourceUri, string apiVersion, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.UsageMetricsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Monitor.IUsageMetricsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Monitor.Models.UsageMetric},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Monitor.IUsageMetricsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt;&gt;" Usage="Microsoft.Azure.Management.Monitor.UsageMetricsOperationsExtensions.ListAsync (operations, resourceUri, apiVersion, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.UsageMetricsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.IUsageMetricsOperations" RefType="this" />
        <Parameter Name="resourceUri" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a79ac-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a79ac-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceUri">
            <span data-ttu-id="a79ac-109">Der Bezeichner der Ressource.</span><span class="sxs-lookup"><span data-stu-id="a79ac-109">The identifier of the resource.</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="a79ac-110">Client-API-Version.</span><span class="sxs-lookup"><span data-stu-id="a79ac-110">Client Api Version.</span></span> <span data-ttu-id="a79ac-111">Hinweis: Dies ist eine Eigenschaft des Clients, muss er explizit im Aufruf, und es ist kein Standardwert.</span><span class="sxs-lookup"><span data-stu-id="a79ac-111">NOTE: This is not a client property, it must be explicit in the call and there is no default value.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="a79ac-112">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="a79ac-112">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a79ac-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a79ac-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a79ac-114">Der List-Vorgang Listet die Nutzungsdaten für die Ressource. &lt;Br&gt;**Warnung**: Dieser Vorgang wird nicht *veraltet* in der nächsten Version.</span><span class="sxs-lookup"><span data-stu-id="a79ac-114">The List operation lists the usage metrics for the resource.&lt;br&gt;**WARNING**: This operation will be *deprecated* in the next release.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>