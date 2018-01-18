<Type Name="AppServicePlansOperationsExtensions" FullName="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AppServicePlansOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AppServicePlansOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AppServicePlansOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AppServicePlansOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1ad7a-101">Erweiterungsmethoden für AppServicePlansOperations.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-101">Extension methods for AppServicePlansOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.AppServicePlan BeginCreateOrUpdate (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.AppServicePlan appServicePlan);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.AppServicePlan BeginCreateOrUpdate(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServicePlan appServicePlan) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServicePlan)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * Microsoft.Azure.Management.WebSites.Models.AppServicePlan -&gt; Microsoft.Azure.Management.WebSites.Models.AppServicePlan" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, name, appServicePlan)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.AppServicePlan</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="appServicePlan" Type="Microsoft.Azure.Management.WebSites.Models.AppServicePlan" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-103">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-103">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-104">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-104">Name of the App Service plan.</span></span>
            </param>
        <param name="appServicePlan">
            <span data-ttu-id="1ad7a-105">Details zu den App-Dienst planen.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-105">Details of the App Service plan.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-106">Erstellt oder aktualisiert eine App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-106">Creates or updates an App Service Plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-107">Erstellt oder aktualisiert eine App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-107">Creates or updates an App Service Plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.AppServicePlan appServicePlan, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServicePlan appServicePlan, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServicePlan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * Microsoft.Azure.Management.WebSites.Models.AppServicePlan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, name, appServicePlan, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__59))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="appServicePlan" Type="Microsoft.Azure.Management.WebSites.Models.AppServicePlan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-109">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-109">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-110">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-110">Name of the App Service plan.</span></span>
            </param>
        <param name="appServicePlan">
            <span data-ttu-id="1ad7a-111">Details zu den App-Dienst planen.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-111">Details of the App Service plan.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-112">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-113">Erstellt oder aktualisiert eine App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-113">Creates or updates an App Service Plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-114">Erstellt oder aktualisiert eine App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-114">Creates or updates an App Service Plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.AppServicePlan CreateOrUpdate (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.AppServicePlan appServicePlan);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.AppServicePlan CreateOrUpdate(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServicePlan appServicePlan) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServicePlan)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * Microsoft.Azure.Management.WebSites.Models.AppServicePlan -&gt; Microsoft.Azure.Management.WebSites.Models.AppServicePlan" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, name, appServicePlan)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.AppServicePlan</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="appServicePlan" Type="Microsoft.Azure.Management.WebSites.Models.AppServicePlan" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-116">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-116">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-117">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-117">Name of the App Service plan.</span></span>
            </param>
        <param name="appServicePlan">
            <span data-ttu-id="1ad7a-118">Details zu den App-Dienst planen.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-118">Details of the App Service plan.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-119">Erstellt oder aktualisiert eine App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-119">Creates or updates an App Service Plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-120">Erstellt oder aktualisiert eine App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-120">Creates or updates an App Service Plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.AppServicePlan appServicePlan, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServicePlan appServicePlan, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServicePlan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * Microsoft.Azure.Management.WebSites.Models.AppServicePlan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, name, appServicePlan, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="appServicePlan" Type="Microsoft.Azure.Management.WebSites.Models.AppServicePlan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-121">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-121">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-122">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-122">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-123">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-123">Name of the App Service plan.</span></span>
            </param>
        <param name="appServicePlan">
            <span data-ttu-id="1ad7a-124">Details zu den App-Dienst planen.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-124">Details of the App Service plan.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-125">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-126">Erstellt oder aktualisiert eine App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-126">Creates or updates an App Service Plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-127">Erstellt oder aktualisiert eine App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-127">Creates or updates an App Service Plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateVnetRoute">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.VnetRoute CreateOrUpdateVnetRoute (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, Microsoft.Azure.Management.WebSites.Models.VnetRoute route);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.VnetRoute CreateOrUpdateVnetRoute(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, class Microsoft.Azure.Management.WebSites.Models.VnetRoute route) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.CreateOrUpdateVnetRoute(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.VnetRoute)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateVnetRoute (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, vnetName As String, routeName As String, route As VnetRoute) As VnetRoute" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateVnetRoute : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * Microsoft.Azure.Management.WebSites.Models.VnetRoute -&gt; Microsoft.Azure.Management.WebSites.Models.VnetRoute" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.CreateOrUpdateVnetRoute (operations, resourceGroupName, name, vnetName, routeName, route)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.VnetRoute</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="route" Type="Microsoft.Azure.Management.WebSites.Models.VnetRoute" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-128">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-129">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-129">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-130">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-130">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="1ad7a-131">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-131">Name of the Virtual Network.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="1ad7a-132">Der Name der Route Virtuellenetzwerk.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-132">Name of the Virtual Network route.</span></span>
            </param>
        <param name="route">
            <span data-ttu-id="1ad7a-133">Die Definition der Route Virtuellenetzwerk.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-133">Definition of the Virtual Network route.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-134">Erstellen Sie oder aktualisieren Sie eine Virtuellenetzwerk-Route in der App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-134">Create or update a Virtual Network route in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-135">Erstellen Sie oder aktualisieren Sie eine Virtuellenetzwerk-Route in der App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-135">Create or update a Virtual Network route in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateVnetRouteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt; CreateOrUpdateVnetRouteAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, Microsoft.Azure.Management.WebSites.Models.VnetRoute route, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt; CreateOrUpdateVnetRouteAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, class Microsoft.Azure.Management.WebSites.Models.VnetRoute route, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.CreateOrUpdateVnetRouteAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.VnetRoute,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateVnetRouteAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * Microsoft.Azure.Management.WebSites.Models.VnetRoute * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.CreateOrUpdateVnetRouteAsync (operations, resourceGroupName, name, vnetName, routeName, route, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;CreateOrUpdateVnetRouteAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="route" Type="Microsoft.Azure.Management.WebSites.Models.VnetRoute" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-136">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-137">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-137">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-138">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-138">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="1ad7a-139">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-139">Name of the Virtual Network.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="1ad7a-140">Der Name der Route Virtuellenetzwerk.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-140">Name of the Virtual Network route.</span></span>
            </param>
        <param name="route">
            <span data-ttu-id="1ad7a-141">Die Definition der Route Virtuellenetzwerk.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-141">Definition of the Virtual Network route.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-142">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-143">Erstellen Sie oder aktualisieren Sie eine Virtuellenetzwerk-Route in der App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-143">Create or update a Virtual Network route in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-144">Erstellen Sie oder aktualisieren Sie eine Virtuellenetzwerk-Route in der App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-144">Create or update a Virtual Network route in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.Delete(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IAppServicePlansOperations, resourceGroupName As String, name As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.Delete (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-145">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-145">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-146">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-146">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-147">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-147">Name of the App Service plan.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-148">Löschen Sie einen App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-148">Delete an App Service plan.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="1ad7a-149">Löschen Sie einen App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-149">Delete an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.DeleteAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;DeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-151">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-151">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-152">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-152">Name of the App Service plan.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-153">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-154">Löschen Sie einen App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-154">Delete an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-155">Löschen Sie einen App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-155">Delete an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteHybridConnection">
      <MemberSignature Language="C#" Value="public static void DeleteHybridConnection (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteHybridConnection(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.DeleteHybridConnection(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteHybridConnection (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, namespaceName As String, relayName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteHybridConnection : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.DeleteHybridConnection (operations, resourceGroupName, name, namespaceName, relayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-156">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-156">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-157">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-157">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-158">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-158">Name of the App Service plan.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="1ad7a-159">Name des Service Bus-Namespace.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-159">Name of the Service Bus namespace.</span></span>
            </param>
        <param name="relayName">
            <span data-ttu-id="1ad7a-160">Name des Service Bus-Relay.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-160">Name of the Service Bus relay.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-161">Löschen Sie eine Hybridverbindung verwendet, im App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-161">Delete a Hybrid Connection in use in an App Service plan.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="1ad7a-162">Löschen Sie eine Hybridverbindung verwendet, im App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-162">Delete a Hybrid Connection in use in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteHybridConnectionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteHybridConnectionAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteHybridConnectionAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.DeleteHybridConnectionAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteHybridConnectionAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.DeleteHybridConnectionAsync (operations, resourceGroupName, name, namespaceName, relayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;DeleteHybridConnectionAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-163">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-164">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-164">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-165">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-165">Name of the App Service plan.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="1ad7a-166">Name des Service Bus-Namespace.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-166">Name of the Service Bus namespace.</span></span>
            </param>
        <param name="relayName">
            <span data-ttu-id="1ad7a-167">Name des Service Bus-Relay.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-167">Name of the Service Bus relay.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-168">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-169">Löschen Sie eine Hybridverbindung verwendet, im App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-169">Delete a Hybrid Connection in use in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-170">Löschen Sie eine Hybridverbindung verwendet, im App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-170">Delete a Hybrid Connection in use in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteVnetRoute">
      <MemberSignature Language="C#" Value="public static void DeleteVnetRoute (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteVnetRoute(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.DeleteVnetRoute(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteVnetRoute (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, vnetName As String, routeName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteVnetRoute : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.DeleteVnetRoute (operations, resourceGroupName, name, vnetName, routeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-171">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-171">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-172">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-172">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-173">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-173">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="1ad7a-174">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-174">Name of the Virtual Network.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="1ad7a-175">Der Name der Route Virtuellenetzwerk.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-175">Name of the Virtual Network route.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-176">Löschen Sie eine Virtuellenetzwerk-Route in der App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-176">Delete a Virtual Network route in an App Service plan.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="1ad7a-177">Löschen Sie eine Virtuellenetzwerk-Route in der App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-177">Delete a Virtual Network route in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteVnetRouteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteVnetRouteAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteVnetRouteAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.DeleteVnetRouteAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteVnetRouteAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.DeleteVnetRouteAsync (operations, resourceGroupName, name, vnetName, routeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;DeleteVnetRouteAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-178">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-178">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-179">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-179">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-180">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-180">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="1ad7a-181">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-181">Name of the Virtual Network.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="1ad7a-182">Der Name der Route Virtuellenetzwerk.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-182">Name of the Virtual Network route.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-183">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-183">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-184">Löschen Sie eine Virtuellenetzwerk-Route in der App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-184">Delete a Virtual Network route in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-185">Löschen Sie eine Virtuellenetzwerk-Route in der App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-185">Delete a Virtual Network route in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.AppServicePlan Get (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.AppServicePlan Get(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.Get(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IAppServicePlansOperations, resourceGroupName As String, name As String) As AppServicePlan" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.AppServicePlan" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.Get (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.AppServicePlan</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-186">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-186">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-187">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-187">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-188">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-188">Name of the App Service plan.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-189">Abgerufen Sie App Service-Plan werden.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-189">Get an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-190">Abgerufen Sie App Service-Plan werden.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-190">Get an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; GetAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; GetAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-191">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-191">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-192">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-192">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-193">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-193">Name of the App Service plan.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-194">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-194">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-195">Abgerufen Sie App Service-Plan werden.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-195">Get an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-196">Abgerufen Sie App Service-Plan werden.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-196">Get an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHybridConnection">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.HybridConnection GetHybridConnection (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.HybridConnection GetHybridConnection(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetHybridConnection(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetHybridConnection (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, namespaceName As String, relayName As String) As HybridConnection" />
      <MemberSignature Language="F#" Value="static member GetHybridConnection : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.HybridConnection" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetHybridConnection (operations, resourceGroupName, name, namespaceName, relayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.HybridConnection</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-197">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-197">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-198">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-198">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-199">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-199">Name of the App Service plan.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="1ad7a-200">Name des Service Bus-Namespace.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-200">Name of the Service Bus namespace.</span></span>
            </param>
        <param name="relayName">
            <span data-ttu-id="1ad7a-201">Name des Service Bus-Relay.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-201">Name of the Service Bus relay.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-202">Abgerufen Sie eine Hybridverbindung verwendet in der App Service-Plan werden.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-202">Retrieve a Hybrid Connection in use in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-203">Abgerufen Sie eine Hybridverbindung verwendet in der App Service-Plan werden.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-203">Retrieve a Hybrid Connection in use in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHybridConnectionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt; GetHybridConnectionAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt; GetHybridConnectionAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetHybridConnectionAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetHybridConnectionAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetHybridConnectionAsync (operations, resourceGroupName, name, namespaceName, relayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;GetHybridConnectionAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-204">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-204">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-205">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-205">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-206">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-206">Name of the App Service plan.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="1ad7a-207">Name des Service Bus-Namespace.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-207">Name of the Service Bus namespace.</span></span>
            </param>
        <param name="relayName">
            <span data-ttu-id="1ad7a-208">Name des Service Bus-Relay.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-208">Name of the Service Bus relay.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-209">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-209">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-210">Abgerufen Sie eine Hybridverbindung verwendet in der App Service-Plan werden.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-210">Retrieve a Hybrid Connection in use in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-211">Abgerufen Sie eine Hybridverbindung verwendet in der App Service-Plan werden.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-211">Retrieve a Hybrid Connection in use in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHybridConnectionPlanLimit">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.HybridConnectionLimits GetHybridConnectionPlanLimit (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.HybridConnectionLimits GetHybridConnectionPlanLimit(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetHybridConnectionPlanLimit(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetHybridConnectionPlanLimit (operations As IAppServicePlansOperations, resourceGroupName As String, name As String) As HybridConnectionLimits" />
      <MemberSignature Language="F#" Value="static member GetHybridConnectionPlanLimit : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.HybridConnectionLimits" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetHybridConnectionPlanLimit (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.HybridConnectionLimits</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-212">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-212">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-213">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-213">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-214">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-214">Name of the App Service plan.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-215">Abgerufen Sie die maximale Anzahl von Hybridverbindungen darf in einer App Service-Plan werden.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-215">Get the maximum number of Hybrid Connections allowed in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-216">Abgerufen Sie die maximale Anzahl von Hybridverbindungen darf in einer App Service-Plan werden.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-216">Get the maximum number of Hybrid Connections allowed in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHybridConnectionPlanLimitAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnectionLimits&gt; GetHybridConnectionPlanLimitAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.HybridConnectionLimits&gt; GetHybridConnectionPlanLimitAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetHybridConnectionPlanLimitAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetHybridConnectionPlanLimitAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnectionLimits&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetHybridConnectionPlanLimitAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;GetHybridConnectionPlanLimitAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnectionLimits&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-217">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-217">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-218">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-218">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-219">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-219">Name of the App Service plan.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-220">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-220">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-221">Abgerufen Sie die maximale Anzahl von Hybridverbindungen darf in einer App Service-Plan werden.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-221">Get the maximum number of Hybrid Connections allowed in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-222">Abgerufen Sie die maximale Anzahl von Hybridverbindungen darf in einer App Service-Plan werden.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-222">Get the maximum number of Hybrid Connections allowed in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRouteForVnet">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt; GetRouteForVnet (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt; GetRouteForVnet(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetRouteForVnet(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetRouteForVnet (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, vnetName As String, routeName As String) As IList(Of VnetRoute)" />
      <MemberSignature Language="F#" Value="static member GetRouteForVnet : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetRouteForVnet (operations, resourceGroupName, name, vnetName, routeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-223">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-223">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-224">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-224">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-225">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-225">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="1ad7a-226">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-226">Name of the Virtual Network.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="1ad7a-227">Der Name der Route Virtuellenetzwerk.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-227">Name of the Virtual Network route.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-228">Abgerufen Sie eine Virtuellenetzwerk-Route in der App Service-Plan werden.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-228">Get a Virtual Network route in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-229">Abgerufen Sie eine Virtuellenetzwerk-Route in der App Service-Plan werden.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-229">Get a Virtual Network route in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRouteForVnetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;&gt; GetRouteForVnetAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;&gt; GetRouteForVnetAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetRouteForVnetAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetRouteForVnetAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetRouteForVnetAsync (operations, resourceGroupName, name, vnetName, routeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;GetRouteForVnetAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-230">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-230">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-231">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-231">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-232">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-232">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="1ad7a-233">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-233">Name of the Virtual Network.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="1ad7a-234">Der Name der Route Virtuellenetzwerk.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-234">Name of the Virtual Network route.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-235">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-235">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-236">Abgerufen Sie eine Virtuellenetzwerk-Route in der App Service-Plan werden.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-236">Get a Virtual Network route in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-237">Abgerufen Sie eine Virtuellenetzwerk-Route in der App Service-Plan werden.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-237">Get a Virtual Network route in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServerFarmSkus">
      <MemberSignature Language="C#" Value="public static object GetServerFarmSkus (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object GetServerFarmSkus(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetServerFarmSkus(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetServerFarmSkus (operations As IAppServicePlansOperations, resourceGroupName As String, name As String) As Object" />
      <MemberSignature Language="F#" Value="static member GetServerFarmSkus : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string -&gt; obj" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetServerFarmSkus (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-238">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-238">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-239">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-239">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-240">Name des App Service-Plan</span><span class="sxs-lookup"><span data-stu-id="1ad7a-240">Name of App Service Plan</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-241">Ruft alle auswählbaren Sku für eine bestimmte App Service-Plan</span><span class="sxs-lookup"><span data-stu-id="1ad7a-241">Gets all selectable sku's for a given App Service Plan</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-242">Ruft alle auswählbaren Sku für eine bestimmte App Service-Plan</span><span class="sxs-lookup"><span data-stu-id="1ad7a-242">Gets all selectable sku's for a given App Service Plan</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServerFarmSkusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; GetServerFarmSkusAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; GetServerFarmSkusAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetServerFarmSkusAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetServerFarmSkusAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetServerFarmSkusAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;GetServerFarmSkusAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-243">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-243">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-244">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-244">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-245">Name des App Service-Plan</span><span class="sxs-lookup"><span data-stu-id="1ad7a-245">Name of App Service Plan</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-246">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-246">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-247">Ruft alle auswählbaren Sku für eine bestimmte App Service-Plan</span><span class="sxs-lookup"><span data-stu-id="1ad7a-247">Gets all selectable sku's for a given App Service Plan</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-248">Ruft alle auswählbaren Sku für eine bestimmte App Service-Plan</span><span class="sxs-lookup"><span data-stu-id="1ad7a-248">Gets all selectable sku's for a given App Service Plan</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVnetFromServerFarm">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.VnetInfo GetVnetFromServerFarm (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.VnetInfo GetVnetFromServerFarm(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetVnetFromServerFarm(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetVnetFromServerFarm (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, vnetName As String) As VnetInfo" />
      <MemberSignature Language="F#" Value="static member GetVnetFromServerFarm : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.VnetInfo" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetVnetFromServerFarm (operations, resourceGroupName, name, vnetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.VnetInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-249">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-249">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-250">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-250">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-251">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-251">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="1ad7a-252">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-252">Name of the Virtual Network.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-253">Rufen Sie ein virtuelles Netzwerk mit der App Service-Plan zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-253">Get a Virtual Network associated with an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-254">Rufen Sie ein virtuelles Netzwerk mit der App Service-Plan zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-254">Get a Virtual Network associated with an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVnetFromServerFarmAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetInfo&gt; GetVnetFromServerFarmAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetInfo&gt; GetVnetFromServerFarmAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetVnetFromServerFarmAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetVnetFromServerFarmAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetInfo&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetVnetFromServerFarmAsync (operations, resourceGroupName, name, vnetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;GetVnetFromServerFarmAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-255">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-255">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-256">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-256">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-257">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-257">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="1ad7a-258">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-258">Name of the Virtual Network.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-259">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-259">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-260">Rufen Sie ein virtuelles Netzwerk mit der App Service-Plan zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-260">Get a Virtual Network associated with an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-261">Rufen Sie ein virtuelles Netzwerk mit der App Service-Plan zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-261">Get a Virtual Network associated with an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVnetGateway">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.VnetGateway GetVnetGateway (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.VnetGateway GetVnetGateway(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetVnetGateway(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetVnetGateway (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, vnetName As String, gatewayName As String) As VnetGateway" />
      <MemberSignature Language="F#" Value="static member GetVnetGateway : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.VnetGateway" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetVnetGateway (operations, resourceGroupName, name, vnetName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.VnetGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-262">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-262">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-263">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-263">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-264">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-264">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="1ad7a-265">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-265">Name of the Virtual Network.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="1ad7a-266">Der Name des Gateways.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-266">Name of the gateway.</span></span> <span data-ttu-id="1ad7a-267">Nur das 'primary' Gateway wird unterstützt.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-267">Only the 'primary' gateway is supported.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-268">Rufen Sie ein Gateway des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-268">Get a Virtual Network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-269">Rufen Sie ein Gateway des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-269">Get a Virtual Network gateway.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVnetGatewayAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetGateway&gt; GetVnetGatewayAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string gatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetGateway&gt; GetVnetGatewayAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string gatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetVnetGatewayAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetVnetGatewayAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetGateway&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetVnetGatewayAsync (operations, resourceGroupName, name, vnetName, gatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;GetVnetGatewayAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-270">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-270">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-271">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-271">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-272">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-272">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="1ad7a-273">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-273">Name of the Virtual Network.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="1ad7a-274">Der Name des Gateways.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-274">Name of the gateway.</span></span> <span data-ttu-id="1ad7a-275">Nur das 'primary' Gateway wird unterstützt.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-275">Only the 'primary' gateway is supported.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-276">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-276">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-277">Rufen Sie ein Gateway des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-277">Get a Virtual Network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-278">Rufen Sie ein Gateway des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-278">Get a Virtual Network gateway.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; List (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, Nullable&lt;bool&gt; detailed = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; List(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, valuetype System.Nullable`1&lt;bool&gt; detailed) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.List(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IAppServicePlansOperations, Optional detailed As Nullable(Of Boolean) = null) As IPage(Of AppServicePlan)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.List (operations, detailed)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="detailed" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-279">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-279">The operations group for this extension method.</span></span>
            </param>
        <param name="detailed">
            <span data-ttu-id="1ad7a-280">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; alle Eigenschaften der App Service-Plan zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-280">Specify &lt;code&gt;true&lt;/code&gt; to return all App Service plan properties.</span></span> <span data-ttu-id="1ad7a-281">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;, wobei eine Teilmenge der Eigenschaften zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-281">The default is &lt;code&gt;false&lt;/code&gt;, which returns a subset of the properties.</span></span>
            <span data-ttu-id="1ad7a-282">Abrufen aller Eigenschaften kann es sich um die API-Latenzzeit erhöhen.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-282">Retrieval of all properties may increase the API latency.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-283">Ruft alle App Service-Pläne für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-283">Get all App Service plans for a subcription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-284">Ruft alle App Service-Pläne für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-284">Get all App Service plans for a subcription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt; ListAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, Nullable&lt;bool&gt; detailed = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt; ListAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, valuetype System.Nullable`1&lt;bool&gt; detailed, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListAsync (operations, detailed, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="detailed" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-285">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-285">The operations group for this extension method.</span></span>
            </param>
        <param name="detailed">
            <span data-ttu-id="1ad7a-286">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; alle Eigenschaften der App Service-Plan zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-286">Specify &lt;code&gt;true&lt;/code&gt; to return all App Service plan properties.</span></span> <span data-ttu-id="1ad7a-287">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;, wobei eine Teilmenge der Eigenschaften zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-287">The default is &lt;code&gt;false&lt;/code&gt;, which returns a subset of the properties.</span></span>
            <span data-ttu-id="1ad7a-288">Abrufen aller Eigenschaften kann es sich um die API-Latenzzeit erhöhen.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-288">Retrieval of all properties may increase the API latency.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-289">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-289">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-290">Ruft alle App Service-Pläne für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-290">Get all App Service plans for a subcription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-291">Ruft alle App Service-Pläne für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-291">Get all App Service plans for a subcription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; ListByResourceGroup (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; ListByResourceGroup(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IAppServicePlansOperations, resourceGroupName As String) As IPage(Of AppServicePlan)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-292">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-292">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-293">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-293">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-294">Ruft alle App Service-Pläne in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-294">Get all App Service plans in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-295">Ruft alle App Service-Pläne in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-295">Get all App Service plans in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-296">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-296">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-297">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-297">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-298">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-298">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-299">Ruft alle App Service-Pläne in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-299">Get all App Service plans in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-300">Ruft alle App Service-Pläne in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-300">Get all App Service plans in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IAppServicePlansOperations, nextPageLink As String) As IPage(Of AppServicePlan)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-301">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-301">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1ad7a-302">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-302">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-303">Ruft alle App Service-Pläne in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-303">Get all App Service plans in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-304">Ruft alle App Service-Pläne in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-304">Get all App Service plans in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__63))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-305">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-305">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1ad7a-306">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-306">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-307">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-307">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-308">Ruft alle App Service-Pläne in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-308">Get all App Service plans in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-309">Ruft alle App Service-Pläne in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-309">Get all App Service plans in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCapabilities">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Capability&gt; ListCapabilities (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Capability&gt; ListCapabilities(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListCapabilities(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListCapabilities (operations As IAppServicePlansOperations, resourceGroupName As String, name As String) As IList(Of Capability)" />
      <MemberSignature Language="F#" Value="static member ListCapabilities : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Capability&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListCapabilities (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Capability&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-310">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-310">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-311">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-311">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-312">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-312">Name of the App Service plan.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-313">Liste aller Funktionen des App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-313">List all capabilities of an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-314">Liste aller Funktionen des App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-314">List all capabilities of an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCapabilitiesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Capability&gt;&gt; ListCapabilitiesAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Capability&gt;&gt; ListCapabilitiesAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListCapabilitiesAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListCapabilitiesAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Capability&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListCapabilitiesAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListCapabilitiesAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Capability&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-315">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-315">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-316">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-316">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-317">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-317">Name of the App Service plan.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-318">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-318">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-319">Liste aller Funktionen des App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-319">List all capabilities of an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-320">Liste aller Funktionen des App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-320">List all capabilities of an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHybridConnectionKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.HybridConnectionKey ListHybridConnectionKeys (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.HybridConnectionKey ListHybridConnectionKeys(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListHybridConnectionKeys(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListHybridConnectionKeys (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, namespaceName As String, relayName As String) As HybridConnectionKey" />
      <MemberSignature Language="F#" Value="static member ListHybridConnectionKeys : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.HybridConnectionKey" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListHybridConnectionKeys (operations, resourceGroupName, name, namespaceName, relayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.HybridConnectionKey</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-321">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-321">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-322">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-322">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-323">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-323">Name of the App Service plan.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="1ad7a-324">Der Name des Service Bus-Namespace.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-324">The name of the Service Bus namespace.</span></span>
            </param>
        <param name="relayName">
            <span data-ttu-id="1ad7a-325">Der Name des Service Bus-Relay.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-325">The name of the Service Bus relay.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-326">Ruft den Send-Schlüsselnamen und den Wert, der eine Hybridverbindung.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-326">Get the send key name and value of a Hybrid Connection.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-327">Ruft den Send-Schlüsselnamen und den Wert, der eine Hybridverbindung.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-327">Get the send key name and value of a Hybrid Connection.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHybridConnectionKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnectionKey&gt; ListHybridConnectionKeysAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.HybridConnectionKey&gt; ListHybridConnectionKeysAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListHybridConnectionKeysAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListHybridConnectionKeysAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnectionKey&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListHybridConnectionKeysAsync (operations, resourceGroupName, name, namespaceName, relayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListHybridConnectionKeysAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnectionKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-328">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-328">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-329">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-329">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-330">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-330">Name of the App Service plan.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="1ad7a-331">Der Name des Service Bus-Namespace.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-331">The name of the Service Bus namespace.</span></span>
            </param>
        <param name="relayName">
            <span data-ttu-id="1ad7a-332">Der Name des Service Bus-Relay.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-332">The name of the Service Bus relay.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-333">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-333">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-334">Ruft den Send-Schlüsselnamen und den Wert, der eine Hybridverbindung.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-334">Get the send key name and value of a Hybrid Connection.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-335">Ruft den Send-Schlüsselnamen und den Wert, der eine Hybridverbindung.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-335">Get the send key name and value of a Hybrid Connection.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHybridConnections">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt; ListHybridConnections (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt; ListHybridConnections(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListHybridConnections(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListHybridConnections (operations As IAppServicePlansOperations, resourceGroupName As String, name As String) As IPage(Of HybridConnection)" />
      <MemberSignature Language="F#" Value="static member ListHybridConnections : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListHybridConnections (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-336">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-336">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-337">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-337">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-338">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-338">Name of the App Service plan.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-339">Abgerufen Sie in der App Service-Plan werden alle Hybridverbindungen verwendet.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-339">Retrieve all Hybrid Connections in use in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-340">Abgerufen Sie in der App Service-Plan werden alle Hybridverbindungen verwendet.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-340">Retrieve all Hybrid Connections in use in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHybridConnectionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;&gt; ListHybridConnectionsAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;&gt; ListHybridConnectionsAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListHybridConnectionsAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListHybridConnectionsAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListHybridConnectionsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListHybridConnectionsAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-341">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-341">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-342">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-342">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-343">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-343">Name of the App Service plan.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-344">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-344">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-345">Abgerufen Sie in der App Service-Plan werden alle Hybridverbindungen verwendet.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-345">Retrieve all Hybrid Connections in use in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-346">Abgerufen Sie in der App Service-Plan werden alle Hybridverbindungen verwendet.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-346">Retrieve all Hybrid Connections in use in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHybridConnectionsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt; ListHybridConnectionsNext (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt; ListHybridConnectionsNext(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListHybridConnectionsNext(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListHybridConnectionsNext (operations As IAppServicePlansOperations, nextPageLink As String) As IPage(Of HybridConnection)" />
      <MemberSignature Language="F#" Value="static member ListHybridConnectionsNext : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListHybridConnectionsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-347">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-347">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1ad7a-348">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-348">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-349">Abgerufen Sie in der App Service-Plan werden alle Hybridverbindungen verwendet.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-349">Retrieve all Hybrid Connections in use in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-350">Abgerufen Sie in der App Service-Plan werden alle Hybridverbindungen verwendet.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-350">Retrieve all Hybrid Connections in use in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHybridConnectionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;&gt; ListHybridConnectionsNextAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;&gt; ListHybridConnectionsNextAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListHybridConnectionsNextAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListHybridConnectionsNextAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListHybridConnectionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListHybridConnectionsNextAsync&gt;d__67))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-351">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-351">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1ad7a-352">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-352">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-353">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-353">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-354">Abgerufen Sie in der App Service-Plan werden alle Hybridverbindungen verwendet.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-354">Retrieve all Hybrid Connections in use in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-355">Abgerufen Sie in der App Service-Plan werden alle Hybridverbindungen verwendet.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-355">Retrieve all Hybrid Connections in use in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefintions">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt; ListMetricDefintions (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt; ListMetricDefintions(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetricDefintions(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetricDefintions (operations As IAppServicePlansOperations, resourceGroupName As String, name As String) As IPage(Of ResourceMetricDefinition)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefintions : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetricDefintions (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-356">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-356">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-357">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-357">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-358">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-358">Name of the App Service plan.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-359">Abrufen von Metriken, die abgefragt werden können für ein App Service-Plan und ihre Definitionen.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-359">Get metrics that can be queried for an App Service plan, and their definitions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-360">Abrufen von Metriken, die abgefragt werden können für ein App Service-Plan und ihre Definitionen.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-360">Get metrics that can be queried for an App Service plan, and their definitions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefintionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt; ListMetricDefintionsAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt; ListMetricDefintionsAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetricDefintionsAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefintionsAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetricDefintionsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListMetricDefintionsAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-361">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-361">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-362">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-362">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-363">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-363">Name of the App Service plan.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-364">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-364">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-365">Abrufen von Metriken, die abgefragt werden können für ein App Service-Plan und ihre Definitionen.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-365">Get metrics that can be queried for an App Service plan, and their definitions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-366">Abrufen von Metriken, die abgefragt werden können für ein App Service-Plan und ihre Definitionen.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-366">Get metrics that can be queried for an App Service plan, and their definitions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefintionsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt; ListMetricDefintionsNext (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt; ListMetricDefintionsNext(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetricDefintionsNext(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetricDefintionsNext (operations As IAppServicePlansOperations, nextPageLink As String) As IPage(Of ResourceMetricDefinition)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefintionsNext : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetricDefintionsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-367">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-367">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1ad7a-368">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-368">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-369">Abrufen von Metriken, die abgefragt werden können für ein App Service-Plan und ihre Definitionen.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-369">Get metrics that can be queried for an App Service plan, and their definitions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-370">Abrufen von Metriken, die abgefragt werden können für ein App Service-Plan und ihre Definitionen.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-370">Get metrics that can be queried for an App Service plan, and their definitions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefintionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt; ListMetricDefintionsNextAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt; ListMetricDefintionsNextAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetricDefintionsNextAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefintionsNextAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetricDefintionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListMetricDefintionsNextAsync&gt;d__69))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-371">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-371">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1ad7a-372">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-372">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-373">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-373">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-374">Abrufen von Metriken, die abgefragt werden können für ein App Service-Plan und ihre Definitionen.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-374">Get metrics that can be queried for an App Service plan, and their definitions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-375">Abrufen von Metriken, die abgefragt werden können für ein App Service-Plan und ihre Definitionen.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-375">Get metrics that can be queried for an App Service plan, and their definitions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetrics">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt; ListMetrics (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, Nullable&lt;bool&gt; details = null, string filter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt; ListMetrics(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; details, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetrics(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetrics (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, Optional details As Nullable(Of Boolean) = null, Optional filter As String = null) As IPage(Of ResourceMetric)" />
      <MemberSignature Language="F#" Value="static member ListMetrics : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * Nullable&lt;bool&gt; * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetrics (operations, resourceGroupName, name, details, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-376">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-376">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-377">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-377">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-378">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-378">Name of the App Service plan.</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="1ad7a-379">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; Instanzdetails einschließen.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-379">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span> <span data-ttu-id="1ad7a-380">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-380">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="1ad7a-381">Geben Sie nur Verwendungen/Metriken-im Filter angegebenen zurück.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-381">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="1ad7a-382">Filter entspricht OData-Syntax.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-382">Filter conforms to odata syntax.</span></span> <span data-ttu-id="1ad7a-383">Beispiel: $filter = (name.value Eq "Metric1" oder name.value Eq "Metric2") und StartTime-Eq "2014-01-01T00:00:00Z" und EndTime-Eq "2014-12-31T23:59:59Z" und die Dauer der timegrain-Wert-Eq "[Stunde | Minute | Tag] ".</span><span class="sxs-lookup"><span data-stu-id="1ad7a-383">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-384">Abrufen von Metriken für einen App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-384">Get metrics for an App Serice plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-385">Abrufen von Metriken für einen App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-385">Get metrics for an App Serice plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt; ListMetricsAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, Nullable&lt;bool&gt; details = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt; ListMetricsAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; details, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetricsAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetricsAsync (operations, resourceGroupName, name, details, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListMetricsAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-386">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-386">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-387">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-387">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-388">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-388">Name of the App Service plan.</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="1ad7a-389">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; Instanzdetails einschließen.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-389">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span> <span data-ttu-id="1ad7a-390">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-390">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="1ad7a-391">Geben Sie nur Verwendungen/Metriken-im Filter angegebenen zurück.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-391">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="1ad7a-392">Filter entspricht OData-Syntax.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-392">Filter conforms to odata syntax.</span></span> <span data-ttu-id="1ad7a-393">Beispiel: $filter = (name.value Eq "Metric1" oder name.value Eq "Metric2") und StartTime-Eq "2014-01-01T00:00:00Z" und EndTime-Eq "2014-12-31T23:59:59Z" und die Dauer der timegrain-Wert-Eq "[Stunde | Minute | Tag] ".</span><span class="sxs-lookup"><span data-stu-id="1ad7a-393">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-394">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-394">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-395">Abrufen von Metriken für einen App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-395">Get metrics for an App Serice plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-396">Abrufen von Metriken für einen App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-396">Get metrics for an App Serice plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt; ListMetricsNext (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt; ListMetricsNext(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetricsNext(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetricsNext (operations As IAppServicePlansOperations, nextPageLink As String) As IPage(Of ResourceMetric)" />
      <MemberSignature Language="F#" Value="static member ListMetricsNext : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetricsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-397">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-397">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1ad7a-398">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-398">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-399">Abrufen von Metriken für einen App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-399">Get metrics for an App Serice plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-400">Abrufen von Metriken für einen App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-400">Get metrics for an App Serice plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt; ListMetricsNextAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt; ListMetricsNextAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetricsNextAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsNextAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetricsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListMetricsNextAsync&gt;d__71))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-401">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-401">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1ad7a-402">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-402">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-403">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-403">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-404">Abrufen von Metriken für einen App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-404">Get metrics for an App Serice plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-405">Abrufen von Metriken für einen App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-405">Get metrics for an App Serice plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; ListNext (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; ListNext(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListNext(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IAppServicePlansOperations, nextPageLink As String) As IPage(Of AppServicePlan)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-406">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-406">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1ad7a-407">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-407">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-408">Ruft alle App Service-Pläne für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-408">Get all App Service plans for a subcription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-409">Ruft alle App Service-Pläne für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-409">Get all App Service plans for a subcription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListNextAsync&gt;d__61))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-410">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-410">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1ad7a-411">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-411">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-412">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-412">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-413">Ruft alle App Service-Pläne für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-413">Get all App Service plans for a subcription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-414">Ruft alle App Service-Pläne für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-414">Get all App Service plans for a subcription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRoutesForVnet">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt; ListRoutesForVnet (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt; ListRoutesForVnet(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListRoutesForVnet(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRoutesForVnet (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, vnetName As String) As IList(Of VnetRoute)" />
      <MemberSignature Language="F#" Value="static member ListRoutesForVnet : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListRoutesForVnet (operations, resourceGroupName, name, vnetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-415">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-415">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-416">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-416">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-417">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-417">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="1ad7a-418">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-418">Name of the Virtual Network.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-419">Erhalten Sie alle Routen, die im App Service-Plan ein virtuelles Netzwerk zugeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-419">Get all routes that are associated with a Virtual Network in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-420">Erhalten Sie alle Routen, die im App Service-Plan ein virtuelles Netzwerk zugeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-420">Get all routes that are associated with a Virtual Network in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRoutesForVnetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;&gt; ListRoutesForVnetAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;&gt; ListRoutesForVnetAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListRoutesForVnetAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRoutesForVnetAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListRoutesForVnetAsync (operations, resourceGroupName, name, vnetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListRoutesForVnetAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-421">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-421">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-422">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-422">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-423">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-423">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="1ad7a-424">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-424">Name of the Virtual Network.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-425">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-425">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-426">Erhalten Sie alle Routen, die im App Service-Plan ein virtuelles Netzwerk zugeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-426">Get all routes that are associated with a Virtual Network in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-427">Erhalten Sie alle Routen, die im App Service-Plan ein virtuelles Netzwerk zugeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-427">Get all routes that are associated with a Virtual Network in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsages">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt; ListUsages (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string filter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt; ListUsages(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListUsages(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListUsages (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, Optional filter As String = null) As IPage(Of CsmUsageQuota)" />
      <MemberSignature Language="F#" Value="static member ListUsages : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListUsages (operations, resourceGroupName, name, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-428">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-428">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-429">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-429">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-430">Name des App Service-Plan</span><span class="sxs-lookup"><span data-stu-id="1ad7a-430">Name of App Service Plan</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="1ad7a-431">Geben Sie nur Verwendungen/Metriken-im Filter angegebenen zurück.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-431">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="1ad7a-432">Filter entspricht OData-Syntax.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-432">Filter conforms to odata syntax.</span></span> <span data-ttu-id="1ad7a-433">Beispiel: $filter = (name.value Eq "Metric1" oder name.value Eq "Metric2").</span><span class="sxs-lookup"><span data-stu-id="1ad7a-433">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2').</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-434">Ruft die Nutzungsinformationen für Server-farm</span><span class="sxs-lookup"><span data-stu-id="1ad7a-434">Gets server farm usage information</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-435">Ruft die Nutzungsinformationen für Server-farm</span><span class="sxs-lookup"><span data-stu-id="1ad7a-435">Gets server farm usage information</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsagesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt; ListUsagesAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt; ListUsagesAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListUsagesAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListUsagesAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListUsagesAsync (operations, resourceGroupName, name, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListUsagesAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-436">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-436">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-437">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-437">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-438">Name des App Service-Plan</span><span class="sxs-lookup"><span data-stu-id="1ad7a-438">Name of App Service Plan</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="1ad7a-439">Geben Sie nur Verwendungen/Metriken-im Filter angegebenen zurück.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-439">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="1ad7a-440">Filter entspricht OData-Syntax.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-440">Filter conforms to odata syntax.</span></span> <span data-ttu-id="1ad7a-441">Beispiel: $filter = (name.value Eq "Metric1" oder name.value Eq "Metric2").</span><span class="sxs-lookup"><span data-stu-id="1ad7a-441">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2').</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-442">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-442">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-443">Ruft die Nutzungsinformationen für Server-farm</span><span class="sxs-lookup"><span data-stu-id="1ad7a-443">Gets server farm usage information</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-444">Ruft die Nutzungsinformationen für Server-farm</span><span class="sxs-lookup"><span data-stu-id="1ad7a-444">Gets server farm usage information</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsagesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt; ListUsagesNext (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt; ListUsagesNext(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListUsagesNext(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListUsagesNext (operations As IAppServicePlansOperations, nextPageLink As String) As IPage(Of CsmUsageQuota)" />
      <MemberSignature Language="F#" Value="static member ListUsagesNext : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListUsagesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-445">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-445">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1ad7a-446">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-446">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-447">Ruft die Nutzungsinformationen für Server-farm</span><span class="sxs-lookup"><span data-stu-id="1ad7a-447">Gets server farm usage information</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-448">Ruft die Nutzungsinformationen für Server-farm</span><span class="sxs-lookup"><span data-stu-id="1ad7a-448">Gets server farm usage information</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsagesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt; ListUsagesNextAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt; ListUsagesNextAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListUsagesNextAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListUsagesNextAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListUsagesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListUsagesNextAsync&gt;d__75))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-449">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-449">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1ad7a-450">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-450">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-451">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-451">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-452">Ruft die Nutzungsinformationen für Server-farm</span><span class="sxs-lookup"><span data-stu-id="1ad7a-452">Gets server farm usage information</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-453">Ruft die Nutzungsinformationen für Server-farm</span><span class="sxs-lookup"><span data-stu-id="1ad7a-453">Gets server farm usage information</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVnets">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetInfo&gt; ListVnets (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetInfo&gt; ListVnets(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListVnets(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListVnets (operations As IAppServicePlansOperations, resourceGroupName As String, name As String) As IList(Of VnetInfo)" />
      <MemberSignature Language="F#" Value="static member ListVnets : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetInfo&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListVnets (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-454">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-454">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-455">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-455">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-456">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-456">Name of the App Service plan.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-457">Rufen Sie aller virtuellen Netzwerke, die App Service-Plan zugeordnet ab.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-457">Get all Virtual Networks associated with an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-458">Rufen Sie aller virtuellen Netzwerke, die App Service-Plan zugeordnet ab.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-458">Get all Virtual Networks associated with an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVnetsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetInfo&gt;&gt; ListVnetsAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetInfo&gt;&gt; ListVnetsAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListVnetsAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVnetsAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetInfo&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListVnetsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListVnetsAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-459">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-459">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-460">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-460">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-461">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-461">Name of the App Service plan.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-462">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-462">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-463">Rufen Sie aller virtuellen Netzwerke, die App Service-Plan zugeordnet ab.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-463">Get all Virtual Networks associated with an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-464">Rufen Sie aller virtuellen Netzwerke, die App Service-Plan zugeordnet ab.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-464">Get all Virtual Networks associated with an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebApps">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt; ListWebApps (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string skipToken = null, string filter = null, string top = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt; ListWebApps(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string skipToken, string filter, string top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebApps(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListWebApps (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, Optional skipToken As String = null, Optional filter As String = null, Optional top As String = null) As IPage(Of Site)" />
      <MemberSignature Language="F#" Value="static member ListWebApps : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebApps (operations, resourceGroupName, name, skipToken, filter, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="skipToken" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="top" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-465">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-465">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-466">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-466">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-467">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-467">Name of the App Service plan.</span></span>
            </param>
        <param name="skipToken">
            <span data-ttu-id="1ad7a-468">Fahren Sie mit einer Web-app in der Liste der Webapps app Service-Plan zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-468">Skip to a web app in the list of webapps associated with app service plan.</span></span>
            <span data-ttu-id="1ad7a-469">Wenn angegeben, enthält die resultierende Liste Web-apps (einschließlich) dem SkipToken ab.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-469">If specified, the resulting list will contain web apps starting from (including) the skipToken.</span></span> <span data-ttu-id="1ad7a-470">Andernfalls enthält die resultierende Liste Web-apps, ab dem Anfang der Liste</span><span class="sxs-lookup"><span data-stu-id="1ad7a-470">Otherwise, the resulting list contains web apps from the start of the list</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="1ad7a-471">Unterstützte Filter: $filter = State Eq ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-471">Supported filter: $filter=state eq running.</span></span> <span data-ttu-id="1ad7a-472">Gibt nur Web-apps, die derzeit ausgeführt werden</span><span class="sxs-lookup"><span data-stu-id="1ad7a-472">Returns only web apps that are currently running</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="1ad7a-473">Liste der Seitengröße.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-473">List page size.</span></span> <span data-ttu-id="1ad7a-474">Wenn angegeben, werden die Ergebnisse seitenweise angegeben.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-474">If specified, results are paged.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-475">Erhalten Sie alle apps, die App Service-Plan zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-475">Get all apps associated with an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-476">Erhalten Sie alle apps, die App Service-Plan zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-476">Get all apps associated with an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt; ListWebAppsAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string skipToken = null, string filter = null, string top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt; ListWebAppsAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string skipToken, string filter, string top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebAppsAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebAppsAsync (operations, resourceGroupName, name, skipToken, filter, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListWebAppsAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="skipToken" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="top" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-477">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-477">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-478">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-478">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-479">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-479">Name of the App Service plan.</span></span>
            </param>
        <param name="skipToken">
            <span data-ttu-id="1ad7a-480">Fahren Sie mit einer Web-app in der Liste der Webapps app Service-Plan zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-480">Skip to a web app in the list of webapps associated with app service plan.</span></span>
            <span data-ttu-id="1ad7a-481">Wenn angegeben, enthält die resultierende Liste Web-apps (einschließlich) dem SkipToken ab.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-481">If specified, the resulting list will contain web apps starting from (including) the skipToken.</span></span> <span data-ttu-id="1ad7a-482">Andernfalls enthält die resultierende Liste Web-apps, ab dem Anfang der Liste</span><span class="sxs-lookup"><span data-stu-id="1ad7a-482">Otherwise, the resulting list contains web apps from the start of the list</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="1ad7a-483">Unterstützte Filter: $filter = State Eq ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-483">Supported filter: $filter=state eq running.</span></span> <span data-ttu-id="1ad7a-484">Gibt nur Web-apps, die derzeit ausgeführt werden</span><span class="sxs-lookup"><span data-stu-id="1ad7a-484">Returns only web apps that are currently running</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="1ad7a-485">Liste der Seitengröße.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-485">List page size.</span></span> <span data-ttu-id="1ad7a-486">Wenn angegeben, werden die Ergebnisse seitenweise angegeben.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-486">If specified, results are paged.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-487">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-487">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-488">Erhalten Sie alle apps, die App Service-Plan zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-488">Get all apps associated with an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-489">Erhalten Sie alle apps, die App Service-Plan zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-489">Get all apps associated with an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsByHybridConnection">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;string&gt; ListWebAppsByHybridConnection (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;string&gt; ListWebAppsByHybridConnection(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebAppsByHybridConnection(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListWebAppsByHybridConnection (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, namespaceName As String, relayName As String) As IPage(Of String)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsByHybridConnection : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;string&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebAppsByHybridConnection (operations, resourceGroupName, name, namespaceName, relayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-490">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-490">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-491">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-491">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-492">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-492">Name of the App Service plan.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="1ad7a-493">Name der Hybridverbindung-Namespace.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-493">Name of the Hybrid Connection namespace.</span></span>
            </param>
        <param name="relayName">
            <span data-ttu-id="1ad7a-494">Der Name der Hybridverbindung Relay.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-494">Name of the Hybrid Connection relay.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-495">Erhalten Sie alle apps, die eine Hybridverbindung in eine App Service-Plan verwenden.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-495">Get all apps that use a Hybrid Connection in an App Service Plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-496">Erhalten Sie alle apps, die eine Hybridverbindung in eine App Service-Plan verwenden.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-496">Get all apps that use a Hybrid Connection in an App Service Plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsByHybridConnectionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt; ListWebAppsByHybridConnectionAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;string&gt;&gt; ListWebAppsByHybridConnectionAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebAppsByHybridConnectionAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsByHybridConnectionAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebAppsByHybridConnectionAsync (operations, resourceGroupName, name, namespaceName, relayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListWebAppsByHybridConnectionAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-497">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-497">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-498">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-498">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-499">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-499">Name of the App Service plan.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="1ad7a-500">Name der Hybridverbindung-Namespace.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-500">Name of the Hybrid Connection namespace.</span></span>
            </param>
        <param name="relayName">
            <span data-ttu-id="1ad7a-501">Der Name der Hybridverbindung Relay.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-501">Name of the Hybrid Connection relay.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-502">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-502">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-503">Erhalten Sie alle apps, die eine Hybridverbindung in eine App Service-Plan verwenden.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-503">Get all apps that use a Hybrid Connection in an App Service Plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-504">Erhalten Sie alle apps, die eine Hybridverbindung in eine App Service-Plan verwenden.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-504">Get all apps that use a Hybrid Connection in an App Service Plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsByHybridConnectionNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;string&gt; ListWebAppsByHybridConnectionNext (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;string&gt; ListWebAppsByHybridConnectionNext(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebAppsByHybridConnectionNext(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListWebAppsByHybridConnectionNext (operations As IAppServicePlansOperations, nextPageLink As String) As IPage(Of String)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsByHybridConnectionNext : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;string&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebAppsByHybridConnectionNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-505">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-505">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1ad7a-506">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-506">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-507">Erhalten Sie alle apps, die eine Hybridverbindung in eine App Service-Plan verwenden.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-507">Get all apps that use a Hybrid Connection in an App Service Plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-508">Erhalten Sie alle apps, die eine Hybridverbindung in eine App Service-Plan verwenden.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-508">Get all apps that use a Hybrid Connection in an App Service Plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsByHybridConnectionNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt; ListWebAppsByHybridConnectionNextAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;string&gt;&gt; ListWebAppsByHybridConnectionNextAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebAppsByHybridConnectionNextAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsByHybridConnectionNextAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebAppsByHybridConnectionNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListWebAppsByHybridConnectionNextAsync&gt;d__65))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-509">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-509">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1ad7a-510">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-510">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-511">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-511">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-512">Erhalten Sie alle apps, die eine Hybridverbindung in eine App Service-Plan verwenden.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-512">Get all apps that use a Hybrid Connection in an App Service Plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-513">Erhalten Sie alle apps, die eine Hybridverbindung in eine App Service-Plan verwenden.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-513">Get all apps that use a Hybrid Connection in an App Service Plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt; ListWebAppsNext (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt; ListWebAppsNext(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebAppsNext(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListWebAppsNext (operations As IAppServicePlansOperations, nextPageLink As String) As IPage(Of Site)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsNext : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebAppsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-514">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-514">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1ad7a-515">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-515">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-516">Erhalten Sie alle apps, die App Service-Plan zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-516">Get all apps associated with an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-517">Erhalten Sie alle apps, die App Service-Plan zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-517">Get all apps associated with an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt; ListWebAppsNextAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt; ListWebAppsNextAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebAppsNextAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsNextAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebAppsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListWebAppsNextAsync&gt;d__73))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-518">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-518">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1ad7a-519">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-519">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-520">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-520">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-521">Erhalten Sie alle apps, die App Service-Plan zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-521">Get all apps associated with an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-522">Erhalten Sie alle apps, die App Service-Plan zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-522">Get all apps associated with an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebootWorker">
      <MemberSignature Language="C#" Value="public static void RebootWorker (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string workerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void RebootWorker(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string workerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.RebootWorker(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub RebootWorker (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, workerName As String)" />
      <MemberSignature Language="F#" Value="static member RebootWorker : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.RebootWorker (operations, resourceGroupName, name, workerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-523">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-523">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-524">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-524">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-525">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-525">Name of the App Service plan.</span></span>
            </param>
        <param name="workerName">
            <span data-ttu-id="1ad7a-526">Name der Worker-Computers, der in der Regel mit RD beginnt</span><span class="sxs-lookup"><span data-stu-id="1ad7a-526">Name of worker machine, which typically starts with RD.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-527">Starten Sie einen Worker-Computers in eine App Service-Plan neu.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-527">Reboot a worker machine in an App Service plan.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="1ad7a-528">Starten Sie einen Worker-Computers in eine App Service-Plan neu.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-528">Reboot a worker machine in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebootWorkerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RebootWorkerAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string workerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RebootWorkerAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string workerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.RebootWorkerAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RebootWorkerAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.RebootWorkerAsync (operations, resourceGroupName, name, workerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;RebootWorkerAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-529">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-529">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-530">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-530">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-531">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-531">Name of the App Service plan.</span></span>
            </param>
        <param name="workerName">
            <span data-ttu-id="1ad7a-532">Name der Worker-Computers, der in der Regel mit RD beginnt</span><span class="sxs-lookup"><span data-stu-id="1ad7a-532">Name of worker machine, which typically starts with RD.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-533">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-533">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-534">Starten Sie einen Worker-Computers in eine App Service-Plan neu.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-534">Reboot a worker machine in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-535">Starten Sie einen Worker-Computers in eine App Service-Plan neu.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-535">Reboot a worker machine in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RestartWebApps">
      <MemberSignature Language="C#" Value="public static void RestartWebApps (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, Nullable&lt;bool&gt; softRestart = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void RestartWebApps(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; softRestart) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.RestartWebApps(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub RestartWebApps (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, Optional softRestart As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="static member RestartWebApps : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * Nullable&lt;bool&gt; -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.RestartWebApps (operations, resourceGroupName, name, softRestart)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="softRestart" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-536">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-536">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-537">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-537">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-538">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-538">Name of the App Service plan.</span></span>
            </param>
        <param name="softRestart">
            <span data-ttu-id="1ad7a-539">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; führt eine weiche Neustart, gilt die Konfigurationseinstellungen und die apps neu gestartet wird, falls erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-539">Specify &lt;code&gt;true&lt;/code&gt; to performa a soft restart, applies the configuration settings and restarts the apps if necessary.</span></span> <span data-ttu-id="1ad7a-540">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;, die immer neu gestartet wurde und die apps reprovisions</span><span class="sxs-lookup"><span data-stu-id="1ad7a-540">The default is &lt;code&gt;false&lt;/code&gt;, which always restarts and reprovisions the apps</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-541">Starten Sie alle apps im App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-541">Restart all apps in an App Service plan.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="1ad7a-542">Starten Sie alle apps im App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-542">Restart all apps in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RestartWebAppsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RestartWebAppsAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, Nullable&lt;bool&gt; softRestart = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RestartWebAppsAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; softRestart, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.RestartWebAppsAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RestartWebAppsAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.RestartWebAppsAsync (operations, resourceGroupName, name, softRestart, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;RestartWebAppsAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="softRestart" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-543">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-543">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-544">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-544">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-545">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-545">Name of the App Service plan.</span></span>
            </param>
        <param name="softRestart">
            <span data-ttu-id="1ad7a-546">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; führt eine weiche Neustart, gilt die Konfigurationseinstellungen und die apps neu gestartet wird, falls erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-546">Specify &lt;code&gt;true&lt;/code&gt; to performa a soft restart, applies the configuration settings and restarts the apps if necessary.</span></span> <span data-ttu-id="1ad7a-547">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;, die immer neu gestartet wurde und die apps reprovisions</span><span class="sxs-lookup"><span data-stu-id="1ad7a-547">The default is &lt;code&gt;false&lt;/code&gt;, which always restarts and reprovisions the apps</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-548">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-548">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-549">Starten Sie alle apps im App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-549">Restart all apps in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-550">Starten Sie alle apps im App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-550">Restart all apps in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.AppServicePlan Update (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource appServicePlan);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.AppServicePlan Update(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource appServicePlan) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.Update(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource -&gt; Microsoft.Azure.Management.WebSites.Models.AppServicePlan" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.Update (operations, resourceGroupName, name, appServicePlan)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.AppServicePlan</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="appServicePlan" Type="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-551">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-551">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-552">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-552">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-553">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-553">Name of the App Service plan.</span></span>
            </param>
        <param name="appServicePlan">
            <span data-ttu-id="1ad7a-554">Details zu den App-Dienst planen.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-554">Details of the App Service plan.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-555">Erstellt oder aktualisiert eine App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-555">Creates or updates an App Service Plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-556">Erstellt oder aktualisiert eine App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-556">Creates or updates an App Service Plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; UpdateAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource appServicePlan, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; UpdateAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource appServicePlan, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.UpdateAsync (operations, resourceGroupName, name, appServicePlan, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;UpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="appServicePlan" Type="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-557">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-557">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-558">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-558">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-559">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-559">Name of the App Service plan.</span></span>
            </param>
        <param name="appServicePlan">
            <span data-ttu-id="1ad7a-560">Details zu den App-Dienst planen.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-560">Details of the App Service plan.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-561">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-561">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-562">Erstellt oder aktualisiert eine App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-562">Creates or updates an App Service Plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-563">Erstellt oder aktualisiert eine App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-563">Creates or updates an App Service Plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateVnetGateway">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.VnetGateway UpdateVnetGateway (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string gatewayName, Microsoft.Azure.Management.WebSites.Models.VnetGateway connectionEnvelope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.VnetGateway UpdateVnetGateway(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string gatewayName, class Microsoft.Azure.Management.WebSites.Models.VnetGateway connectionEnvelope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.UpdateVnetGateway(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.VnetGateway)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateVnetGateway (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, vnetName As String, gatewayName As String, connectionEnvelope As VnetGateway) As VnetGateway" />
      <MemberSignature Language="F#" Value="static member UpdateVnetGateway : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * Microsoft.Azure.Management.WebSites.Models.VnetGateway -&gt; Microsoft.Azure.Management.WebSites.Models.VnetGateway" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.UpdateVnetGateway (operations, resourceGroupName, name, vnetName, gatewayName, connectionEnvelope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.VnetGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="connectionEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.VnetGateway" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-564">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-564">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-565">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-565">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-566">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-566">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="1ad7a-567">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-567">Name of the Virtual Network.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="1ad7a-568">Der Name des Gateways.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-568">Name of the gateway.</span></span> <span data-ttu-id="1ad7a-569">Nur das 'primary' Gateway wird unterstützt.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-569">Only the 'primary' gateway is supported.</span></span>
            </param>
        <param name="connectionEnvelope">
            <span data-ttu-id="1ad7a-570">Die Definition des Gateways.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-570">Definition of the gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-571">Aktualisieren eines virtuellen Netzwerkgateways.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-571">Update a Virtual Network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-572">Aktualisieren eines virtuellen Netzwerkgateways.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-572">Update a Virtual Network gateway.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateVnetGatewayAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetGateway&gt; UpdateVnetGatewayAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string gatewayName, Microsoft.Azure.Management.WebSites.Models.VnetGateway connectionEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetGateway&gt; UpdateVnetGatewayAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string gatewayName, class Microsoft.Azure.Management.WebSites.Models.VnetGateway connectionEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.UpdateVnetGatewayAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.VnetGateway,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateVnetGatewayAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * Microsoft.Azure.Management.WebSites.Models.VnetGateway * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetGateway&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.UpdateVnetGatewayAsync (operations, resourceGroupName, name, vnetName, gatewayName, connectionEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;UpdateVnetGatewayAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="connectionEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.VnetGateway" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-573">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-573">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-574">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-574">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-575">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-575">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="1ad7a-576">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-576">Name of the Virtual Network.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="1ad7a-577">Der Name des Gateways.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-577">Name of the gateway.</span></span> <span data-ttu-id="1ad7a-578">Nur das 'primary' Gateway wird unterstützt.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-578">Only the 'primary' gateway is supported.</span></span>
            </param>
        <param name="connectionEnvelope">
            <span data-ttu-id="1ad7a-579">Die Definition des Gateways.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-579">Definition of the gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-580">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-580">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-581">Aktualisieren eines virtuellen Netzwerkgateways.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-581">Update a Virtual Network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-582">Aktualisieren eines virtuellen Netzwerkgateways.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-582">Update a Virtual Network gateway.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateVnetRoute">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.VnetRoute UpdateVnetRoute (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, Microsoft.Azure.Management.WebSites.Models.VnetRoute route);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.VnetRoute UpdateVnetRoute(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, class Microsoft.Azure.Management.WebSites.Models.VnetRoute route) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.UpdateVnetRoute(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.VnetRoute)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateVnetRoute (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, vnetName As String, routeName As String, route As VnetRoute) As VnetRoute" />
      <MemberSignature Language="F#" Value="static member UpdateVnetRoute : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * Microsoft.Azure.Management.WebSites.Models.VnetRoute -&gt; Microsoft.Azure.Management.WebSites.Models.VnetRoute" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.UpdateVnetRoute (operations, resourceGroupName, name, vnetName, routeName, route)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.VnetRoute</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="route" Type="Microsoft.Azure.Management.WebSites.Models.VnetRoute" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-583">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-583">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-584">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-584">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-585">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-585">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="1ad7a-586">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-586">Name of the Virtual Network.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="1ad7a-587">Der Name der Route Virtuellenetzwerk.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-587">Name of the Virtual Network route.</span></span>
            </param>
        <param name="route">
            <span data-ttu-id="1ad7a-588">Die Definition der Route Virtuellenetzwerk.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-588">Definition of the Virtual Network route.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-589">Erstellen Sie oder aktualisieren Sie eine Virtuellenetzwerk-Route in der App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-589">Create or update a Virtual Network route in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-590">Erstellen Sie oder aktualisieren Sie eine Virtuellenetzwerk-Route in der App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-590">Create or update a Virtual Network route in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateVnetRouteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt; UpdateVnetRouteAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, Microsoft.Azure.Management.WebSites.Models.VnetRoute route, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt; UpdateVnetRouteAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, class Microsoft.Azure.Management.WebSites.Models.VnetRoute route, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.UpdateVnetRouteAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.VnetRoute,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateVnetRouteAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * Microsoft.Azure.Management.WebSites.Models.VnetRoute * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.UpdateVnetRouteAsync (operations, resourceGroupName, name, vnetName, routeName, route, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;UpdateVnetRouteAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="route" Type="Microsoft.Azure.Management.WebSites.Models.VnetRoute" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1ad7a-591">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-591">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ad7a-592">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-592">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1ad7a-593">Name des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-593">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="1ad7a-594">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-594">Name of the Virtual Network.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="1ad7a-595">Der Name der Route Virtuellenetzwerk.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-595">Name of the Virtual Network route.</span></span>
            </param>
        <param name="route">
            <span data-ttu-id="1ad7a-596">Die Definition der Route Virtuellenetzwerk.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-596">Definition of the Virtual Network route.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ad7a-597">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-597">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ad7a-598">Erstellen Sie oder aktualisieren Sie eine Virtuellenetzwerk-Route in der App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-598">Create or update a Virtual Network route in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1ad7a-599">Erstellen Sie oder aktualisieren Sie eine Virtuellenetzwerk-Route in der App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="1ad7a-599">Create or update a Virtual Network route in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>