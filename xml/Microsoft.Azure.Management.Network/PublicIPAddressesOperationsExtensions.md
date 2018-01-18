<Type Name="PublicIPAddressesOperationsExtensions" FullName="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class PublicIPAddressesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PublicIPAddressesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PublicIPAddressesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type PublicIPAddressesOperationsExtensions = class" />
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
            <span data-ttu-id="69b71-101">Erweiterungsmethoden für PublicIPAddressesOperations.</span><span class="sxs-lookup"><span data-stu-id="69b71-101">Extension methods for PublicIPAddressesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.PublicIPAddress BeginCreateOrUpdate (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, Microsoft.Azure.Management.Network.Models.PublicIPAddress parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.PublicIPAddress BeginCreateOrUpdate(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, class Microsoft.Azure.Management.Network.Models.PublicIPAddress parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.PublicIPAddress)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IPublicIPAddressesOperations, resourceGroupName As String, publicIpAddressName As String, parameters As PublicIPAddress) As PublicIPAddress" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * Microsoft.Azure.Management.Network.Models.PublicIPAddress -&gt; Microsoft.Azure.Management.Network.Models.PublicIPAddress" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, publicIpAddressName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.PublicIPAddress</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.PublicIPAddress" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="69b71-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-103">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="69b71-104">Der Name der öffentlichen IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="69b71-104">The name of the public IP address.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="69b71-105">Parameter zum Erstellen oder aktualisieren öffentliche IP-Adresse Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="69b71-105">Parameters supplied to the create or update public IP address operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-106">Erstellt oder aktualisiert eine statische oder dynamische öffentliche IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="69b71-106">Creates or updates a static or dynamic public IP address.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, Microsoft.Azure.Management.Network.Models.PublicIPAddress parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, class Microsoft.Azure.Management.Network.Models.PublicIPAddress parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.PublicIPAddress,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * Microsoft.Azure.Management.Network.Models.PublicIPAddress * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, publicIpAddressName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.PublicIPAddress" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="69b71-108">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-108">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="69b71-109">Der Name der öffentlichen IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="69b71-109">The name of the public IP address.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="69b71-110">Parameter zum Erstellen oder aktualisieren öffentliche IP-Adresse Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="69b71-110">Parameters supplied to the create or update public IP address operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="69b71-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="69b71-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-112">Erstellt oder aktualisiert eine statische oder dynamische öffentliche IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="69b71-112">Creates or updates a static or dynamic public IP address.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IPublicIPAddressesOperations, resourceGroupName As String, publicIpAddressName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.BeginDelete (operations, resourceGroupName, publicIpAddressName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="69b71-114">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-114">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="69b71-115">Der Name des Subnetzes.</span><span class="sxs-lookup"><span data-stu-id="69b71-115">The name of the subnet.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-116">Löscht die angegebene öffentliche IP-Adresse an.</span><span class="sxs-lookup"><span data-stu-id="69b71-116">Deletes the specified public IP address.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, publicIpAddressName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="69b71-118">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-118">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="69b71-119">Der Name des Subnetzes.</span><span class="sxs-lookup"><span data-stu-id="69b71-119">The name of the subnet.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="69b71-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="69b71-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-121">Löscht die angegebene öffentliche IP-Adresse an.</span><span class="sxs-lookup"><span data-stu-id="69b71-121">Deletes the specified public IP address.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.PublicIPAddress BeginUpdateTags (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.PublicIPAddress BeginUpdateTags(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.BeginUpdateTags(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdateTags (operations As IPublicIPAddressesOperations, resourceGroupName As String, publicIpAddressName As String, parameters As TagsObject) As PublicIPAddress" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTags : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.PublicIPAddress" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.BeginUpdateTags (operations, resourceGroupName, publicIpAddressName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.PublicIPAddress</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="69b71-123">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-123">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="69b71-124">Der Name der öffentlichen IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="69b71-124">The name of the public IP address.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="69b71-125">Parameter, die zum Aktualisieren der öffentlichen IP-adresstags angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="69b71-125">Parameters supplied to update public IP address tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-126">Öffentliche IP-adresstags wird aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="69b71-126">Updates public IP address tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; BeginUpdateTagsAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; BeginUpdateTagsAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.BeginUpdateTagsAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTagsAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.BeginUpdateTagsAsync (operations, resourceGroupName, publicIpAddressName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;BeginUpdateTagsAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-127">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="69b71-128">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-128">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="69b71-129">Der Name der öffentlichen IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="69b71-129">The name of the public IP address.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="69b71-130">Parameter, die zum Aktualisieren der öffentlichen IP-adresstags angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="69b71-130">Parameters supplied to update public IP address tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="69b71-131">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="69b71-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-132">Öffentliche IP-adresstags wird aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="69b71-132">Updates public IP address tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.PublicIPAddress CreateOrUpdate (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, Microsoft.Azure.Management.Network.Models.PublicIPAddress parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.PublicIPAddress CreateOrUpdate(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, class Microsoft.Azure.Management.Network.Models.PublicIPAddress parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.PublicIPAddress)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IPublicIPAddressesOperations, resourceGroupName As String, publicIpAddressName As String, parameters As PublicIPAddress) As PublicIPAddress" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * Microsoft.Azure.Management.Network.Models.PublicIPAddress -&gt; Microsoft.Azure.Management.Network.Models.PublicIPAddress" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, publicIpAddressName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.PublicIPAddress</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.PublicIPAddress" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="69b71-134">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-134">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="69b71-135">Der Name der öffentlichen IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="69b71-135">The name of the public IP address.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="69b71-136">Parameter zum Erstellen oder aktualisieren öffentliche IP-Adresse Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="69b71-136">Parameters supplied to the create or update public IP address operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-137">Erstellt oder aktualisiert eine statische oder dynamische öffentliche IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="69b71-137">Creates or updates a static or dynamic public IP address.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, Microsoft.Azure.Management.Network.Models.PublicIPAddress parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, class Microsoft.Azure.Management.Network.Models.PublicIPAddress parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.PublicIPAddress,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * Microsoft.Azure.Management.Network.Models.PublicIPAddress * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, publicIpAddressName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.PublicIPAddress" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-138">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-138">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="69b71-139">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-139">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="69b71-140">Der Name der öffentlichen IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="69b71-140">The name of the public IP address.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="69b71-141">Parameter zum Erstellen oder aktualisieren öffentliche IP-Adresse Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="69b71-141">Parameters supplied to the create or update public IP address operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="69b71-142">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="69b71-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-143">Erstellt oder aktualisiert eine statische oder dynamische öffentliche IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="69b71-143">Creates or updates a static or dynamic public IP address.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.Delete(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IPublicIPAddressesOperations, resourceGroupName As String, publicIpAddressName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.Delete (operations, resourceGroupName, publicIpAddressName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-144">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="69b71-145">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-145">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="69b71-146">Der Name des Subnetzes.</span><span class="sxs-lookup"><span data-stu-id="69b71-146">The name of the subnet.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-147">Löscht die angegebene öffentliche IP-Adresse an.</span><span class="sxs-lookup"><span data-stu-id="69b71-147">Deletes the specified public IP address.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.DeleteAsync (operations, resourceGroupName, publicIpAddressName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-148">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="69b71-149">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-149">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="69b71-150">Der Name des Subnetzes.</span><span class="sxs-lookup"><span data-stu-id="69b71-150">The name of the subnet.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="69b71-151">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="69b71-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-152">Löscht die angegebene öffentliche IP-Adresse an.</span><span class="sxs-lookup"><span data-stu-id="69b71-152">Deletes the specified public IP address.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.PublicIPAddress Get (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.PublicIPAddress Get(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.Get(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IPublicIPAddressesOperations, resourceGroupName As String, publicIpAddressName As String, Optional expand As String = null) As PublicIPAddress" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.PublicIPAddress" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.Get (operations, resourceGroupName, publicIpAddressName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.PublicIPAddress</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-153">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="69b71-154">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-154">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="69b71-155">Der Name des Subnetzes.</span><span class="sxs-lookup"><span data-stu-id="69b71-155">The name of the subnet.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="69b71-156">Wird erweitert, referenzierte Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="69b71-156">Expands referenced resources.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-157">Ruft die angegebene öffentliche IP-Adresse in einer angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-157">Gets the specified public IP address in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; GetAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; GetAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.GetAsync (operations, resourceGroupName, publicIpAddressName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="69b71-159">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-159">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="69b71-160">Der Name des Subnetzes.</span><span class="sxs-lookup"><span data-stu-id="69b71-160">The name of the subnet.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="69b71-161">Wird erweitert, referenzierte Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="69b71-161">Expands referenced resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="69b71-162">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="69b71-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-163">Ruft die angegebene öffentliche IP-Adresse in einer angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-163">Gets the specified public IP address in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVirtualMachineScaleSetPublicIPAddress">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.PublicIPAddress GetVirtualMachineScaleSetPublicIPAddress (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string ipConfigurationName, string publicIpAddressName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.PublicIPAddress GetVirtualMachineScaleSetPublicIPAddress(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string ipConfigurationName, string publicIpAddressName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.GetVirtualMachineScaleSetPublicIPAddress(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetVirtualMachineScaleSetPublicIPAddress (operations As IPublicIPAddressesOperations, resourceGroupName As String, virtualMachineScaleSetName As String, virtualmachineIndex As String, networkInterfaceName As String, ipConfigurationName As String, publicIpAddressName As String, Optional expand As String = null) As PublicIPAddress" />
      <MemberSignature Language="F#" Value="static member GetVirtualMachineScaleSetPublicIPAddress : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.PublicIPAddress" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.GetVirtualMachineScaleSetPublicIPAddress (operations, resourceGroupName, virtualMachineScaleSetName, virtualmachineIndex, networkInterfaceName, ipConfigurationName, publicIpAddressName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.PublicIPAddress</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="virtualmachineIndex" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="ipConfigurationName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-164">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="69b71-165">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-165">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="69b71-166">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-166">The name of the virtual machine scale set.</span></span>
            </param>
        <param name="virtualmachineIndex">
            <span data-ttu-id="69b71-167">Der Index des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="69b71-167">The virtual machine index.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="69b71-168">Der Name der Netzwerkschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="69b71-168">The name of the network interface.</span></span>
            </param>
        <param name="ipConfigurationName">
            <span data-ttu-id="69b71-169">Der Name der IP-Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="69b71-169">The name of the IP configuration.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="69b71-170">Der Name der öffentlichen IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="69b71-170">The name of the public IP Address.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="69b71-171">Wird erweitert, referenzierte Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="69b71-171">Expands referenced resources.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-172">Erhalten Sie die angegebene öffentliche IP-Adresse in einem VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-172">Get the specified public IP address in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVirtualMachineScaleSetPublicIPAddressAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; GetVirtualMachineScaleSetPublicIPAddressAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string ipConfigurationName, string publicIpAddressName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; GetVirtualMachineScaleSetPublicIPAddressAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string ipConfigurationName, string publicIpAddressName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.GetVirtualMachineScaleSetPublicIPAddressAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetVirtualMachineScaleSetPublicIPAddressAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.GetVirtualMachineScaleSetPublicIPAddressAsync (operations, resourceGroupName, virtualMachineScaleSetName, virtualmachineIndex, networkInterfaceName, ipConfigurationName, publicIpAddressName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;GetVirtualMachineScaleSetPublicIPAddressAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="virtualmachineIndex" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="ipConfigurationName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-173">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-173">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="69b71-174">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-174">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="69b71-175">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-175">The name of the virtual machine scale set.</span></span>
            </param>
        <param name="virtualmachineIndex">
            <span data-ttu-id="69b71-176">Der Index des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="69b71-176">The virtual machine index.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="69b71-177">Der Name der Netzwerkschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="69b71-177">The name of the network interface.</span></span>
            </param>
        <param name="ipConfigurationName">
            <span data-ttu-id="69b71-178">Der Name der IP-Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="69b71-178">The name of the IP configuration.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="69b71-179">Der Name der öffentlichen IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="69b71-179">The name of the public IP Address.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="69b71-180">Wird erweitert, referenzierte Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="69b71-180">Expands referenced resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="69b71-181">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="69b71-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-182">Erhalten Sie die angegebene öffentliche IP-Adresse in einem VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-182">Get the specified public IP address in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; List (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; List(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.List(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IPublicIPAddressesOperations, resourceGroupName As String) As IPage(Of PublicIPAddress)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-183">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-183">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="69b71-184">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-184">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-185">Ruft alle öffentliche IP-Adressen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-185">Gets all public IP addresses in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAll">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; ListAll (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; ListAll(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListAll(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAll (operations As IPublicIPAddressesOperations) As IPage(Of PublicIPAddress)" />
      <MemberSignature Language="F#" Value="static member ListAll : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListAll operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-186">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-186">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-187">Ruft den öffentlichen IP-Adressen in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="69b71-187">Gets all the public IP addresses in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;ListAllAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-188">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-188">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="69b71-189">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="69b71-189">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-190">Ruft den öffentlichen IP-Adressen in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="69b71-190">Gets all the public IP addresses in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; ListAllNext (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; ListAllNext(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListAllNext(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAllNext (operations As IPublicIPAddressesOperations, nextPageLink As String) As IPage(Of PublicIPAddress)" />
      <MemberSignature Language="F#" Value="static member ListAllNext : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListAllNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-191">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-191">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="69b71-192">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="69b71-192">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-193">Ruft den öffentlichen IP-Adressen in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="69b71-193">Gets all the public IP addresses in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;ListAllNextAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-194">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-194">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="69b71-195">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="69b71-195">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="69b71-196">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="69b71-196">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-197">Ruft den öffentlichen IP-Adressen in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="69b71-197">Gets all the public IP addresses in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-198">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-198">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="69b71-199">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-199">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="69b71-200">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="69b71-200">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-201">Ruft alle öffentliche IP-Adressen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-201">Gets all public IP addresses in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; ListNext (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; ListNext(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IPublicIPAddressesOperations, nextPageLink As String) As IPage(Of PublicIPAddress)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-202">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-202">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="69b71-203">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="69b71-203">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-204">Ruft alle öffentliche IP-Adressen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-204">Gets all public IP addresses in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;ListNextAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-205">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-205">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="69b71-206">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="69b71-206">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="69b71-207">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="69b71-207">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-208">Ruft alle öffentliche IP-Adressen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-208">Gets all public IP addresses in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetPublicIPAddresses">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; ListVirtualMachineScaleSetPublicIPAddresses (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; ListVirtualMachineScaleSetPublicIPAddresses(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetPublicIPAddresses(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListVirtualMachineScaleSetPublicIPAddresses (operations As IPublicIPAddressesOperations, resourceGroupName As String, virtualMachineScaleSetName As String) As IPage(Of PublicIPAddress)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetPublicIPAddresses : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetPublicIPAddresses (operations, resourceGroupName, virtualMachineScaleSetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-209">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-209">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="69b71-210">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-210">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="69b71-211">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-211">The name of the virtual machine scale set.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-212">Ruft Informationen über alle öffentlichen IP-Adressen auf einer VM-Skalierungsgruppe Ebene festzulegen.</span><span class="sxs-lookup"><span data-stu-id="69b71-212">Gets information about all public IP addresses on a virtual machine scale set level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetPublicIPAddressesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListVirtualMachineScaleSetPublicIPAddressesAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListVirtualMachineScaleSetPublicIPAddressesAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetPublicIPAddressesAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetPublicIPAddressesAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetPublicIPAddressesAsync (operations, resourceGroupName, virtualMachineScaleSetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;ListVirtualMachineScaleSetPublicIPAddressesAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-213">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-213">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="69b71-214">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-214">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="69b71-215">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-215">The name of the virtual machine scale set.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="69b71-216">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="69b71-216">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-217">Ruft Informationen über alle öffentlichen IP-Adressen auf einer VM-Skalierungsgruppe Ebene festzulegen.</span><span class="sxs-lookup"><span data-stu-id="69b71-217">Gets information about all public IP addresses on a virtual machine scale set level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetPublicIPAddressesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; ListVirtualMachineScaleSetPublicIPAddressesNext (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; ListVirtualMachineScaleSetPublicIPAddressesNext(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetPublicIPAddressesNext(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListVirtualMachineScaleSetPublicIPAddressesNext (operations As IPublicIPAddressesOperations, nextPageLink As String) As IPage(Of PublicIPAddress)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetPublicIPAddressesNext : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetPublicIPAddressesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-218">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-218">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="69b71-219">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="69b71-219">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-220">Ruft Informationen über alle öffentlichen IP-Adressen auf einer VM-Skalierungsgruppe Ebene festzulegen.</span><span class="sxs-lookup"><span data-stu-id="69b71-220">Gets information about all public IP addresses on a virtual machine scale set level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetPublicIPAddressesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListVirtualMachineScaleSetPublicIPAddressesNextAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListVirtualMachineScaleSetPublicIPAddressesNextAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetPublicIPAddressesNextAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetPublicIPAddressesNextAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetPublicIPAddressesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;ListVirtualMachineScaleSetPublicIPAddressesNextAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-221">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-221">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="69b71-222">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="69b71-222">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="69b71-223">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="69b71-223">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-224">Ruft Informationen über alle öffentlichen IP-Adressen auf einer VM-Skalierungsgruppe Ebene festzulegen.</span><span class="sxs-lookup"><span data-stu-id="69b71-224">Gets information about all public IP addresses on a virtual machine scale set level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetVMPublicIPAddresses">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; ListVirtualMachineScaleSetVMPublicIPAddresses (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string ipConfigurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; ListVirtualMachineScaleSetVMPublicIPAddresses(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string ipConfigurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetVMPublicIPAddresses(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListVirtualMachineScaleSetVMPublicIPAddresses (operations As IPublicIPAddressesOperations, resourceGroupName As String, virtualMachineScaleSetName As String, virtualmachineIndex As String, networkInterfaceName As String, ipConfigurationName As String) As IPage(Of PublicIPAddress)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetVMPublicIPAddresses : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetVMPublicIPAddresses (operations, resourceGroupName, virtualMachineScaleSetName, virtualmachineIndex, networkInterfaceName, ipConfigurationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="virtualmachineIndex" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="ipConfigurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-225">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-225">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="69b71-226">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-226">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="69b71-227">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-227">The name of the virtual machine scale set.</span></span>
            </param>
        <param name="virtualmachineIndex">
            <span data-ttu-id="69b71-228">Der Index des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="69b71-228">The virtual machine index.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="69b71-229">Der Name des Netzwerk-Schnittstelle.</span><span class="sxs-lookup"><span data-stu-id="69b71-229">The network interface name.</span></span>
            </param>
        <param name="ipConfigurationName">
            <span data-ttu-id="69b71-230">Der Name des IP-Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="69b71-230">The IP configuration name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-231">Ruft Informationen über alle öffentlichen IP-Adressen in eine IP-Konfiguration des virtuellen Computers in einem VM-Skalierungsgruppe ab.</span><span class="sxs-lookup"><span data-stu-id="69b71-231">Gets information about all public IP addresses in a virtual machine IP configuration in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetVMPublicIPAddressesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListVirtualMachineScaleSetVMPublicIPAddressesAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string ipConfigurationName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListVirtualMachineScaleSetVMPublicIPAddressesAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string ipConfigurationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetVMPublicIPAddressesAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetVMPublicIPAddressesAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetVMPublicIPAddressesAsync (operations, resourceGroupName, virtualMachineScaleSetName, virtualmachineIndex, networkInterfaceName, ipConfigurationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;ListVirtualMachineScaleSetVMPublicIPAddressesAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="virtualmachineIndex" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="ipConfigurationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-232">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-232">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="69b71-233">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-233">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="69b71-234">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-234">The name of the virtual machine scale set.</span></span>
            </param>
        <param name="virtualmachineIndex">
            <span data-ttu-id="69b71-235">Der Index des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="69b71-235">The virtual machine index.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="69b71-236">Der Name des Netzwerk-Schnittstelle.</span><span class="sxs-lookup"><span data-stu-id="69b71-236">The network interface name.</span></span>
            </param>
        <param name="ipConfigurationName">
            <span data-ttu-id="69b71-237">Der Name des IP-Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="69b71-237">The IP configuration name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="69b71-238">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="69b71-238">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-239">Ruft Informationen über alle öffentlichen IP-Adressen in eine IP-Konfiguration des virtuellen Computers in einem VM-Skalierungsgruppe ab.</span><span class="sxs-lookup"><span data-stu-id="69b71-239">Gets information about all public IP addresses in a virtual machine IP configuration in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetVMPublicIPAddressesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; ListVirtualMachineScaleSetVMPublicIPAddressesNext (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; ListVirtualMachineScaleSetVMPublicIPAddressesNext(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetVMPublicIPAddressesNext(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListVirtualMachineScaleSetVMPublicIPAddressesNext (operations As IPublicIPAddressesOperations, nextPageLink As String) As IPage(Of PublicIPAddress)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetVMPublicIPAddressesNext : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetVMPublicIPAddressesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-240">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-240">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="69b71-241">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="69b71-241">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-242">Ruft Informationen über alle öffentlichen IP-Adressen in eine IP-Konfiguration des virtuellen Computers in einem VM-Skalierungsgruppe ab.</span><span class="sxs-lookup"><span data-stu-id="69b71-242">Gets information about all public IP addresses in a virtual machine IP configuration in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetVMPublicIPAddressesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListVirtualMachineScaleSetVMPublicIPAddressesNextAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListVirtualMachineScaleSetVMPublicIPAddressesNextAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetVMPublicIPAddressesNextAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetVMPublicIPAddressesNextAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetVMPublicIPAddressesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;ListVirtualMachineScaleSetVMPublicIPAddressesNextAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-243">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-243">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="69b71-244">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="69b71-244">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="69b71-245">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="69b71-245">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-246">Ruft Informationen über alle öffentlichen IP-Adressen in eine IP-Konfiguration des virtuellen Computers in einem VM-Skalierungsgruppe ab.</span><span class="sxs-lookup"><span data-stu-id="69b71-246">Gets information about all public IP addresses in a virtual machine IP configuration in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.PublicIPAddress UpdateTags (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.PublicIPAddress UpdateTags(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.UpdateTags(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateTags (operations As IPublicIPAddressesOperations, resourceGroupName As String, publicIpAddressName As String, parameters As TagsObject) As PublicIPAddress" />
      <MemberSignature Language="F#" Value="static member UpdateTags : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.PublicIPAddress" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.UpdateTags (operations, resourceGroupName, publicIpAddressName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.PublicIPAddress</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-247">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-247">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="69b71-248">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-248">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="69b71-249">Der Name der öffentlichen IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="69b71-249">The name of the public IP address.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="69b71-250">Parameter, die zum Aktualisieren der öffentlichen IP-adresstags angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="69b71-250">Parameters supplied to update public IP address tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-251">Öffentliche IP-adresstags wird aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="69b71-251">Updates public IP address tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; UpdateTagsAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; UpdateTagsAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.UpdateTagsAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateTagsAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.UpdateTagsAsync (operations, resourceGroupName, publicIpAddressName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;UpdateTagsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="69b71-252">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="69b71-252">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="69b71-253">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="69b71-253">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="69b71-254">Der Name der öffentlichen IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="69b71-254">The name of the public IP address.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="69b71-255">Parameter, die zum Aktualisieren der öffentlichen IP-adresstags angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="69b71-255">Parameters supplied to update public IP address tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="69b71-256">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="69b71-256">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="69b71-257">Öffentliche IP-adresstags wird aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="69b71-257">Updates public IP address tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>