<Type Name="WebSiteManagementClientExtensions" FullName="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions">
  <TypeSignature Language="C#" Value="public static class WebSiteManagementClientExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit WebSiteManagementClientExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module WebSiteManagementClientExtensions" />
  <TypeSignature Language="F#" Value="type WebSiteManagementClientExtensions = class" />
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
            <span data-ttu-id="882e9-101">Erweiterungsmethoden für WebSiteManagementClient.</span><span class="sxs-lookup"><span data-stu-id="882e9-101">Extension methods for WebSiteManagementClient.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckNameAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability CheckNameAvailability (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string name, string type, Nullable&lt;bool&gt; isFqdn = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability CheckNameAvailability(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string name, string type, valuetype System.Nullable`1&lt;bool&gt; isFqdn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.CheckNameAvailability(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckNameAvailability (operations As IWebSiteManagementClient, name As String, type As String, Optional isFqdn As Nullable(Of Boolean) = null) As ResourceNameAvailability" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailability : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.CheckNameAvailability (operations, name, type, isFqdn)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="isFqdn" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-102">The operations group for this extension method.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="882e9-103">Der Ressourcenname überprüfen.</span><span class="sxs-lookup"><span data-stu-id="882e9-103">Resource name to verify.</span></span>
            </param>
        <param name="type">
            <span data-ttu-id="882e9-104">Ressourcentyp zur Überprüfung verwendet.</span><span class="sxs-lookup"><span data-stu-id="882e9-104">Resource type used for verification.</span></span> <span data-ttu-id="882e9-105">Folgende Werte sind möglich: "Website", "Slot", "HostingEnvironment"</span><span class="sxs-lookup"><span data-stu-id="882e9-105">Possible values include: 'Site', 'Slot', 'HostingEnvironment'</span></span>
            </param>
        <param name="isFqdn">
            <span data-ttu-id="882e9-106">Ist vollqualifizierte Domänenname.</span><span class="sxs-lookup"><span data-stu-id="882e9-106">Is fully qualified domain name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-107">Überprüfen Sie, ob der Name einer Ressource verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="882e9-107">Check if a resource name is available.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-108">Überprüfen Sie, ob der Name einer Ressource verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="882e9-108">Check if a resource name is available.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability&gt; CheckNameAvailabilityAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string name, string type, Nullable&lt;bool&gt; isFqdn = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability&gt; CheckNameAvailabilityAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string name, string type, valuetype System.Nullable`1&lt;bool&gt; isFqdn, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.CheckNameAvailabilityAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailabilityAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.CheckNameAvailabilityAsync (operations, name, type, isFqdn, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;CheckNameAvailabilityAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="isFqdn" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-109">The operations group for this extension method.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="882e9-110">Der Ressourcenname überprüfen.</span><span class="sxs-lookup"><span data-stu-id="882e9-110">Resource name to verify.</span></span>
            </param>
        <param name="type">
            <span data-ttu-id="882e9-111">Ressourcentyp zur Überprüfung verwendet.</span><span class="sxs-lookup"><span data-stu-id="882e9-111">Resource type used for verification.</span></span> <span data-ttu-id="882e9-112">Folgende Werte sind möglich: "Website", "Slot", "HostingEnvironment"</span><span class="sxs-lookup"><span data-stu-id="882e9-112">Possible values include: 'Site', 'Slot', 'HostingEnvironment'</span></span>
            </param>
        <param name="isFqdn">
            <span data-ttu-id="882e9-113">Ist vollqualifizierte Domänenname.</span><span class="sxs-lookup"><span data-stu-id="882e9-113">Is fully qualified domain name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="882e9-114">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="882e9-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-115">Überprüfen Sie, ob der Name einer Ressource verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="882e9-115">Check if a resource name is available.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-116">Überprüfen Sie, ob der Name einer Ressource verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="882e9-116">Check if a resource name is available.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPublishingUser">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.User GetPublishingUser (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.User GetPublishingUser(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.GetPublishingUser(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetPublishingUser (operations As IWebSiteManagementClient) As User" />
      <MemberSignature Language="F#" Value="static member GetPublishingUser : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient -&gt; Microsoft.Azure.Management.WebSites.Models.User" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.GetPublishingUser operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.User</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-117">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-118">Benutzer ruft veröffentlicht werden.</span><span class="sxs-lookup"><span data-stu-id="882e9-118">Gets publishing user</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-119">Benutzer ruft veröffentlicht werden.</span><span class="sxs-lookup"><span data-stu-id="882e9-119">Gets publishing user</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPublishingUserAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.User&gt; GetPublishingUserAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.User&gt; GetPublishingUserAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.GetPublishingUserAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetPublishingUserAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.User&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.GetPublishingUserAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;GetPublishingUserAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.User&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-120">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-120">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="882e9-121">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="882e9-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-122">Benutzer ruft veröffentlicht werden.</span><span class="sxs-lookup"><span data-stu-id="882e9-122">Gets publishing user</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-123">Benutzer ruft veröffentlicht werden.</span><span class="sxs-lookup"><span data-stu-id="882e9-123">Gets publishing user</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSourceControl">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.SourceControl GetSourceControl (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string sourceControlType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.SourceControl GetSourceControl(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string sourceControlType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.GetSourceControl(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetSourceControl (operations As IWebSiteManagementClient, sourceControlType As String) As SourceControl" />
      <MemberSignature Language="F#" Value="static member GetSourceControl : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string -&gt; Microsoft.Azure.Management.WebSites.Models.SourceControl" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.GetSourceControl (operations, sourceControlType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.SourceControl</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="sourceControlType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-124">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-124">The operations group for this extension method.</span></span>
            </param>
        <param name="sourceControlType">
            <span data-ttu-id="882e9-125">Typ des Datenquellen-Steuerelements</span><span class="sxs-lookup"><span data-stu-id="882e9-125">Type of source control</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-126">Ruft die Datenquellen-Steuerelements token</span><span class="sxs-lookup"><span data-stu-id="882e9-126">Gets source control token</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-127">Ruft die Datenquellen-Steuerelements token</span><span class="sxs-lookup"><span data-stu-id="882e9-127">Gets source control token</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSourceControlAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt; GetSourceControlAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string sourceControlType, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.SourceControl&gt; GetSourceControlAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string sourceControlType, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.GetSourceControlAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSourceControlAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.GetSourceControlAsync (operations, sourceControlType, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;GetSourceControlAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="sourceControlType" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-128">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-128">The operations group for this extension method.</span></span>
            </param>
        <param name="sourceControlType">
            <span data-ttu-id="882e9-129">Typ des Datenquellen-Steuerelements</span><span class="sxs-lookup"><span data-stu-id="882e9-129">Type of source control</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="882e9-130">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="882e9-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-131">Ruft die Datenquellen-Steuerelements token</span><span class="sxs-lookup"><span data-stu-id="882e9-131">Gets source control token</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-132">Ruft die Datenquellen-Steuerelements token</span><span class="sxs-lookup"><span data-stu-id="882e9-132">Gets source control token</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSubscriptionDeploymentLocations">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.DeploymentLocations GetSubscriptionDeploymentLocations (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.DeploymentLocations GetSubscriptionDeploymentLocations(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.GetSubscriptionDeploymentLocations(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetSubscriptionDeploymentLocations (operations As IWebSiteManagementClient) As DeploymentLocations" />
      <MemberSignature Language="F#" Value="static member GetSubscriptionDeploymentLocations : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient -&gt; Microsoft.Azure.Management.WebSites.Models.DeploymentLocations" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.GetSubscriptionDeploymentLocations operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.DeploymentLocations</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-133">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-134">Ruft die Liste der verfügbaren geografischen Regionen sowie ministamps</span><span class="sxs-lookup"><span data-stu-id="882e9-134">Gets list of available geo regions plus ministamps</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-135">Ruft die Liste der verfügbaren geografischen Regionen sowie ministamps</span><span class="sxs-lookup"><span data-stu-id="882e9-135">Gets list of available geo regions plus ministamps</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSubscriptionDeploymentLocationsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DeploymentLocations&gt; GetSubscriptionDeploymentLocationsAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.DeploymentLocations&gt; GetSubscriptionDeploymentLocationsAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.GetSubscriptionDeploymentLocationsAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSubscriptionDeploymentLocationsAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DeploymentLocations&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.GetSubscriptionDeploymentLocationsAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;GetSubscriptionDeploymentLocationsAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DeploymentLocations&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-136">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-136">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="882e9-137">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="882e9-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-138">Ruft die Liste der verfügbaren geografischen Regionen sowie ministamps</span><span class="sxs-lookup"><span data-stu-id="882e9-138">Gets list of available geo regions plus ministamps</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-139">Ruft die Liste der verfügbaren geografischen Regionen sowie ministamps</span><span class="sxs-lookup"><span data-stu-id="882e9-139">Gets list of available geo regions plus ministamps</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGeoRegions">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt; ListGeoRegions (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string sku = null, Nullable&lt;bool&gt; linuxWorkersEnabled = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt; ListGeoRegions(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string sku, valuetype System.Nullable`1&lt;bool&gt; linuxWorkersEnabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListGeoRegions(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListGeoRegions (operations As IWebSiteManagementClient, Optional sku As String = null, Optional linuxWorkersEnabled As Nullable(Of Boolean) = null) As IPage(Of GeoRegion)" />
      <MemberSignature Language="F#" Value="static member ListGeoRegions : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListGeoRegions (operations, sku, linuxWorkersEnabled)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="sku" Type="System.String" />
        <Parameter Name="linuxWorkersEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-140">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-140">The operations group for this extension method.</span></span>
            </param>
        <param name="sku">
            <span data-ttu-id="882e9-141">Name der SKU, die zum Filtern der Regionen verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="882e9-141">Name of SKU used to filter the regions.</span></span> <span data-ttu-id="882e9-142">Folgende Werte sind möglich: "Free", "Shared", "Basic", "Standard", "Premium", "PremiumV2", "Dynamic", "Isoliert"</span><span class="sxs-lookup"><span data-stu-id="882e9-142">Possible values include: 'Free', 'Shared', 'Basic', 'Standard', 'Premium', 'PremiumV2', 'Dynamic', 'Isolated'</span></span>
            </param>
        <param name="linuxWorkersEnabled">
            <span data-ttu-id="882e9-143">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; ggf. nur Regionen zu filtern, die Linux-Worker-Unterstützung.</span><span class="sxs-lookup"><span data-stu-id="882e9-143">Specify &lt;code&gt;true&lt;/code&gt; if you want to filter to only regions that support Linux workers.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-144">Ruft eine Liste der verfügbaren geografischen Regionen.</span><span class="sxs-lookup"><span data-stu-id="882e9-144">Get a list of available geographical regions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-145">Ruft eine Liste der verfügbaren geografischen Regionen.</span><span class="sxs-lookup"><span data-stu-id="882e9-145">Get a list of available geographical regions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGeoRegionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt; ListGeoRegionsAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string sku = null, Nullable&lt;bool&gt; linuxWorkersEnabled = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt; ListGeoRegionsAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string sku, valuetype System.Nullable`1&lt;bool&gt; linuxWorkersEnabled, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListGeoRegionsAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListGeoRegionsAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListGeoRegionsAsync (operations, sku, linuxWorkersEnabled, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;ListGeoRegionsAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="sku" Type="System.String" />
        <Parameter Name="linuxWorkersEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-146">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-146">The operations group for this extension method.</span></span>
            </param>
        <param name="sku">
            <span data-ttu-id="882e9-147">Name der SKU, die zum Filtern der Regionen verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="882e9-147">Name of SKU used to filter the regions.</span></span> <span data-ttu-id="882e9-148">Folgende Werte sind möglich: "Free", "Shared", "Basic", "Standard", "Premium", "PremiumV2", "Dynamic", "Isoliert"</span><span class="sxs-lookup"><span data-stu-id="882e9-148">Possible values include: 'Free', 'Shared', 'Basic', 'Standard', 'Premium', 'PremiumV2', 'Dynamic', 'Isolated'</span></span>
            </param>
        <param name="linuxWorkersEnabled">
            <span data-ttu-id="882e9-149">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; ggf. nur Regionen zu filtern, die Linux-Worker-Unterstützung.</span><span class="sxs-lookup"><span data-stu-id="882e9-149">Specify &lt;code&gt;true&lt;/code&gt; if you want to filter to only regions that support Linux workers.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="882e9-150">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="882e9-150">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-151">Ruft eine Liste der verfügbaren geografischen Regionen.</span><span class="sxs-lookup"><span data-stu-id="882e9-151">Get a list of available geographical regions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-152">Ruft eine Liste der verfügbaren geografischen Regionen.</span><span class="sxs-lookup"><span data-stu-id="882e9-152">Get a list of available geographical regions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGeoRegionsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt; ListGeoRegionsNext (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt; ListGeoRegionsNext(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListGeoRegionsNext(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListGeoRegionsNext (operations As IWebSiteManagementClient, nextPageLink As String) As IPage(Of GeoRegion)" />
      <MemberSignature Language="F#" Value="static member ListGeoRegionsNext : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListGeoRegionsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-153">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-153">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="882e9-154">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="882e9-154">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-155">Ruft eine Liste der verfügbaren geografischen Regionen.</span><span class="sxs-lookup"><span data-stu-id="882e9-155">Get a list of available geographical regions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-156">Ruft eine Liste der verfügbaren geografischen Regionen.</span><span class="sxs-lookup"><span data-stu-id="882e9-156">Get a list of available geographical regions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGeoRegionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt; ListGeoRegionsNextAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt; ListGeoRegionsNextAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListGeoRegionsNextAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListGeoRegionsNextAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListGeoRegionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;ListGeoRegionsNextAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-157">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-157">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="882e9-158">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="882e9-158">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="882e9-159">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="882e9-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-160">Ruft eine Liste der verfügbaren geografischen Regionen.</span><span class="sxs-lookup"><span data-stu-id="882e9-160">Get a list of available geographical regions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-161">Ruft eine Liste der verfügbaren geografischen Regionen.</span><span class="sxs-lookup"><span data-stu-id="882e9-161">Get a list of available geographical regions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPremierAddOnOffers">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt; ListPremierAddOnOffers (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt; ListPremierAddOnOffers(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListPremierAddOnOffers(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListPremierAddOnOffers (operations As IWebSiteManagementClient) As IPage(Of PremierAddOnOffer)" />
      <MemberSignature Language="F#" Value="static member ListPremierAddOnOffers : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListPremierAddOnOffers operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-162">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-162">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-163">Listen Sie aller premier-Add-Angebote auf.</span><span class="sxs-lookup"><span data-stu-id="882e9-163">List all premier add-on offers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-164">Listen Sie aller premier-Add-Angebote auf.</span><span class="sxs-lookup"><span data-stu-id="882e9-164">List all premier add-on offers.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPremierAddOnOffersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt; ListPremierAddOnOffersAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt; ListPremierAddOnOffersAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListPremierAddOnOffersAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListPremierAddOnOffersAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListPremierAddOnOffersAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;ListPremierAddOnOffersAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-165">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-165">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="882e9-166">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="882e9-166">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-167">Listen Sie aller premier-Add-Angebote auf.</span><span class="sxs-lookup"><span data-stu-id="882e9-167">List all premier add-on offers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-168">Listen Sie aller premier-Add-Angebote auf.</span><span class="sxs-lookup"><span data-stu-id="882e9-168">List all premier add-on offers.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPremierAddOnOffersNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt; ListPremierAddOnOffersNext (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt; ListPremierAddOnOffersNext(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListPremierAddOnOffersNext(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListPremierAddOnOffersNext (operations As IWebSiteManagementClient, nextPageLink As String) As IPage(Of PremierAddOnOffer)" />
      <MemberSignature Language="F#" Value="static member ListPremierAddOnOffersNext : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListPremierAddOnOffersNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-169">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-169">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="882e9-170">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="882e9-170">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-171">Listen Sie aller premier-Add-Angebote auf.</span><span class="sxs-lookup"><span data-stu-id="882e9-171">List all premier add-on offers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-172">Listen Sie aller premier-Add-Angebote auf.</span><span class="sxs-lookup"><span data-stu-id="882e9-172">List all premier add-on offers.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPremierAddOnOffersNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt; ListPremierAddOnOffersNextAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt; ListPremierAddOnOffersNextAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListPremierAddOnOffersNextAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListPremierAddOnOffersNextAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListPremierAddOnOffersNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;ListPremierAddOnOffersNextAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-173">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-173">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="882e9-174">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="882e9-174">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="882e9-175">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="882e9-175">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-176">Listen Sie aller premier-Add-Angebote auf.</span><span class="sxs-lookup"><span data-stu-id="882e9-176">List all premier add-on offers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-177">Listen Sie aller premier-Add-Angebote auf.</span><span class="sxs-lookup"><span data-stu-id="882e9-177">List all premier add-on offers.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSkus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.SkuInfos ListSkus (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.SkuInfos ListSkus(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListSkus(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListSkus (operations As IWebSiteManagementClient) As SkuInfos" />
      <MemberSignature Language="F#" Value="static member ListSkus : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient -&gt; Microsoft.Azure.Management.WebSites.Models.SkuInfos" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListSkus operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.SkuInfos</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-178">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-178">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-179">Listen Sie alle SKUs.</span><span class="sxs-lookup"><span data-stu-id="882e9-179">List all SKUs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-180">Listen Sie alle SKUs.</span><span class="sxs-lookup"><span data-stu-id="882e9-180">List all SKUs.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSkusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfos&gt; ListSkusAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.SkuInfos&gt; ListSkusAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListSkusAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSkusAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfos&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListSkusAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;ListSkusAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfos&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-181">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-181">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="882e9-182">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="882e9-182">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-183">Listen Sie alle SKUs.</span><span class="sxs-lookup"><span data-stu-id="882e9-183">List all SKUs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-184">Listen Sie alle SKUs.</span><span class="sxs-lookup"><span data-stu-id="882e9-184">List all SKUs.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSourceControls">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt; ListSourceControls (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.SourceControl&gt; ListSourceControls(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListSourceControls(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListSourceControls (operations As IWebSiteManagementClient) As IPage(Of SourceControl)" />
      <MemberSignature Language="F#" Value="static member ListSourceControls : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListSourceControls operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-185">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-185">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-186">Ruft die verfügbaren Datenquellen-Steuerelementen für Azure-Websites.</span><span class="sxs-lookup"><span data-stu-id="882e9-186">Gets the source controls available for Azure websites.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-187">Ruft die verfügbaren Datenquellen-Steuerelementen für Azure-Websites.</span><span class="sxs-lookup"><span data-stu-id="882e9-187">Gets the source controls available for Azure websites.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSourceControlsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt; ListSourceControlsAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt; ListSourceControlsAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListSourceControlsAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSourceControlsAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListSourceControlsAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;ListSourceControlsAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-188">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-188">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="882e9-189">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="882e9-189">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-190">Ruft die verfügbaren Datenquellen-Steuerelementen für Azure-Websites.</span><span class="sxs-lookup"><span data-stu-id="882e9-190">Gets the source controls available for Azure websites.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-191">Ruft die verfügbaren Datenquellen-Steuerelementen für Azure-Websites.</span><span class="sxs-lookup"><span data-stu-id="882e9-191">Gets the source controls available for Azure websites.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSourceControlsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt; ListSourceControlsNext (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.SourceControl&gt; ListSourceControlsNext(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListSourceControlsNext(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListSourceControlsNext (operations As IWebSiteManagementClient, nextPageLink As String) As IPage(Of SourceControl)" />
      <MemberSignature Language="F#" Value="static member ListSourceControlsNext : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListSourceControlsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-192">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-192">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="882e9-193">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="882e9-193">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-194">Ruft die verfügbaren Datenquellen-Steuerelementen für Azure-Websites.</span><span class="sxs-lookup"><span data-stu-id="882e9-194">Gets the source controls available for Azure websites.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-195">Ruft die verfügbaren Datenquellen-Steuerelementen für Azure-Websites.</span><span class="sxs-lookup"><span data-stu-id="882e9-195">Gets the source controls available for Azure websites.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSourceControlsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt; ListSourceControlsNextAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt; ListSourceControlsNextAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListSourceControlsNextAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSourceControlsNextAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListSourceControlsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;ListSourceControlsNextAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-196">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-196">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="882e9-197">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="882e9-197">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="882e9-198">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="882e9-198">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-199">Ruft die verfügbaren Datenquellen-Steuerelementen für Azure-Websites.</span><span class="sxs-lookup"><span data-stu-id="882e9-199">Gets the source controls available for Azure websites.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-200">Ruft die verfügbaren Datenquellen-Steuerelementen für Azure-Websites.</span><span class="sxs-lookup"><span data-stu-id="882e9-200">Gets the source controls available for Azure websites.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Move">
      <MemberSignature Language="C#" Value="public static void Move (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string resourceGroupName, Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope moveResourceEnvelope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Move(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string resourceGroupName, class Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope moveResourceEnvelope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.Move(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Move (operations As IWebSiteManagementClient, resourceGroupName As String, moveResourceEnvelope As CsmMoveResourceEnvelope)" />
      <MemberSignature Language="F#" Value="static member Move : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.Move (operations, resourceGroupName, moveResourceEnvelope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="moveResourceEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-201">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-201">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="882e9-202">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="882e9-202">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="moveResourceEnvelope">
            <span data-ttu-id="882e9-203">Objekt, das Verschieben die Ressource darstellt.</span><span class="sxs-lookup"><span data-stu-id="882e9-203">Object that represents the resource to move.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-204">Verschieben von Ressourcen zwischen Ressourcengruppen.</span><span class="sxs-lookup"><span data-stu-id="882e9-204">Move resources between resource groups.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="882e9-205">Verschieben von Ressourcen zwischen Ressourcengruppen.</span><span class="sxs-lookup"><span data-stu-id="882e9-205">Move resources between resource groups.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MoveAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task MoveAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string resourceGroupName, Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope moveResourceEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task MoveAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string resourceGroupName, class Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope moveResourceEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.MoveAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member MoveAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.MoveAsync (operations, resourceGroupName, moveResourceEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;MoveAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="moveResourceEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-206">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-206">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="882e9-207">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="882e9-207">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="moveResourceEnvelope">
            <span data-ttu-id="882e9-208">Objekt, das Verschieben die Ressource darstellt.</span><span class="sxs-lookup"><span data-stu-id="882e9-208">Object that represents the resource to move.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="882e9-209">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="882e9-209">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-210">Verschieben von Ressourcen zwischen Ressourcengruppen.</span><span class="sxs-lookup"><span data-stu-id="882e9-210">Move resources between resource groups.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-211">Verschieben von Ressourcen zwischen Ressourcengruppen.</span><span class="sxs-lookup"><span data-stu-id="882e9-211">Move resources between resource groups.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatePublishingUser">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.User UpdatePublishingUser (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, Microsoft.Azure.Management.WebSites.Models.User userDetails);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.User UpdatePublishingUser(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, class Microsoft.Azure.Management.WebSites.Models.User userDetails) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.UpdatePublishingUser(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,Microsoft.Azure.Management.WebSites.Models.User)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdatePublishingUser (operations As IWebSiteManagementClient, userDetails As User) As User" />
      <MemberSignature Language="F#" Value="static member UpdatePublishingUser : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * Microsoft.Azure.Management.WebSites.Models.User -&gt; Microsoft.Azure.Management.WebSites.Models.User" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.UpdatePublishingUser (operations, userDetails)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.User</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="userDetails" Type="Microsoft.Azure.Management.WebSites.Models.User" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-212">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-212">The operations group for this extension method.</span></span>
            </param>
        <param name="userDetails">
            <span data-ttu-id="882e9-213">Details des Benutzers veröffentlichen</span><span class="sxs-lookup"><span data-stu-id="882e9-213">Details of publishing user</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-214">Updates, die publishing Benutzer</span><span class="sxs-lookup"><span data-stu-id="882e9-214">Updates publishing user</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-215">Updates, die publishing Benutzer</span><span class="sxs-lookup"><span data-stu-id="882e9-215">Updates publishing user</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatePublishingUserAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.User&gt; UpdatePublishingUserAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, Microsoft.Azure.Management.WebSites.Models.User userDetails, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.User&gt; UpdatePublishingUserAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, class Microsoft.Azure.Management.WebSites.Models.User userDetails, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.UpdatePublishingUserAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,Microsoft.Azure.Management.WebSites.Models.User,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdatePublishingUserAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * Microsoft.Azure.Management.WebSites.Models.User * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.User&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.UpdatePublishingUserAsync (operations, userDetails, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;UpdatePublishingUserAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.User&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="userDetails" Type="Microsoft.Azure.Management.WebSites.Models.User" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-216">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-216">The operations group for this extension method.</span></span>
            </param>
        <param name="userDetails">
            <span data-ttu-id="882e9-217">Details des Benutzers veröffentlichen</span><span class="sxs-lookup"><span data-stu-id="882e9-217">Details of publishing user</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="882e9-218">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="882e9-218">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-219">Updates, die publishing Benutzer</span><span class="sxs-lookup"><span data-stu-id="882e9-219">Updates publishing user</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-220">Updates, die publishing Benutzer</span><span class="sxs-lookup"><span data-stu-id="882e9-220">Updates publishing user</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSourceControl">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.SourceControl UpdateSourceControl (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string sourceControlType, Microsoft.Azure.Management.WebSites.Models.SourceControl requestMessage);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.SourceControl UpdateSourceControl(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string sourceControlType, class Microsoft.Azure.Management.WebSites.Models.SourceControl requestMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.UpdateSourceControl(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,Microsoft.Azure.Management.WebSites.Models.SourceControl)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateSourceControl (operations As IWebSiteManagementClient, sourceControlType As String, requestMessage As SourceControl) As SourceControl" />
      <MemberSignature Language="F#" Value="static member UpdateSourceControl : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * Microsoft.Azure.Management.WebSites.Models.SourceControl -&gt; Microsoft.Azure.Management.WebSites.Models.SourceControl" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.UpdateSourceControl (operations, sourceControlType, requestMessage)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.SourceControl</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="sourceControlType" Type="System.String" />
        <Parameter Name="requestMessage" Type="Microsoft.Azure.Management.WebSites.Models.SourceControl" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-221">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-221">The operations group for this extension method.</span></span>
            </param>
        <param name="sourceControlType">
            <span data-ttu-id="882e9-222">Typ des Datenquellen-Steuerelements</span><span class="sxs-lookup"><span data-stu-id="882e9-222">Type of source control</span></span>
            </param>
        <param name="requestMessage">
            <span data-ttu-id="882e9-223">Token Quellinformationen für Steuerelement</span><span class="sxs-lookup"><span data-stu-id="882e9-223">Source control token information</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-224">Updates Source Control token</span><span class="sxs-lookup"><span data-stu-id="882e9-224">Updates source control token</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-225">Updates Source Control token</span><span class="sxs-lookup"><span data-stu-id="882e9-225">Updates source control token</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSourceControlAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt; UpdateSourceControlAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string sourceControlType, Microsoft.Azure.Management.WebSites.Models.SourceControl requestMessage, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.SourceControl&gt; UpdateSourceControlAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string sourceControlType, class Microsoft.Azure.Management.WebSites.Models.SourceControl requestMessage, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.UpdateSourceControlAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,Microsoft.Azure.Management.WebSites.Models.SourceControl,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateSourceControlAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * Microsoft.Azure.Management.WebSites.Models.SourceControl * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.UpdateSourceControlAsync (operations, sourceControlType, requestMessage, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;UpdateSourceControlAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="sourceControlType" Type="System.String" />
        <Parameter Name="requestMessage" Type="Microsoft.Azure.Management.WebSites.Models.SourceControl" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-226">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-226">The operations group for this extension method.</span></span>
            </param>
        <param name="sourceControlType">
            <span data-ttu-id="882e9-227">Typ des Datenquellen-Steuerelements</span><span class="sxs-lookup"><span data-stu-id="882e9-227">Type of source control</span></span>
            </param>
        <param name="requestMessage">
            <span data-ttu-id="882e9-228">Token Quellinformationen für Steuerelement</span><span class="sxs-lookup"><span data-stu-id="882e9-228">Source control token information</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="882e9-229">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="882e9-229">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-230">Updates Source Control token</span><span class="sxs-lookup"><span data-stu-id="882e9-230">Updates source control token</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-231">Updates Source Control token</span><span class="sxs-lookup"><span data-stu-id="882e9-231">Updates source control token</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.ValidateResponse Validate (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string resourceGroupName, Microsoft.Azure.Management.WebSites.Models.ValidateRequest validateRequest);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.ValidateResponse Validate(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string resourceGroupName, class Microsoft.Azure.Management.WebSites.Models.ValidateRequest validateRequest) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.Validate(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,Microsoft.Azure.Management.WebSites.Models.ValidateRequest)" />
      <MemberSignature Language="F#" Value="static member Validate : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * Microsoft.Azure.Management.WebSites.Models.ValidateRequest -&gt; Microsoft.Azure.Management.WebSites.Models.ValidateResponse" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.Validate (operations, resourceGroupName, validateRequest)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.ValidateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="validateRequest" Type="Microsoft.Azure.Management.WebSites.Models.ValidateRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-232">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-232">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="882e9-233">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="882e9-233">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="validateRequest">
            <span data-ttu-id="882e9-234">Fordern Sie hinsichtlich der Ressourcen, um zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="882e9-234">Request with the resources to validate.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-235">Überprüfen Sie, ob eine Ressource erstellt werden kann.</span><span class="sxs-lookup"><span data-stu-id="882e9-235">Validate if a resource can be created.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-236">Überprüfen Sie, ob eine Ressource erstellt werden kann.</span><span class="sxs-lookup"><span data-stu-id="882e9-236">Validate if a resource can be created.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.ValidateResponse&gt; ValidateAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string resourceGroupName, Microsoft.Azure.Management.WebSites.Models.ValidateRequest validateRequest, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.ValidateResponse&gt; ValidateAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string resourceGroupName, class Microsoft.Azure.Management.WebSites.Models.ValidateRequest validateRequest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ValidateAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,Microsoft.Azure.Management.WebSites.Models.ValidateRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ValidateAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * Microsoft.Azure.Management.WebSites.Models.ValidateRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.ValidateResponse&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ValidateAsync (operations, resourceGroupName, validateRequest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;ValidateAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.ValidateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="validateRequest" Type="Microsoft.Azure.Management.WebSites.Models.ValidateRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-237">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-237">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="882e9-238">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="882e9-238">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="validateRequest">
            <span data-ttu-id="882e9-239">Fordern Sie hinsichtlich der Ressourcen, um zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="882e9-239">Request with the resources to validate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="882e9-240">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="882e9-240">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-241">Überprüfen Sie, ob eine Ressource erstellt werden kann.</span><span class="sxs-lookup"><span data-stu-id="882e9-241">Validate if a resource can be created.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-242">Überprüfen Sie, ob eine Ressource erstellt werden kann.</span><span class="sxs-lookup"><span data-stu-id="882e9-242">Validate if a resource can be created.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateMove">
      <MemberSignature Language="C#" Value="public static void ValidateMove (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string resourceGroupName, Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope moveResourceEnvelope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ValidateMove(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string resourceGroupName, class Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope moveResourceEnvelope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ValidateMove(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub ValidateMove (operations As IWebSiteManagementClient, resourceGroupName As String, moveResourceEnvelope As CsmMoveResourceEnvelope)" />
      <MemberSignature Language="F#" Value="static member ValidateMove : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ValidateMove (operations, resourceGroupName, moveResourceEnvelope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="moveResourceEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-243">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-243">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="882e9-244">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="882e9-244">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="moveResourceEnvelope">
            <span data-ttu-id="882e9-245">Objekt, das Verschieben die Ressource darstellt.</span><span class="sxs-lookup"><span data-stu-id="882e9-245">Object that represents the resource to move.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-246">Überprüfen Sie, ob eine Ressource verschoben werden kann.</span><span class="sxs-lookup"><span data-stu-id="882e9-246">Validate whether a resource can be moved.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="882e9-247">Überprüfen Sie, ob eine Ressource verschoben werden kann.</span><span class="sxs-lookup"><span data-stu-id="882e9-247">Validate whether a resource can be moved.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateMoveAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ValidateMoveAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string resourceGroupName, Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope moveResourceEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ValidateMoveAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string resourceGroupName, class Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope moveResourceEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ValidateMoveAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ValidateMoveAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ValidateMoveAsync (operations, resourceGroupName, moveResourceEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;ValidateMoveAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="moveResourceEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-248">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-248">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="882e9-249">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="882e9-249">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="moveResourceEnvelope">
            <span data-ttu-id="882e9-250">Objekt, das Verschieben die Ressource darstellt.</span><span class="sxs-lookup"><span data-stu-id="882e9-250">Object that represents the resource to move.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="882e9-251">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="882e9-251">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-252">Überprüfen Sie, ob eine Ressource verschoben werden kann.</span><span class="sxs-lookup"><span data-stu-id="882e9-252">Validate whether a resource can be moved.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-253">Überprüfen Sie, ob eine Ressource verschoben werden kann.</span><span class="sxs-lookup"><span data-stu-id="882e9-253">Validate whether a resource can be moved.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyHostingEnvironmentVnet">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails VerifyHostingEnvironmentVnet (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, Microsoft.Azure.Management.WebSites.Models.VnetParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails VerifyHostingEnvironmentVnet(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, class Microsoft.Azure.Management.WebSites.Models.VnetParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.VerifyHostingEnvironmentVnet(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,Microsoft.Azure.Management.WebSites.Models.VnetParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function VerifyHostingEnvironmentVnet (operations As IWebSiteManagementClient, parameters As VnetParameters) As VnetValidationFailureDetails" />
      <MemberSignature Language="F#" Value="static member VerifyHostingEnvironmentVnet : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * Microsoft.Azure.Management.WebSites.Models.VnetParameters -&gt; Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.VerifyHostingEnvironmentVnet (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.WebSites.Models.VnetParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-254">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-254">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="882e9-255">VNET-Informationen</span><span class="sxs-lookup"><span data-stu-id="882e9-255">VNET information</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-256">Überprüft, ob dieses VNET mit einer App Service-Umgebung kompatibel ist, durch die Analyse der Netzwerksicherheitsgruppe-Regeln.</span><span class="sxs-lookup"><span data-stu-id="882e9-256">Verifies if this VNET is compatible with an App Service Environment by analyzing the Network Security Group rules.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-257">Überprüft, ob dieses VNET mit einer App Service-Umgebung kompatibel ist, durch die Analyse der Netzwerksicherheitsgruppe-Regeln.</span><span class="sxs-lookup"><span data-stu-id="882e9-257">Verifies if this VNET is compatible with an App Service Environment by analyzing the Network Security Group rules.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyHostingEnvironmentVnetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails&gt; VerifyHostingEnvironmentVnetAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, Microsoft.Azure.Management.WebSites.Models.VnetParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails&gt; VerifyHostingEnvironmentVnetAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, class Microsoft.Azure.Management.WebSites.Models.VnetParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.VerifyHostingEnvironmentVnetAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,Microsoft.Azure.Management.WebSites.Models.VnetParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member VerifyHostingEnvironmentVnetAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * Microsoft.Azure.Management.WebSites.Models.VnetParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.VerifyHostingEnvironmentVnetAsync (operations, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;VerifyHostingEnvironmentVnetAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.WebSites.Models.VnetParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="882e9-258">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="882e9-258">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="882e9-259">VNET-Informationen</span><span class="sxs-lookup"><span data-stu-id="882e9-259">VNET information</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="882e9-260">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="882e9-260">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="882e9-261">Überprüft, ob dieses VNET mit einer App Service-Umgebung kompatibel ist, durch die Analyse der Netzwerksicherheitsgruppe-Regeln.</span><span class="sxs-lookup"><span data-stu-id="882e9-261">Verifies if this VNET is compatible with an App Service Environment by analyzing the Network Security Group rules.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="882e9-262">Überprüft, ob dieses VNET mit einer App Service-Umgebung kompatibel ist, durch die Analyse der Netzwerksicherheitsgruppe-Regeln.</span><span class="sxs-lookup"><span data-stu-id="882e9-262">Verifies if this VNET is compatible with an App Service Environment by analyzing the Network Security Group rules.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>