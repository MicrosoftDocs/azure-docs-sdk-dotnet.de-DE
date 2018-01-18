<Type Name="PipelinesOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class PipelinesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PipelinesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PipelinesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type PipelinesOperationsExtensions = class" />
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
            <span data-ttu-id="608d6-101">Erweiterungsmethoden für PipelinesOperations.</span><span class="sxs-lookup"><span data-stu-id="608d6-101">Extension methods for PipelinesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.PipelineResource CreateOrUpdate (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, Microsoft.Azure.Management.DataFactory.Models.PipelineResource pipeline, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.PipelineResource CreateOrUpdate(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, class Microsoft.Azure.Management.DataFactory.Models.PipelineResource pipeline, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.PipelineResource,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IPipelinesOperations, resourceGroupName As String, factoryName As String, pipelineName As String, pipeline As PipelineResource, Optional ifMatch As String = null) As PipelineResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.PipelineResource * string -&gt; Microsoft.Azure.Management.DataFactory.Models.PipelineResource" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, factoryName, pipelineName, pipeline, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.PipelineResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="pipelineName" Type="System.String" />
        <Parameter Name="pipeline" Type="Microsoft.Azure.Management.DataFactory.Models.PipelineResource" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="608d6-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="608d6-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="608d6-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="608d6-103">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="608d6-104">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="608d6-104">The factory name.</span></span>
            </param>
        <param name="pipelineName">
            <span data-ttu-id="608d6-105">Der pipelinename.</span><span class="sxs-lookup"><span data-stu-id="608d6-105">The pipeline name.</span></span>
            </param>
        <param name="pipeline">
            <span data-ttu-id="608d6-106">Pipeline in der Ressourcendefinition.</span><span class="sxs-lookup"><span data-stu-id="608d6-106">Pipeline resource definition.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="608d6-107">ETag der Entität Pipeline.</span><span class="sxs-lookup"><span data-stu-id="608d6-107">ETag of the pipeline entity.</span></span>  <span data-ttu-id="608d6-108">Sollte nur angegeben werden, für das Update, für die vorhandene Entität übereinstimmen oder können werden \* für unbedingtes Update.</span><span class="sxs-lookup"><span data-stu-id="608d6-108">Should only be specified for update, for which it should match existing entity or can be \* for unconditional update.</span></span>
            </param>
        <summary>
            <span data-ttu-id="608d6-109">Erstellt oder aktualisiert eine Pipeline.</span><span class="sxs-lookup"><span data-stu-id="608d6-109">Creates or updates a pipeline.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, Microsoft.Azure.Management.DataFactory.Models.PipelineResource pipeline, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, class Microsoft.Azure.Management.DataFactory.Models.PipelineResource pipeline, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.PipelineResource,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.PipelineResource * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, factoryName, pipelineName, pipeline, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="pipelineName" Type="System.String" />
        <Parameter Name="pipeline" Type="Microsoft.Azure.Management.DataFactory.Models.PipelineResource" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="608d6-110">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="608d6-110">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="608d6-111">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="608d6-111">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="608d6-112">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="608d6-112">The factory name.</span></span>
            </param>
        <param name="pipelineName">
            <span data-ttu-id="608d6-113">Der pipelinename.</span><span class="sxs-lookup"><span data-stu-id="608d6-113">The pipeline name.</span></span>
            </param>
        <param name="pipeline">
            <span data-ttu-id="608d6-114">Pipeline in der Ressourcendefinition.</span><span class="sxs-lookup"><span data-stu-id="608d6-114">Pipeline resource definition.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="608d6-115">ETag der Entität Pipeline.</span><span class="sxs-lookup"><span data-stu-id="608d6-115">ETag of the pipeline entity.</span></span>  <span data-ttu-id="608d6-116">Sollte nur angegeben werden, für das Update, für die vorhandene Entität übereinstimmen oder können werden \* für unbedingtes Update.</span><span class="sxs-lookup"><span data-stu-id="608d6-116">Should only be specified for update, for which it should match existing entity or can be \* for unconditional update.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="608d6-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="608d6-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="608d6-118">Erstellt oder aktualisiert eine Pipeline.</span><span class="sxs-lookup"><span data-stu-id="608d6-118">Creates or updates a pipeline.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRun">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse CreateRun (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, System.Collections.Generic.IDictionary&lt;string,object&gt; parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse CreateRun(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.CreateRun(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateRun (operations As IPipelinesOperations, resourceGroupName As String, factoryName As String, pipelineName As String, Optional parameters As IDictionary(Of String, Object) = null) As CreateRunResponse" />
      <MemberSignature Language="F#" Value="static member CreateRun : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string * string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.CreateRun (operations, resourceGroupName, factoryName, pipelineName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="pipelineName" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="608d6-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="608d6-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="608d6-120">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="608d6-120">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="608d6-121">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="608d6-121">The factory name.</span></span>
            </param>
        <param name="pipelineName">
            <span data-ttu-id="608d6-122">Der pipelinename.</span><span class="sxs-lookup"><span data-stu-id="608d6-122">The pipeline name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="608d6-123">Führen Sie die Parameter der Pipeline.</span><span class="sxs-lookup"><span data-stu-id="608d6-123">Parameters of the pipeline run.</span></span>
            </param>
        <summary>
            <span data-ttu-id="608d6-124">Erstellt eine Ausführung einer Pipeline.</span><span class="sxs-lookup"><span data-stu-id="608d6-124">Creates a run of a pipeline.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRunAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse&gt; CreateRunAsync (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, System.Collections.Generic.IDictionary&lt;string,object&gt; parameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse&gt; CreateRunAsync(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.CreateRunAsync(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.Object},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateRunAsync : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string * string * System.Collections.Generic.IDictionary&lt;string, obj&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse&gt;" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.CreateRunAsync (operations, resourceGroupName, factoryName, pipelineName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions/&lt;CreateRunAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="pipelineName" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="608d6-125">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="608d6-125">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="608d6-126">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="608d6-126">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="608d6-127">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="608d6-127">The factory name.</span></span>
            </param>
        <param name="pipelineName">
            <span data-ttu-id="608d6-128">Der pipelinename.</span><span class="sxs-lookup"><span data-stu-id="608d6-128">The pipeline name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="608d6-129">Führen Sie die Parameter der Pipeline.</span><span class="sxs-lookup"><span data-stu-id="608d6-129">Parameters of the pipeline run.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="608d6-130">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="608d6-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="608d6-131">Erstellt eine Ausführung einer Pipeline.</span><span class="sxs-lookup"><span data-stu-id="608d6-131">Creates a run of a pipeline.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.Delete(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IPipelinesOperations, resourceGroupName As String, factoryName As String, pipelineName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.Delete (operations, resourceGroupName, factoryName, pipelineName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="pipelineName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="608d6-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="608d6-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="608d6-133">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="608d6-133">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="608d6-134">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="608d6-134">The factory name.</span></span>
            </param>
        <param name="pipelineName">
            <span data-ttu-id="608d6-135">Der pipelinename.</span><span class="sxs-lookup"><span data-stu-id="608d6-135">The pipeline name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="608d6-136">Löscht eine Pipeline.</span><span class="sxs-lookup"><span data-stu-id="608d6-136">Deletes a pipeline.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.DeleteAsync (operations, resourceGroupName, factoryName, pipelineName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="pipelineName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="608d6-137">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="608d6-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="608d6-138">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="608d6-138">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="608d6-139">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="608d6-139">The factory name.</span></span>
            </param>
        <param name="pipelineName">
            <span data-ttu-id="608d6-140">Der pipelinename.</span><span class="sxs-lookup"><span data-stu-id="608d6-140">The pipeline name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="608d6-141">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="608d6-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="608d6-142">Löscht eine Pipeline.</span><span class="sxs-lookup"><span data-stu-id="608d6-142">Deletes a pipeline.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.PipelineResource Get (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.PipelineResource Get(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.Get(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IPipelinesOperations, resourceGroupName As String, factoryName As String, pipelineName As String) As PipelineResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.PipelineResource" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.Get (operations, resourceGroupName, factoryName, pipelineName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.PipelineResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="pipelineName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="608d6-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="608d6-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="608d6-144">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="608d6-144">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="608d6-145">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="608d6-145">The factory name.</span></span>
            </param>
        <param name="pipelineName">
            <span data-ttu-id="608d6-146">Der pipelinename.</span><span class="sxs-lookup"><span data-stu-id="608d6-146">The pipeline name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="608d6-147">Ruft eine Pipeline ab.</span><span class="sxs-lookup"><span data-stu-id="608d6-147">Gets a pipeline.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt; GetAsync (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt; GetAsync(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.GetAsync (operations, resourceGroupName, factoryName, pipelineName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="pipelineName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="608d6-148">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="608d6-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="608d6-149">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="608d6-149">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="608d6-150">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="608d6-150">The factory name.</span></span>
            </param>
        <param name="pipelineName">
            <span data-ttu-id="608d6-151">Der pipelinename.</span><span class="sxs-lookup"><span data-stu-id="608d6-151">The pipeline name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="608d6-152">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="608d6-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="608d6-153">Ruft eine Pipeline ab.</span><span class="sxs-lookup"><span data-stu-id="608d6-153">Gets a pipeline.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactory">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt; ListByFactory (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt; ListByFactory(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.ListByFactory(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByFactory (operations As IPipelinesOperations, resourceGroupName As String, factoryName As String) As IPage(Of PipelineResource)" />
      <MemberSignature Language="F#" Value="static member ListByFactory : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.ListByFactory (operations, resourceGroupName, factoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="608d6-154">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="608d6-154">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="608d6-155">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="608d6-155">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="608d6-156">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="608d6-156">The factory name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="608d6-157">Listen-Pipelines.</span><span class="sxs-lookup"><span data-stu-id="608d6-157">Lists pipelines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt; ListByFactoryAsync (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt; ListByFactoryAsync(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.ListByFactoryAsync(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByFactoryAsync : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.ListByFactoryAsync (operations, resourceGroupName, factoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions/&lt;ListByFactoryAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="608d6-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="608d6-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="608d6-159">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="608d6-159">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="608d6-160">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="608d6-160">The factory name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="608d6-161">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="608d6-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="608d6-162">Listen-Pipelines.</span><span class="sxs-lookup"><span data-stu-id="608d6-162">Lists pipelines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt; ListByFactoryNext (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt; ListByFactoryNext(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.ListByFactoryNext(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByFactoryNext (operations As IPipelinesOperations, nextPageLink As String) As IPage(Of PipelineResource)" />
      <MemberSignature Language="F#" Value="static member ListByFactoryNext : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.ListByFactoryNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="608d6-163">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="608d6-163">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="608d6-164">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="608d6-164">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="608d6-165">Listen-Pipelines.</span><span class="sxs-lookup"><span data-stu-id="608d6-165">Lists pipelines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt; ListByFactoryNextAsync (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt; ListByFactoryNextAsync(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.ListByFactoryNextAsync(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByFactoryNextAsync : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.ListByFactoryNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions/&lt;ListByFactoryNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="608d6-166">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="608d6-166">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="608d6-167">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="608d6-167">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="608d6-168">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="608d6-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="608d6-169">Listen-Pipelines.</span><span class="sxs-lookup"><span data-stu-id="608d6-169">Lists pipelines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>