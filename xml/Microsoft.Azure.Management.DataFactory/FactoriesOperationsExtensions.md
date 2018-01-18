<Type Name="FactoriesOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class FactoriesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit FactoriesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module FactoriesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type FactoriesOperationsExtensions = class" />
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
            <span data-ttu-id="1cfda-101">Erweiterungsmethoden für FactoriesOperations.</span><span class="sxs-lookup"><span data-stu-id="1cfda-101">Extension methods for FactoriesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CancelPipelineRun">
      <MemberSignature Language="C#" Value="public static void CancelPipelineRun (this Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string resourceGroupName, string factoryName, string runId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void CancelPipelineRun(class Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string resourceGroupName, string factoryName, string runId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.CancelPipelineRun(Microsoft.Azure.Management.DataFactory.IFactoriesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub CancelPipelineRun (operations As IFactoriesOperations, resourceGroupName As String, factoryName As String, runId As String)" />
      <MemberSignature Language="F#" Value="static member CancelPipelineRun : Microsoft.Azure.Management.DataFactory.IFactoriesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.CancelPipelineRun (operations, resourceGroupName, factoryName, runId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IFactoriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="runId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1cfda-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1cfda-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1cfda-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1cfda-103">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="1cfda-104">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="1cfda-104">The factory name.</span></span>
            </param>
        <param name="runId">
            <span data-ttu-id="1cfda-105">Die Pipeline Bezeichner ausführen.</span><span class="sxs-lookup"><span data-stu-id="1cfda-105">The pipeline run identifier.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1cfda-106">Abbrechen einer Pipeline ausführen, indem die Testlauf-ID.</span><span class="sxs-lookup"><span data-stu-id="1cfda-106">Cancel a pipeline run by its run ID.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelPipelineRunAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CancelPipelineRunAsync (this Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string resourceGroupName, string factoryName, string runId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CancelPipelineRunAsync(class Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string resourceGroupName, string factoryName, string runId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.CancelPipelineRunAsync(Microsoft.Azure.Management.DataFactory.IFactoriesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CancelPipelineRunAsync : Microsoft.Azure.Management.DataFactory.IFactoriesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.CancelPipelineRunAsync (operations, resourceGroupName, factoryName, runId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions/&lt;CancelPipelineRunAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IFactoriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="runId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1cfda-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1cfda-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1cfda-108">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1cfda-108">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="1cfda-109">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="1cfda-109">The factory name.</span></span>
            </param>
        <param name="runId">
            <span data-ttu-id="1cfda-110">Die Pipeline Bezeichner ausführen.</span><span class="sxs-lookup"><span data-stu-id="1cfda-110">The pipeline run identifier.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1cfda-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1cfda-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1cfda-112">Abbrechen einer Pipeline ausführen, indem die Testlauf-ID.</span><span class="sxs-lookup"><span data-stu-id="1cfda-112">Cancel a pipeline run by its run ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.Factory CreateOrUpdate (this Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string resourceGroupName, string factoryName, Microsoft.Azure.Management.DataFactory.Models.Factory factory);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.Factory CreateOrUpdate(class Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string resourceGroupName, string factoryName, class Microsoft.Azure.Management.DataFactory.Models.Factory factory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataFactory.IFactoriesOperations,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.Factory)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataFactory.IFactoriesOperations * string * string * Microsoft.Azure.Management.DataFactory.Models.Factory -&gt; Microsoft.Azure.Management.DataFactory.Models.Factory" Usage="Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, factoryName, factory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.Factory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IFactoriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="factory" Type="Microsoft.Azure.Management.DataFactory.Models.Factory" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1cfda-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1cfda-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1cfda-114">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1cfda-114">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="1cfda-115">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="1cfda-115">The factory name.</span></span>
            </param>
        <param name="factory">
            <span data-ttu-id="1cfda-116">Factory-Ressourcendefinition.</span><span class="sxs-lookup"><span data-stu-id="1cfda-116">Factory resource definition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1cfda-117">Erstellt oder aktualisiert eine Factory.</span><span class="sxs-lookup"><span data-stu-id="1cfda-117">Creates or updates a factory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string resourceGroupName, string factoryName, Microsoft.Azure.Management.DataFactory.Models.Factory factory, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.Factory&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string resourceGroupName, string factoryName, class Microsoft.Azure.Management.DataFactory.Models.Factory factory, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataFactory.IFactoriesOperations,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.Factory,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataFactory.IFactoriesOperations * string * string * Microsoft.Azure.Management.DataFactory.Models.Factory * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt;" Usage="Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, factoryName, factory, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IFactoriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="factory" Type="Microsoft.Azure.Management.DataFactory.Models.Factory" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1cfda-118">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1cfda-118">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1cfda-119">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1cfda-119">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="1cfda-120">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="1cfda-120">The factory name.</span></span>
            </param>
        <param name="factory">
            <span data-ttu-id="1cfda-121">Factory-Ressourcendefinition.</span><span class="sxs-lookup"><span data-stu-id="1cfda-121">Factory resource definition.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1cfda-122">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1cfda-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1cfda-123">Erstellt oder aktualisiert eine Factory.</span><span class="sxs-lookup"><span data-stu-id="1cfda-123">Creates or updates a factory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string resourceGroupName, string factoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string resourceGroupName, string factoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.Delete(Microsoft.Azure.Management.DataFactory.IFactoriesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IFactoriesOperations, resourceGroupName As String, factoryName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataFactory.IFactoriesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.Delete (operations, resourceGroupName, factoryName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IFactoriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1cfda-124">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1cfda-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1cfda-125">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1cfda-125">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="1cfda-126">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="1cfda-126">The factory name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1cfda-127">Löscht eine Factory.</span><span class="sxs-lookup"><span data-stu-id="1cfda-127">Deletes a factory.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string resourceGroupName, string factoryName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string resourceGroupName, string factoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataFactory.IFactoriesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataFactory.IFactoriesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.DeleteAsync (operations, resourceGroupName, factoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions/&lt;DeleteAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IFactoriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1cfda-128">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1cfda-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1cfda-129">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1cfda-129">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="1cfda-130">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="1cfda-130">The factory name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1cfda-131">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1cfda-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1cfda-132">Löscht eine Factory.</span><span class="sxs-lookup"><span data-stu-id="1cfda-132">Deletes a factory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.Factory Get (this Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string resourceGroupName, string factoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.Factory Get(class Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string resourceGroupName, string factoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.Get(Microsoft.Azure.Management.DataFactory.IFactoriesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IFactoriesOperations, resourceGroupName As String, factoryName As String) As Factory" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactory.IFactoriesOperations * string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.Factory" Usage="Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.Get (operations, resourceGroupName, factoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.Factory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IFactoriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1cfda-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1cfda-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1cfda-134">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1cfda-134">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="1cfda-135">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="1cfda-135">The factory name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1cfda-136">Ruft eine Factory ab.</span><span class="sxs-lookup"><span data-stu-id="1cfda-136">Gets a factory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt; GetAsync (this Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string resourceGroupName, string factoryName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.Factory&gt; GetAsync(class Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string resourceGroupName, string factoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactory.IFactoriesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactory.IFactoriesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt;" Usage="Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.GetAsync (operations, resourceGroupName, factoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions/&lt;GetAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IFactoriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1cfda-137">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1cfda-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1cfda-138">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1cfda-138">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="1cfda-139">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="1cfda-139">The factory name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1cfda-140">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1cfda-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1cfda-141">Ruft eine Factory ab.</span><span class="sxs-lookup"><span data-stu-id="1cfda-141">Gets a factory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt; List (this Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.Factory&gt; List(class Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.List(Microsoft.Azure.Management.DataFactory.IFactoriesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IFactoriesOperations) As IPage(Of Factory)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataFactory.IFactoriesOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt;" Usage="Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IFactoriesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1cfda-142">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1cfda-142">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1cfda-143">Listet die Factorys unter dem angegebenen Abonnement.</span><span class="sxs-lookup"><span data-stu-id="1cfda-143">Lists factories under the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt;&gt; ListAsync (this Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.Factory&gt;&gt; ListAsync(class Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataFactory.IFactoriesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataFactory.IFactoriesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IFactoriesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1cfda-144">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1cfda-144">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1cfda-145">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1cfda-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1cfda-146">Listet die Factorys unter dem angegebenen Abonnement.</span><span class="sxs-lookup"><span data-stu-id="1cfda-146">Lists factories under the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt; ListByResourceGroup (this Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.Factory&gt; ListByResourceGroup(class Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.DataFactory.IFactoriesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IFactoriesOperations, resourceGroupName As String) As IPage(Of Factory)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.DataFactory.IFactoriesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt;" Usage="Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IFactoriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1cfda-147">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1cfda-147">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1cfda-148">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1cfda-148">The resource group name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1cfda-149">Listenerfactorys.</span><span class="sxs-lookup"><span data-stu-id="1cfda-149">Lists factories.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.Factory&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.DataFactory.IFactoriesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.DataFactory.IFactoriesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IFactoriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1cfda-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1cfda-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1cfda-151">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1cfda-151">The resource group name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1cfda-152">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1cfda-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1cfda-153">Listenerfactorys.</span><span class="sxs-lookup"><span data-stu-id="1cfda-153">Lists factories.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.Factory&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.DataFactory.IFactoriesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IFactoriesOperations, nextPageLink As String) As IPage(Of Factory)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.DataFactory.IFactoriesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt;" Usage="Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IFactoriesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1cfda-154">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1cfda-154">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1cfda-155">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1cfda-155">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1cfda-156">Listenerfactorys.</span><span class="sxs-lookup"><span data-stu-id="1cfda-156">Lists factories.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.Factory&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.DataFactory.IFactoriesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.DataFactory.IFactoriesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IFactoriesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1cfda-157">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1cfda-157">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1cfda-158">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1cfda-158">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1cfda-159">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1cfda-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1cfda-160">Listenerfactorys.</span><span class="sxs-lookup"><span data-stu-id="1cfda-160">Lists factories.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt; ListNext (this Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.Factory&gt; ListNext(class Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.ListNext(Microsoft.Azure.Management.DataFactory.IFactoriesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IFactoriesOperations, nextPageLink As String) As IPage(Of Factory)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataFactory.IFactoriesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt;" Usage="Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IFactoriesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1cfda-161">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1cfda-161">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1cfda-162">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1cfda-162">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1cfda-163">Listet die Factorys unter dem angegebenen Abonnement.</span><span class="sxs-lookup"><span data-stu-id="1cfda-163">Lists factories under the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.Factory&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataFactory.IFactoriesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataFactory.IFactoriesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions/&lt;ListNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IFactoriesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1cfda-164">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1cfda-164">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1cfda-165">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1cfda-165">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1cfda-166">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1cfda-166">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1cfda-167">Listet die Factorys unter dem angegebenen Abonnement.</span><span class="sxs-lookup"><span data-stu-id="1cfda-167">Lists factories under the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.Factory Update (this Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string resourceGroupName, string factoryName, Microsoft.Azure.Management.DataFactory.Models.FactoryUpdateParameters factoryUpdateParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.Factory Update(class Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string resourceGroupName, string factoryName, class Microsoft.Azure.Management.DataFactory.Models.FactoryUpdateParameters factoryUpdateParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.Update(Microsoft.Azure.Management.DataFactory.IFactoriesOperations,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.FactoryUpdateParameters)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.DataFactory.IFactoriesOperations * string * string * Microsoft.Azure.Management.DataFactory.Models.FactoryUpdateParameters -&gt; Microsoft.Azure.Management.DataFactory.Models.Factory" Usage="Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.Update (operations, resourceGroupName, factoryName, factoryUpdateParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.Factory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IFactoriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="factoryUpdateParameters" Type="Microsoft.Azure.Management.DataFactory.Models.FactoryUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1cfda-168">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1cfda-168">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1cfda-169">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1cfda-169">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="1cfda-170">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="1cfda-170">The factory name.</span></span>
            </param>
        <param name="factoryUpdateParameters">
            <span data-ttu-id="1cfda-171">Die Parameter für das Aktualisieren einer Factory.</span><span class="sxs-lookup"><span data-stu-id="1cfda-171">The parameters for updating a factory.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1cfda-172">Aktualisiert eine Factory.</span><span class="sxs-lookup"><span data-stu-id="1cfda-172">Updates a factory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt; UpdateAsync (this Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string resourceGroupName, string factoryName, Microsoft.Azure.Management.DataFactory.Models.FactoryUpdateParameters factoryUpdateParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.Factory&gt; UpdateAsync(class Microsoft.Azure.Management.DataFactory.IFactoriesOperations operations, string resourceGroupName, string factoryName, class Microsoft.Azure.Management.DataFactory.Models.FactoryUpdateParameters factoryUpdateParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.DataFactory.IFactoriesOperations,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.FactoryUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.DataFactory.IFactoriesOperations * string * string * Microsoft.Azure.Management.DataFactory.Models.FactoryUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt;" Usage="Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions.UpdateAsync (operations, resourceGroupName, factoryName, factoryUpdateParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.FactoriesOperationsExtensions/&lt;UpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.Factory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IFactoriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="factoryUpdateParameters" Type="Microsoft.Azure.Management.DataFactory.Models.FactoryUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1cfda-173">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1cfda-173">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1cfda-174">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1cfda-174">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="1cfda-175">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="1cfda-175">The factory name.</span></span>
            </param>
        <param name="factoryUpdateParameters">
            <span data-ttu-id="1cfda-176">Die Parameter für das Aktualisieren einer Factory.</span><span class="sxs-lookup"><span data-stu-id="1cfda-176">The parameters for updating a factory.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1cfda-177">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1cfda-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1cfda-178">Aktualisiert eine Factory.</span><span class="sxs-lookup"><span data-stu-id="1cfda-178">Updates a factory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>