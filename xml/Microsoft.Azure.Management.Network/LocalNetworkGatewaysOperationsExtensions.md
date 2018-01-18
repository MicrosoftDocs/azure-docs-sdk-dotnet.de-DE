<Type Name="LocalNetworkGatewaysOperationsExtensions" FullName="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class LocalNetworkGatewaysOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit LocalNetworkGatewaysOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module LocalNetworkGatewaysOperationsExtensions" />
  <TypeSignature Language="F#" Value="type LocalNetworkGatewaysOperationsExtensions = class" />
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
            <span data-ttu-id="b2617-101">Erweiterungsmethoden für LocalNetworkGatewaysOperations.</span><span class="sxs-lookup"><span data-stu-id="b2617-101">Extension methods for LocalNetworkGatewaysOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.LocalNetworkGateway BeginCreateOrUpdate (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, Microsoft.Azure.Management.Network.Models.LocalNetworkGateway parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway BeginCreateOrUpdate(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.LocalNetworkGateway)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As ILocalNetworkGatewaysOperations, resourceGroupName As String, localNetworkGatewayName As String, parameters As LocalNetworkGateway) As LocalNetworkGateway" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.LocalNetworkGateway -&gt; Microsoft.Azure.Management.Network.Models.LocalNetworkGateway" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, localNetworkGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.LocalNetworkGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.LocalNetworkGateway" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b2617-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b2617-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b2617-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b2617-103">The name of the resource group.</span></span>
            </param>
        <param name="localNetworkGatewayName">
            <span data-ttu-id="b2617-104">Der Name des Gateways des lokalen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="b2617-104">The name of the local network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b2617-105">Parameter für den erstellen oder aktualisieren lokales Netzwerk-Gateway-Vorgang bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="b2617-105">Parameters supplied to the create or update local network gateway operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2617-106">Erstellt oder aktualisiert ein lokales Netzwerkgateway in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b2617-106">Creates or updates a local network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, Microsoft.Azure.Management.Network.Models.LocalNetworkGateway parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.LocalNetworkGateway,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.LocalNetworkGateway * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, localNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.LocalNetworkGateway" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b2617-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b2617-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b2617-108">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b2617-108">The name of the resource group.</span></span>
            </param>
        <param name="localNetworkGatewayName">
            <span data-ttu-id="b2617-109">Der Name des Gateways des lokalen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="b2617-109">The name of the local network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b2617-110">Parameter für den erstellen oder aktualisieren lokales Netzwerk-Gateway-Vorgang bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="b2617-110">Parameters supplied to the create or update local network gateway operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2617-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b2617-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2617-112">Erstellt oder aktualisiert ein lokales Netzwerkgateway in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b2617-112">Creates or updates a local network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As ILocalNetworkGatewaysOperations, resourceGroupName As String, localNetworkGatewayName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.BeginDelete (operations, resourceGroupName, localNetworkGatewayName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b2617-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b2617-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b2617-114">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b2617-114">The name of the resource group.</span></span>
            </param>
        <param name="localNetworkGatewayName">
            <span data-ttu-id="b2617-115">Der Name des Gateways des lokalen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="b2617-115">The name of the local network gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2617-116">Löscht das angegebene lokale Netzwerkgateway.</span><span class="sxs-lookup"><span data-stu-id="b2617-116">Deletes the specified local network gateway.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, localNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions/&lt;BeginDeleteAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b2617-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b2617-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b2617-118">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b2617-118">The name of the resource group.</span></span>
            </param>
        <param name="localNetworkGatewayName">
            <span data-ttu-id="b2617-119">Der Name des Gateways des lokalen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="b2617-119">The name of the local network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2617-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b2617-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2617-121">Löscht das angegebene lokale Netzwerkgateway.</span><span class="sxs-lookup"><span data-stu-id="b2617-121">Deletes the specified local network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.LocalNetworkGateway BeginUpdateTags (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway BeginUpdateTags(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.BeginUpdateTags(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdateTags (operations As ILocalNetworkGatewaysOperations, resourceGroupName As String, localNetworkGatewayName As String, parameters As TagsObject) As LocalNetworkGateway" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTags : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.LocalNetworkGateway" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.BeginUpdateTags (operations, resourceGroupName, localNetworkGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.LocalNetworkGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b2617-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b2617-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b2617-123">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b2617-123">The name of the resource group.</span></span>
            </param>
        <param name="localNetworkGatewayName">
            <span data-ttu-id="b2617-124">Der Name des Gateways des lokalen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="b2617-124">The name of the local network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b2617-125">Parameter, die zum Aktualisieren der lokalen Netzwerk-Gateway-Tags angegeben.</span><span class="sxs-lookup"><span data-stu-id="b2617-125">Parameters supplied to update local network gateway tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2617-126">Aktualisiert ein lokales Netzwerk-Gateway-Tags.</span><span class="sxs-lookup"><span data-stu-id="b2617-126">Updates a local network gateway tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt; BeginUpdateTagsAsync (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt; BeginUpdateTagsAsync(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.BeginUpdateTagsAsync(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTagsAsync : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.BeginUpdateTagsAsync (operations, resourceGroupName, localNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions/&lt;BeginUpdateTagsAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b2617-127">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b2617-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b2617-128">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b2617-128">The name of the resource group.</span></span>
            </param>
        <param name="localNetworkGatewayName">
            <span data-ttu-id="b2617-129">Der Name des Gateways des lokalen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="b2617-129">The name of the local network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b2617-130">Parameter, die zum Aktualisieren der lokalen Netzwerk-Gateway-Tags angegeben.</span><span class="sxs-lookup"><span data-stu-id="b2617-130">Parameters supplied to update local network gateway tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2617-131">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b2617-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2617-132">Aktualisiert ein lokales Netzwerk-Gateway-Tags.</span><span class="sxs-lookup"><span data-stu-id="b2617-132">Updates a local network gateway tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.LocalNetworkGateway CreateOrUpdate (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, Microsoft.Azure.Management.Network.Models.LocalNetworkGateway parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway CreateOrUpdate(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.LocalNetworkGateway)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ILocalNetworkGatewaysOperations, resourceGroupName As String, localNetworkGatewayName As String, parameters As LocalNetworkGateway) As LocalNetworkGateway" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.LocalNetworkGateway -&gt; Microsoft.Azure.Management.Network.Models.LocalNetworkGateway" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, localNetworkGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.LocalNetworkGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.LocalNetworkGateway" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b2617-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b2617-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b2617-134">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b2617-134">The name of the resource group.</span></span>
            </param>
        <param name="localNetworkGatewayName">
            <span data-ttu-id="b2617-135">Der Name des Gateways des lokalen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="b2617-135">The name of the local network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b2617-136">Parameter für den erstellen oder aktualisieren lokales Netzwerk-Gateway-Vorgang bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="b2617-136">Parameters supplied to the create or update local network gateway operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2617-137">Erstellt oder aktualisiert ein lokales Netzwerkgateway in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b2617-137">Creates or updates a local network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, Microsoft.Azure.Management.Network.Models.LocalNetworkGateway parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.LocalNetworkGateway,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.LocalNetworkGateway * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, localNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.LocalNetworkGateway" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b2617-138">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b2617-138">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b2617-139">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b2617-139">The name of the resource group.</span></span>
            </param>
        <param name="localNetworkGatewayName">
            <span data-ttu-id="b2617-140">Der Name des Gateways des lokalen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="b2617-140">The name of the local network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b2617-141">Parameter für den erstellen oder aktualisieren lokales Netzwerk-Gateway-Vorgang bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="b2617-141">Parameters supplied to the create or update local network gateway operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2617-142">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b2617-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2617-143">Erstellt oder aktualisiert ein lokales Netzwerkgateway in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b2617-143">Creates or updates a local network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.Delete(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ILocalNetworkGatewaysOperations, resourceGroupName As String, localNetworkGatewayName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.Delete (operations, resourceGroupName, localNetworkGatewayName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b2617-144">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b2617-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b2617-145">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b2617-145">The name of the resource group.</span></span>
            </param>
        <param name="localNetworkGatewayName">
            <span data-ttu-id="b2617-146">Der Name des Gateways des lokalen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="b2617-146">The name of the local network gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2617-147">Löscht das angegebene lokale Netzwerkgateway.</span><span class="sxs-lookup"><span data-stu-id="b2617-147">Deletes the specified local network gateway.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.DeleteAsync (operations, resourceGroupName, localNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b2617-148">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b2617-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b2617-149">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b2617-149">The name of the resource group.</span></span>
            </param>
        <param name="localNetworkGatewayName">
            <span data-ttu-id="b2617-150">Der Name des Gateways des lokalen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="b2617-150">The name of the local network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2617-151">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b2617-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2617-152">Löscht das angegebene lokale Netzwerkgateway.</span><span class="sxs-lookup"><span data-stu-id="b2617-152">Deletes the specified local network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.LocalNetworkGateway Get (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway Get(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.Get(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ILocalNetworkGatewaysOperations, resourceGroupName As String, localNetworkGatewayName As String) As LocalNetworkGateway" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * string -&gt; Microsoft.Azure.Management.Network.Models.LocalNetworkGateway" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.Get (operations, resourceGroupName, localNetworkGatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.LocalNetworkGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b2617-153">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b2617-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b2617-154">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b2617-154">The name of the resource group.</span></span>
            </param>
        <param name="localNetworkGatewayName">
            <span data-ttu-id="b2617-155">Der Name des Gateways des lokalen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="b2617-155">The name of the local network gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2617-156">Ruft das angegebene lokale Netzwerkgateway in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b2617-156">Gets the specified local network gateway in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt; GetAsync (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt; GetAsync(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.GetAsync (operations, resourceGroupName, localNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b2617-157">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b2617-157">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b2617-158">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b2617-158">The name of the resource group.</span></span>
            </param>
        <param name="localNetworkGatewayName">
            <span data-ttu-id="b2617-159">Der Name des Gateways des lokalen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="b2617-159">The name of the local network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2617-160">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b2617-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2617-161">Ruft das angegebene lokale Netzwerkgateway in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b2617-161">Gets the specified local network gateway in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt; List (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt; List(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.List(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ILocalNetworkGatewaysOperations, resourceGroupName As String) As IPage(Of LocalNetworkGateway)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b2617-162">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b2617-162">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b2617-163">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b2617-163">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2617-164">Ruft die lokalen Netzwerkgateways in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b2617-164">Gets all the local network gateways in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;&gt;" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions/&lt;ListAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b2617-165">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b2617-165">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b2617-166">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b2617-166">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2617-167">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b2617-167">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2617-168">Ruft die lokalen Netzwerkgateways in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b2617-168">Gets all the local network gateways in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt; ListNext (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt; ListNext(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As ILocalNetworkGatewaysOperations, nextPageLink As String) As IPage(Of LocalNetworkGateway)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b2617-169">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b2617-169">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="b2617-170">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b2617-170">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2617-171">Ruft die lokalen Netzwerkgateways in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b2617-171">Gets all the local network gateways in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;&gt;" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions/&lt;ListNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b2617-172">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b2617-172">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="b2617-173">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b2617-173">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2617-174">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b2617-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2617-175">Ruft die lokalen Netzwerkgateways in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b2617-175">Gets all the local network gateways in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.LocalNetworkGateway UpdateTags (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway UpdateTags(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.UpdateTags(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateTags (operations As ILocalNetworkGatewaysOperations, resourceGroupName As String, localNetworkGatewayName As String, parameters As TagsObject) As LocalNetworkGateway" />
      <MemberSignature Language="F#" Value="static member UpdateTags : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.LocalNetworkGateway" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.UpdateTags (operations, resourceGroupName, localNetworkGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.LocalNetworkGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b2617-176">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b2617-176">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b2617-177">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b2617-177">The name of the resource group.</span></span>
            </param>
        <param name="localNetworkGatewayName">
            <span data-ttu-id="b2617-178">Der Name des Gateways des lokalen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="b2617-178">The name of the local network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b2617-179">Parameter, die zum Aktualisieren der lokalen Netzwerk-Gateway-Tags angegeben.</span><span class="sxs-lookup"><span data-stu-id="b2617-179">Parameters supplied to update local network gateway tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2617-180">Aktualisiert ein lokales Netzwerk-Gateway-Tags.</span><span class="sxs-lookup"><span data-stu-id="b2617-180">Updates a local network gateway tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt; UpdateTagsAsync (this Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt; UpdateTagsAsync(class Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations operations, string resourceGroupName, string localNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.UpdateTagsAsync(Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateTagsAsync : Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions.UpdateTagsAsync (operations, resourceGroupName, localNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LocalNetworkGatewaysOperationsExtensions/&lt;UpdateTagsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LocalNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILocalNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="localNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b2617-181">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b2617-181">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b2617-182">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b2617-182">The name of the resource group.</span></span>
            </param>
        <param name="localNetworkGatewayName">
            <span data-ttu-id="b2617-183">Der Name des Gateways des lokalen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="b2617-183">The name of the local network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b2617-184">Parameter, die zum Aktualisieren der lokalen Netzwerk-Gateway-Tags angegeben.</span><span class="sxs-lookup"><span data-stu-id="b2617-184">Parameters supplied to update local network gateway tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2617-185">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b2617-185">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2617-186">Aktualisiert ein lokales Netzwerk-Gateway-Tags.</span><span class="sxs-lookup"><span data-stu-id="b2617-186">Updates a local network gateway tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>