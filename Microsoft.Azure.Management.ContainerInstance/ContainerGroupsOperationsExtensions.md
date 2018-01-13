<Type Name="ContainerGroupsOperationsExtensions" FullName="Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ContainerGroupsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ContainerGroupsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ContainerGroupsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ContainerGroupsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
    <AssemblyVersion>0.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="cf9f8-101">Erweiterungsmethoden für ContainerGroupsOperations.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-101">Extension methods for ContainerGroupsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup CreateOrUpdate (this Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations operations, string resourceGroupName, string containerGroupName, Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup containerGroup);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup CreateOrUpdate(class Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations operations, string resourceGroupName, string containerGroupName, class Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup containerGroup) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations,System.String,System.String,Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations * string * string * Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup -&gt; Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup" Usage="Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, containerGroupName, containerGroup)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerGroupName" Type="System.String" />
        <Parameter Name="containerGroup" Type="Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cf9f8-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cf9f8-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-103">The name of the resource group.</span></span>
            </param>
        <param name="containerGroupName">
            <span data-ttu-id="cf9f8-104">Der Name der Gruppe "Container".</span><span class="sxs-lookup"><span data-stu-id="cf9f8-104">The name of the container group.</span></span>
            </param>
        <param name="containerGroup">
            <span data-ttu-id="cf9f8-105">Die Eigenschaften der Gruppe "Container" erstellt oder aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-105">The properties of the container group to be created or updated.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf9f8-106">Erstellen oder Aktualisieren von Containergruppen.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-106">Create or update container groups.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cf9f8-107">Erstellen oder Aktualisieren von Containergruppen mit festgelegten Konfigurationen.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-107">Create or update container groups with specified configurations.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations operations, string resourceGroupName, string containerGroupName, Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup containerGroup, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations operations, string resourceGroupName, string containerGroupName, class Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup containerGroup, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations,System.String,System.String,Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations * string * string * Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;" Usage="Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, containerGroupName, containerGroup, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerGroupName" Type="System.String" />
        <Parameter Name="containerGroup" Type="Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cf9f8-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cf9f8-109">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-109">The name of the resource group.</span></span>
            </param>
        <param name="containerGroupName">
            <span data-ttu-id="cf9f8-110">Der Name der Gruppe "Container".</span><span class="sxs-lookup"><span data-stu-id="cf9f8-110">The name of the container group.</span></span>
            </param>
        <param name="containerGroup">
            <span data-ttu-id="cf9f8-111">Die Eigenschaften der Gruppe "Container" erstellt oder aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-111">The properties of the container group to be created or updated.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cf9f8-112">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf9f8-113">Erstellen oder Aktualisieren von Containergruppen.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-113">Create or update container groups.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cf9f8-114">Erstellen oder Aktualisieren von Containergruppen mit festgelegten Konfigurationen.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-114">Create or update container groups with specified configurations.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup Delete (this Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations operations, string resourceGroupName, string containerGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup Delete(class Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations operations, string resourceGroupName, string containerGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions.Delete(Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IContainerGroupsOperations, resourceGroupName As String, containerGroupName As String) As ContainerGroup" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations * string * string -&gt; Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup" Usage="Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions.Delete (operations, resourceGroupName, containerGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cf9f8-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cf9f8-116">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-116">The name of the resource group.</span></span>
            </param>
        <param name="containerGroupName">
            <span data-ttu-id="cf9f8-117">Der Name der Gruppe "Container".</span><span class="sxs-lookup"><span data-stu-id="cf9f8-117">The name of the container group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf9f8-118">Löschen Sie die Gruppe angegebenen Container.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-118">Delete the specified container group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cf9f8-119">Löschen Sie die Gruppe der angegebenen Container im angegebenen Abonnement und die Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-119">Delete the specified container group in the specified subscription and resource group.</span></span> <span data-ttu-id="cf9f8-120">Der Vorgang löscht keine anderen Ressourcen, die vom Benutzer, z. B. Volumes bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-120">The operation does not delete other resources provided by the user, such as volumes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt; DeleteAsync (this Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations operations, string resourceGroupName, string containerGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt; DeleteAsync(class Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations operations, string resourceGroupName, string containerGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;" Usage="Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions.DeleteAsync (operations, resourceGroupName, containerGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions/&lt;DeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cf9f8-121">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-121">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cf9f8-122">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-122">The name of the resource group.</span></span>
            </param>
        <param name="containerGroupName">
            <span data-ttu-id="cf9f8-123">Der Name der Gruppe "Container".</span><span class="sxs-lookup"><span data-stu-id="cf9f8-123">The name of the container group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cf9f8-124">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf9f8-125">Löschen Sie die Gruppe angegebenen Container.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-125">Delete the specified container group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cf9f8-126">Löschen Sie die Gruppe der angegebenen Container im angegebenen Abonnement und die Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-126">Delete the specified container group in the specified subscription and resource group.</span></span> <span data-ttu-id="cf9f8-127">Der Vorgang löscht keine anderen Ressourcen, die vom Benutzer, z. B. Volumes bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-127">The operation does not delete other resources provided by the user, such as volumes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup Get (this Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations operations, string resourceGroupName, string containerGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup Get(class Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations operations, string resourceGroupName, string containerGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions.Get(Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IContainerGroupsOperations, resourceGroupName As String, containerGroupName As String) As ContainerGroup" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations * string * string -&gt; Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup" Usage="Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions.Get (operations, resourceGroupName, containerGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cf9f8-128">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cf9f8-129">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-129">The name of the resource group.</span></span>
            </param>
        <param name="containerGroupName">
            <span data-ttu-id="cf9f8-130">Der Name der Gruppe "Container".</span><span class="sxs-lookup"><span data-stu-id="cf9f8-130">The name of the container group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf9f8-131">Rufen Sie die Eigenschaften der Gruppe "angegebenen Container".</span><span class="sxs-lookup"><span data-stu-id="cf9f8-131">Get the properties of the specified container group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cf9f8-132">Ruft die Eigenschaften des angegebenen Container Gruppieren im angegebenen Abonnement oder Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-132">Gets the properties of the specified container group in the specified subscription and resource group.</span></span> <span data-ttu-id="cf9f8-133">Der Vorgang gibt die Eigenschaften der Gruppe "jeder Container" Containers Image Registrierung Anmeldeinformationen, einschließlich Richtlinie, IP-Adresstyp, BS-Typ, Zustand und Volumes neu gestartet.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-133">The operation returns the properties of each container group including containers, image registry credentials, restart policy, IP address type, OS type, state, and volumes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt; GetAsync (this Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations operations, string resourceGroupName, string containerGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt; GetAsync(class Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations operations, string resourceGroupName, string containerGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions.GetAsync(Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;" Usage="Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions.GetAsync (operations, resourceGroupName, containerGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cf9f8-134">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cf9f8-135">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-135">The name of the resource group.</span></span>
            </param>
        <param name="containerGroupName">
            <span data-ttu-id="cf9f8-136">Der Name der Gruppe "Container".</span><span class="sxs-lookup"><span data-stu-id="cf9f8-136">The name of the container group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cf9f8-137">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf9f8-138">Rufen Sie die Eigenschaften der Gruppe "angegebenen Container".</span><span class="sxs-lookup"><span data-stu-id="cf9f8-138">Get the properties of the specified container group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cf9f8-139">Ruft die Eigenschaften des angegebenen Container Gruppieren im angegebenen Abonnement oder Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-139">Gets the properties of the specified container group in the specified subscription and resource group.</span></span> <span data-ttu-id="cf9f8-140">Der Vorgang gibt die Eigenschaften der Gruppe "jeder Container" Containers Image Registrierung Anmeldeinformationen, einschließlich Richtlinie, IP-Adresstyp, BS-Typ, Zustand und Volumes neu gestartet.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-140">The operation returns the properties of each container group including containers, image registry credentials, restart policy, IP address type, OS type, state, and volumes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt; List (this Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt; List(class Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions.List(Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IContainerGroupsOperations) As IPage(Of ContainerGroup)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;" Usage="Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cf9f8-141">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-141">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf9f8-142">Abrufen einer Liste von Containergruppen im angegebenen Abonnement.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-142">Get a list of container groups in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cf9f8-143">Abrufen einer Liste von Containergruppen im angegebenen Abonnement.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-143">Get a list of container groups in the specified subscription.</span></span> <span data-ttu-id="cf9f8-144">Dieser Vorgang gibt die Eigenschaften der einzelnen Containergruppen, einschließlich Container, Image Registrierung Anmeldeinformationen Neustartrichtlinie, IP-Adresstyp, BS-Typ, Zustand und Volumes zurück.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-144">This operation returns properties of each container group including containers, image registry credentials, restart policy, IP address type, OS type, state, and volumes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt; ListAsync (this Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt; ListAsync(class Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions.ListAsync(Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;" Usage="Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cf9f8-145">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-145">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cf9f8-146">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf9f8-147">Abrufen einer Liste von Containergruppen im angegebenen Abonnement.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-147">Get a list of container groups in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cf9f8-148">Abrufen einer Liste von Containergruppen im angegebenen Abonnement.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-148">Get a list of container groups in the specified subscription.</span></span> <span data-ttu-id="cf9f8-149">Dieser Vorgang gibt die Eigenschaften der einzelnen Containergruppen, einschließlich Container, Image Registrierung Anmeldeinformationen Neustartrichtlinie, IP-Adresstyp, BS-Typ, Zustand und Volumes zurück.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-149">This operation returns properties of each container group including containers, image registry credentials, restart policy, IP address type, OS type, state, and volumes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt; ListByResourceGroup (this Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt; ListByResourceGroup(class Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IContainerGroupsOperations, resourceGroupName As String) As IPage(Of ContainerGroup)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;" Usage="Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cf9f8-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cf9f8-151">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-151">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf9f8-152">Ruft eine Liste der Containergruppen in der angegebenen Abonnement und die Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-152">Get a list of container groups in the specified subscription and resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cf9f8-153">Ruft eine Liste der Containergruppen in einem angegebenen Abonnement und die Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-153">Get a list of container groups in a specified subscription and resource group.</span></span> <span data-ttu-id="cf9f8-154">Dieser Vorgang gibt die Eigenschaften der einzelnen Containergruppen, einschließlich Container, Image Registrierung Anmeldeinformationen Neustartrichtlinie, IP-Adresstyp, BS-Typ, Zustand und Volumes zurück.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-154">This operation returns properties of each container group including containers, image registry credentials, restart policy, IP address type, OS type, state, and volumes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;" Usage="Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cf9f8-155">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cf9f8-156">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-156">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cf9f8-157">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf9f8-158">Ruft eine Liste der Containergruppen in der angegebenen Abonnement und die Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-158">Get a list of container groups in the specified subscription and resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cf9f8-159">Ruft eine Liste der Containergruppen in einem angegebenen Abonnement und die Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-159">Get a list of container groups in a specified subscription and resource group.</span></span> <span data-ttu-id="cf9f8-160">Dieser Vorgang gibt die Eigenschaften der einzelnen Containergruppen, einschließlich Container, Image Registrierung Anmeldeinformationen Neustartrichtlinie, IP-Adresstyp, BS-Typ, Zustand und Volumes zurück.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-160">This operation returns properties of each container group including containers, image registry credentials, restart policy, IP address type, OS type, state, and volumes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IContainerGroupsOperations, nextPageLink As String) As IPage(Of ContainerGroup)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;" Usage="Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cf9f8-161">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-161">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="cf9f8-162">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-162">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf9f8-163">Ruft eine Liste der Containergruppen in der angegebenen Abonnement und die Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-163">Get a list of container groups in the specified subscription and resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cf9f8-164">Ruft eine Liste der Containergruppen in einem angegebenen Abonnement und die Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-164">Get a list of container groups in a specified subscription and resource group.</span></span> <span data-ttu-id="cf9f8-165">Dieser Vorgang gibt die Eigenschaften der einzelnen Containergruppen, einschließlich Container, Image Registrierung Anmeldeinformationen Neustartrichtlinie, IP-Adresstyp, BS-Typ, Zustand und Volumes zurück.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-165">This operation returns properties of each container group including containers, image registry credentials, restart policy, IP address type, OS type, state, and volumes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;" Usage="Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cf9f8-166">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-166">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="cf9f8-167">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-167">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cf9f8-168">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf9f8-169">Ruft eine Liste der Containergruppen in der angegebenen Abonnement und die Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-169">Get a list of container groups in the specified subscription and resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cf9f8-170">Ruft eine Liste der Containergruppen in einem angegebenen Abonnement und die Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-170">Get a list of container groups in a specified subscription and resource group.</span></span> <span data-ttu-id="cf9f8-171">Dieser Vorgang gibt die Eigenschaften der einzelnen Containergruppen, einschließlich Container, Image Registrierung Anmeldeinformationen Neustartrichtlinie, IP-Adresstyp, BS-Typ, Zustand und Volumes zurück.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-171">This operation returns properties of each container group including containers, image registry credentials, restart policy, IP address type, OS type, state, and volumes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt; ListNext (this Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt; ListNext(class Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions.ListNext(Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IContainerGroupsOperations, nextPageLink As String) As IPage(Of ContainerGroup)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;" Usage="Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cf9f8-172">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-172">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="cf9f8-173">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-173">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf9f8-174">Abrufen einer Liste von Containergruppen im angegebenen Abonnement.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-174">Get a list of container groups in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cf9f8-175">Abrufen einer Liste von Containergruppen im angegebenen Abonnement.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-175">Get a list of container groups in the specified subscription.</span></span> <span data-ttu-id="cf9f8-176">Dieser Vorgang gibt die Eigenschaften der einzelnen Containergruppen, einschließlich Container, Image Registrierung Anmeldeinformationen Neustartrichtlinie, IP-Adresstyp, BS-Typ, Zustand und Volumes zurück.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-176">This operation returns properties of each container group including containers, image registry credentials, restart policy, IP address type, OS type, state, and volumes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;" Usage="Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerInstance.ContainerGroupsOperationsExtensions/&lt;ListNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cf9f8-177">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-177">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="cf9f8-178">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-178">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cf9f8-179">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-179">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf9f8-180">Abrufen einer Liste von Containergruppen im angegebenen Abonnement.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-180">Get a list of container groups in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cf9f8-181">Abrufen einer Liste von Containergruppen im angegebenen Abonnement.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-181">Get a list of container groups in the specified subscription.</span></span> <span data-ttu-id="cf9f8-182">Dieser Vorgang gibt die Eigenschaften der einzelnen Containergruppen, einschließlich Container, Image Registrierung Anmeldeinformationen Neustartrichtlinie, IP-Adresstyp, BS-Typ, Zustand und Volumes zurück.</span><span class="sxs-lookup"><span data-stu-id="cf9f8-182">This operation returns properties of each container group including containers, image registry credentials, restart policy, IP address type, OS type, state, and volumes.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>