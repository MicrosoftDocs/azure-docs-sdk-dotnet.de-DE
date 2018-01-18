<Type Name="LocalNetworkGatewaysOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.LocalNetworkGatewaysOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class LocalNetworkGatewaysOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit LocalNetworkGatewaysOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LocalNetworkGatewaysOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module LocalNetworkGatewaysOperationsExtensions" />
  <TypeSignature Language="F#" Value="type LocalNetworkGatewaysOperationsExtensions = class" />
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
            <span data-ttu-id="a5290-101">Erweiterungsmethoden für LocalNetworkGatewaysOperations.</span><span class="sxs-lookup"><span data-stu-id="a5290-101">Extension methods for LocalNetworkGatewaysOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, class Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LocalNetworkGatewaysOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.LocalNetworkGatewaysOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, localNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.LocalNetworkGatewaysOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a5290-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a5290-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a5290-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="a5290-103">The name of the resource group.</span></span>
            </param>
        <param name="localNetworkGatewayName">
            <span data-ttu-id="a5290-104">Der Name des Gateways des lokalen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="a5290-104">The name of the local network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="a5290-105">Parameter für den erstellen oder aktualisieren lokales Netzwerk-Gateway-Vorgang bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="a5290-105">Parameters supplied to the create or update local network gateway operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a5290-106">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a5290-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a5290-107">Erstellt oder aktualisiert ein lokales Netzwerkgateway in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="a5290-107">Creates or updates a local network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LocalNetworkGatewaysOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.LocalNetworkGatewaysOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, localNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.LocalNetworkGatewaysOperationsExtensions/&lt;BeginDeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a5290-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a5290-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a5290-109">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="a5290-109">The name of the resource group.</span></span>
            </param>
        <param name="localNetworkGatewayName">
            <span data-ttu-id="a5290-110">Der Name des Gateways des lokalen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="a5290-110">The name of the local network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a5290-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a5290-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a5290-112">Löscht das angegebene lokale Netzwerkgateway.</span><span class="sxs-lookup"><span data-stu-id="a5290-112">Deletes the specified local network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, class Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LocalNetworkGatewaysOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.LocalNetworkGatewaysOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, localNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.LocalNetworkGatewaysOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a5290-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a5290-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a5290-114">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="a5290-114">The name of the resource group.</span></span>
            </param>
        <param name="localNetworkGatewayName">
            <span data-ttu-id="a5290-115">Der Name des Gateways des lokalen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="a5290-115">The name of the local network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="a5290-116">Parameter für den erstellen oder aktualisieren lokales Netzwerk-Gateway-Vorgang bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="a5290-116">Parameters supplied to the create or update local network gateway operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a5290-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a5290-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a5290-118">Erstellt oder aktualisiert ein lokales Netzwerkgateway in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="a5290-118">Creates or updates a local network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LocalNetworkGatewaysOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.LocalNetworkGatewaysOperationsExtensions.DeleteAsync (operations, resourceGroupName, localNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.LocalNetworkGatewaysOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a5290-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a5290-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a5290-120">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="a5290-120">The name of the resource group.</span></span>
            </param>
        <param name="localNetworkGatewayName">
            <span data-ttu-id="a5290-121">Der Name des Gateways des lokalen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="a5290-121">The name of the local network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a5290-122">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a5290-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a5290-123">Löscht das angegebene lokale Netzwerkgateway.</span><span class="sxs-lookup"><span data-stu-id="a5290-123">Deletes the specified local network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LocalNetworkGatewaysOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.LocalNetworkGatewaysOperationsExtensions.GetAsync (operations, resourceGroupName, localNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.LocalNetworkGatewaysOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a5290-124">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a5290-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a5290-125">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="a5290-125">The name of the resource group.</span></span>
            </param>
        <param name="localNetworkGatewayName">
            <span data-ttu-id="a5290-126">Der Name des Gateways des lokalen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="a5290-126">The name of the local network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a5290-127">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a5290-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a5290-128">Ruft das angegebene lokale Netzwerkgateway in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="a5290-128">Gets the specified local network gateway in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LocalNetworkGatewaysOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.LocalNetworkGatewaysOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.LocalNetworkGatewaysOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a5290-129">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a5290-129">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a5290-130">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="a5290-130">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a5290-131">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a5290-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a5290-132">Ruft die lokalen Netzwerkgateways in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="a5290-132">Gets all the local network gateways in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LocalNetworkGatewaysOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.LocalNetworkGatewaysOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.LocalNetworkGatewaysOperationsExtensions/&lt;ListNextAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a5290-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a5290-133">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="a5290-134">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="a5290-134">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a5290-135">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a5290-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a5290-136">Ruft die lokalen Netzwerkgateways in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="a5290-136">Gets all the local network gateways in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>