<Type Name="ActivityRunsOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactory.ActivityRunsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ActivityRunsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ActivityRunsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.ActivityRunsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ActivityRunsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ActivityRunsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2a3d5-101">Erweiterungsmethoden für ActivityRunsOperations.</span><span class="sxs-lookup"><span data-stu-id="2a3d5-101">Extension methods for ActivityRunsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListByPipelineRun">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt; ListByPipelineRun (this Microsoft.Azure.Management.DataFactory.IActivityRunsOperations operations, string resourceGroupName, string factoryName, string runId, DateTime startTime, DateTime endTime, string status = null, string activityName = null, string linkedServiceName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt; ListByPipelineRun(class Microsoft.Azure.Management.DataFactory.IActivityRunsOperations operations, string resourceGroupName, string factoryName, string runId, valuetype System.DateTime startTime, valuetype System.DateTime endTime, string status, string activityName, string linkedServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.ActivityRunsOperationsExtensions.ListByPipelineRun(Microsoft.Azure.Management.DataFactory.IActivityRunsOperations,System.String,System.String,System.String,System.DateTime,System.DateTime,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByPipelineRun (operations As IActivityRunsOperations, resourceGroupName As String, factoryName As String, runId As String, startTime As DateTime, endTime As DateTime, Optional status As String = null, Optional activityName As String = null, Optional linkedServiceName As String = null) As IPage(Of ActivityRun)" />
      <MemberSignature Language="F#" Value="static member ListByPipelineRun : Microsoft.Azure.Management.DataFactory.IActivityRunsOperations * string * string * string * DateTime * DateTime * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;" Usage="Microsoft.Azure.Management.DataFactory.ActivityRunsOperationsExtensions.ListByPipelineRun (operations, resourceGroupName, factoryName, runId, startTime, endTime, status, activityName, linkedServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IActivityRunsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="runId" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="endTime" Type="System.DateTime" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="activityName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2a3d5-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2a3d5-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2a3d5-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2a3d5-103">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="2a3d5-104">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="2a3d5-104">The factory name.</span></span>
            </param>
        <param name="runId">
            <span data-ttu-id="2a3d5-105">Die Pipeline Bezeichner ausführen.</span><span class="sxs-lookup"><span data-stu-id="2a3d5-105">The pipeline run identifier.</span></span>
            </param>
        <param name="startTime">
            <span data-ttu-id="2a3d5-106">Die Startzeit der Aktivität wird im ISO8601-Format ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="2a3d5-106">The start time of activity runs in ISO8601 format.</span></span>
            </param>
        <param name="endTime">
            <span data-ttu-id="2a3d5-107">Die Endzeit der Aktivität wird im ISO8601-Format ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="2a3d5-107">The end time of activity runs in ISO8601 format.</span></span>
            </param>
        <param name="status">
            <span data-ttu-id="2a3d5-108">Führen Sie der Status der Pipeline.</span><span class="sxs-lookup"><span data-stu-id="2a3d5-108">The status of the pipeline run.</span></span>
            </param>
        <param name="activityName">
            <span data-ttu-id="2a3d5-109">Der Name der Aktivität.</span><span class="sxs-lookup"><span data-stu-id="2a3d5-109">The name of the activity.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="2a3d5-110">Der Name des verknüpften Diensts.</span><span class="sxs-lookup"><span data-stu-id="2a3d5-110">The linked service name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2a3d5-111">Liste Aktivität wird basierend auf Eingabefilter Bedingungen ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="2a3d5-111">List activity runs based on input filter conditions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByPipelineRunAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;&gt; ListByPipelineRunAsync (this Microsoft.Azure.Management.DataFactory.IActivityRunsOperations operations, string resourceGroupName, string factoryName, string runId, DateTime startTime, DateTime endTime, string status = null, string activityName = null, string linkedServiceName = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;&gt; ListByPipelineRunAsync(class Microsoft.Azure.Management.DataFactory.IActivityRunsOperations operations, string resourceGroupName, string factoryName, string runId, valuetype System.DateTime startTime, valuetype System.DateTime endTime, string status, string activityName, string linkedServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.ActivityRunsOperationsExtensions.ListByPipelineRunAsync(Microsoft.Azure.Management.DataFactory.IActivityRunsOperations,System.String,System.String,System.String,System.DateTime,System.DateTime,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByPipelineRunAsync : Microsoft.Azure.Management.DataFactory.IActivityRunsOperations * string * string * string * DateTime * DateTime * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.ActivityRunsOperationsExtensions.ListByPipelineRunAsync (operations, resourceGroupName, factoryName, runId, startTime, endTime, status, activityName, linkedServiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.ActivityRunsOperationsExtensions/&lt;ListByPipelineRunAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IActivityRunsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="runId" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="endTime" Type="System.DateTime" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="activityName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2a3d5-112">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2a3d5-112">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2a3d5-113">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2a3d5-113">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="2a3d5-114">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="2a3d5-114">The factory name.</span></span>
            </param>
        <param name="runId">
            <span data-ttu-id="2a3d5-115">Die Pipeline Bezeichner ausführen.</span><span class="sxs-lookup"><span data-stu-id="2a3d5-115">The pipeline run identifier.</span></span>
            </param>
        <param name="startTime">
            <span data-ttu-id="2a3d5-116">Die Startzeit der Aktivität wird im ISO8601-Format ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="2a3d5-116">The start time of activity runs in ISO8601 format.</span></span>
            </param>
        <param name="endTime">
            <span data-ttu-id="2a3d5-117">Die Endzeit der Aktivität wird im ISO8601-Format ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="2a3d5-117">The end time of activity runs in ISO8601 format.</span></span>
            </param>
        <param name="status">
            <span data-ttu-id="2a3d5-118">Führen Sie der Status der Pipeline.</span><span class="sxs-lookup"><span data-stu-id="2a3d5-118">The status of the pipeline run.</span></span>
            </param>
        <param name="activityName">
            <span data-ttu-id="2a3d5-119">Der Name der Aktivität.</span><span class="sxs-lookup"><span data-stu-id="2a3d5-119">The name of the activity.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="2a3d5-120">Der Name des verknüpften Diensts.</span><span class="sxs-lookup"><span data-stu-id="2a3d5-120">The linked service name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2a3d5-121">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2a3d5-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2a3d5-122">Liste Aktivität wird basierend auf Eingabefilter Bedingungen ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="2a3d5-122">List activity runs based on input filter conditions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByPipelineRunNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt; ListByPipelineRunNext (this Microsoft.Azure.Management.DataFactory.IActivityRunsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt; ListByPipelineRunNext(class Microsoft.Azure.Management.DataFactory.IActivityRunsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.ActivityRunsOperationsExtensions.ListByPipelineRunNext(Microsoft.Azure.Management.DataFactory.IActivityRunsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByPipelineRunNext (operations As IActivityRunsOperations, nextPageLink As String) As IPage(Of ActivityRun)" />
      <MemberSignature Language="F#" Value="static member ListByPipelineRunNext : Microsoft.Azure.Management.DataFactory.IActivityRunsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;" Usage="Microsoft.Azure.Management.DataFactory.ActivityRunsOperationsExtensions.ListByPipelineRunNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IActivityRunsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2a3d5-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2a3d5-123">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="2a3d5-124">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="2a3d5-124">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2a3d5-125">Liste Aktivität wird basierend auf Eingabefilter Bedingungen ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="2a3d5-125">List activity runs based on input filter conditions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByPipelineRunNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;&gt; ListByPipelineRunNextAsync (this Microsoft.Azure.Management.DataFactory.IActivityRunsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;&gt; ListByPipelineRunNextAsync(class Microsoft.Azure.Management.DataFactory.IActivityRunsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.ActivityRunsOperationsExtensions.ListByPipelineRunNextAsync(Microsoft.Azure.Management.DataFactory.IActivityRunsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByPipelineRunNextAsync : Microsoft.Azure.Management.DataFactory.IActivityRunsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.ActivityRunsOperationsExtensions.ListByPipelineRunNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.ActivityRunsOperationsExtensions/&lt;ListByPipelineRunNextAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IActivityRunsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2a3d5-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2a3d5-126">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="2a3d5-127">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="2a3d5-127">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2a3d5-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2a3d5-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2a3d5-129">Liste Aktivität wird basierend auf Eingabefilter Bedingungen ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="2a3d5-129">List activity runs based on input filter conditions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>