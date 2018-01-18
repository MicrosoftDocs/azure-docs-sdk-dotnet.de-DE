<Type Name="PermissionOperationsExtensions" FullName="Microsoft.Azure.Management.Authorization.PermissionOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class PermissionOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PermissionOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Authorization.PermissionOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PermissionOperationsExtensions" />
  <TypeSignature Language="F#" Value="type PermissionOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListForResource">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Authorization.Models.PermissionGetResult ListForResource (this Microsoft.Azure.Management.Authorization.IPermissionOperations operations, string resourceGroupName, Microsoft.Azure.ResourceIdentity identity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Authorization.Models.PermissionGetResult ListForResource(class Microsoft.Azure.Management.Authorization.IPermissionOperations operations, string resourceGroupName, class Microsoft.Azure.ResourceIdentity identity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.PermissionOperationsExtensions.ListForResource(Microsoft.Azure.Management.Authorization.IPermissionOperations,System.String,Microsoft.Azure.ResourceIdentity)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListForResource (operations As IPermissionOperations, resourceGroupName As String, identity As ResourceIdentity) As PermissionGetResult" />
      <MemberSignature Language="F#" Value="static member ListForResource : Microsoft.Azure.Management.Authorization.IPermissionOperations * string * Microsoft.Azure.ResourceIdentity -&gt; Microsoft.Azure.Management.Authorization.Models.PermissionGetResult" Usage="Microsoft.Azure.Management.Authorization.PermissionOperationsExtensions.ListForResource (operations, resourceGroupName, identity)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.Models.PermissionGetResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IPermissionOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="identity" Type="Microsoft.Azure.ResourceIdentity" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="48a16-101">Verweis auf die Microsoft.Azure.Management.Authorization.IPermissionOperations.</span><span class="sxs-lookup"><span data-stu-id="48a16-101">Reference to the Microsoft.Azure.Management.Authorization.IPermissionOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="48a16-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="48a16-102">Required.</span></span> <span data-ttu-id="48a16-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="48a16-103">The name of the resource group.</span></span> <span data-ttu-id="48a16-104">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="48a16-104">The name is case insensitive.</span></span>
            </param>
        <param name="identity">
            <span data-ttu-id="48a16-105">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="48a16-105">Required.</span></span> <span data-ttu-id="48a16-106">Ressource</span><span class="sxs-lookup"><span data-stu-id="48a16-106">Resource</span></span>
            </param>
        <summary>
            <span data-ttu-id="48a16-107">Ruft eine Ressource Berechtigungen ab.</span><span class="sxs-lookup"><span data-stu-id="48a16-107">Gets a resource permissions.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="48a16-108">Berechtigungsinformationen.</span><span class="sxs-lookup"><span data-stu-id="48a16-108">Permissions information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt; ListForResourceAsync (this Microsoft.Azure.Management.Authorization.IPermissionOperations operations, string resourceGroupName, Microsoft.Azure.ResourceIdentity identity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt; ListForResourceAsync(class Microsoft.Azure.Management.Authorization.IPermissionOperations operations, string resourceGroupName, class Microsoft.Azure.ResourceIdentity identity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.PermissionOperationsExtensions.ListForResourceAsync(Microsoft.Azure.Management.Authorization.IPermissionOperations,System.String,Microsoft.Azure.ResourceIdentity)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListForResourceAsync (operations As IPermissionOperations, resourceGroupName As String, identity As ResourceIdentity) As Task(Of PermissionGetResult)" />
      <MemberSignature Language="F#" Value="static member ListForResourceAsync : Microsoft.Azure.Management.Authorization.IPermissionOperations * string * Microsoft.Azure.ResourceIdentity -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt;" Usage="Microsoft.Azure.Management.Authorization.PermissionOperationsExtensions.ListForResourceAsync (operations, resourceGroupName, identity)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IPermissionOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="identity" Type="Microsoft.Azure.ResourceIdentity" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="48a16-109">Verweis auf die Microsoft.Azure.Management.Authorization.IPermissionOperations.</span><span class="sxs-lookup"><span data-stu-id="48a16-109">Reference to the Microsoft.Azure.Management.Authorization.IPermissionOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="48a16-110">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="48a16-110">Required.</span></span> <span data-ttu-id="48a16-111">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="48a16-111">The name of the resource group.</span></span> <span data-ttu-id="48a16-112">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="48a16-112">The name is case insensitive.</span></span>
            </param>
        <param name="identity">
            <span data-ttu-id="48a16-113">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="48a16-113">Required.</span></span> <span data-ttu-id="48a16-114">Ressource</span><span class="sxs-lookup"><span data-stu-id="48a16-114">Resource</span></span>
            </param>
        <summary>
            <span data-ttu-id="48a16-115">Ruft eine Ressource Berechtigungen ab.</span><span class="sxs-lookup"><span data-stu-id="48a16-115">Gets a resource permissions.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="48a16-116">Berechtigungsinformationen.</span><span class="sxs-lookup"><span data-stu-id="48a16-116">Permissions information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Authorization.Models.PermissionGetResult ListForResourceGroup (this Microsoft.Azure.Management.Authorization.IPermissionOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Authorization.Models.PermissionGetResult ListForResourceGroup(class Microsoft.Azure.Management.Authorization.IPermissionOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.PermissionOperationsExtensions.ListForResourceGroup(Microsoft.Azure.Management.Authorization.IPermissionOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListForResourceGroup (operations As IPermissionOperations, resourceGroupName As String) As PermissionGetResult" />
      <MemberSignature Language="F#" Value="static member ListForResourceGroup : Microsoft.Azure.Management.Authorization.IPermissionOperations * string -&gt; Microsoft.Azure.Management.Authorization.Models.PermissionGetResult" Usage="Microsoft.Azure.Management.Authorization.PermissionOperationsExtensions.ListForResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.Models.PermissionGetResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IPermissionOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="48a16-117">Verweis auf die Microsoft.Azure.Management.Authorization.IPermissionOperations.</span><span class="sxs-lookup"><span data-stu-id="48a16-117">Reference to the Microsoft.Azure.Management.Authorization.IPermissionOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="48a16-118">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="48a16-118">Required.</span></span> <span data-ttu-id="48a16-119">Der Name der Ressourcengruppe, um die Berechtigungen für zu erhalten. Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="48a16-119">Name of the resource group to get the permissions for.The name is case insensitive.</span></span>
            </param>
        <summary>
            <span data-ttu-id="48a16-120">Ruft eine Ressource Gruppenberechtigungen ab.</span><span class="sxs-lookup"><span data-stu-id="48a16-120">Gets a resource group permissions.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="48a16-121">Berechtigungsinformationen.</span><span class="sxs-lookup"><span data-stu-id="48a16-121">Permissions information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt; ListForResourceGroupAsync (this Microsoft.Azure.Management.Authorization.IPermissionOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt; ListForResourceGroupAsync(class Microsoft.Azure.Management.Authorization.IPermissionOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.PermissionOperationsExtensions.ListForResourceGroupAsync(Microsoft.Azure.Management.Authorization.IPermissionOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListForResourceGroupAsync (operations As IPermissionOperations, resourceGroupName As String) As Task(Of PermissionGetResult)" />
      <MemberSignature Language="F#" Value="static member ListForResourceGroupAsync : Microsoft.Azure.Management.Authorization.IPermissionOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt;" Usage="Microsoft.Azure.Management.Authorization.PermissionOperationsExtensions.ListForResourceGroupAsync (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IPermissionOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="48a16-122">Verweis auf die Microsoft.Azure.Management.Authorization.IPermissionOperations.</span><span class="sxs-lookup"><span data-stu-id="48a16-122">Reference to the Microsoft.Azure.Management.Authorization.IPermissionOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="48a16-123">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="48a16-123">Required.</span></span> <span data-ttu-id="48a16-124">Der Name der Ressourcengruppe, um die Berechtigungen für zu erhalten. Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="48a16-124">Name of the resource group to get the permissions for.The name is case insensitive.</span></span>
            </param>
        <summary>
            <span data-ttu-id="48a16-125">Ruft eine Ressource Gruppenberechtigungen ab.</span><span class="sxs-lookup"><span data-stu-id="48a16-125">Gets a resource group permissions.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="48a16-126">Berechtigungsinformationen.</span><span class="sxs-lookup"><span data-stu-id="48a16-126">Permissions information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>