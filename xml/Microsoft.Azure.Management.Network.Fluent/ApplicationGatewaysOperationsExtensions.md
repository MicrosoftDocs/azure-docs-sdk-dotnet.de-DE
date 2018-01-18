<Type Name="ApplicationGatewaysOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ApplicationGatewaysOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ApplicationGatewaysOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ApplicationGatewaysOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ApplicationGatewaysOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="15548-101">Erweiterungsmethoden für ApplicationGatewaysOperations.</span><span class="sxs-lookup"><span data-stu-id="15548-101">Extension methods for ApplicationGatewaysOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BackendHealthAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthInner&gt; BackendHealthAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthInner&gt; BackendHealthAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.BackendHealthAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BackendHealthAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.BackendHealthAsync (operations, resourceGroupName, applicationGatewayName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;BackendHealthAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15548-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="15548-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15548-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="15548-103">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="15548-104">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="15548-104">The name of the application gateway.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="15548-105">Wird erweitert, BackendAddressPool und "backendhttpsettings" in der Back-End-Integrität verwiesen wird.</span><span class="sxs-lookup"><span data-stu-id="15548-105">Expands BackendAddressPool and BackendHttpSettings referenced in backend health.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15548-106">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="15548-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15548-107">Ruft die Back-End-Integrität des Gateways angegebene Anwendung in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="15548-107">Gets the backend health of the specified application gateway in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginBackendHealthAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthInner&gt; BeginBackendHealthAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthInner&gt; BeginBackendHealthAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.BeginBackendHealthAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginBackendHealthAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.BeginBackendHealthAsync (operations, resourceGroupName, applicationGatewayName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;BeginBackendHealthAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15548-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="15548-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15548-109">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="15548-109">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="15548-110">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="15548-110">The name of the application gateway.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="15548-111">Wird erweitert, BackendAddressPool und "backendhttpsettings" in der Back-End-Integrität verwiesen wird.</span><span class="sxs-lookup"><span data-stu-id="15548-111">Expands BackendAddressPool and BackendHttpSettings referenced in backend health.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15548-112">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="15548-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15548-113">Ruft die Back-End-Integrität des Gateways angegebene Anwendung in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="15548-113">Gets the backend health of the specified application gateway in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, applicationGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15548-114">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="15548-114">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15548-115">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="15548-115">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="15548-116">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="15548-116">The name of the application gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="15548-117">Parameter zum Erstellen oder aktualisieren Anwendung Gateway Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="15548-117">Parameters supplied to the create or update application gateway operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15548-118">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="15548-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15548-119">Erstellt oder aktualisiert die angegebene Anwendung-Gateway.</span><span class="sxs-lookup"><span data-stu-id="15548-119">Creates or updates the specified application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, applicationGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;BeginDeleteAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15548-120">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="15548-120">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15548-121">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="15548-121">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="15548-122">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="15548-122">The name of the application gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15548-123">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="15548-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15548-124">Löscht das angegebene Anwendungsgateway.</span><span class="sxs-lookup"><span data-stu-id="15548-124">Deletes the specified application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginStartAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginStartAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.BeginStartAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStartAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.BeginStartAsync (operations, resourceGroupName, applicationGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;BeginStartAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15548-125">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="15548-125">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15548-126">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="15548-126">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="15548-127">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="15548-127">The name of the application gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15548-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="15548-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15548-129">Startet die angegebene Anwendung-Gateway.</span><span class="sxs-lookup"><span data-stu-id="15548-129">Starts the specified application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginStopAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginStopAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.BeginStopAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStopAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.BeginStopAsync (operations, resourceGroupName, applicationGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;BeginStopAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15548-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="15548-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15548-131">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="15548-131">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="15548-132">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="15548-132">The name of the application gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15548-133">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="15548-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15548-134">Beendet die angegebene Anwendungsgateway in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="15548-134">Stops the specified application gateway in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, applicationGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15548-135">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="15548-135">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15548-136">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="15548-136">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="15548-137">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="15548-137">The name of the application gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="15548-138">Parameter zum Erstellen oder aktualisieren Anwendung Gateway Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="15548-138">Parameters supplied to the create or update application gateway operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15548-139">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="15548-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15548-140">Erstellt oder aktualisiert die angegebene Anwendung-Gateway.</span><span class="sxs-lookup"><span data-stu-id="15548-140">Creates or updates the specified application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.DeleteAsync (operations, resourceGroupName, applicationGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;DeleteAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15548-141">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="15548-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15548-142">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="15548-142">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="15548-143">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="15548-143">The name of the application gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15548-144">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="15548-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15548-145">Löscht das angegebene Anwendungsgateway.</span><span class="sxs-lookup"><span data-stu-id="15548-145">Deletes the specified application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.GetAsync (operations, resourceGroupName, applicationGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15548-146">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="15548-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15548-147">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="15548-147">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="15548-148">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="15548-148">The name of the application gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15548-149">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="15548-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15548-150">Ruft das angegebene Anwendungsgateway ab.</span><span class="sxs-lookup"><span data-stu-id="15548-150">Gets the specified application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSslPredefinedPolicyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPredefinedPolicyInner&gt; GetSslPredefinedPolicyAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string predefinedPolicyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPredefinedPolicyInner&gt; GetSslPredefinedPolicyAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string predefinedPolicyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.GetSslPredefinedPolicyAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSslPredefinedPolicyAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPredefinedPolicyInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.GetSslPredefinedPolicyAsync (operations, predefinedPolicyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;GetSslPredefinedPolicyAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPredefinedPolicyInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="predefinedPolicyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="predefinedPolicyName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;ListAllAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15548-151">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="15548-151">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15548-152">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="15548-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15548-153">Ruft alle Anwendungsgateways in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="15548-153">Gets all the application gateways in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;ListAllNextAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15548-154">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="15548-154">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="15548-155">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="15548-155">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15548-156">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="15548-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15548-157">Ruft alle Anwendungsgateways in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="15548-157">Gets all the application gateways in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15548-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="15548-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15548-159">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="15548-159">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15548-160">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="15548-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15548-161">Listet alle Anwendungsgateways in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="15548-161">Lists all application gateways in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableSslOptionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayAvailableSslOptionsInner&gt; ListAvailableSslOptionsAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayAvailableSslOptionsInner&gt; ListAvailableSslOptionsAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListAvailableSslOptionsAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAvailableSslOptionsAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayAvailableSslOptionsInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListAvailableSslOptionsAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;ListAvailableSslOptionsAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayAvailableSslOptionsInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableSslPredefinedPoliciesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPredefinedPolicyInner&gt;&gt; ListAvailableSslPredefinedPoliciesAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPredefinedPolicyInner&gt;&gt; ListAvailableSslPredefinedPoliciesAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListAvailableSslPredefinedPoliciesAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAvailableSslPredefinedPoliciesAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPredefinedPolicyInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListAvailableSslPredefinedPoliciesAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;ListAvailableSslPredefinedPoliciesAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPredefinedPolicyInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableSslPredefinedPoliciesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPredefinedPolicyInner&gt;&gt; ListAvailableSslPredefinedPoliciesNextAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPredefinedPolicyInner&gt;&gt; ListAvailableSslPredefinedPoliciesNextAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListAvailableSslPredefinedPoliciesNextAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAvailableSslPredefinedPoliciesNextAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPredefinedPolicyInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListAvailableSslPredefinedPoliciesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;ListAvailableSslPredefinedPoliciesNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPredefinedPolicyInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableWafRuleSetsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayAvailableWafRuleSetsResultInner&gt; ListAvailableWafRuleSetsAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayAvailableWafRuleSetsResultInner&gt; ListAvailableWafRuleSetsAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListAvailableWafRuleSetsAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAvailableWafRuleSetsAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayAvailableWafRuleSetsResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListAvailableWafRuleSetsAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;ListAvailableWafRuleSetsAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayAvailableWafRuleSetsResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;ListNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15548-162">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="15548-162">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="15548-163">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="15548-163">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15548-164">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="15548-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15548-165">Listet alle Anwendungsgateways in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="15548-165">Lists all application gateways in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task StartAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task StartAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.StartAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StartAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.StartAsync (operations, resourceGroupName, applicationGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;StartAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15548-166">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="15548-166">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15548-167">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="15548-167">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="15548-168">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="15548-168">The name of the application gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15548-169">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="15548-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15548-170">Startet die angegebene Anwendung-Gateway.</span><span class="sxs-lookup"><span data-stu-id="15548-170">Starts the specified application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task StopAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task StopAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.StopAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StopAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.StopAsync (operations, resourceGroupName, applicationGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;StopAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15548-171">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="15548-171">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15548-172">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="15548-172">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="15548-173">Der Name des Anwendungsgateways.</span><span class="sxs-lookup"><span data-stu-id="15548-173">The name of the application gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15548-174">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="15548-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15548-175">Beendet die angegebene Anwendungsgateway in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="15548-175">Stops the specified application gateway in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>