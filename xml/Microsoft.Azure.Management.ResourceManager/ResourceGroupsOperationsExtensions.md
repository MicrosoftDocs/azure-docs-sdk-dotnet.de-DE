<Type Name="ResourceGroupsOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ResourceGroupsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ResourceGroupsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ResourceGroupsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ResourceGroupsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f91ce-101">Erweiterungsmethoden für ResourceGroupsOperations.</span><span class="sxs-lookup"><span data-stu-id="f91ce-101">Extension methods for ResourceGroupsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IResourceGroupsOperations, resourceGroupName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.BeginDelete (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f91ce-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f91ce-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f91ce-103">Der Name der Ressourcengruppe, zu löschen.</span><span class="sxs-lookup"><span data-stu-id="f91ce-103">The name of the resource group to delete.</span></span> <span data-ttu-id="f91ce-104">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="f91ce-104">The name is case insensitive.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f91ce-105">Löscht eine Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="f91ce-105">Deletes a resource group.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="f91ce-106">Wenn Sie eine Ressourcengruppe löschen, werden alle Ressourcen ebenfalls gelöscht.</span><span class="sxs-lookup"><span data-stu-id="f91ce-106">When you delete a resource group, all of its resources are also deleted.</span></span>
            <span data-ttu-id="f91ce-107">Durch das Löschen einer Ressourcengruppe löscht alle ihre vorlagenbereitstellungen und zurzeit gespeicherten Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="f91ce-107">Deleting a resource group deletes all of its template deployments and currently stored operations.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f91ce-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f91ce-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f91ce-109">Der Name der Ressourcengruppe, zu löschen.</span><span class="sxs-lookup"><span data-stu-id="f91ce-109">The name of the resource group to delete.</span></span> <span data-ttu-id="f91ce-110">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="f91ce-110">The name is case insensitive.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f91ce-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f91ce-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f91ce-112">Löscht eine Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="f91ce-112">Deletes a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f91ce-113">Wenn Sie eine Ressourcengruppe löschen, werden alle Ressourcen ebenfalls gelöscht.</span><span class="sxs-lookup"><span data-stu-id="f91ce-113">When you delete a resource group, all of its resources are also deleted.</span></span>
            <span data-ttu-id="f91ce-114">Durch das Löschen einer Ressourcengruppe löscht alle ihre vorlagenbereitstellungen und zurzeit gespeicherten Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="f91ce-114">Deleting a resource group deletes all of its template deployments and currently stored operations.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckExistence">
      <MemberSignature Language="C#" Value="public static bool CheckExistence (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool CheckExistence(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.CheckExistence(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckExistence (operations As IResourceGroupsOperations, resourceGroupName As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member CheckExistence : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string -&gt; bool" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.CheckExistence (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f91ce-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f91ce-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f91ce-116">Der Name der Ressourcengruppe, um zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="f91ce-116">The name of the resource group to check.</span></span> <span data-ttu-id="f91ce-117">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="f91ce-117">The name is case insensitive.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f91ce-118">Überprüft, ob eine Ressourcengruppe vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="f91ce-118">Checks whether a resource group exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckExistenceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; CheckExistenceAsync (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; CheckExistenceAsync(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.CheckExistenceAsync(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckExistenceAsync : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.CheckExistenceAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions/&lt;CheckExistenceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f91ce-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f91ce-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f91ce-120">Der Name der Ressourcengruppe, um zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="f91ce-120">The name of the resource group to check.</span></span> <span data-ttu-id="f91ce-121">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="f91ce-121">The name is case insensitive.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f91ce-122">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f91ce-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f91ce-123">Überprüft, ob eine Ressourcengruppe vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="f91ce-123">Checks whether a resource group exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup CreateOrUpdate (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup CreateOrUpdate(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IResourceGroupsOperations, resourceGroupName As String, parameters As ResourceGroup) As ResourceGroup" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup -&gt; Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f91ce-124">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f91ce-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f91ce-125">Der Name der Ressourcengruppe erstellt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="f91ce-125">The name of the resource group to create or update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f91ce-126">Parameter angegeben wird, auf die erstellen oder Aktualisieren einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="f91ce-126">Parameters supplied to the create or update a resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f91ce-127">Erstellt oder aktualisiert eine Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="f91ce-127">Creates or updates a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f91ce-128">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f91ce-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f91ce-129">Der Name der Ressourcengruppe erstellt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="f91ce-129">The name of the resource group to create or update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f91ce-130">Parameter angegeben wird, auf die erstellen oder Aktualisieren einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="f91ce-130">Parameters supplied to the create or update a resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f91ce-131">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f91ce-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f91ce-132">Erstellt oder aktualisiert eine Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="f91ce-132">Creates or updates a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.Delete(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IResourceGroupsOperations, resourceGroupName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.Delete (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f91ce-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f91ce-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f91ce-134">Der Name der Ressourcengruppe, zu löschen.</span><span class="sxs-lookup"><span data-stu-id="f91ce-134">The name of the resource group to delete.</span></span> <span data-ttu-id="f91ce-135">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="f91ce-135">The name is case insensitive.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f91ce-136">Löscht eine Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="f91ce-136">Deletes a resource group.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="f91ce-137">Wenn Sie eine Ressourcengruppe löschen, werden alle Ressourcen ebenfalls gelöscht.</span><span class="sxs-lookup"><span data-stu-id="f91ce-137">When you delete a resource group, all of its resources are also deleted.</span></span>
            <span data-ttu-id="f91ce-138">Durch das Löschen einer Ressourcengruppe löscht alle ihre vorlagenbereitstellungen und zurzeit gespeicherten Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="f91ce-138">Deleting a resource group deletes all of its template deployments and currently stored operations.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.DeleteAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f91ce-139">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f91ce-139">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f91ce-140">Der Name der Ressourcengruppe, zu löschen.</span><span class="sxs-lookup"><span data-stu-id="f91ce-140">The name of the resource group to delete.</span></span> <span data-ttu-id="f91ce-141">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="f91ce-141">The name is case insensitive.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f91ce-142">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f91ce-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f91ce-143">Löscht eine Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="f91ce-143">Deletes a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f91ce-144">Wenn Sie eine Ressourcengruppe löschen, werden alle Ressourcen ebenfalls gelöscht.</span><span class="sxs-lookup"><span data-stu-id="f91ce-144">When you delete a resource group, all of its resources are also deleted.</span></span>
            <span data-ttu-id="f91ce-145">Durch das Löschen einer Ressourcengruppe löscht alle ihre vorlagenbereitstellungen und zurzeit gespeicherten Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="f91ce-145">Deleting a resource group deletes all of its template deployments and currently stored operations.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportTemplate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult ExportTemplate (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult ExportTemplate(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ExportTemplate(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ExportTemplate (operations As IResourceGroupsOperations, resourceGroupName As String, parameters As ExportTemplateRequest) As ResourceGroupExportResult" />
      <MemberSignature Language="F#" Value="static member ExportTemplate : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest -&gt; Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ExportTemplate (operations, resourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f91ce-146">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f91ce-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f91ce-147">Der Name der Ressourcengruppe als Vorlage zu exportieren.</span><span class="sxs-lookup"><span data-stu-id="f91ce-147">The name of the resource group to export as a template.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f91ce-148">Parameter für das Exportieren der Vorlage.</span><span class="sxs-lookup"><span data-stu-id="f91ce-148">Parameters for exporting the template.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f91ce-149">Zeichnet die angegebene Ressourcengruppe als Vorlage.</span><span class="sxs-lookup"><span data-stu-id="f91ce-149">Captures the specified resource group as a template.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportTemplateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult&gt; ExportTemplateAsync (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult&gt; ExportTemplateAsync(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ExportTemplateAsync(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExportTemplateAsync : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ExportTemplateAsync (operations, resourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions/&lt;ExportTemplateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f91ce-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f91ce-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f91ce-151">Der Name der Ressourcengruppe als Vorlage zu exportieren.</span><span class="sxs-lookup"><span data-stu-id="f91ce-151">The name of the resource group to export as a template.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f91ce-152">Parameter für das Exportieren der Vorlage.</span><span class="sxs-lookup"><span data-stu-id="f91ce-152">Parameters for exporting the template.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f91ce-153">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f91ce-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f91ce-154">Zeichnet die angegebene Ressourcengruppe als Vorlage.</span><span class="sxs-lookup"><span data-stu-id="f91ce-154">Captures the specified resource group as a template.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup Get (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup Get(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.Get(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IResourceGroupsOperations, resourceGroupName As String) As ResourceGroup" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.Get (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f91ce-155">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f91ce-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f91ce-156">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="f91ce-156">The name of the resource group to get.</span></span> <span data-ttu-id="f91ce-157">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="f91ce-157">The name is case insensitive.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f91ce-158">Ruft eine Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="f91ce-158">Gets a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.GetAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f91ce-159">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f91ce-159">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f91ce-160">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="f91ce-160">The name of the resource group to get.</span></span> <span data-ttu-id="f91ce-161">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="f91ce-161">The name is case insensitive.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f91ce-162">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f91ce-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f91ce-163">Ruft eine Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="f91ce-163">Gets a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; List (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; List(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.List(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IResourceGroupsOperations, Optional odataQuery As ODataQuery(Of ResourceGroupFilter) = null) As IPage(Of ResourceGroup)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.List (operations, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f91ce-164">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f91ce-164">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="f91ce-165">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="f91ce-165">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f91ce-166">Ruft alle Ressourcengruppen für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="f91ce-166">Gets all the resource groups for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ListAsync (operations, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions/&lt;ListAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f91ce-167">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f91ce-167">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="f91ce-168">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="f91ce-168">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f91ce-169">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f91ce-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f91ce-170">Ruft alle Ressourcengruppen für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="f91ce-170">Gets all the resource groups for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; ListNext (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; ListNext(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ListNext(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IResourceGroupsOperations, nextPageLink As String) As IPage(Of ResourceGroup)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f91ce-171">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f91ce-171">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f91ce-172">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f91ce-172">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f91ce-173">Ruft alle Ressourcengruppen für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="f91ce-173">Gets all the resource groups for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions/&lt;ListNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f91ce-174">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f91ce-174">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f91ce-175">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f91ce-175">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f91ce-176">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f91ce-176">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f91ce-177">Ruft alle Ressourcengruppen für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="f91ce-177">Gets all the resource groups for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup Update (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup Update(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.Update(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IResourceGroupsOperations, resourceGroupName As String, parameters As ResourceGroupPatchable) As ResourceGroup" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable -&gt; Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.Update (operations, resourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f91ce-178">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f91ce-178">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f91ce-179">Der Name der Ressourcengruppe, zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="f91ce-179">The name of the resource group to update.</span></span> <span data-ttu-id="f91ce-180">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="f91ce-180">The name is case insensitive.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f91ce-181">Parameter, die zum Aktualisieren einer Ressourcengruppe bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="f91ce-181">Parameters supplied to update a resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f91ce-182">Aktualisiert eine Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="f91ce-182">Updates a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f91ce-183">Ressourcengruppen können über einen einfachen Patchvorgang zu einer Gruppenadresse aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="f91ce-183">Resource groups can be updated through a simple PATCH operation to a group address.</span></span> <span data-ttu-id="f91ce-184">Das Format der Anforderung ist identisch, die zum Erstellen einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="f91ce-184">The format of the request is the same as that for creating a resource group.</span></span> <span data-ttu-id="f91ce-185">Wenn ein Feld nicht angegeben wird, wird der aktuelle Wert beibehalten.</span><span class="sxs-lookup"><span data-stu-id="f91ce-185">If a field is unspecified, the current value is retained.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; UpdateAsync (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; UpdateAsync(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.UpdateAsync (operations, resourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions/&lt;UpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f91ce-186">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f91ce-186">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f91ce-187">Der Name der Ressourcengruppe, zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="f91ce-187">The name of the resource group to update.</span></span> <span data-ttu-id="f91ce-188">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="f91ce-188">The name is case insensitive.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f91ce-189">Parameter, die zum Aktualisieren einer Ressourcengruppe bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="f91ce-189">Parameters supplied to update a resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f91ce-190">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f91ce-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f91ce-191">Aktualisiert eine Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="f91ce-191">Updates a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f91ce-192">Ressourcengruppen können über einen einfachen Patchvorgang zu einer Gruppenadresse aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="f91ce-192">Resource groups can be updated through a simple PATCH operation to a group address.</span></span> <span data-ttu-id="f91ce-193">Das Format der Anforderung ist identisch, die zum Erstellen einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="f91ce-193">The format of the request is the same as that for creating a resource group.</span></span> <span data-ttu-id="f91ce-194">Wenn ein Feld nicht angegeben wird, wird der aktuelle Wert beibehalten.</span><span class="sxs-lookup"><span data-stu-id="f91ce-194">If a field is unspecified, the current value is retained.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>