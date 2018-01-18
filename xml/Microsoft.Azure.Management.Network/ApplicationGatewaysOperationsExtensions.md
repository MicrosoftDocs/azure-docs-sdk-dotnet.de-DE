<Type Name="ApplicationGatewaysOperationsExtensions" FullName="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ApplicationGatewaysOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ApplicationGatewaysOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ApplicationGatewaysOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ApplicationGatewaysOperationsExtensions = class" />
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
            <span data-ttu-id="e4cbf-101">Erweiterungsmethoden für ApplicationGatewaysOperations.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-101">Extension methods for ApplicationGatewaysOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BackendHealth">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealth BackendHealth (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealth BackendHealth(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.BackendHealth(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BackendHealth (operations As IApplicationGatewaysOperations, resourceGroupName As String, applicationGatewayName As String, Optional expand As String = null) As ApplicationGatewayBackendHealth" />
      <MemberSignature Language="F#" Value="static member BackendHealth : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealth" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.BackendHealth (operations, resourceGroupName, applicationGatewayName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealth</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4cbf-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-103">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="e4cbf-104">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-104">The name of the application gateway.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="e4cbf-105">Wird erweitert, BackendAddressPool und "backendhttpsettings" in der Back-End-Integrität verwiesen wird.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-105">Expands BackendAddressPool and BackendHttpSettings referenced in backend health.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-106">Ruft die Back-End-Integrität des Gateways angegebene Anwendung in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-106">Gets the backend health of the specified application gateway in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendHealthAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealth&gt; BackendHealthAsync (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealth&gt; BackendHealthAsync(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.BackendHealthAsync(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BackendHealthAsync : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealth&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.BackendHealthAsync (operations, resourceGroupName, applicationGatewayName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions/&lt;BackendHealthAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4cbf-108">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-108">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="e4cbf-109">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-109">The name of the application gateway.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="e4cbf-110">Wird erweitert, BackendAddressPool und "backendhttpsettings" in der Back-End-Integrität verwiesen wird.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-110">Expands BackendAddressPool and BackendHttpSettings referenced in backend health.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4cbf-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-112">Ruft die Back-End-Integrität des Gateways angegebene Anwendung in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-112">Gets the backend health of the specified application gateway in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginBackendHealth">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealth BeginBackendHealth (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealth BeginBackendHealth(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.BeginBackendHealth(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginBackendHealth (operations As IApplicationGatewaysOperations, resourceGroupName As String, applicationGatewayName As String, Optional expand As String = null) As ApplicationGatewayBackendHealth" />
      <MemberSignature Language="F#" Value="static member BeginBackendHealth : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealth" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.BeginBackendHealth (operations, resourceGroupName, applicationGatewayName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealth</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4cbf-114">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-114">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="e4cbf-115">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-115">The name of the application gateway.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="e4cbf-116">Wird erweitert, BackendAddressPool und "backendhttpsettings" in der Back-End-Integrität verwiesen wird.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-116">Expands BackendAddressPool and BackendHttpSettings referenced in backend health.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-117">Ruft die Back-End-Integrität des Gateways angegebene Anwendung in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-117">Gets the backend health of the specified application gateway in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginBackendHealthAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealth&gt; BeginBackendHealthAsync (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealth&gt; BeginBackendHealthAsync(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.BeginBackendHealthAsync(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginBackendHealthAsync : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealth&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.BeginBackendHealthAsync (operations, resourceGroupName, applicationGatewayName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions/&lt;BeginBackendHealthAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-118">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-118">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4cbf-119">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-119">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="e4cbf-120">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-120">The name of the application gateway.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="e4cbf-121">Wird erweitert, BackendAddressPool und "backendhttpsettings" in der Back-End-Integrität verwiesen wird.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-121">Expands BackendAddressPool and BackendHttpSettings referenced in backend health.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4cbf-122">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-123">Ruft die Back-End-Integrität des Gateways angegebene Anwendung in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-123">Gets the backend health of the specified application gateway in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ApplicationGateway BeginCreateOrUpdate (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, Microsoft.Azure.Management.Network.Models.ApplicationGateway parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ApplicationGateway BeginCreateOrUpdate(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, class Microsoft.Azure.Management.Network.Models.ApplicationGateway parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ApplicationGateway)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IApplicationGatewaysOperations, resourceGroupName As String, applicationGatewayName As String, parameters As ApplicationGateway) As ApplicationGateway" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.ApplicationGateway -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGateway" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, applicationGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ApplicationGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ApplicationGateway" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-124">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4cbf-125">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-125">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="e4cbf-126">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-126">The name of the application gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e4cbf-127">Parameter zum Erstellen oder aktualisieren Anwendung Gateway Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-127">Parameters supplied to the create or update application gateway operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-128">Erstellt oder aktualisiert die angegebene Anwendung-Gateway.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-128">Creates or updates the specified application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, Microsoft.Azure.Management.Network.Models.ApplicationGateway parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, class Microsoft.Azure.Management.Network.Models.ApplicationGateway parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ApplicationGateway,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.ApplicationGateway * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, applicationGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ApplicationGateway" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-129">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-129">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4cbf-130">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-130">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="e4cbf-131">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-131">The name of the application gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e4cbf-132">Parameter zum Erstellen oder aktualisieren Anwendung Gateway Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-132">Parameters supplied to the create or update application gateway operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4cbf-133">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-134">Erstellt oder aktualisiert die angegebene Anwendung-Gateway.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-134">Creates or updates the specified application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IApplicationGatewaysOperations, resourceGroupName As String, applicationGatewayName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.BeginDelete (operations, resourceGroupName, applicationGatewayName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-135">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-135">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4cbf-136">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-136">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="e4cbf-137">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-137">The name of the application gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-138">Löscht das angegebene Anwendungsgateway.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-138">Deletes the specified application gateway.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, applicationGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions/&lt;BeginDeleteAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-139">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-139">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4cbf-140">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-140">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="e4cbf-141">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-141">The name of the application gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4cbf-142">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-143">Löscht das angegebene Anwendungsgateway.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-143">Deletes the specified application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStart">
      <MemberSignature Language="C#" Value="public static void BeginStart (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginStart(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.BeginStart(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginStart (operations As IApplicationGatewaysOperations, resourceGroupName As String, applicationGatewayName As String)" />
      <MemberSignature Language="F#" Value="static member BeginStart : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.BeginStart (operations, resourceGroupName, applicationGatewayName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-144">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4cbf-145">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-145">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="e4cbf-146">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-146">The name of the application gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-147">Startet die angegebene Anwendung-Gateway.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-147">Starts the specified application gateway.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginStartAsync (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginStartAsync(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.BeginStartAsync(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStartAsync : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.BeginStartAsync (operations, resourceGroupName, applicationGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions/&lt;BeginStartAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-148">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4cbf-149">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-149">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="e4cbf-150">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-150">The name of the application gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4cbf-151">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-152">Startet die angegebene Anwendung-Gateway.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-152">Starts the specified application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStop">
      <MemberSignature Language="C#" Value="public static void BeginStop (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginStop(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.BeginStop(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginStop (operations As IApplicationGatewaysOperations, resourceGroupName As String, applicationGatewayName As String)" />
      <MemberSignature Language="F#" Value="static member BeginStop : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.BeginStop (operations, resourceGroupName, applicationGatewayName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-153">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4cbf-154">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-154">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="e4cbf-155">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-155">The name of the application gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-156">Beendet die angegebene Anwendungsgateway in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-156">Stops the specified application gateway in a resource group.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginStopAsync (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginStopAsync(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.BeginStopAsync(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStopAsync : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.BeginStopAsync (operations, resourceGroupName, applicationGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions/&lt;BeginStopAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-157">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-157">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4cbf-158">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-158">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="e4cbf-159">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-159">The name of the application gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4cbf-160">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-161">Beendet die angegebene Anwendungsgateway in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-161">Stops the specified application gateway in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ApplicationGateway BeginUpdateTags (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ApplicationGateway BeginUpdateTags(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.BeginUpdateTags(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdateTags (operations As IApplicationGatewaysOperations, resourceGroupName As String, applicationGatewayName As String, parameters As TagsObject) As ApplicationGateway" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTags : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGateway" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.BeginUpdateTags (operations, resourceGroupName, applicationGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ApplicationGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-162">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-162">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4cbf-163">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-163">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="e4cbf-164">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-164">The name of the application gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e4cbf-165">Parameter, die zum Aktualisieren der Anwendung Gateway Tags angegeben.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-165">Parameters supplied to update application gateway tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-166">Aktualisiert die angegebene Anwendung Gateway-Tags.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-166">Updates the specified application gateway tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt; BeginUpdateTagsAsync (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt; BeginUpdateTagsAsync(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.BeginUpdateTagsAsync(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTagsAsync : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.BeginUpdateTagsAsync (operations, resourceGroupName, applicationGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions/&lt;BeginUpdateTagsAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-167">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-167">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4cbf-168">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-168">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="e4cbf-169">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-169">The name of the application gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e4cbf-170">Parameter, die zum Aktualisieren der Anwendung Gateway Tags angegeben.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-170">Parameters supplied to update application gateway tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4cbf-171">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-172">Aktualisiert die angegebene Anwendung Gateway-Tags.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-172">Updates the specified application gateway tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ApplicationGateway CreateOrUpdate (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, Microsoft.Azure.Management.Network.Models.ApplicationGateway parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ApplicationGateway CreateOrUpdate(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, class Microsoft.Azure.Management.Network.Models.ApplicationGateway parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ApplicationGateway)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IApplicationGatewaysOperations, resourceGroupName As String, applicationGatewayName As String, parameters As ApplicationGateway) As ApplicationGateway" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.ApplicationGateway -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGateway" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, applicationGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ApplicationGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ApplicationGateway" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-173">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-173">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4cbf-174">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-174">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="e4cbf-175">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-175">The name of the application gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e4cbf-176">Parameter zum Erstellen oder aktualisieren Anwendung Gateway Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-176">Parameters supplied to the create or update application gateway operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-177">Erstellt oder aktualisiert die angegebene Anwendung-Gateway.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-177">Creates or updates the specified application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, Microsoft.Azure.Management.Network.Models.ApplicationGateway parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, class Microsoft.Azure.Management.Network.Models.ApplicationGateway parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ApplicationGateway,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.ApplicationGateway * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, applicationGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ApplicationGateway" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-178">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-178">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4cbf-179">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-179">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="e4cbf-180">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-180">The name of the application gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e4cbf-181">Parameter zum Erstellen oder aktualisieren Anwendung Gateway Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-181">Parameters supplied to the create or update application gateway operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4cbf-182">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-182">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-183">Erstellt oder aktualisiert die angegebene Anwendung-Gateway.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-183">Creates or updates the specified application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.Delete(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IApplicationGatewaysOperations, resourceGroupName As String, applicationGatewayName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.Delete (operations, resourceGroupName, applicationGatewayName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-184">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-184">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4cbf-185">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-185">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="e4cbf-186">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-186">The name of the application gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-187">Löscht das angegebene Anwendungsgateway.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-187">Deletes the specified application gateway.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.DeleteAsync (operations, resourceGroupName, applicationGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-188">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-188">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4cbf-189">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-189">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="e4cbf-190">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-190">The name of the application gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4cbf-191">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-191">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-192">Löscht das angegebene Anwendungsgateway.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-192">Deletes the specified application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ApplicationGateway Get (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ApplicationGateway Get(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.Get(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IApplicationGatewaysOperations, resourceGroupName As String, applicationGatewayName As String) As ApplicationGateway" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * string -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGateway" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.Get (operations, resourceGroupName, applicationGatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ApplicationGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-193">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-193">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4cbf-194">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-194">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="e4cbf-195">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-195">The name of the application gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-196">Ruft das angegebene Anwendungsgateway ab.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-196">Gets the specified application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt; GetAsync (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt; GetAsync(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.GetAsync (operations, resourceGroupName, applicationGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-197">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-197">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4cbf-198">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-198">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="e4cbf-199">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-199">The name of the application gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4cbf-200">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-200">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-201">Ruft das angegebene Anwendungsgateway ab.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-201">Gets the specified application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSslPredefinedPolicy">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy GetSslPredefinedPolicy (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string predefinedPolicyName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy GetSslPredefinedPolicy(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string predefinedPolicyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.GetSslPredefinedPolicy(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetSslPredefinedPolicy (operations As IApplicationGatewaysOperations, predefinedPolicyName As String) As ApplicationGatewaySslPredefinedPolicy" />
      <MemberSignature Language="F#" Value="static member GetSslPredefinedPolicy : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.GetSslPredefinedPolicy (operations, predefinedPolicyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="predefinedPolicyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-202">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-202">The operations group for this extension method.</span></span>
            </param>
        <param name="predefinedPolicyName">
            <span data-ttu-id="e4cbf-203">Name der Ssl vordefinierten Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-203">Name of Ssl predefined policy.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-204">Ruft Ssl vordefinierte Richtlinie mit dem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-204">Gets Ssl predefined policy with the specified policy name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSslPredefinedPolicyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy&gt; GetSslPredefinedPolicyAsync (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string predefinedPolicyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy&gt; GetSslPredefinedPolicyAsync(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string predefinedPolicyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.GetSslPredefinedPolicyAsync(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSslPredefinedPolicyAsync : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.GetSslPredefinedPolicyAsync (operations, predefinedPolicyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions/&lt;GetSslPredefinedPolicyAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="predefinedPolicyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-205">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-205">The operations group for this extension method.</span></span>
            </param>
        <param name="predefinedPolicyName">
            <span data-ttu-id="e4cbf-206">Name der Ssl vordefinierten Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-206">Name of Ssl predefined policy.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4cbf-207">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-207">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-208">Ruft Ssl vordefinierte Richtlinie mit dem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-208">Gets Ssl predefined policy with the specified policy name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt; List (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt; List(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.List(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IApplicationGatewaysOperations, resourceGroupName As String) As IPage(Of ApplicationGateway)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-209">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-209">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4cbf-210">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-210">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-211">Listet alle Anwendungsgateways in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-211">Lists all application gateways in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAll">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt; ListAll (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt; ListAll(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListAll(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAll (operations As IApplicationGatewaysOperations) As IPage(Of ApplicationGateway)" />
      <MemberSignature Language="F#" Value="static member ListAll : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListAll operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-212">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-212">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-213">Ruft alle Anwendungsgateways in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-213">Gets all the application gateways in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions/&lt;ListAllAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-214">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-214">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4cbf-215">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-215">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-216">Ruft alle Anwendungsgateways in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-216">Gets all the application gateways in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt; ListAllNext (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt; ListAllNext(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListAllNext(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAllNext (operations As IApplicationGatewaysOperations, nextPageLink As String) As IPage(Of ApplicationGateway)" />
      <MemberSignature Language="F#" Value="static member ListAllNext : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListAllNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-217">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-217">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e4cbf-218">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-218">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-219">Ruft alle Anwendungsgateways in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-219">Gets all the application gateways in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions/&lt;ListAllNextAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-220">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-220">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e4cbf-221">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-221">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4cbf-222">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-222">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-223">Ruft alle Anwendungsgateways in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-223">Gets all the application gateways in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions/&lt;ListAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-224">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-224">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4cbf-225">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-225">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4cbf-226">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-226">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-227">Listet alle Anwendungsgateways in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-227">Lists all application gateways in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableSslOptions">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableSslOptions ListAvailableSslOptions (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableSslOptions ListAvailableSslOptions(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListAvailableSslOptions(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAvailableSslOptions (operations As IApplicationGatewaysOperations) As ApplicationGatewayAvailableSslOptions" />
      <MemberSignature Language="F#" Value="static member ListAvailableSslOptions : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableSslOptions" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListAvailableSslOptions operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableSslOptions</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-228">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-228">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-229">Listet die verfügbare Ssl-Optionen zum Konfigurieren von Ssl-Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-229">Lists available Ssl options for configuring Ssl policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableSslOptionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableSslOptions&gt; ListAvailableSslOptionsAsync (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableSslOptions&gt; ListAvailableSslOptionsAsync(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListAvailableSslOptionsAsync(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAvailableSslOptionsAsync : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableSslOptions&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListAvailableSslOptionsAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions/&lt;ListAvailableSslOptionsAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableSslOptions&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-230">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-230">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4cbf-231">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-231">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-232">Listet die verfügbare Ssl-Optionen zum Konfigurieren von Ssl-Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-232">Lists available Ssl options for configuring Ssl policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableSslPredefinedPolicies">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy&gt; ListAvailableSslPredefinedPolicies (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy&gt; ListAvailableSslPredefinedPolicies(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListAvailableSslPredefinedPolicies(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAvailableSslPredefinedPolicies (operations As IApplicationGatewaysOperations) As IPage(Of ApplicationGatewaySslPredefinedPolicy)" />
      <MemberSignature Language="F#" Value="static member ListAvailableSslPredefinedPolicies : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListAvailableSslPredefinedPolicies operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-233">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-233">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-234">Listet alle SSL vordefinierte Richtlinien zum Konfigurieren von Ssl-Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-234">Lists all SSL predefined policies for configuring Ssl policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableSslPredefinedPoliciesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy&gt;&gt; ListAvailableSslPredefinedPoliciesAsync (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy&gt;&gt; ListAvailableSslPredefinedPoliciesAsync(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListAvailableSslPredefinedPoliciesAsync(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAvailableSslPredefinedPoliciesAsync : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy&gt;&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListAvailableSslPredefinedPoliciesAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions/&lt;ListAvailableSslPredefinedPoliciesAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-235">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-235">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4cbf-236">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-236">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-237">Listet alle SSL vordefinierte Richtlinien zum Konfigurieren von Ssl-Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-237">Lists all SSL predefined policies for configuring Ssl policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableSslPredefinedPoliciesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy&gt; ListAvailableSslPredefinedPoliciesNext (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy&gt; ListAvailableSslPredefinedPoliciesNext(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListAvailableSslPredefinedPoliciesNext(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAvailableSslPredefinedPoliciesNext (operations As IApplicationGatewaysOperations, nextPageLink As String) As IPage(Of ApplicationGatewaySslPredefinedPolicy)" />
      <MemberSignature Language="F#" Value="static member ListAvailableSslPredefinedPoliciesNext : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListAvailableSslPredefinedPoliciesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-238">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-238">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e4cbf-239">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-239">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-240">Listet alle SSL vordefinierte Richtlinien zum Konfigurieren von Ssl-Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-240">Lists all SSL predefined policies for configuring Ssl policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableSslPredefinedPoliciesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy&gt;&gt; ListAvailableSslPredefinedPoliciesNextAsync (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy&gt;&gt; ListAvailableSslPredefinedPoliciesNextAsync(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListAvailableSslPredefinedPoliciesNextAsync(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAvailableSslPredefinedPoliciesNextAsync : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy&gt;&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListAvailableSslPredefinedPoliciesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions/&lt;ListAvailableSslPredefinedPoliciesNextAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-241">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-241">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e4cbf-242">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-242">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4cbf-243">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-243">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-244">Listet alle SSL vordefinierte Richtlinien zum Konfigurieren von Ssl-Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-244">Lists all SSL predefined policies for configuring Ssl policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableWafRuleSets">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableWafRuleSetsResult ListAvailableWafRuleSets (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableWafRuleSetsResult ListAvailableWafRuleSets(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListAvailableWafRuleSets(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAvailableWafRuleSets (operations As IApplicationGatewaysOperations) As ApplicationGatewayAvailableWafRuleSetsResult" />
      <MemberSignature Language="F#" Value="static member ListAvailableWafRuleSets : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableWafRuleSetsResult" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListAvailableWafRuleSets operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableWafRuleSetsResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-245">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-245">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-246">Listet alle verfügbaren Web Application Firewall Regelsätze.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-246">Lists all available web application firewall rule sets.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableWafRuleSetsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableWafRuleSetsResult&gt; ListAvailableWafRuleSetsAsync (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableWafRuleSetsResult&gt; ListAvailableWafRuleSetsAsync(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListAvailableWafRuleSetsAsync(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAvailableWafRuleSetsAsync : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableWafRuleSetsResult&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListAvailableWafRuleSetsAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions/&lt;ListAvailableWafRuleSetsAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableWafRuleSetsResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-247">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-247">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4cbf-248">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-248">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-249">Listet alle verfügbaren Web Application Firewall Regelsätze.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-249">Lists all available web application firewall rule sets.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt; ListNext (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt; ListNext(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IApplicationGatewaysOperations, nextPageLink As String) As IPage(Of ApplicationGateway)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-250">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-250">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e4cbf-251">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-251">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-252">Listet alle Anwendungsgateways in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-252">Lists all application gateways in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions/&lt;ListNextAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-253">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-253">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e4cbf-254">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-254">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4cbf-255">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-255">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-256">Listet alle Anwendungsgateways in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-256">Lists all application gateways in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public static void Start (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Start(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.Start(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Start (operations As IApplicationGatewaysOperations, resourceGroupName As String, applicationGatewayName As String)" />
      <MemberSignature Language="F#" Value="static member Start : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.Start (operations, resourceGroupName, applicationGatewayName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-257">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-257">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4cbf-258">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-258">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="e4cbf-259">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-259">The name of the application gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-260">Startet die angegebene Anwendung-Gateway.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-260">Starts the specified application gateway.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task StartAsync (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task StartAsync(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.StartAsync(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StartAsync : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.StartAsync (operations, resourceGroupName, applicationGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions/&lt;StartAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-261">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-261">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4cbf-262">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-262">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="e4cbf-263">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-263">The name of the application gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4cbf-264">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-264">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-265">Startet die angegebene Anwendung-Gateway.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-265">Starts the specified application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stop">
      <MemberSignature Language="C#" Value="public static void Stop (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Stop(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.Stop(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Stop (operations As IApplicationGatewaysOperations, resourceGroupName As String, applicationGatewayName As String)" />
      <MemberSignature Language="F#" Value="static member Stop : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.Stop (operations, resourceGroupName, applicationGatewayName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-266">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-266">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4cbf-267">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-267">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="e4cbf-268">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-268">The name of the application gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-269">Beendet die angegebene Anwendungsgateway in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-269">Stops the specified application gateway in a resource group.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task StopAsync (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task StopAsync(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.StopAsync(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StopAsync : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.StopAsync (operations, resourceGroupName, applicationGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions/&lt;StopAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-270">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-270">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4cbf-271">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-271">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="e4cbf-272">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-272">The name of the application gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4cbf-273">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-273">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-274">Beendet die angegebene Anwendungsgateway in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-274">Stops the specified application gateway in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ApplicationGateway UpdateTags (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ApplicationGateway UpdateTags(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.UpdateTags(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateTags (operations As IApplicationGatewaysOperations, resourceGroupName As String, applicationGatewayName As String, parameters As TagsObject) As ApplicationGateway" />
      <MemberSignature Language="F#" Value="static member UpdateTags : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGateway" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.UpdateTags (operations, resourceGroupName, applicationGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ApplicationGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-275">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-275">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4cbf-276">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-276">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="e4cbf-277">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-277">The name of the application gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e4cbf-278">Parameter, die zum Aktualisieren der Anwendung Gateway Tags angegeben.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-278">Parameters supplied to update application gateway tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-279">Aktualisiert die angegebene Anwendung Gateway-Tags.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-279">Updates the specified application gateway tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt; UpdateTagsAsync (this Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt; UpdateTagsAsync(class Microsoft.Azure.Management.Network.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.UpdateTagsAsync(Microsoft.Azure.Management.Network.IApplicationGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateTagsAsync : Microsoft.Azure.Management.Network.IApplicationGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;" Usage="Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions.UpdateTagsAsync (operations, resourceGroupName, applicationGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ApplicationGatewaysOperationsExtensions/&lt;UpdateTagsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ApplicationGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4cbf-280">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-280">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4cbf-281">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-281">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="e4cbf-282">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-282">The name of the application gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e4cbf-283">Parameter, die zum Aktualisieren der Anwendung Gateway Tags angegeben.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-283">Parameters supplied to update application gateway tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4cbf-284">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-284">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4cbf-285">Aktualisiert die angegebene Anwendung Gateway-Tags.</span><span class="sxs-lookup"><span data-stu-id="e4cbf-285">Updates the specified application gateway tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>