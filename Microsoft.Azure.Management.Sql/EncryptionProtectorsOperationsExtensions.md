<Type Name="EncryptionProtectorsOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class EncryptionProtectorsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit EncryptionProtectorsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module EncryptionProtectorsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type EncryptionProtectorsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0cca6-101">Erweiterungsmethoden für EncryptionProtectorsOperations.</span><span class="sxs-lookup"><span data-stu-id="0cca6-101">Extension methods for EncryptionProtectorsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.EncryptionProtector BeginCreateOrUpdate (this Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.EncryptionProtector parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.EncryptionProtector BeginCreateOrUpdate(class Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.EncryptionProtector parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.EncryptionProtector)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IEncryptionProtectorsOperations, resourceGroupName As String, serverName As String, parameters As EncryptionProtector) As EncryptionProtector" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations * string * string * Microsoft.Azure.Management.Sql.Models.EncryptionProtector -&gt; Microsoft.Azure.Management.Sql.Models.EncryptionProtector" Usage="Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, serverName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.EncryptionProtector</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.EncryptionProtector" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0cca6-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0cca6-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0cca6-103">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0cca6-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0cca6-104">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0cca6-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0cca6-105">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0cca6-105">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0cca6-106">Der angeforderte Schutzvorrichtung Ressource Verschlüsselungsstatus.</span><span class="sxs-lookup"><span data-stu-id="0cca6-106">The requested encryption protector resource state.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0cca6-107">Aktualisiert eine vorhandene Verschlüsselung Schutzvorrichtung.</span><span class="sxs-lookup"><span data-stu-id="0cca6-107">Updates an existing encryption protector.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.EncryptionProtector parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.EncryptionProtector parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.EncryptionProtector,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations * string * string * Microsoft.Azure.Management.Sql.Models.EncryptionProtector * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;" Usage="Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, serverName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.EncryptionProtector" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0cca6-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0cca6-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0cca6-109">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0cca6-109">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0cca6-110">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0cca6-110">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0cca6-111">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0cca6-111">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0cca6-112">Der angeforderte Schutzvorrichtung Ressource Verschlüsselungsstatus.</span><span class="sxs-lookup"><span data-stu-id="0cca6-112">The requested encryption protector resource state.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0cca6-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0cca6-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0cca6-114">Aktualisiert eine vorhandene Verschlüsselung Schutzvorrichtung.</span><span class="sxs-lookup"><span data-stu-id="0cca6-114">Updates an existing encryption protector.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.EncryptionProtector CreateOrUpdate (this Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.EncryptionProtector parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.EncryptionProtector CreateOrUpdate(class Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.EncryptionProtector parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.EncryptionProtector)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IEncryptionProtectorsOperations, resourceGroupName As String, serverName As String, parameters As EncryptionProtector) As EncryptionProtector" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations * string * string * Microsoft.Azure.Management.Sql.Models.EncryptionProtector -&gt; Microsoft.Azure.Management.Sql.Models.EncryptionProtector" Usage="Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.EncryptionProtector</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.EncryptionProtector" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0cca6-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0cca6-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0cca6-116">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0cca6-116">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0cca6-117">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0cca6-117">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0cca6-118">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0cca6-118">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0cca6-119">Der angeforderte Schutzvorrichtung Ressource Verschlüsselungsstatus.</span><span class="sxs-lookup"><span data-stu-id="0cca6-119">The requested encryption protector resource state.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0cca6-120">Aktualisiert eine vorhandene Verschlüsselung Schutzvorrichtung.</span><span class="sxs-lookup"><span data-stu-id="0cca6-120">Updates an existing encryption protector.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.EncryptionProtector parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.EncryptionProtector parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.EncryptionProtector,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations * string * string * Microsoft.Azure.Management.Sql.Models.EncryptionProtector * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;" Usage="Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.EncryptionProtector" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0cca6-121">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0cca6-121">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0cca6-122">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0cca6-122">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0cca6-123">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0cca6-123">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0cca6-124">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0cca6-124">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0cca6-125">Der angeforderte Schutzvorrichtung Ressource Verschlüsselungsstatus.</span><span class="sxs-lookup"><span data-stu-id="0cca6-125">The requested encryption protector resource state.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0cca6-126">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0cca6-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0cca6-127">Aktualisiert eine vorhandene Verschlüsselung Schutzvorrichtung.</span><span class="sxs-lookup"><span data-stu-id="0cca6-127">Updates an existing encryption protector.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.EncryptionProtector Get (this Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.EncryptionProtector Get(class Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IEncryptionProtectorsOperations, resourceGroupName As String, serverName As String) As EncryptionProtector" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations * string * string -&gt; Microsoft.Azure.Management.Sql.Models.EncryptionProtector" Usage="Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.Get (operations, resourceGroupName, serverName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.EncryptionProtector</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0cca6-128">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0cca6-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0cca6-129">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0cca6-129">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0cca6-130">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0cca6-130">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0cca6-131">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0cca6-131">The name of the server.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0cca6-132">Ruft eine Verschlüsselung Schutzvorrichtung ab.</span><span class="sxs-lookup"><span data-stu-id="0cca6-132">Gets a server encryption protector.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt; GetAsync (this Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt; GetAsync(class Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;" Usage="Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0cca6-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0cca6-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0cca6-134">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0cca6-134">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0cca6-135">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0cca6-135">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0cca6-136">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0cca6-136">The name of the server.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0cca6-137">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0cca6-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0cca6-138">Ruft eine Verschlüsselung Schutzvorrichtung ab.</span><span class="sxs-lookup"><span data-stu-id="0cca6-138">Gets a server encryption protector.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServer">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt; ListByServer (this Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt; ListByServer(class Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.ListByServer(Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByServer (operations As IEncryptionProtectorsOperations, resourceGroupName As String, serverName As String) As IPage(Of EncryptionProtector)" />
      <MemberSignature Language="F#" Value="static member ListByServer : Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;" Usage="Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.ListByServer (operations, resourceGroupName, serverName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0cca6-139">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0cca6-139">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0cca6-140">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0cca6-140">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0cca6-141">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0cca6-141">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0cca6-142">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0cca6-142">The name of the server.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0cca6-143">Ruft eine Liste der Server-Verschlüsselung Schutzvorrichtungen</span><span class="sxs-lookup"><span data-stu-id="0cca6-143">Gets a list of server encryption protectors</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;&gt; ListByServerAsync (this Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;&gt; ListByServerAsync(class Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.ListByServerAsync(Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerAsync : Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.ListByServerAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions/&lt;ListByServerAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0cca6-144">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0cca6-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0cca6-145">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0cca6-145">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0cca6-146">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0cca6-146">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0cca6-147">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="0cca6-147">The name of the server.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0cca6-148">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0cca6-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0cca6-149">Ruft eine Liste der Server-Verschlüsselung Schutzvorrichtungen</span><span class="sxs-lookup"><span data-stu-id="0cca6-149">Gets a list of server encryption protectors</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt; ListByServerNext (this Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt; ListByServerNext(class Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.ListByServerNext(Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByServerNext (operations As IEncryptionProtectorsOperations, nextPageLink As String) As IPage(Of EncryptionProtector)" />
      <MemberSignature Language="F#" Value="static member ListByServerNext : Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;" Usage="Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.ListByServerNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0cca6-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0cca6-150">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="0cca6-151">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0cca6-151">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0cca6-152">Ruft eine Liste der Server-Verschlüsselung Schutzvorrichtungen</span><span class="sxs-lookup"><span data-stu-id="0cca6-152">Gets a list of server encryption protectors</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;&gt; ListByServerNextAsync (this Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;&gt; ListByServerNextAsync(class Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.ListByServerNextAsync(Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerNextAsync : Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.ListByServerNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions/&lt;ListByServerNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0cca6-153">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0cca6-153">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="0cca6-154">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0cca6-154">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0cca6-155">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0cca6-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0cca6-156">Ruft eine Liste der Server-Verschlüsselung Schutzvorrichtungen</span><span class="sxs-lookup"><span data-stu-id="0cca6-156">Gets a list of server encryption protectors</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>