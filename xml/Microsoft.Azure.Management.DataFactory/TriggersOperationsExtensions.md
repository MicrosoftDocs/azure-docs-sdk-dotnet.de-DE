<Type Name="TriggersOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class TriggersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TriggersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TriggersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type TriggersOperationsExtensions = class" />
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
            <span data-ttu-id="b40b7-101">Erweiterungsmethoden für TriggersOperations.</span><span class="sxs-lookup"><span data-stu-id="b40b7-101">Extension methods for TriggersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginStart">
      <MemberSignature Language="C#" Value="public static void BeginStart (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginStart(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.BeginStart(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginStart (operations As ITriggersOperations, resourceGroupName As String, factoryName As String, triggerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginStart : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.BeginStart (operations, resourceGroupName, factoryName, triggerName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b40b7-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b40b7-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b40b7-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b40b7-103">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="b40b7-104">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="b40b7-104">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="b40b7-105">Der Triggername.</span><span class="sxs-lookup"><span data-stu-id="b40b7-105">The trigger name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b40b7-106">Startet einen Trigger.</span><span class="sxs-lookup"><span data-stu-id="b40b7-106">Starts a trigger.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginStartAsync (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginStartAsync(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.BeginStartAsync(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStartAsync : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.BeginStartAsync (operations, resourceGroupName, factoryName, triggerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions/&lt;BeginStartAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b40b7-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b40b7-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b40b7-108">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b40b7-108">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="b40b7-109">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="b40b7-109">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="b40b7-110">Der Triggername.</span><span class="sxs-lookup"><span data-stu-id="b40b7-110">The trigger name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b40b7-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b40b7-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b40b7-112">Startet einen Trigger.</span><span class="sxs-lookup"><span data-stu-id="b40b7-112">Starts a trigger.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStop">
      <MemberSignature Language="C#" Value="public static void BeginStop (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginStop(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.BeginStop(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginStop (operations As ITriggersOperations, resourceGroupName As String, factoryName As String, triggerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginStop : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.BeginStop (operations, resourceGroupName, factoryName, triggerName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b40b7-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b40b7-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b40b7-114">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b40b7-114">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="b40b7-115">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="b40b7-115">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="b40b7-116">Der Triggername.</span><span class="sxs-lookup"><span data-stu-id="b40b7-116">The trigger name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b40b7-117">Beendet einen Trigger.</span><span class="sxs-lookup"><span data-stu-id="b40b7-117">Stops a trigger.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginStopAsync (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginStopAsync(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.BeginStopAsync(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStopAsync : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.BeginStopAsync (operations, resourceGroupName, factoryName, triggerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions/&lt;BeginStopAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b40b7-118">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b40b7-118">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b40b7-119">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b40b7-119">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="b40b7-120">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="b40b7-120">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="b40b7-121">Der Triggername.</span><span class="sxs-lookup"><span data-stu-id="b40b7-121">The trigger name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b40b7-122">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b40b7-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b40b7-123">Beendet einen Trigger.</span><span class="sxs-lookup"><span data-stu-id="b40b7-123">Stops a trigger.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.TriggerResource CreateOrUpdate (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, Microsoft.Azure.Management.DataFactory.Models.TriggerResource trigger, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.TriggerResource CreateOrUpdate(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, class Microsoft.Azure.Management.DataFactory.Models.TriggerResource trigger, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.TriggerResource,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ITriggersOperations, resourceGroupName As String, factoryName As String, triggerName As String, trigger As TriggerResource, Optional ifMatch As String = null) As TriggerResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.TriggerResource * string -&gt; Microsoft.Azure.Management.DataFactory.Models.TriggerResource" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, factoryName, triggerName, trigger, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.TriggerResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="trigger" Type="Microsoft.Azure.Management.DataFactory.Models.TriggerResource" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b40b7-124">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b40b7-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b40b7-125">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b40b7-125">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="b40b7-126">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="b40b7-126">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="b40b7-127">Der Triggername.</span><span class="sxs-lookup"><span data-stu-id="b40b7-127">The trigger name.</span></span>
            </param>
        <param name="trigger">
            <span data-ttu-id="b40b7-128">Auslösen der Ressourcendefinition.</span><span class="sxs-lookup"><span data-stu-id="b40b7-128">Trigger resource definition.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="b40b7-129">ETag der Entität Trigger.</span><span class="sxs-lookup"><span data-stu-id="b40b7-129">ETag of the trigger entity.</span></span>  <span data-ttu-id="b40b7-130">Sollte nur angegeben werden, für das Update, für die vorhandene Entität übereinstimmen oder können werden \* für unbedingtes Update.</span><span class="sxs-lookup"><span data-stu-id="b40b7-130">Should only be specified for update, for which it should match existing entity or can be \* for unconditional update.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b40b7-131">Erstellt oder aktualisiert einen Trigger.</span><span class="sxs-lookup"><span data-stu-id="b40b7-131">Creates or updates a trigger.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, Microsoft.Azure.Management.DataFactory.Models.TriggerResource trigger, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, class Microsoft.Azure.Management.DataFactory.Models.TriggerResource trigger, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.TriggerResource,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.TriggerResource * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, factoryName, triggerName, trigger, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="trigger" Type="Microsoft.Azure.Management.DataFactory.Models.TriggerResource" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b40b7-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b40b7-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b40b7-133">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b40b7-133">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="b40b7-134">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="b40b7-134">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="b40b7-135">Der Triggername.</span><span class="sxs-lookup"><span data-stu-id="b40b7-135">The trigger name.</span></span>
            </param>
        <param name="trigger">
            <span data-ttu-id="b40b7-136">Auslösen der Ressourcendefinition.</span><span class="sxs-lookup"><span data-stu-id="b40b7-136">Trigger resource definition.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="b40b7-137">ETag der Entität Trigger.</span><span class="sxs-lookup"><span data-stu-id="b40b7-137">ETag of the trigger entity.</span></span>  <span data-ttu-id="b40b7-138">Sollte nur angegeben werden, für das Update, für die vorhandene Entität übereinstimmen oder können werden \* für unbedingtes Update.</span><span class="sxs-lookup"><span data-stu-id="b40b7-138">Should only be specified for update, for which it should match existing entity or can be \* for unconditional update.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b40b7-139">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b40b7-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b40b7-140">Erstellt oder aktualisiert einen Trigger.</span><span class="sxs-lookup"><span data-stu-id="b40b7-140">Creates or updates a trigger.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.Delete(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ITriggersOperations, resourceGroupName As String, factoryName As String, triggerName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.Delete (operations, resourceGroupName, factoryName, triggerName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b40b7-141">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b40b7-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b40b7-142">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b40b7-142">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="b40b7-143">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="b40b7-143">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="b40b7-144">Der Triggername.</span><span class="sxs-lookup"><span data-stu-id="b40b7-144">The trigger name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b40b7-145">Löscht einen Trigger.</span><span class="sxs-lookup"><span data-stu-id="b40b7-145">Deletes a trigger.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.DeleteAsync (operations, resourceGroupName, factoryName, triggerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b40b7-146">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b40b7-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b40b7-147">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b40b7-147">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="b40b7-148">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="b40b7-148">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="b40b7-149">Der Triggername.</span><span class="sxs-lookup"><span data-stu-id="b40b7-149">The trigger name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b40b7-150">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b40b7-150">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b40b7-151">Löscht einen Trigger.</span><span class="sxs-lookup"><span data-stu-id="b40b7-151">Deletes a trigger.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.TriggerResource Get (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.TriggerResource Get(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.Get(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ITriggersOperations, resourceGroupName As String, factoryName As String, triggerName As String) As TriggerResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.TriggerResource" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.Get (operations, resourceGroupName, factoryName, triggerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.TriggerResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b40b7-152">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b40b7-152">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b40b7-153">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b40b7-153">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="b40b7-154">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="b40b7-154">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="b40b7-155">Der Triggername.</span><span class="sxs-lookup"><span data-stu-id="b40b7-155">The trigger name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b40b7-156">Ruft einen Trigger ab.</span><span class="sxs-lookup"><span data-stu-id="b40b7-156">Gets a trigger.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt; GetAsync (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt; GetAsync(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.GetAsync (operations, resourceGroupName, factoryName, triggerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b40b7-157">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b40b7-157">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b40b7-158">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b40b7-158">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="b40b7-159">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="b40b7-159">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="b40b7-160">Der Triggername.</span><span class="sxs-lookup"><span data-stu-id="b40b7-160">The trigger name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b40b7-161">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b40b7-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b40b7-162">Ruft einen Trigger ab.</span><span class="sxs-lookup"><span data-stu-id="b40b7-162">Gets a trigger.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactory">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt; ListByFactory (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt; ListByFactory(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListByFactory(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByFactory (operations As ITriggersOperations, resourceGroupName As String, factoryName As String) As IPage(Of TriggerResource)" />
      <MemberSignature Language="F#" Value="static member ListByFactory : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListByFactory (operations, resourceGroupName, factoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b40b7-163">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b40b7-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b40b7-164">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b40b7-164">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="b40b7-165">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="b40b7-165">The factory name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b40b7-166">Listen-Trigger.</span><span class="sxs-lookup"><span data-stu-id="b40b7-166">Lists triggers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt; ListByFactoryAsync (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt; ListByFactoryAsync(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListByFactoryAsync(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByFactoryAsync : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListByFactoryAsync (operations, resourceGroupName, factoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions/&lt;ListByFactoryAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b40b7-167">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b40b7-167">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b40b7-168">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b40b7-168">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="b40b7-169">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="b40b7-169">The factory name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b40b7-170">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b40b7-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b40b7-171">Listen-Trigger.</span><span class="sxs-lookup"><span data-stu-id="b40b7-171">Lists triggers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt; ListByFactoryNext (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt; ListByFactoryNext(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListByFactoryNext(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByFactoryNext (operations As ITriggersOperations, nextPageLink As String) As IPage(Of TriggerResource)" />
      <MemberSignature Language="F#" Value="static member ListByFactoryNext : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListByFactoryNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b40b7-172">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b40b7-172">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="b40b7-173">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b40b7-173">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b40b7-174">Listen-Trigger.</span><span class="sxs-lookup"><span data-stu-id="b40b7-174">Lists triggers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt; ListByFactoryNextAsync (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt; ListByFactoryNextAsync(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListByFactoryNextAsync(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByFactoryNextAsync : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListByFactoryNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions/&lt;ListByFactoryNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b40b7-175">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b40b7-175">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="b40b7-176">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b40b7-176">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b40b7-177">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b40b7-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b40b7-178">Listen-Trigger.</span><span class="sxs-lookup"><span data-stu-id="b40b7-178">Lists triggers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRuns">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt; ListRuns (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, DateTime startTime, DateTime endTime);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt; ListRuns(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, valuetype System.DateTime startTime, valuetype System.DateTime endTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListRuns(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String,System.DateTime,System.DateTime)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRuns (operations As ITriggersOperations, resourceGroupName As String, factoryName As String, triggerName As String, startTime As DateTime, endTime As DateTime) As IPage(Of TriggerRun)" />
      <MemberSignature Language="F#" Value="static member ListRuns : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string * DateTime * DateTime -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListRuns (operations, resourceGroupName, factoryName, triggerName, startTime, endTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="endTime" Type="System.DateTime" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b40b7-179">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b40b7-179">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b40b7-180">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b40b7-180">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="b40b7-181">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="b40b7-181">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="b40b7-182">Der Triggername.</span><span class="sxs-lookup"><span data-stu-id="b40b7-182">The trigger name.</span></span>
            </param>
        <param name="startTime">
            <span data-ttu-id="b40b7-183">Die Startzeit für Trigger ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="b40b7-183">Start time for trigger runs.</span></span>
            </param>
        <param name="endTime">
            <span data-ttu-id="b40b7-184">Endzeit der Trigger ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="b40b7-184">End time for trigger runs.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b40b7-185">Liste Trigger ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="b40b7-185">List trigger runs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRunsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;&gt; ListRunsAsync (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, DateTime startTime, DateTime endTime, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;&gt; ListRunsAsync(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, valuetype System.DateTime startTime, valuetype System.DateTime endTime, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListRunsAsync(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String,System.DateTime,System.DateTime,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRunsAsync : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string * DateTime * DateTime * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListRunsAsync (operations, resourceGroupName, factoryName, triggerName, startTime, endTime, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions/&lt;ListRunsAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="endTime" Type="System.DateTime" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b40b7-186">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b40b7-186">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b40b7-187">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b40b7-187">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="b40b7-188">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="b40b7-188">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="b40b7-189">Der Triggername.</span><span class="sxs-lookup"><span data-stu-id="b40b7-189">The trigger name.</span></span>
            </param>
        <param name="startTime">
            <span data-ttu-id="b40b7-190">Die Startzeit für Trigger ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="b40b7-190">Start time for trigger runs.</span></span>
            </param>
        <param name="endTime">
            <span data-ttu-id="b40b7-191">Endzeit der Trigger ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="b40b7-191">End time for trigger runs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b40b7-192">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b40b7-192">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b40b7-193">Liste Trigger ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="b40b7-193">List trigger runs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRunsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt; ListRunsNext (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt; ListRunsNext(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListRunsNext(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRunsNext (operations As ITriggersOperations, nextPageLink As String) As IPage(Of TriggerRun)" />
      <MemberSignature Language="F#" Value="static member ListRunsNext : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListRunsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b40b7-194">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b40b7-194">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="b40b7-195">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b40b7-195">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b40b7-196">Liste Trigger ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="b40b7-196">List trigger runs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRunsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;&gt; ListRunsNextAsync (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;&gt; ListRunsNextAsync(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListRunsNextAsync(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRunsNextAsync : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListRunsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions/&lt;ListRunsNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b40b7-197">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b40b7-197">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="b40b7-198">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b40b7-198">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b40b7-199">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b40b7-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b40b7-200">Liste Trigger ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="b40b7-200">List trigger runs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public static void Start (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Start(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.Start(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Start (operations As ITriggersOperations, resourceGroupName As String, factoryName As String, triggerName As String)" />
      <MemberSignature Language="F#" Value="static member Start : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.Start (operations, resourceGroupName, factoryName, triggerName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b40b7-201">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b40b7-201">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b40b7-202">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b40b7-202">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="b40b7-203">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="b40b7-203">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="b40b7-204">Der Triggername.</span><span class="sxs-lookup"><span data-stu-id="b40b7-204">The trigger name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b40b7-205">Startet einen Trigger.</span><span class="sxs-lookup"><span data-stu-id="b40b7-205">Starts a trigger.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task StartAsync (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task StartAsync(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.StartAsync(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StartAsync : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.StartAsync (operations, resourceGroupName, factoryName, triggerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions/&lt;StartAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b40b7-206">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b40b7-206">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b40b7-207">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b40b7-207">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="b40b7-208">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="b40b7-208">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="b40b7-209">Der Triggername.</span><span class="sxs-lookup"><span data-stu-id="b40b7-209">The trigger name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b40b7-210">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b40b7-210">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b40b7-211">Startet einen Trigger.</span><span class="sxs-lookup"><span data-stu-id="b40b7-211">Starts a trigger.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stop">
      <MemberSignature Language="C#" Value="public static void Stop (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Stop(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.Stop(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Stop (operations As ITriggersOperations, resourceGroupName As String, factoryName As String, triggerName As String)" />
      <MemberSignature Language="F#" Value="static member Stop : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.Stop (operations, resourceGroupName, factoryName, triggerName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b40b7-212">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b40b7-212">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b40b7-213">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b40b7-213">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="b40b7-214">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="b40b7-214">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="b40b7-215">Der Triggername.</span><span class="sxs-lookup"><span data-stu-id="b40b7-215">The trigger name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b40b7-216">Beendet einen Trigger.</span><span class="sxs-lookup"><span data-stu-id="b40b7-216">Stops a trigger.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task StopAsync (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task StopAsync(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.StopAsync(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StopAsync : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.StopAsync (operations, resourceGroupName, factoryName, triggerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions/&lt;StopAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b40b7-217">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b40b7-217">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b40b7-218">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b40b7-218">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="b40b7-219">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="b40b7-219">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="b40b7-220">Der Triggername.</span><span class="sxs-lookup"><span data-stu-id="b40b7-220">The trigger name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b40b7-221">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b40b7-221">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b40b7-222">Beendet einen Trigger.</span><span class="sxs-lookup"><span data-stu-id="b40b7-222">Stops a trigger.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>