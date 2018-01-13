<Type Name="DomainsOperationsExtensions" FullName="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DomainsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DomainsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DomainsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DomainsOperationsExtensions = class" />
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
            <span data-ttu-id="81d42-101">Erweiterungsmethoden für DomainsOperations.</span><span class="sxs-lookup"><span data-stu-id="81d42-101">Extension methods for DomainsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.Domain BeginCreateOrUpdate (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, Microsoft.Azure.Management.WebSites.Models.Domain domain);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.Domain BeginCreateOrUpdate(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, class Microsoft.Azure.Management.WebSites.Models.Domain domain) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.Domain)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * Microsoft.Azure.Management.WebSites.Models.Domain -&gt; Microsoft.Azure.Management.WebSites.Models.Domain" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, domainName, domain)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.Domain</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="domain" Type="Microsoft.Azure.Management.WebSites.Models.Domain" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="81d42-103">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="81d42-103">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="81d42-104">Der Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-104">Name of the domain.</span></span>
            </param>
        <param name="domain">
            <span data-ttu-id="81d42-105">Registrierungsinformationen Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-105">Domain registration information.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-106">Erstellt oder aktualisiert eine Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-106">Creates or updates a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-107">Erstellt oder aktualisiert eine Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-107">Creates or updates a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, Microsoft.Azure.Management.WebSites.Models.Domain domain, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, class Microsoft.Azure.Management.WebSites.Models.Domain domain, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.Domain,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * Microsoft.Azure.Management.WebSites.Models.Domain * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, domainName, domain, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="domain" Type="Microsoft.Azure.Management.WebSites.Models.Domain" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="81d42-109">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="81d42-109">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="81d42-110">Der Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-110">Name of the domain.</span></span>
            </param>
        <param name="domain">
            <span data-ttu-id="81d42-111">Registrierungsinformationen Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-111">Domain registration information.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81d42-112">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="81d42-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-113">Erstellt oder aktualisiert eine Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-113">Creates or updates a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-114">Erstellt oder aktualisiert eine Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-114">Creates or updates a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult CheckAvailability (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, Microsoft.Azure.Management.WebSites.Models.NameIdentifier identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult CheckAvailability(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, class Microsoft.Azure.Management.WebSites.Models.NameIdentifier identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.CheckAvailability(Microsoft.Azure.Management.WebSites.IDomainsOperations,Microsoft.Azure.Management.WebSites.Models.NameIdentifier)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckAvailability (operations As IDomainsOperations, identifier As NameIdentifier) As DomainAvailablilityCheckResult" />
      <MemberSignature Language="F#" Value="static member CheckAvailability : Microsoft.Azure.Management.WebSites.IDomainsOperations * Microsoft.Azure.Management.WebSites.Models.NameIdentifier -&gt; Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.CheckAvailability (operations, identifier)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="identifier" Type="Microsoft.Azure.Management.WebSites.Models.NameIdentifier" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-115">The operations group for this extension method.</span></span>
            </param>
        <param name="identifier">
            <span data-ttu-id="81d42-116">Der Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-116">Name of the domain.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-117">Überprüfen Sie, ob eine Domäne für die Registrierung verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="81d42-117">Check if a domain is available for registration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-118">Überprüfen Sie, ob eine Domäne für die Registrierung verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="81d42-118">Check if a domain is available for registration.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult&gt; CheckAvailabilityAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, Microsoft.Azure.Management.WebSites.Models.NameIdentifier identifier, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult&gt; CheckAvailabilityAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, class Microsoft.Azure.Management.WebSites.Models.NameIdentifier identifier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.CheckAvailabilityAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,Microsoft.Azure.Management.WebSites.Models.NameIdentifier,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckAvailabilityAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * Microsoft.Azure.Management.WebSites.Models.NameIdentifier * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.CheckAvailabilityAsync (operations, identifier, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;CheckAvailabilityAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="identifier" Type="Microsoft.Azure.Management.WebSites.Models.NameIdentifier" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-119">The operations group for this extension method.</span></span>
            </param>
        <param name="identifier">
            <span data-ttu-id="81d42-120">Der Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-120">Name of the domain.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81d42-121">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="81d42-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-122">Überprüfen Sie, ob eine Domäne für die Registrierung verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="81d42-122">Check if a domain is available for registration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-123">Überprüfen Sie, ob eine Domäne für die Registrierung verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="81d42-123">Check if a domain is available for registration.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.Domain CreateOrUpdate (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, Microsoft.Azure.Management.WebSites.Models.Domain domain);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.Domain CreateOrUpdate(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, class Microsoft.Azure.Management.WebSites.Models.Domain domain) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.Domain)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * Microsoft.Azure.Management.WebSites.Models.Domain -&gt; Microsoft.Azure.Management.WebSites.Models.Domain" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, domainName, domain)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.Domain</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="domain" Type="Microsoft.Azure.Management.WebSites.Models.Domain" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-124">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="81d42-125">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="81d42-125">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="81d42-126">Der Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-126">Name of the domain.</span></span>
            </param>
        <param name="domain">
            <span data-ttu-id="81d42-127">Registrierungsinformationen Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-127">Domain registration information.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-128">Erstellt oder aktualisiert eine Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-128">Creates or updates a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-129">Erstellt oder aktualisiert eine Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-129">Creates or updates a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, Microsoft.Azure.Management.WebSites.Models.Domain domain, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, class Microsoft.Azure.Management.WebSites.Models.Domain domain, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.Domain,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * Microsoft.Azure.Management.WebSites.Models.Domain * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, domainName, domain, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="domain" Type="Microsoft.Azure.Management.WebSites.Models.Domain" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="81d42-131">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="81d42-131">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="81d42-132">Der Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-132">Name of the domain.</span></span>
            </param>
        <param name="domain">
            <span data-ttu-id="81d42-133">Registrierungsinformationen Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-133">Domain registration information.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81d42-134">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="81d42-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-135">Erstellt oder aktualisiert eine Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-135">Creates or updates a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-136">Erstellt oder aktualisiert eine Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-136">Creates or updates a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateOwnershipIdentifier">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier CreateOrUpdateOwnershipIdentifier (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name, Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier domainOwnershipIdentifier);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier CreateOrUpdateOwnershipIdentifier(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name, class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier domainOwnershipIdentifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.CreateOrUpdateOwnershipIdentifier(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateOwnershipIdentifier : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * string * Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier -&gt; Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.CreateOrUpdateOwnershipIdentifier (operations, resourceGroupName, domainName, name, domainOwnershipIdentifier)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="domainOwnershipIdentifier" Type="Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-137">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="81d42-138">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="81d42-138">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="81d42-139">Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-139">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="81d42-140">Der Name eines Bezeichners.</span><span class="sxs-lookup"><span data-stu-id="81d42-140">Name of identifier.</span></span>
            </param>
        <param name="domainOwnershipIdentifier">
            <span data-ttu-id="81d42-141">Eine JSON-Darstellung der Domäne des Besitzes Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="81d42-141">A JSON representation of the domain ownership properties.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-142">Erstellt einen Bezeichner des Besitzes für einen Bezeichner Domänen- oder Updates Details für eine vorhandene Bezeichner</span><span class="sxs-lookup"><span data-stu-id="81d42-142">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-143">Erstellt einen Bezeichner des Besitzes für einen Bezeichner Domänen- oder Updates Details für eine vorhandene Bezeichner</span><span class="sxs-lookup"><span data-stu-id="81d42-143">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateOwnershipIdentifierAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt; CreateOrUpdateOwnershipIdentifierAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name, Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier domainOwnershipIdentifier, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt; CreateOrUpdateOwnershipIdentifierAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name, class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier domainOwnershipIdentifier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.CreateOrUpdateOwnershipIdentifierAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateOwnershipIdentifierAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * string * Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.CreateOrUpdateOwnershipIdentifierAsync (operations, resourceGroupName, domainName, name, domainOwnershipIdentifier, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;CreateOrUpdateOwnershipIdentifierAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="domainOwnershipIdentifier" Type="Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-144">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="81d42-145">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="81d42-145">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="81d42-146">Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-146">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="81d42-147">Der Name eines Bezeichners.</span><span class="sxs-lookup"><span data-stu-id="81d42-147">Name of identifier.</span></span>
            </param>
        <param name="domainOwnershipIdentifier">
            <span data-ttu-id="81d42-148">Eine JSON-Darstellung der Domäne des Besitzes Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="81d42-148">A JSON representation of the domain ownership properties.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81d42-149">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="81d42-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-150">Erstellt einen Bezeichner des Besitzes für einen Bezeichner Domänen- oder Updates Details für eine vorhandene Bezeichner</span><span class="sxs-lookup"><span data-stu-id="81d42-150">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-151">Erstellt einen Bezeichner des Besitzes für einen Bezeichner Domänen- oder Updates Details für eine vorhandene Bezeichner</span><span class="sxs-lookup"><span data-stu-id="81d42-151">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, Nullable&lt;bool&gt; forceHardDeleteDomain = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, valuetype System.Nullable`1&lt;bool&gt; forceHardDeleteDomain) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.Delete(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IDomainsOperations, resourceGroupName As String, domainName As String, Optional forceHardDeleteDomain As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * Nullable&lt;bool&gt; -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.Delete (operations, resourceGroupName, domainName, forceHardDeleteDomain)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="forceHardDeleteDomain" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-152">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-152">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="81d42-153">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="81d42-153">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="81d42-154">Der Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-154">Name of the domain.</span></span>
            </param>
        <param name="forceHardDeleteDomain">
            <span data-ttu-id="81d42-155">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; zum sofortigen Löschen die Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-155">Specify &lt;code&gt;true&lt;/code&gt; to delete the domain immediately.</span></span> <span data-ttu-id="81d42-156">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt; die Domäne nach 24 Stunden gelöscht.</span><span class="sxs-lookup"><span data-stu-id="81d42-156">The default is &lt;code&gt;false&lt;/code&gt; which deletes the domain after 24 hours.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-157">Löschen einer Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-157">Delete a domain.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="81d42-158">Löschen einer Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-158">Delete a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, Nullable&lt;bool&gt; forceHardDeleteDomain = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, valuetype System.Nullable`1&lt;bool&gt; forceHardDeleteDomain, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.DeleteAsync (operations, resourceGroupName, domainName, forceHardDeleteDomain, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;DeleteAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="forceHardDeleteDomain" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-159">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-159">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="81d42-160">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="81d42-160">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="81d42-161">Der Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-161">Name of the domain.</span></span>
            </param>
        <param name="forceHardDeleteDomain">
            <span data-ttu-id="81d42-162">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; zum sofortigen Löschen die Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-162">Specify &lt;code&gt;true&lt;/code&gt; to delete the domain immediately.</span></span> <span data-ttu-id="81d42-163">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt; die Domäne nach 24 Stunden gelöscht.</span><span class="sxs-lookup"><span data-stu-id="81d42-163">The default is &lt;code&gt;false&lt;/code&gt; which deletes the domain after 24 hours.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81d42-164">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="81d42-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-165">Löschen einer Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-165">Delete a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-166">Löschen einer Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-166">Delete a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteOwnershipIdentifier">
      <MemberSignature Language="C#" Value="public static void DeleteOwnershipIdentifier (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteOwnershipIdentifier(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.DeleteOwnershipIdentifier(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteOwnershipIdentifier (operations As IDomainsOperations, resourceGroupName As String, domainName As String, name As String)" />
      <MemberSignature Language="F#" Value="static member DeleteOwnershipIdentifier : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.DeleteOwnershipIdentifier (operations, resourceGroupName, domainName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-167">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-167">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="81d42-168">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="81d42-168">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="81d42-169">Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-169">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="81d42-170">Der Name eines Bezeichners.</span><span class="sxs-lookup"><span data-stu-id="81d42-170">Name of identifier.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-171">Löschen Sie den Besitz Bezeichner für die Domäne</span><span class="sxs-lookup"><span data-stu-id="81d42-171">Delete ownership identifier for domain</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="81d42-172">Löschen Sie den Besitz Bezeichner für die Domäne</span><span class="sxs-lookup"><span data-stu-id="81d42-172">Delete ownership identifier for domain</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteOwnershipIdentifierAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteOwnershipIdentifierAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteOwnershipIdentifierAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.DeleteOwnershipIdentifierAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteOwnershipIdentifierAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.DeleteOwnershipIdentifierAsync (operations, resourceGroupName, domainName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;DeleteOwnershipIdentifierAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-173">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-173">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="81d42-174">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="81d42-174">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="81d42-175">Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-175">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="81d42-176">Der Name eines Bezeichners.</span><span class="sxs-lookup"><span data-stu-id="81d42-176">Name of identifier.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81d42-177">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="81d42-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-178">Löschen Sie den Besitz Bezeichner für die Domäne</span><span class="sxs-lookup"><span data-stu-id="81d42-178">Delete ownership identifier for domain</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-179">Löschen Sie den Besitz Bezeichner für die Domäne</span><span class="sxs-lookup"><span data-stu-id="81d42-179">Delete ownership identifier for domain</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.Domain Get (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.Domain Get(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.Get(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDomainsOperations, resourceGroupName As String, domainName As String) As Domain" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.Domain" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.Get (operations, resourceGroupName, domainName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.Domain</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-180">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-180">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="81d42-181">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="81d42-181">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="81d42-182">Der Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-182">Name of the domain.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-183">Abrufen einer Domänenkontos an.</span><span class="sxs-lookup"><span data-stu-id="81d42-183">Get a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-184">Abrufen einer Domänenkontos an.</span><span class="sxs-lookup"><span data-stu-id="81d42-184">Get a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt; GetAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt; GetAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.GetAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.GetAsync (operations, resourceGroupName, domainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;GetAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-185">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-185">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="81d42-186">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="81d42-186">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="81d42-187">Der Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-187">Name of the domain.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81d42-188">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="81d42-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-189">Abrufen einer Domänenkontos an.</span><span class="sxs-lookup"><span data-stu-id="81d42-189">Get a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-190">Abrufen einer Domänenkontos an.</span><span class="sxs-lookup"><span data-stu-id="81d42-190">Get a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetControlCenterSsoRequest">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest GetControlCenterSsoRequest (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest GetControlCenterSsoRequest(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.GetControlCenterSsoRequest(Microsoft.Azure.Management.WebSites.IDomainsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetControlCenterSsoRequest (operations As IDomainsOperations) As DomainControlCenterSsoRequest" />
      <MemberSignature Language="F#" Value="static member GetControlCenterSsoRequest : Microsoft.Azure.Management.WebSites.IDomainsOperations -&gt; Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.GetControlCenterSsoRequest operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-191">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-191">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-192">Generieren Sie eine einzelne anmelden-Anforderung für das Verwaltungsportal für die Domäne an.</span><span class="sxs-lookup"><span data-stu-id="81d42-192">Generate a single sign-on request for the domain management portal.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-193">Generieren Sie eine einzelne anmelden-Anforderung für das Verwaltungsportal für die Domäne an.</span><span class="sxs-lookup"><span data-stu-id="81d42-193">Generate a single sign-on request for the domain management portal.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetControlCenterSsoRequestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest&gt; GetControlCenterSsoRequestAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest&gt; GetControlCenterSsoRequestAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.GetControlCenterSsoRequestAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetControlCenterSsoRequestAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.GetControlCenterSsoRequestAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;GetControlCenterSsoRequestAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-194">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-194">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81d42-195">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="81d42-195">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-196">Generieren Sie eine einzelne anmelden-Anforderung für das Verwaltungsportal für die Domäne an.</span><span class="sxs-lookup"><span data-stu-id="81d42-196">Generate a single sign-on request for the domain management portal.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-197">Generieren Sie eine einzelne anmelden-Anforderung für das Verwaltungsportal für die Domäne an.</span><span class="sxs-lookup"><span data-stu-id="81d42-197">Generate a single sign-on request for the domain management portal.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOwnershipIdentifier">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier GetOwnershipIdentifier (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier GetOwnershipIdentifier(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.GetOwnershipIdentifier(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetOwnershipIdentifier (operations As IDomainsOperations, resourceGroupName As String, domainName As String, name As String) As DomainOwnershipIdentifier" />
      <MemberSignature Language="F#" Value="static member GetOwnershipIdentifier : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.GetOwnershipIdentifier (operations, resourceGroupName, domainName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-198">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-198">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="81d42-199">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="81d42-199">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="81d42-200">Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-200">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="81d42-201">Der Name eines Bezeichners.</span><span class="sxs-lookup"><span data-stu-id="81d42-201">Name of identifier.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-202">Besitzer-ID für die Domäne abrufen</span><span class="sxs-lookup"><span data-stu-id="81d42-202">Get ownership identifier for domain</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-203">Besitzer-ID für die Domäne abrufen</span><span class="sxs-lookup"><span data-stu-id="81d42-203">Get ownership identifier for domain</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOwnershipIdentifierAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt; GetOwnershipIdentifierAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt; GetOwnershipIdentifierAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.GetOwnershipIdentifierAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetOwnershipIdentifierAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.GetOwnershipIdentifierAsync (operations, resourceGroupName, domainName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;GetOwnershipIdentifierAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-204">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-204">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="81d42-205">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="81d42-205">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="81d42-206">Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-206">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="81d42-207">Der Name eines Bezeichners.</span><span class="sxs-lookup"><span data-stu-id="81d42-207">Name of identifier.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81d42-208">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="81d42-208">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-209">Besitzer-ID für die Domäne abrufen</span><span class="sxs-lookup"><span data-stu-id="81d42-209">Get ownership identifier for domain</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-210">Besitzer-ID für die Domäne abrufen</span><span class="sxs-lookup"><span data-stu-id="81d42-210">Get ownership identifier for domain</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt; List (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt; List(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.List(Microsoft.Azure.Management.WebSites.IDomainsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IDomainsOperations) As IPage(Of Domain)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.WebSites.IDomainsOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-211">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-211">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-212">Rufen Sie aller Domänen in einem Abonnement an ab.</span><span class="sxs-lookup"><span data-stu-id="81d42-212">Get all domains in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-213">Rufen Sie aller Domänen in einem Abonnement an ab.</span><span class="sxs-lookup"><span data-stu-id="81d42-213">Get all domains in a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt; ListAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt; ListAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-214">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-214">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81d42-215">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="81d42-215">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-216">Rufen Sie aller Domänen in einem Abonnement an ab.</span><span class="sxs-lookup"><span data-stu-id="81d42-216">Get all domains in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-217">Rufen Sie aller Domänen in einem Abonnement an ab.</span><span class="sxs-lookup"><span data-stu-id="81d42-217">Get all domains in a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt; ListByResourceGroup (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt; ListByResourceGroup(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IDomainsOperations, resourceGroupName As String) As IPage(Of Domain)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.WebSites.IDomainsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-218">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-218">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="81d42-219">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="81d42-219">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-220">Rufen Sie alle Domänen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="81d42-220">Get all domains in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-221">Rufen Sie alle Domänen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="81d42-221">Get all domains in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-222">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-222">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="81d42-223">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="81d42-223">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81d42-224">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="81d42-224">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-225">Rufen Sie alle Domänen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="81d42-225">Get all domains in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-226">Rufen Sie alle Domänen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="81d42-226">Get all domains in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IDomainsOperations, nextPageLink As String) As IPage(Of Domain)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.WebSites.IDomainsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-227">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-227">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="81d42-228">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="81d42-228">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-229">Rufen Sie alle Domänen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="81d42-229">Get all domains in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-230">Rufen Sie alle Domänen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="81d42-230">Get all domains in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-231">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-231">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="81d42-232">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="81d42-232">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81d42-233">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="81d42-233">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-234">Rufen Sie alle Domänen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="81d42-234">Get all domains in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-235">Rufen Sie alle Domänen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="81d42-235">Get all domains in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt; ListNext (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt; ListNext(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListNext(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IDomainsOperations, nextPageLink As String) As IPage(Of Domain)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.WebSites.IDomainsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-236">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-236">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="81d42-237">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="81d42-237">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-238">Rufen Sie aller Domänen in einem Abonnement an ab.</span><span class="sxs-lookup"><span data-stu-id="81d42-238">Get all domains in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-239">Rufen Sie aller Domänen in einem Abonnement an ab.</span><span class="sxs-lookup"><span data-stu-id="81d42-239">Get all domains in a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;ListNextAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-240">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-240">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="81d42-241">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="81d42-241">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81d42-242">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="81d42-242">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-243">Rufen Sie aller Domänen in einem Abonnement an ab.</span><span class="sxs-lookup"><span data-stu-id="81d42-243">Get all domains in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-244">Rufen Sie aller Domänen in einem Abonnement an ab.</span><span class="sxs-lookup"><span data-stu-id="81d42-244">Get all domains in a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOwnershipIdentifiers">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt; ListOwnershipIdentifiers (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt; ListOwnershipIdentifiers(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListOwnershipIdentifiers(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListOwnershipIdentifiers (operations As IDomainsOperations, resourceGroupName As String, domainName As String) As IPage(Of DomainOwnershipIdentifier)" />
      <MemberSignature Language="F#" Value="static member ListOwnershipIdentifiers : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListOwnershipIdentifiers (operations, resourceGroupName, domainName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-245">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-245">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="81d42-246">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="81d42-246">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="81d42-247">Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-247">Name of domain.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-248">Listet die Domäne des Besitzes Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="81d42-248">Lists domain ownership identifiers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-249">Listet die Domäne des Besitzes Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="81d42-249">Lists domain ownership identifiers.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOwnershipIdentifiersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt; ListOwnershipIdentifiersAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt; ListOwnershipIdentifiersAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListOwnershipIdentifiersAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListOwnershipIdentifiersAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListOwnershipIdentifiersAsync (operations, resourceGroupName, domainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;ListOwnershipIdentifiersAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-250">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-250">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="81d42-251">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="81d42-251">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="81d42-252">Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-252">Name of domain.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81d42-253">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="81d42-253">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-254">Listet die Domäne des Besitzes Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="81d42-254">Lists domain ownership identifiers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-255">Listet die Domäne des Besitzes Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="81d42-255">Lists domain ownership identifiers.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOwnershipIdentifiersNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt; ListOwnershipIdentifiersNext (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt; ListOwnershipIdentifiersNext(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListOwnershipIdentifiersNext(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListOwnershipIdentifiersNext (operations As IDomainsOperations, nextPageLink As String) As IPage(Of DomainOwnershipIdentifier)" />
      <MemberSignature Language="F#" Value="static member ListOwnershipIdentifiersNext : Microsoft.Azure.Management.WebSites.IDomainsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListOwnershipIdentifiersNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-256">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-256">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="81d42-257">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="81d42-257">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-258">Listet die Domäne des Besitzes Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="81d42-258">Lists domain ownership identifiers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-259">Listet die Domäne des Besitzes Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="81d42-259">Lists domain ownership identifiers.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOwnershipIdentifiersNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt; ListOwnershipIdentifiersNextAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt; ListOwnershipIdentifiersNextAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListOwnershipIdentifiersNextAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListOwnershipIdentifiersNextAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListOwnershipIdentifiersNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;ListOwnershipIdentifiersNextAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-260">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-260">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="81d42-261">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="81d42-261">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81d42-262">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="81d42-262">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-263">Listet die Domäne des Besitzes Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="81d42-263">Lists domain ownership identifiers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-264">Listet die Domäne des Besitzes Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="81d42-264">Lists domain ownership identifiers.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRecommendations">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt; ListRecommendations (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt; ListRecommendations(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, class Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListRecommendations(Microsoft.Azure.Management.WebSites.IDomainsOperations,Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRecommendations (operations As IDomainsOperations, parameters As DomainRecommendationSearchParameters) As IPage(Of NameIdentifier)" />
      <MemberSignature Language="F#" Value="static member ListRecommendations : Microsoft.Azure.Management.WebSites.IDomainsOperations * Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListRecommendations (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-265">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-265">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="81d42-266">Suchen Sie die Parameter für die Domäne Name Empfehlungen.</span><span class="sxs-lookup"><span data-stu-id="81d42-266">Search parameters for domain name recommendations.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-267">Abgerufen Sie Domain Name Empfehlungen anhand von Schlüsselwörtern werden.</span><span class="sxs-lookup"><span data-stu-id="81d42-267">Get domain name recommendations based on keywords.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-268">Abgerufen Sie Domain Name Empfehlungen anhand von Schlüsselwörtern werden.</span><span class="sxs-lookup"><span data-stu-id="81d42-268">Get domain name recommendations based on keywords.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRecommendationsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;&gt; ListRecommendationsAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;&gt; ListRecommendationsAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, class Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListRecommendationsAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRecommendationsAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListRecommendationsAsync (operations, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;ListRecommendationsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-269">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-269">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="81d42-270">Suchen Sie die Parameter für die Domäne Name Empfehlungen.</span><span class="sxs-lookup"><span data-stu-id="81d42-270">Search parameters for domain name recommendations.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81d42-271">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="81d42-271">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-272">Abgerufen Sie Domain Name Empfehlungen anhand von Schlüsselwörtern werden.</span><span class="sxs-lookup"><span data-stu-id="81d42-272">Get domain name recommendations based on keywords.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-273">Abgerufen Sie Domain Name Empfehlungen anhand von Schlüsselwörtern werden.</span><span class="sxs-lookup"><span data-stu-id="81d42-273">Get domain name recommendations based on keywords.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRecommendationsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt; ListRecommendationsNext (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt; ListRecommendationsNext(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListRecommendationsNext(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRecommendationsNext (operations As IDomainsOperations, nextPageLink As String) As IPage(Of NameIdentifier)" />
      <MemberSignature Language="F#" Value="static member ListRecommendationsNext : Microsoft.Azure.Management.WebSites.IDomainsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListRecommendationsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-274">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-274">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="81d42-275">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="81d42-275">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-276">Abgerufen Sie Domain Name Empfehlungen anhand von Schlüsselwörtern werden.</span><span class="sxs-lookup"><span data-stu-id="81d42-276">Get domain name recommendations based on keywords.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-277">Abgerufen Sie Domain Name Empfehlungen anhand von Schlüsselwörtern werden.</span><span class="sxs-lookup"><span data-stu-id="81d42-277">Get domain name recommendations based on keywords.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRecommendationsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;&gt; ListRecommendationsNextAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;&gt; ListRecommendationsNextAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListRecommendationsNextAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRecommendationsNextAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListRecommendationsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;ListRecommendationsNextAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-278">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-278">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="81d42-279">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="81d42-279">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81d42-280">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="81d42-280">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-281">Abgerufen Sie Domain Name Empfehlungen anhand von Schlüsselwörtern werden.</span><span class="sxs-lookup"><span data-stu-id="81d42-281">Get domain name recommendations based on keywords.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-282">Abgerufen Sie Domain Name Empfehlungen anhand von Schlüsselwörtern werden.</span><span class="sxs-lookup"><span data-stu-id="81d42-282">Get domain name recommendations based on keywords.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.Domain Update (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, Microsoft.Azure.Management.WebSites.Models.DomainPatchResource domain);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.Domain Update(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, class Microsoft.Azure.Management.WebSites.Models.DomainPatchResource domain) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.Update(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.DomainPatchResource)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * Microsoft.Azure.Management.WebSites.Models.DomainPatchResource -&gt; Microsoft.Azure.Management.WebSites.Models.Domain" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.Update (operations, resourceGroupName, domainName, domain)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.Domain</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="domain" Type="Microsoft.Azure.Management.WebSites.Models.DomainPatchResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-283">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-283">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="81d42-284">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="81d42-284">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="81d42-285">Der Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-285">Name of the domain.</span></span>
            </param>
        <param name="domain">
            <span data-ttu-id="81d42-286">Registrierungsinformationen Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-286">Domain registration information.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-287">Erstellt oder aktualisiert eine Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-287">Creates or updates a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-288">Erstellt oder aktualisiert eine Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-288">Creates or updates a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt; UpdateAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, Microsoft.Azure.Management.WebSites.Models.DomainPatchResource domain, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt; UpdateAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, class Microsoft.Azure.Management.WebSites.Models.DomainPatchResource domain, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.DomainPatchResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * Microsoft.Azure.Management.WebSites.Models.DomainPatchResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.UpdateAsync (operations, resourceGroupName, domainName, domain, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;UpdateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="domain" Type="Microsoft.Azure.Management.WebSites.Models.DomainPatchResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-289">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-289">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="81d42-290">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="81d42-290">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="81d42-291">Der Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-291">Name of the domain.</span></span>
            </param>
        <param name="domain">
            <span data-ttu-id="81d42-292">Registrierungsinformationen Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-292">Domain registration information.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81d42-293">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="81d42-293">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-294">Erstellt oder aktualisiert eine Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-294">Creates or updates a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-295">Erstellt oder aktualisiert eine Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-295">Creates or updates a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateOwnershipIdentifier">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier UpdateOwnershipIdentifier (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name, Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier domainOwnershipIdentifier);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier UpdateOwnershipIdentifier(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name, class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier domainOwnershipIdentifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.UpdateOwnershipIdentifier(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier)" />
      <MemberSignature Language="F#" Value="static member UpdateOwnershipIdentifier : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * string * Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier -&gt; Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.UpdateOwnershipIdentifier (operations, resourceGroupName, domainName, name, domainOwnershipIdentifier)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="domainOwnershipIdentifier" Type="Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-296">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-296">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="81d42-297">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="81d42-297">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="81d42-298">Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-298">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="81d42-299">Der Name eines Bezeichners.</span><span class="sxs-lookup"><span data-stu-id="81d42-299">Name of identifier.</span></span>
            </param>
        <param name="domainOwnershipIdentifier">
            <span data-ttu-id="81d42-300">Eine JSON-Darstellung der Domäne des Besitzes Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="81d42-300">A JSON representation of the domain ownership properties.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-301">Erstellt einen Bezeichner des Besitzes für einen Bezeichner Domänen- oder Updates Details für eine vorhandene Bezeichner</span><span class="sxs-lookup"><span data-stu-id="81d42-301">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-302">Erstellt einen Bezeichner des Besitzes für einen Bezeichner Domänen- oder Updates Details für eine vorhandene Bezeichner</span><span class="sxs-lookup"><span data-stu-id="81d42-302">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateOwnershipIdentifierAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt; UpdateOwnershipIdentifierAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name, Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier domainOwnershipIdentifier, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt; UpdateOwnershipIdentifierAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name, class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier domainOwnershipIdentifier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.UpdateOwnershipIdentifierAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateOwnershipIdentifierAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * string * Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.UpdateOwnershipIdentifierAsync (operations, resourceGroupName, domainName, name, domainOwnershipIdentifier, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;UpdateOwnershipIdentifierAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="domainOwnershipIdentifier" Type="Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81d42-303">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81d42-303">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="81d42-304">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="81d42-304">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="81d42-305">Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="81d42-305">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="81d42-306">Der Name eines Bezeichners.</span><span class="sxs-lookup"><span data-stu-id="81d42-306">Name of identifier.</span></span>
            </param>
        <param name="domainOwnershipIdentifier">
            <span data-ttu-id="81d42-307">Eine JSON-Darstellung der Domäne des Besitzes Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="81d42-307">A JSON representation of the domain ownership properties.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81d42-308">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="81d42-308">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81d42-309">Erstellt einen Bezeichner des Besitzes für einen Bezeichner Domänen- oder Updates Details für eine vorhandene Bezeichner</span><span class="sxs-lookup"><span data-stu-id="81d42-309">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81d42-310">Erstellt einen Bezeichner des Besitzes für einen Bezeichner Domänen- oder Updates Details für eine vorhandene Bezeichner</span><span class="sxs-lookup"><span data-stu-id="81d42-310">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>