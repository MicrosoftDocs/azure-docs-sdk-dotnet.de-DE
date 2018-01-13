<Type Name="SubnetsOperationsExtensions" FullName="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class SubnetsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SubnetsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module SubnetsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type SubnetsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3d3c2-101">Erweiterungsmethoden für SubnetsOperations.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-101">Extension methods for SubnetsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.Subnet BeginCreateOrUpdate (this Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, Microsoft.Azure.Management.Network.Models.Subnet subnetParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.Subnet BeginCreateOrUpdate(class Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, class Microsoft.Azure.Management.Network.Models.Subnet subnetParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Network.ISubnetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.Subnet)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As ISubnetsOperations, resourceGroupName As String, virtualNetworkName As String, subnetName As String, subnetParameters As Subnet) As Subnet" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Network.ISubnetsOperations * string * string * string * Microsoft.Azure.Management.Network.Models.Subnet -&gt; Microsoft.Azure.Management.Network.Models.Subnet" Usage="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, virtualNetworkName, subnetName, subnetParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.Subnet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="subnetName" Type="System.String" />
        <Parameter Name="subnetParameters" Type="Microsoft.Azure.Management.Network.Models.Subnet" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3d3c2-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3d3c2-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-103">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="3d3c2-104">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-104">The name of the virtual network.</span></span>
            </param>
        <param name="subnetName">
            <span data-ttu-id="3d3c2-105">Der Name des Subnetzes.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-105">The name of the subnet.</span></span>
            </param>
        <param name="subnetParameters">
            <span data-ttu-id="3d3c2-106">Parameter für das Erstellen oder aktualisieren Subnetz zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-106">Parameters supplied to the create or update subnet operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3d3c2-107">Erstellt oder aktualisiert ein Subnetz im angegebenen virtuellen Netzwerk.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-107">Creates or updates a subnet in the specified virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, Microsoft.Azure.Management.Network.Models.Subnet subnetParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.Subnet&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, class Microsoft.Azure.Management.Network.Models.Subnet subnetParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.ISubnetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.Subnet,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.ISubnetsOperations * string * string * string * Microsoft.Azure.Management.Network.Models.Subnet * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;" Usage="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, virtualNetworkName, subnetName, subnetParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.SubnetsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="subnetName" Type="System.String" />
        <Parameter Name="subnetParameters" Type="Microsoft.Azure.Management.Network.Models.Subnet" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3d3c2-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3d3c2-109">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-109">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="3d3c2-110">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-110">The name of the virtual network.</span></span>
            </param>
        <param name="subnetName">
            <span data-ttu-id="3d3c2-111">Der Name des Subnetzes.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-111">The name of the subnet.</span></span>
            </param>
        <param name="subnetParameters">
            <span data-ttu-id="3d3c2-112">Parameter für das Erstellen oder aktualisieren Subnetz zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-112">Parameters supplied to the create or update subnet operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3d3c2-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3d3c2-114">Erstellt oder aktualisiert ein Subnetz im angegebenen virtuellen Netzwerk.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-114">Creates or updates a subnet in the specified virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.ISubnetsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As ISubnetsOperations, resourceGroupName As String, virtualNetworkName As String, subnetName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.ISubnetsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.BeginDelete (operations, resourceGroupName, virtualNetworkName, subnetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="subnetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3d3c2-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3d3c2-116">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-116">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="3d3c2-117">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-117">The name of the virtual network.</span></span>
            </param>
        <param name="subnetName">
            <span data-ttu-id="3d3c2-118">Der Name des Subnetzes.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-118">The name of the subnet.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3d3c2-119">Löscht das angegebene Subnetz an.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-119">Deletes the specified subnet.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.ISubnetsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.ISubnetsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, virtualNetworkName, subnetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.SubnetsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="subnetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3d3c2-120">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-120">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3d3c2-121">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-121">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="3d3c2-122">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-122">The name of the virtual network.</span></span>
            </param>
        <param name="subnetName">
            <span data-ttu-id="3d3c2-123">Der Name des Subnetzes.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-123">The name of the subnet.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3d3c2-124">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3d3c2-125">Löscht das angegebene Subnetz an.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-125">Deletes the specified subnet.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.Subnet CreateOrUpdate (this Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, Microsoft.Azure.Management.Network.Models.Subnet subnetParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.Subnet CreateOrUpdate(class Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, class Microsoft.Azure.Management.Network.Models.Subnet subnetParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.ISubnetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.Subnet)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ISubnetsOperations, resourceGroupName As String, virtualNetworkName As String, subnetName As String, subnetParameters As Subnet) As Subnet" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.ISubnetsOperations * string * string * string * Microsoft.Azure.Management.Network.Models.Subnet -&gt; Microsoft.Azure.Management.Network.Models.Subnet" Usage="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, virtualNetworkName, subnetName, subnetParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.Subnet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="subnetName" Type="System.String" />
        <Parameter Name="subnetParameters" Type="Microsoft.Azure.Management.Network.Models.Subnet" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3d3c2-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3d3c2-127">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-127">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="3d3c2-128">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-128">The name of the virtual network.</span></span>
            </param>
        <param name="subnetName">
            <span data-ttu-id="3d3c2-129">Der Name des Subnetzes.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-129">The name of the subnet.</span></span>
            </param>
        <param name="subnetParameters">
            <span data-ttu-id="3d3c2-130">Parameter für das Erstellen oder aktualisieren Subnetz zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-130">Parameters supplied to the create or update subnet operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3d3c2-131">Erstellt oder aktualisiert ein Subnetz im angegebenen virtuellen Netzwerk.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-131">Creates or updates a subnet in the specified virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, Microsoft.Azure.Management.Network.Models.Subnet subnetParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.Subnet&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, class Microsoft.Azure.Management.Network.Models.Subnet subnetParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.ISubnetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.Subnet,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.ISubnetsOperations * string * string * string * Microsoft.Azure.Management.Network.Models.Subnet * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;" Usage="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, virtualNetworkName, subnetName, subnetParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.SubnetsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="subnetName" Type="System.String" />
        <Parameter Name="subnetParameters" Type="Microsoft.Azure.Management.Network.Models.Subnet" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3d3c2-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3d3c2-133">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-133">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="3d3c2-134">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-134">The name of the virtual network.</span></span>
            </param>
        <param name="subnetName">
            <span data-ttu-id="3d3c2-135">Der Name des Subnetzes.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-135">The name of the subnet.</span></span>
            </param>
        <param name="subnetParameters">
            <span data-ttu-id="3d3c2-136">Parameter für das Erstellen oder aktualisieren Subnetz zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-136">Parameters supplied to the create or update subnet operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3d3c2-137">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3d3c2-138">Erstellt oder aktualisiert ein Subnetz im angegebenen virtuellen Netzwerk.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-138">Creates or updates a subnet in the specified virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.Delete(Microsoft.Azure.Management.Network.ISubnetsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ISubnetsOperations, resourceGroupName As String, virtualNetworkName As String, subnetName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.ISubnetsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.Delete (operations, resourceGroupName, virtualNetworkName, subnetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="subnetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3d3c2-139">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-139">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3d3c2-140">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-140">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="3d3c2-141">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-141">The name of the virtual network.</span></span>
            </param>
        <param name="subnetName">
            <span data-ttu-id="3d3c2-142">Der Name des Subnetzes.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-142">The name of the subnet.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3d3c2-143">Löscht das angegebene Subnetz an.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-143">Deletes the specified subnet.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.ISubnetsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.ISubnetsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.DeleteAsync (operations, resourceGroupName, virtualNetworkName, subnetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.SubnetsOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="subnetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3d3c2-144">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3d3c2-145">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-145">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="3d3c2-146">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-146">The name of the virtual network.</span></span>
            </param>
        <param name="subnetName">
            <span data-ttu-id="3d3c2-147">Der Name des Subnetzes.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-147">The name of the subnet.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3d3c2-148">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3d3c2-149">Löscht das angegebene Subnetz an.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-149">Deletes the specified subnet.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.Subnet Get (this Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.Subnet Get(class Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.Get(Microsoft.Azure.Management.Network.ISubnetsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ISubnetsOperations, resourceGroupName As String, virtualNetworkName As String, subnetName As String, Optional expand As String = null) As Subnet" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.ISubnetsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.Subnet" Usage="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.Get (operations, resourceGroupName, virtualNetworkName, subnetName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.Subnet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="subnetName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3d3c2-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3d3c2-151">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-151">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="3d3c2-152">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-152">The name of the virtual network.</span></span>
            </param>
        <param name="subnetName">
            <span data-ttu-id="3d3c2-153">Der Name des Subnetzes.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-153">The name of the subnet.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="3d3c2-154">Wird erweitert, referenzierte Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-154">Expands referenced resources.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3d3c2-155">Ruft das angegebene Subnetz vom virtuellen Netzwerk und Ressourcen Gruppe ab.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-155">Gets the specified subnet by virtual network and resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt; GetAsync (this Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.Subnet&gt; GetAsync(class Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.ISubnetsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.ISubnetsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;" Usage="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.GetAsync (operations, resourceGroupName, virtualNetworkName, subnetName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.SubnetsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="subnetName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3d3c2-156">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-156">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3d3c2-157">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-157">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="3d3c2-158">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-158">The name of the virtual network.</span></span>
            </param>
        <param name="subnetName">
            <span data-ttu-id="3d3c2-159">Der Name des Subnetzes.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-159">The name of the subnet.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="3d3c2-160">Wird erweitert, referenzierte Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-160">Expands referenced resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3d3c2-161">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3d3c2-162">Ruft das angegebene Subnetz vom virtuellen Netzwerk und Ressourcen Gruppe ab.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-162">Gets the specified subnet by virtual network and resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt; List (this Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.Subnet&gt; List(class Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.List(Microsoft.Azure.Management.Network.ISubnetsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ISubnetsOperations, resourceGroupName As String, virtualNetworkName As String) As IPage(Of Subnet)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.ISubnetsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;" Usage="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.List (operations, resourceGroupName, virtualNetworkName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3d3c2-163">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3d3c2-164">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-164">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="3d3c2-165">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-165">The name of the virtual network.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3d3c2-166">Ruft alle Subnetze in einem virtuellen Netzwerk an.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-166">Gets all subnets in a virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.Subnet&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.ISubnetsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.ISubnetsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;&gt;" Usage="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.ListAsync (operations, resourceGroupName, virtualNetworkName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.SubnetsOperationsExtensions/&lt;ListAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3d3c2-167">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-167">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3d3c2-168">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-168">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="3d3c2-169">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-169">The name of the virtual network.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3d3c2-170">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3d3c2-171">Ruft alle Subnetze in einem virtuellen Netzwerk an.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-171">Gets all subnets in a virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt; ListNext (this Microsoft.Azure.Management.Network.ISubnetsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.Subnet&gt; ListNext(class Microsoft.Azure.Management.Network.ISubnetsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.ISubnetsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As ISubnetsOperations, nextPageLink As String) As IPage(Of Subnet)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.ISubnetsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;" Usage="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ISubnetsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3d3c2-172">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-172">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3d3c2-173">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-173">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3d3c2-174">Ruft alle Subnetze in einem virtuellen Netzwerk an.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-174">Gets all subnets in a virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.ISubnetsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.Subnet&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.ISubnetsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.ISubnetsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.ISubnetsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;&gt;" Usage="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.SubnetsOperationsExtensions/&lt;ListNextAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ISubnetsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3d3c2-175">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-175">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3d3c2-176">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-176">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3d3c2-177">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3d3c2-178">Ruft alle Subnetze in einem virtuellen Netzwerk an.</span><span class="sxs-lookup"><span data-stu-id="3d3c2-178">Gets all subnets in a virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>