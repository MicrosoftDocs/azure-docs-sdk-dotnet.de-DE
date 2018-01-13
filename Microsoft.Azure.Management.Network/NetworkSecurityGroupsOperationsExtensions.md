<Type Name="NetworkSecurityGroupsOperationsExtensions" FullName="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class NetworkSecurityGroupsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit NetworkSecurityGroupsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module NetworkSecurityGroupsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type NetworkSecurityGroupsOperationsExtensions = class" />
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
            <span data-ttu-id="158d3-101">Erweiterungsmethoden für NetworkSecurityGroupsOperations.</span><span class="sxs-lookup"><span data-stu-id="158d3-101">Extension methods for NetworkSecurityGroupsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup BeginCreateOrUpdate (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup BeginCreateOrUpdate(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As INetworkSecurityGroupsOperations, resourceGroupName As String, networkSecurityGroupName As String, parameters As NetworkSecurityGroup) As NetworkSecurityGroup" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * string * Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup -&gt; Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, networkSecurityGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="158d3-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="158d3-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="158d3-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-103">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="158d3-104">Der Name der Netzwerksicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-104">The name of the network security group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="158d3-105">Parameter, die den Vorgang erstellen oder aktualisieren Network Security "Gruppe" übergeben.</span><span class="sxs-lookup"><span data-stu-id="158d3-105">Parameters supplied to the create or update network security group operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="158d3-106">Erstellt oder aktualisiert eine Netzwerksicherheitsgruppe in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-106">Creates or updates a network security group in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * string * Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, networkSecurityGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="158d3-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="158d3-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="158d3-108">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-108">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="158d3-109">Der Name der Netzwerksicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-109">The name of the network security group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="158d3-110">Parameter, die den Vorgang erstellen oder aktualisieren Network Security "Gruppe" übergeben.</span><span class="sxs-lookup"><span data-stu-id="158d3-110">Parameters supplied to the create or update network security group operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="158d3-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="158d3-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="158d3-112">Erstellt oder aktualisiert eine Netzwerksicherheitsgruppe in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-112">Creates or updates a network security group in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As INetworkSecurityGroupsOperations, resourceGroupName As String, networkSecurityGroupName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.BeginDelete (operations, resourceGroupName, networkSecurityGroupName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="158d3-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="158d3-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="158d3-114">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-114">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="158d3-115">Der Name der Netzwerksicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-115">The name of the network security group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="158d3-116">Löscht die angegebene Netzwerksicherheitsgruppe an.</span><span class="sxs-lookup"><span data-stu-id="158d3-116">Deletes the specified network security group.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, networkSecurityGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="158d3-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="158d3-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="158d3-118">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-118">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="158d3-119">Der Name der Netzwerksicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-119">The name of the network security group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="158d3-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="158d3-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="158d3-121">Löscht die angegebene Netzwerksicherheitsgruppe an.</span><span class="sxs-lookup"><span data-stu-id="158d3-121">Deletes the specified network security group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup BeginUpdateTags (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup BeginUpdateTags(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.BeginUpdateTags(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdateTags (operations As INetworkSecurityGroupsOperations, resourceGroupName As String, networkSecurityGroupName As String, parameters As TagsObject) As NetworkSecurityGroup" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTags : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.BeginUpdateTags (operations, resourceGroupName, networkSecurityGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="158d3-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="158d3-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="158d3-123">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-123">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="158d3-124">Der Name der Netzwerksicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-124">The name of the network security group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="158d3-125">Der Parameter angegeben, um die Netzwerk-Sicherheit-RFID-Transponder zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="158d3-125">Parameters supplied to update network security group tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="158d3-126">Aktualisiert ein Netzwerk Security Group-Tags an.</span><span class="sxs-lookup"><span data-stu-id="158d3-126">Updates a network security group tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; BeginUpdateTagsAsync (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; BeginUpdateTagsAsync(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.BeginUpdateTagsAsync(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTagsAsync : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.BeginUpdateTagsAsync (operations, resourceGroupName, networkSecurityGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions/&lt;BeginUpdateTagsAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="158d3-127">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="158d3-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="158d3-128">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-128">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="158d3-129">Der Name der Netzwerksicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-129">The name of the network security group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="158d3-130">Der Parameter angegeben, um die Netzwerk-Sicherheit-RFID-Transponder zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="158d3-130">Parameters supplied to update network security group tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="158d3-131">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="158d3-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="158d3-132">Aktualisiert ein Netzwerk Security Group-Tags an.</span><span class="sxs-lookup"><span data-stu-id="158d3-132">Updates a network security group tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup CreateOrUpdate (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup CreateOrUpdate(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As INetworkSecurityGroupsOperations, resourceGroupName As String, networkSecurityGroupName As String, parameters As NetworkSecurityGroup) As NetworkSecurityGroup" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * string * Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup -&gt; Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, networkSecurityGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="158d3-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="158d3-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="158d3-134">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-134">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="158d3-135">Der Name der Netzwerksicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-135">The name of the network security group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="158d3-136">Parameter, die den Vorgang erstellen oder aktualisieren Network Security "Gruppe" übergeben.</span><span class="sxs-lookup"><span data-stu-id="158d3-136">Parameters supplied to the create or update network security group operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="158d3-137">Erstellt oder aktualisiert eine Netzwerksicherheitsgruppe in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-137">Creates or updates a network security group in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * string * Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, networkSecurityGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="158d3-138">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="158d3-138">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="158d3-139">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-139">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="158d3-140">Der Name der Netzwerksicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-140">The name of the network security group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="158d3-141">Parameter, die den Vorgang erstellen oder aktualisieren Network Security "Gruppe" übergeben.</span><span class="sxs-lookup"><span data-stu-id="158d3-141">Parameters supplied to the create or update network security group operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="158d3-142">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="158d3-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="158d3-143">Erstellt oder aktualisiert eine Netzwerksicherheitsgruppe in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-143">Creates or updates a network security group in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.Delete(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As INetworkSecurityGroupsOperations, resourceGroupName As String, networkSecurityGroupName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.Delete (operations, resourceGroupName, networkSecurityGroupName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="158d3-144">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="158d3-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="158d3-145">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-145">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="158d3-146">Der Name der Netzwerksicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-146">The name of the network security group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="158d3-147">Löscht die angegebene Netzwerksicherheitsgruppe an.</span><span class="sxs-lookup"><span data-stu-id="158d3-147">Deletes the specified network security group.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.DeleteAsync (operations, resourceGroupName, networkSecurityGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="158d3-148">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="158d3-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="158d3-149">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-149">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="158d3-150">Der Name der Netzwerksicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-150">The name of the network security group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="158d3-151">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="158d3-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="158d3-152">Löscht die angegebene Netzwerksicherheitsgruppe an.</span><span class="sxs-lookup"><span data-stu-id="158d3-152">Deletes the specified network security group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup Get (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup Get(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.Get(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As INetworkSecurityGroupsOperations, resourceGroupName As String, networkSecurityGroupName As String, Optional expand As String = null) As NetworkSecurityGroup" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.Get (operations, resourceGroupName, networkSecurityGroupName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="158d3-153">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="158d3-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="158d3-154">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-154">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="158d3-155">Der Name der Netzwerksicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-155">The name of the network security group.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="158d3-156">Wird erweitert, referenzierte Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="158d3-156">Expands referenced resources.</span></span>
            </param>
        <summary>
            <span data-ttu-id="158d3-157">Ruft die angegebene Netzwerksicherheitsgruppe ab.</span><span class="sxs-lookup"><span data-stu-id="158d3-157">Gets the specified network security group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; GetAsync (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; GetAsync(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.GetAsync (operations, resourceGroupName, networkSecurityGroupName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="158d3-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="158d3-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="158d3-159">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-159">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="158d3-160">Der Name der Netzwerksicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-160">The name of the network security group.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="158d3-161">Wird erweitert, referenzierte Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="158d3-161">Expands referenced resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="158d3-162">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="158d3-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="158d3-163">Ruft die angegebene Netzwerksicherheitsgruppe ab.</span><span class="sxs-lookup"><span data-stu-id="158d3-163">Gets the specified network security group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; List (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; List(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.List(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As INetworkSecurityGroupsOperations, resourceGroupName As String) As IPage(Of NetworkSecurityGroup)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="158d3-164">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="158d3-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="158d3-165">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-165">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="158d3-166">Ruft alle netzwerksicherheitsgruppen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-166">Gets all network security groups in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAll">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; ListAll (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; ListAll(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.ListAll(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAll (operations As INetworkSecurityGroupsOperations) As IPage(Of NetworkSecurityGroup)" />
      <MemberSignature Language="F#" Value="static member ListAll : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.ListAll operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="158d3-167">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="158d3-167">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="158d3-168">Ruft alle netzwerksicherheitsgruppen in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="158d3-168">Gets all network security groups in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt;" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions/&lt;ListAllAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="158d3-169">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="158d3-169">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="158d3-170">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="158d3-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="158d3-171">Ruft alle netzwerksicherheitsgruppen in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="158d3-171">Gets all network security groups in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; ListAllNext (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; ListAllNext(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.ListAllNext(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAllNext (operations As INetworkSecurityGroupsOperations, nextPageLink As String) As IPage(Of NetworkSecurityGroup)" />
      <MemberSignature Language="F#" Value="static member ListAllNext : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.ListAllNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="158d3-172">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="158d3-172">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="158d3-173">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="158d3-173">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="158d3-174">Ruft alle netzwerksicherheitsgruppen in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="158d3-174">Gets all network security groups in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt;" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions/&lt;ListAllNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="158d3-175">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="158d3-175">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="158d3-176">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="158d3-176">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="158d3-177">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="158d3-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="158d3-178">Ruft alle netzwerksicherheitsgruppen in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="158d3-178">Gets all network security groups in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt;" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="158d3-179">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="158d3-179">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="158d3-180">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-180">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="158d3-181">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="158d3-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="158d3-182">Ruft alle netzwerksicherheitsgruppen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-182">Gets all network security groups in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; ListNext (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; ListNext(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As INetworkSecurityGroupsOperations, nextPageLink As String) As IPage(Of NetworkSecurityGroup)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="158d3-183">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="158d3-183">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="158d3-184">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="158d3-184">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="158d3-185">Ruft alle netzwerksicherheitsgruppen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-185">Gets all network security groups in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt;" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions/&lt;ListNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="158d3-186">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="158d3-186">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="158d3-187">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="158d3-187">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="158d3-188">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="158d3-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="158d3-189">Ruft alle netzwerksicherheitsgruppen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-189">Gets all network security groups in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup UpdateTags (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup UpdateTags(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.UpdateTags(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateTags (operations As INetworkSecurityGroupsOperations, resourceGroupName As String, networkSecurityGroupName As String, parameters As TagsObject) As NetworkSecurityGroup" />
      <MemberSignature Language="F#" Value="static member UpdateTags : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.UpdateTags (operations, resourceGroupName, networkSecurityGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="158d3-190">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="158d3-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="158d3-191">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-191">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="158d3-192">Der Name der Netzwerksicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-192">The name of the network security group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="158d3-193">Der Parameter angegeben, um die Netzwerk-Sicherheit-RFID-Transponder zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="158d3-193">Parameters supplied to update network security group tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="158d3-194">Aktualisiert ein Netzwerk Security Group-Tags an.</span><span class="sxs-lookup"><span data-stu-id="158d3-194">Updates a network security group tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; UpdateTagsAsync (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; UpdateTagsAsync(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.UpdateTagsAsync(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateTagsAsync : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.UpdateTagsAsync (operations, resourceGroupName, networkSecurityGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions/&lt;UpdateTagsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="158d3-195">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="158d3-195">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="158d3-196">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-196">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="158d3-197">Der Name der Netzwerksicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="158d3-197">The name of the network security group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="158d3-198">Der Parameter angegeben, um die Netzwerk-Sicherheit-RFID-Transponder zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="158d3-198">Parameters supplied to update network security group tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="158d3-199">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="158d3-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="158d3-200">Aktualisiert ein Netzwerk Security Group-Tags an.</span><span class="sxs-lookup"><span data-stu-id="158d3-200">Updates a network security group tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>