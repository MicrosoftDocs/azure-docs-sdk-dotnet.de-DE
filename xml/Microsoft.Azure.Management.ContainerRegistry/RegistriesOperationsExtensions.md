<Type Name="RegistriesOperationsExtensions" FullName="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RegistriesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RegistriesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RegistriesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RegistriesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1c972-101">Erweiterungsmethoden für RegistriesOperations.</span><span class="sxs-lookup"><span data-stu-id="1c972-101">Extension methods for RegistriesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.Registry BeginCreate (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, Microsoft.Azure.Management.ContainerRegistry.Models.Registry registry);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.Registry BeginCreate(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, class Microsoft.Azure.Management.ContainerRegistry.Models.Registry registry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.BeginCreate(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.Registry)" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.Registry -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Registry" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.BeginCreate (operations, resourceGroupName, registryName, registry)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Registry</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="registry" Type="Microsoft.Azure.Management.ContainerRegistry.Models.Registry" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c972-103">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="1c972-103">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="1c972-104">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-104">The name of the container registry.</span></span>
            </param>
        <param name="registry">
            <span data-ttu-id="1c972-105">Die Parameter für das Erstellen einer containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-105">The parameters for creating a container registry.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-106">Erstellt eine containerregistrierung mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="1c972-106">Creates a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt; BeginCreateAsync (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, Microsoft.Azure.Management.ContainerRegistry.Models.Registry registry, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt; BeginCreateAsync(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, class Microsoft.Azure.Management.ContainerRegistry.Models.Registry registry, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.Registry,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.Registry * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, registryName, registry, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions/&lt;BeginCreateAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="registry" Type="Microsoft.Azure.Management.ContainerRegistry.Models.Registry" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c972-108">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="1c972-108">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="1c972-109">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-109">The name of the container registry.</span></span>
            </param>
        <param name="registry">
            <span data-ttu-id="1c972-110">Die Parameter für das Erstellen einer containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-110">The parameters for creating a container registry.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c972-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1c972-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-112">Erstellt eine containerregistrierung mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="1c972-112">Creates a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IRegistriesOperations, resourceGroupName As String, registryName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.BeginDelete (operations, resourceGroupName, registryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c972-114">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="1c972-114">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="1c972-115">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-115">The name of the container registry.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-116">Löscht eine containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-116">Deletes a container registry.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, registryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c972-118">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="1c972-118">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="1c972-119">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-119">The name of the container registry.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c972-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1c972-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-121">Löscht eine containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-121">Deletes a container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.Registry BeginUpdate (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters registryUpdateParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.Registry BeginUpdate(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, class Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters registryUpdateParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters)" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Registry" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.BeginUpdate (operations, resourceGroupName, registryName, registryUpdateParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Registry</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="registryUpdateParameters" Type="Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c972-123">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="1c972-123">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="1c972-124">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-124">The name of the container registry.</span></span>
            </param>
        <param name="registryUpdateParameters">
            <span data-ttu-id="1c972-125">Die Parameter für den eine containerregistrierung aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="1c972-125">The parameters for updating a container registry.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-126">Aktualisiert die containerregistrierung eines mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="1c972-126">Updates a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt; BeginUpdateAsync (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters registryUpdateParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt; BeginUpdateAsync(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, class Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters registryUpdateParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, registryName, registryUpdateParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions/&lt;BeginUpdateAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="registryUpdateParameters" Type="Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-127">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c972-128">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="1c972-128">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="1c972-129">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-129">The name of the container registry.</span></span>
            </param>
        <param name="registryUpdateParameters">
            <span data-ttu-id="1c972-130">Die Parameter für den eine containerregistrierung aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="1c972-130">The parameters for updating a container registry.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c972-131">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1c972-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-132">Aktualisiert die containerregistrierung eines mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="1c972-132">Updates a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.RegistryNameStatus CheckNameAvailability (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.RegistryNameStatus CheckNameAvailability(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.CheckNameAvailability(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckNameAvailability (operations As IRegistriesOperations, name As String) As RegistryNameStatus" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailability : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations * string -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.RegistryNameStatus" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.CheckNameAvailability (operations, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.RegistryNameStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-133">The operations group for this extension method.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1c972-134">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-134">The name of the container registry.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-135">Überprüft, ob der Containername für die Registrierung für die Verwendung verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="1c972-135">Checks whether the container registry name is available for use.</span></span> <span data-ttu-id="1c972-136">Der Name darf nur alphanumerische Zeichen, global eindeutig sein, und zwischen 5 und 50 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="1c972-136">The name must contain only alphanumeric characters, be globally unique, and between 5 and 50 characters in length.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.RegistryNameStatus&gt; CheckNameAvailabilityAsync (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.RegistryNameStatus&gt; CheckNameAvailabilityAsync(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.CheckNameAvailabilityAsync(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailabilityAsync : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.RegistryNameStatus&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.CheckNameAvailabilityAsync (operations, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions/&lt;CheckNameAvailabilityAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.RegistryNameStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-137">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-137">The operations group for this extension method.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1c972-138">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-138">The name of the container registry.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c972-139">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1c972-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-140">Überprüft, ob der Containername für die Registrierung für die Verwendung verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="1c972-140">Checks whether the container registry name is available for use.</span></span> <span data-ttu-id="1c972-141">Der Name darf nur alphanumerische Zeichen, global eindeutig sein, und zwischen 5 und 50 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="1c972-141">The name must contain only alphanumeric characters, be globally unique, and between 5 and 50 characters in length.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.Registry Create (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, Microsoft.Azure.Management.ContainerRegistry.Models.Registry registry);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.Registry Create(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, class Microsoft.Azure.Management.ContainerRegistry.Models.Registry registry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.Create(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.Registry)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.Registry -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Registry" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.Create (operations, resourceGroupName, registryName, registry)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Registry</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="registry" Type="Microsoft.Azure.Management.ContainerRegistry.Models.Registry" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-142">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-142">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c972-143">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="1c972-143">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="1c972-144">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-144">The name of the container registry.</span></span>
            </param>
        <param name="registry">
            <span data-ttu-id="1c972-145">Die Parameter für das Erstellen einer containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-145">The parameters for creating a container registry.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-146">Erstellt eine containerregistrierung mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="1c972-146">Creates a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt; CreateAsync (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, Microsoft.Azure.Management.ContainerRegistry.Models.Registry registry, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt; CreateAsync(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, class Microsoft.Azure.Management.ContainerRegistry.Models.Registry registry, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.CreateAsync(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.Registry,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.Registry * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.CreateAsync (operations, resourceGroupName, registryName, registry, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions/&lt;CreateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="registry" Type="Microsoft.Azure.Management.ContainerRegistry.Models.Registry" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-147">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-147">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c972-148">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="1c972-148">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="1c972-149">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-149">The name of the container registry.</span></span>
            </param>
        <param name="registry">
            <span data-ttu-id="1c972-150">Die Parameter für das Erstellen einer containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-150">The parameters for creating a container registry.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c972-151">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1c972-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-152">Erstellt eine containerregistrierung mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="1c972-152">Creates a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.Delete(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IRegistriesOperations, resourceGroupName As String, registryName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.Delete (operations, resourceGroupName, registryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-153">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c972-154">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="1c972-154">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="1c972-155">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-155">The name of the container registry.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-156">Löscht eine containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-156">Deletes a container registry.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.DeleteAsync (operations, resourceGroupName, registryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-157">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-157">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c972-158">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="1c972-158">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="1c972-159">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-159">The name of the container registry.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c972-160">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1c972-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-161">Löscht eine containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-161">Deletes a container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.Registry Get (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.Registry Get(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.Get(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IRegistriesOperations, resourceGroupName As String, registryName As String) As Registry" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations * string * string -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Registry" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.Get (operations, resourceGroupName, registryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Registry</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-162">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-162">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c972-163">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="1c972-163">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="1c972-164">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-164">The name of the container registry.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-165">Ruft die Eigenschaften der Registrierung angegebenen Container ab.</span><span class="sxs-lookup"><span data-stu-id="1c972-165">Gets the properties of the specified container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt; GetAsync (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt; GetAsync(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.GetAsync(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.GetAsync (operations, resourceGroupName, registryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-166">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-166">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c972-167">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="1c972-167">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="1c972-168">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-168">The name of the container registry.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c972-169">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1c972-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-170">Ruft die Eigenschaften der Registrierung angegebenen Container ab.</span><span class="sxs-lookup"><span data-stu-id="1c972-170">Gets the properties of the specified container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt; List (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt; List(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.List(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IRegistriesOperations) As IPage(Of Registry)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-171">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-171">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-172">Listet alle Registrierungen, die Container unter dem angegebenen Abonnement.</span><span class="sxs-lookup"><span data-stu-id="1c972-172">Lists all the container registries under the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;&gt; ListAsync (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;&gt; ListAsync(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.ListAsync(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions/&lt;ListAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-173">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-173">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c972-174">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1c972-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-175">Listet alle Registrierungen, die Container unter dem angegebenen Abonnement.</span><span class="sxs-lookup"><span data-stu-id="1c972-175">Lists all the container registries under the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt; ListByResourceGroup (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt; ListByResourceGroup(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IRegistriesOperations, resourceGroupName As String) As IPage(Of Registry)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-176">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-176">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c972-177">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="1c972-177">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-178">Listet alle Container-Registrierungen unter der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1c972-178">Lists all the container registries under the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-179">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-179">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c972-180">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="1c972-180">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c972-181">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1c972-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-182">Listet alle Container-Registrierungen unter der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1c972-182">Lists all the container registries under the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IRegistriesOperations, nextPageLink As String) As IPage(Of Registry)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-183">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-183">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1c972-184">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1c972-184">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-185">Listet alle Container-Registrierungen unter der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1c972-185">Lists all the container registries under the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-186">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-186">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1c972-187">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1c972-187">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c972-188">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1c972-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-189">Listet alle Container-Registrierungen unter der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1c972-189">Lists all the container registries under the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCredentials">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.RegistryListCredentialsResult ListCredentials (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.RegistryListCredentialsResult ListCredentials(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.ListCredentials(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListCredentials (operations As IRegistriesOperations, resourceGroupName As String, registryName As String) As RegistryListCredentialsResult" />
      <MemberSignature Language="F#" Value="static member ListCredentials : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations * string * string -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.RegistryListCredentialsResult" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.ListCredentials (operations, resourceGroupName, registryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.RegistryListCredentialsResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-190">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c972-191">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="1c972-191">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="1c972-192">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-192">The name of the container registry.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-193">Listet die Anmeldeinformationen für die angegebene Containerregistrierung auf.</span><span class="sxs-lookup"><span data-stu-id="1c972-193">Lists the login credentials for the specified container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCredentialsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.RegistryListCredentialsResult&gt; ListCredentialsAsync (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.RegistryListCredentialsResult&gt; ListCredentialsAsync(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.ListCredentialsAsync(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListCredentialsAsync : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.RegistryListCredentialsResult&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.ListCredentialsAsync (operations, resourceGroupName, registryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions/&lt;ListCredentialsAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.RegistryListCredentialsResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-194">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-194">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c972-195">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="1c972-195">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="1c972-196">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-196">The name of the container registry.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c972-197">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1c972-197">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-198">Listet die Anmeldeinformationen für die angegebene Containerregistrierung auf.</span><span class="sxs-lookup"><span data-stu-id="1c972-198">Lists the login credentials for the specified container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt; ListNext (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt; ListNext(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.ListNext(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IRegistriesOperations, nextPageLink As String) As IPage(Of Registry)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-199">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-199">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1c972-200">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1c972-200">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-201">Listet alle Registrierungen, die Container unter dem angegebenen Abonnement.</span><span class="sxs-lookup"><span data-stu-id="1c972-201">Lists all the container registries under the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions/&lt;ListNextAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-202">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-202">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1c972-203">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1c972-203">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c972-204">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1c972-204">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-205">Listet alle Registrierungen, die Container unter dem angegebenen Abonnement.</span><span class="sxs-lookup"><span data-stu-id="1c972-205">Lists all the container registries under the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsages">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUsageListResult ListUsages (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUsageListResult ListUsages(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.ListUsages(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListUsages (operations As IRegistriesOperations, resourceGroupName As String, registryName As String) As RegistryUsageListResult" />
      <MemberSignature Language="F#" Value="static member ListUsages : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations * string * string -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUsageListResult" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.ListUsages (operations, resourceGroupName, registryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUsageListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-206">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-206">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c972-207">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="1c972-207">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="1c972-208">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-208">The name of the container registry.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-209">Ruft die kontingentverwendung für die Registrierung des angegebenen Container ab.</span><span class="sxs-lookup"><span data-stu-id="1c972-209">Gets the quota usages for the specified container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsagesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUsageListResult&gt; ListUsagesAsync (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUsageListResult&gt; ListUsagesAsync(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.ListUsagesAsync(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListUsagesAsync : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUsageListResult&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.ListUsagesAsync (operations, resourceGroupName, registryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions/&lt;ListUsagesAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUsageListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-210">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-210">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c972-211">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="1c972-211">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="1c972-212">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-212">The name of the container registry.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c972-213">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1c972-213">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-214">Ruft die kontingentverwendung für die Registrierung des angegebenen Container ab.</span><span class="sxs-lookup"><span data-stu-id="1c972-214">Gets the quota usages for the specified container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateCredential">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.RegistryListCredentialsResult RegenerateCredential (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, Microsoft.Azure.Management.ContainerRegistry.Models.PasswordName name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.RegistryListCredentialsResult RegenerateCredential(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, valuetype Microsoft.Azure.Management.ContainerRegistry.Models.PasswordName name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.RegenerateCredential(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.PasswordName)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateCredential (operations As IRegistriesOperations, resourceGroupName As String, registryName As String, name As PasswordName) As RegistryListCredentialsResult" />
      <MemberSignature Language="F#" Value="static member RegenerateCredential : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.PasswordName -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.RegistryListCredentialsResult" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.RegenerateCredential (operations, resourceGroupName, registryName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.RegistryListCredentialsResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="name" Type="Microsoft.Azure.Management.ContainerRegistry.Models.PasswordName" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-215">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-215">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c972-216">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="1c972-216">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="1c972-217">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-217">The name of the container registry.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1c972-218">Gibt das Kennwort das neu generiert werden soll – Kennwort oder password2 Namen.</span><span class="sxs-lookup"><span data-stu-id="1c972-218">Specifies name of the password which should be regenerated -- password or password2.</span></span> <span data-ttu-id="1c972-219">Folgende Werte sind möglich: "Kennwort", "password2"</span><span class="sxs-lookup"><span data-stu-id="1c972-219">Possible values include: 'password', 'password2'</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-220">Generiert eine der Anmeldeinformationen des für die Registrierung des angegebenen Container.</span><span class="sxs-lookup"><span data-stu-id="1c972-220">Regenerates one of the login credentials for the specified container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateCredentialAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.RegistryListCredentialsResult&gt; RegenerateCredentialAsync (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, Microsoft.Azure.Management.ContainerRegistry.Models.PasswordName name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.RegistryListCredentialsResult&gt; RegenerateCredentialAsync(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, valuetype Microsoft.Azure.Management.ContainerRegistry.Models.PasswordName name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.RegenerateCredentialAsync(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.PasswordName,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateCredentialAsync : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.PasswordName * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.RegistryListCredentialsResult&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.RegenerateCredentialAsync (operations, resourceGroupName, registryName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions/&lt;RegenerateCredentialAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.RegistryListCredentialsResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="name" Type="Microsoft.Azure.Management.ContainerRegistry.Models.PasswordName" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-221">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-221">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c972-222">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="1c972-222">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="1c972-223">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-223">The name of the container registry.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1c972-224">Gibt das Kennwort das neu generiert werden soll – Kennwort oder password2 Namen.</span><span class="sxs-lookup"><span data-stu-id="1c972-224">Specifies name of the password which should be regenerated -- password or password2.</span></span> <span data-ttu-id="1c972-225">Folgende Werte sind möglich: "Kennwort", "password2"</span><span class="sxs-lookup"><span data-stu-id="1c972-225">Possible values include: 'password', 'password2'</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c972-226">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1c972-226">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-227">Generiert eine der Anmeldeinformationen des für die Registrierung des angegebenen Container.</span><span class="sxs-lookup"><span data-stu-id="1c972-227">Regenerates one of the login credentials for the specified container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.Registry Update (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters registryUpdateParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.Registry Update(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, class Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters registryUpdateParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.Update(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Registry" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.Update (operations, resourceGroupName, registryName, registryUpdateParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Registry</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="registryUpdateParameters" Type="Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-228">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-228">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c972-229">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="1c972-229">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="1c972-230">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-230">The name of the container registry.</span></span>
            </param>
        <param name="registryUpdateParameters">
            <span data-ttu-id="1c972-231">Die Parameter für den eine containerregistrierung aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="1c972-231">The parameters for updating a container registry.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-232">Aktualisiert die containerregistrierung eines mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="1c972-232">Updates a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt; UpdateAsync (this Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters registryUpdateParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt; UpdateAsync(class Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations operations, string resourceGroupName, string registryName, class Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters registryUpdateParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions.UpdateAsync (operations, resourceGroupName, registryName, registryUpdateParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.RegistriesOperationsExtensions/&lt;UpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Registry&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IRegistriesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="registryUpdateParameters" Type="Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c972-233">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1c972-233">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c972-234">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="1c972-234">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="1c972-235">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="1c972-235">The name of the container registry.</span></span>
            </param>
        <param name="registryUpdateParameters">
            <span data-ttu-id="1c972-236">Die Parameter für den eine containerregistrierung aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="1c972-236">The parameters for updating a container registry.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c972-237">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1c972-237">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c972-238">Aktualisiert die containerregistrierung eines mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="1c972-238">Updates a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>