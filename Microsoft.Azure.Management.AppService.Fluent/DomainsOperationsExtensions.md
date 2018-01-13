<Type Name="DomainsOperationsExtensions" FullName="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DomainsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DomainsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DomainsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DomainsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9c615-101">Erweiterungsmethoden für DomainsOperations.</span><span class="sxs-lookup"><span data-stu-id="9c615-101">Extension methods for DomainsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner domain, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner domain, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, domainName, domain, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="domain" Type="Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c615-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c615-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c615-103">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="9c615-103">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="9c615-104">Der Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="9c615-104">Name of the domain.</span></span>
            </param>
        <param name="domain">
            <span data-ttu-id="9c615-105">Registrierungsinformationen Domäne.</span><span class="sxs-lookup"><span data-stu-id="9c615-105">Domain registration information.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c615-106">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c615-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c615-107">Erstellt oder aktualisiert eine Domäne.</span><span class="sxs-lookup"><span data-stu-id="9c615-107">Creates or updates a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9c615-108">Erstellt oder aktualisiert eine Domäne.</span><span class="sxs-lookup"><span data-stu-id="9c615-108">Creates or updates a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainAvailablilityCheckResultInner&gt; CheckAvailabilityAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner identifier, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainAvailablilityCheckResultInner&gt; CheckAvailabilityAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, class Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner identifier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.CheckAvailabilityAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckAvailabilityAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainAvailablilityCheckResultInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.CheckAvailabilityAsync (operations, identifier, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;CheckAvailabilityAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainAvailablilityCheckResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="identifier" Type="Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="identifier">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner domain, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner domain, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, domainName, domain, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="domain" Type="Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c615-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c615-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c615-110">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="9c615-110">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="9c615-111">Der Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="9c615-111">Name of the domain.</span></span>
            </param>
        <param name="domain">
            <span data-ttu-id="9c615-112">Registrierungsinformationen Domäne.</span><span class="sxs-lookup"><span data-stu-id="9c615-112">Domain registration information.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c615-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c615-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c615-114">Erstellt oder aktualisiert eine Domäne.</span><span class="sxs-lookup"><span data-stu-id="9c615-114">Creates or updates a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9c615-115">Erstellt oder aktualisiert eine Domäne.</span><span class="sxs-lookup"><span data-stu-id="9c615-115">Creates or updates a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateOwnershipIdentifierAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt; CreateOrUpdateOwnershipIdentifierAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner domainOwnershipIdentifier, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt; CreateOrUpdateOwnershipIdentifierAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner domainOwnershipIdentifier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.CreateOrUpdateOwnershipIdentifierAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateOwnershipIdentifierAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.CreateOrUpdateOwnershipIdentifierAsync (operations, resourceGroupName, domainName, name, domainOwnershipIdentifier, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;CreateOrUpdateOwnershipIdentifierAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="domainOwnershipIdentifier" Type="Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c615-116">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c615-116">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c615-117">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="9c615-117">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="9c615-118">Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="9c615-118">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="9c615-119">Der Name eines Bezeichners.</span><span class="sxs-lookup"><span data-stu-id="9c615-119">Name of identifier.</span></span>
            </param>
        <param name="domainOwnershipIdentifier">
            <span data-ttu-id="9c615-120">Eine JSON-Darstellung der Domäne des Besitzes Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="9c615-120">A JSON representation of the domain ownership properties.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c615-121">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c615-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c615-122">Erstellt einen Bezeichner des Besitzes für einen Bezeichner Domänen- oder Updates Details für eine vorhandene Bezeichner</span><span class="sxs-lookup"><span data-stu-id="9c615-122">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9c615-123">Erstellt einen Bezeichner des Besitzes für einen Bezeichner Domänen- oder Updates Details für eine vorhandene Bezeichner</span><span class="sxs-lookup"><span data-stu-id="9c615-123">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, Nullable&lt;bool&gt; forceHardDeleteDomain = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, valuetype System.Nullable`1&lt;bool&gt; forceHardDeleteDomain, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.DeleteAsync (operations, resourceGroupName, domainName, forceHardDeleteDomain, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="forceHardDeleteDomain" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c615-124">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c615-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c615-125">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="9c615-125">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="9c615-126">Der Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="9c615-126">Name of the domain.</span></span>
            </param>
        <param name="forceHardDeleteDomain">
            <span data-ttu-id="9c615-127">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; zum sofortigen Löschen die Domäne.</span><span class="sxs-lookup"><span data-stu-id="9c615-127">Specify &lt;code&gt;true&lt;/code&gt; to delete the domain immediately.</span></span> <span data-ttu-id="9c615-128">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt; die Domäne nach 24 Stunden gelöscht.</span><span class="sxs-lookup"><span data-stu-id="9c615-128">The default is &lt;code&gt;false&lt;/code&gt; which deletes the domain after 24 hours.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c615-129">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c615-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c615-130">Löschen einer Domäne.</span><span class="sxs-lookup"><span data-stu-id="9c615-130">Delete a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9c615-131">Löschen einer Domäne.</span><span class="sxs-lookup"><span data-stu-id="9c615-131">Delete a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteOwnershipIdentifierAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteOwnershipIdentifierAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteOwnershipIdentifierAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.DeleteOwnershipIdentifierAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteOwnershipIdentifierAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.DeleteOwnershipIdentifierAsync (operations, resourceGroupName, domainName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;DeleteOwnershipIdentifierAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c615-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c615-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c615-133">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="9c615-133">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="9c615-134">Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="9c615-134">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="9c615-135">Der Name eines Bezeichners.</span><span class="sxs-lookup"><span data-stu-id="9c615-135">Name of identifier.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c615-136">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c615-136">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c615-137">Löschen Sie den Besitz Bezeichner für die Domäne</span><span class="sxs-lookup"><span data-stu-id="9c615-137">Delete ownership identifier for domain</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9c615-138">Löschen Sie den Besitz Bezeichner für die Domäne</span><span class="sxs-lookup"><span data-stu-id="9c615-138">Delete ownership identifier for domain</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt; GetAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt; GetAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.GetAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.GetAsync (operations, resourceGroupName, domainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c615-139">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c615-139">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c615-140">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="9c615-140">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="9c615-141">Der Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="9c615-141">Name of the domain.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c615-142">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c615-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c615-143">Abrufen einer Domänenkontos an.</span><span class="sxs-lookup"><span data-stu-id="9c615-143">Get a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9c615-144">Abrufen einer Domänenkontos an.</span><span class="sxs-lookup"><span data-stu-id="9c615-144">Get a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetControlCenterSsoRequestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainControlCenterSsoRequestInner&gt; GetControlCenterSsoRequestAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainControlCenterSsoRequestInner&gt; GetControlCenterSsoRequestAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.GetControlCenterSsoRequestAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetControlCenterSsoRequestAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainControlCenterSsoRequestInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.GetControlCenterSsoRequestAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;GetControlCenterSsoRequestAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainControlCenterSsoRequestInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c615-145">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c615-145">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c615-146">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c615-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c615-147">Generieren Sie eine einzelne anmelden-Anforderung für das Verwaltungsportal für die Domäne an.</span><span class="sxs-lookup"><span data-stu-id="9c615-147">Generate a single sign-on request for the domain management portal.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9c615-148">Generieren Sie eine einzelne anmelden-Anforderung für das Verwaltungsportal für die Domäne an.</span><span class="sxs-lookup"><span data-stu-id="9c615-148">Generate a single sign-on request for the domain management portal.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOwnershipIdentifierAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt; GetOwnershipIdentifierAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt; GetOwnershipIdentifierAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.GetOwnershipIdentifierAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetOwnershipIdentifierAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.GetOwnershipIdentifierAsync (operations, resourceGroupName, domainName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;GetOwnershipIdentifierAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c615-149">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c615-149">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c615-150">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="9c615-150">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="9c615-151">Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="9c615-151">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="9c615-152">Der Name eines Bezeichners.</span><span class="sxs-lookup"><span data-stu-id="9c615-152">Name of identifier.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c615-153">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c615-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c615-154">Besitzer-ID für die Domäne abrufen</span><span class="sxs-lookup"><span data-stu-id="9c615-154">Get ownership identifier for domain</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9c615-155">Besitzer-ID für die Domäne abrufen</span><span class="sxs-lookup"><span data-stu-id="9c615-155">Get ownership identifier for domain</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c615-156">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c615-156">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c615-157">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c615-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c615-158">Rufen Sie aller Domänen in einem Abonnement an ab.</span><span class="sxs-lookup"><span data-stu-id="9c615-158">Get all domains in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9c615-159">Rufen Sie aller Domänen in einem Abonnement an ab.</span><span class="sxs-lookup"><span data-stu-id="9c615-159">Get all domains in a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c615-160">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c615-160">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c615-161">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="9c615-161">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c615-162">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c615-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c615-163">Rufen Sie alle Domänen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9c615-163">Get all domains in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9c615-164">Rufen Sie alle Domänen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9c615-164">Get all domains in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c615-165">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c615-165">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9c615-166">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9c615-166">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c615-167">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c615-167">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c615-168">Rufen Sie alle Domänen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9c615-168">Get all domains in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9c615-169">Rufen Sie alle Domänen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9c615-169">Get all domains in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;ListNextAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c615-170">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c615-170">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9c615-171">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9c615-171">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c615-172">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c615-172">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c615-173">Rufen Sie aller Domänen in einem Abonnement an ab.</span><span class="sxs-lookup"><span data-stu-id="9c615-173">Get all domains in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9c615-174">Rufen Sie aller Domänen in einem Abonnement an ab.</span><span class="sxs-lookup"><span data-stu-id="9c615-174">Get all domains in a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOwnershipIdentifiersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt; ListOwnershipIdentifiersAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt; ListOwnershipIdentifiersAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListOwnershipIdentifiersAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListOwnershipIdentifiersAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListOwnershipIdentifiersAsync (operations, resourceGroupName, domainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;ListOwnershipIdentifiersAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c615-175">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c615-175">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c615-176">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="9c615-176">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="9c615-177">Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="9c615-177">Name of domain.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c615-178">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c615-178">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c615-179">Listet die Domäne des Besitzes Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="9c615-179">Lists domain ownership identifiers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9c615-180">Listet die Domäne des Besitzes Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="9c615-180">Lists domain ownership identifiers.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOwnershipIdentifiersNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt; ListOwnershipIdentifiersNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt; ListOwnershipIdentifiersNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListOwnershipIdentifiersNextAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListOwnershipIdentifiersNextAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListOwnershipIdentifiersNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;ListOwnershipIdentifiersNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c615-181">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c615-181">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9c615-182">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9c615-182">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c615-183">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c615-183">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c615-184">Listet die Domäne des Besitzes Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="9c615-184">Lists domain ownership identifiers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9c615-185">Listet die Domäne des Besitzes Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="9c615-185">Lists domain ownership identifiers.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRecommendationsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt; ListRecommendationsAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt; ListRecommendationsAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, class Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListRecommendationsAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRecommendationsAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListRecommendationsAsync (operations, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;ListRecommendationsAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRecommendationsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt; ListRecommendationsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt; ListRecommendationsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListRecommendationsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRecommendationsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListRecommendationsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;ListRecommendationsNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
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
    <Member MemberName="UpdateOwnershipIdentifierAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt; UpdateOwnershipIdentifierAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner domainOwnershipIdentifier, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt; UpdateOwnershipIdentifierAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner domainOwnershipIdentifier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.UpdateOwnershipIdentifierAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateOwnershipIdentifierAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.UpdateOwnershipIdentifierAsync (operations, resourceGroupName, domainName, name, domainOwnershipIdentifier, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;UpdateOwnershipIdentifierAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="domainOwnershipIdentifier" Type="Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c615-186">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c615-186">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c615-187">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="9c615-187">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="9c615-188">Name der Domäne.</span><span class="sxs-lookup"><span data-stu-id="9c615-188">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="9c615-189">Der Name eines Bezeichners.</span><span class="sxs-lookup"><span data-stu-id="9c615-189">Name of identifier.</span></span>
            </param>
        <param name="domainOwnershipIdentifier">
            <span data-ttu-id="9c615-190">Eine JSON-Darstellung der Domäne des Besitzes Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="9c615-190">A JSON representation of the domain ownership properties.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c615-191">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c615-191">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c615-192">Erstellt einen Bezeichner des Besitzes für einen Bezeichner Domänen- oder Updates Details für eine vorhandene Bezeichner</span><span class="sxs-lookup"><span data-stu-id="9c615-192">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9c615-193">Erstellt einen Bezeichner des Besitzes für einen Bezeichner Domänen- oder Updates Details für eine vorhandene Bezeichner</span><span class="sxs-lookup"><span data-stu-id="9c615-193">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>