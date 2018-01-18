<Type Name="CustomDomainsOperationsExtensions" FullName="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class CustomDomainsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CustomDomainsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CustomDomainsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type CustomDomainsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="742c5-101">Erweiterungsmethoden für CustomDomainsOperations.</span><span class="sxs-lookup"><span data-stu-id="742c5-101">Extension methods for CustomDomainsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; BeginCreateAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, string hostName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; BeginCreateAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, string hostName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, profileName, endpointName, customDomainName, hostName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;BeginCreateAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="742c5-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="742c5-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="742c5-103">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="742c5-103">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="742c5-104">Name des CDN-Profil, das in der Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="742c5-104">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="742c5-105">Der Name des Endpunkts unter dem Profil, das global eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="742c5-105">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customDomainName">
            <span data-ttu-id="742c5-106">Der Name der benutzerdefinierten Domäne innerhalb eines Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="742c5-106">Name of the custom domain within an endpoint.</span></span>
            </param>
        <param name="hostName">
            <span data-ttu-id="742c5-107">Der Hostname der benutzerdefinierten Domäne.</span><span class="sxs-lookup"><span data-stu-id="742c5-107">The host name of the custom domain.</span></span> <span data-ttu-id="742c5-108">Ein Domänenname muss sein.</span><span class="sxs-lookup"><span data-stu-id="742c5-108">Must be a domain name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="742c5-109">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="742c5-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="742c5-110">Erstellt eine neue benutzerdefinierte Domäne innerhalb eines Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="742c5-110">Creates a new custom domain within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, profileName, endpointName, customDomainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="742c5-111">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="742c5-111">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="742c5-112">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="742c5-112">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="742c5-113">Name des CDN-Profil, das in der Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="742c5-113">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="742c5-114">Der Name des Endpunkts unter dem Profil, das global eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="742c5-114">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customDomainName">
            <span data-ttu-id="742c5-115">Der Name der benutzerdefinierten Domäne innerhalb eines Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="742c5-115">Name of the custom domain within an endpoint.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="742c5-116">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="742c5-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="742c5-117">Löscht eine vorhandene benutzerdefinierte Domäne innerhalb eines Endpunkts an.</span><span class="sxs-lookup"><span data-stu-id="742c5-117">Deletes an existing custom domain within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; CreateAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, string hostName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; CreateAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, string hostName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.CreateAsync (operations, resourceGroupName, profileName, endpointName, customDomainName, hostName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;CreateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="742c5-118">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="742c5-118">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="742c5-119">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="742c5-119">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="742c5-120">Name des CDN-Profil, das in der Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="742c5-120">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="742c5-121">Der Name des Endpunkts unter dem Profil, das global eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="742c5-121">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customDomainName">
            <span data-ttu-id="742c5-122">Der Name der benutzerdefinierten Domäne innerhalb eines Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="742c5-122">Name of the custom domain within an endpoint.</span></span>
            </param>
        <param name="hostName">
            <span data-ttu-id="742c5-123">Der Hostname der benutzerdefinierten Domäne.</span><span class="sxs-lookup"><span data-stu-id="742c5-123">The host name of the custom domain.</span></span> <span data-ttu-id="742c5-124">Ein Domänenname muss sein.</span><span class="sxs-lookup"><span data-stu-id="742c5-124">Must be a domain name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="742c5-125">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="742c5-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="742c5-126">Erstellt eine neue benutzerdefinierte Domäne innerhalb eines Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="742c5-126">Creates a new custom domain within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; DeleteAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; DeleteAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.DeleteAsync (operations, resourceGroupName, profileName, endpointName, customDomainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="742c5-127">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="742c5-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="742c5-128">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="742c5-128">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="742c5-129">Name des CDN-Profil, das in der Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="742c5-129">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="742c5-130">Der Name des Endpunkts unter dem Profil, das global eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="742c5-130">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customDomainName">
            <span data-ttu-id="742c5-131">Der Name der benutzerdefinierten Domäne innerhalb eines Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="742c5-131">Name of the custom domain within an endpoint.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="742c5-132">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="742c5-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="742c5-133">Löscht eine vorhandene benutzerdefinierte Domäne innerhalb eines Endpunkts an.</span><span class="sxs-lookup"><span data-stu-id="742c5-133">Deletes an existing custom domain within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableCustomHttpsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; DisableCustomHttpsAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; DisableCustomHttpsAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.DisableCustomHttpsAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DisableCustomHttpsAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.DisableCustomHttpsAsync (operations, resourceGroupName, profileName, endpointName, customDomainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;DisableCustomHttpsAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="742c5-134">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="742c5-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="742c5-135">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="742c5-135">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="742c5-136">Name des CDN-Profil, das in der Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="742c5-136">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="742c5-137">Der Name des Endpunkts unter dem Profil, das global eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="742c5-137">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customDomainName">
            <span data-ttu-id="742c5-138">Der Name der benutzerdefinierten Domäne innerhalb eines Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="742c5-138">Name of the custom domain within an endpoint.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="742c5-139">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="742c5-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="742c5-140">Deaktivieren Sie die Https-Übermittlung der benutzerdefinierten Domäne.</span><span class="sxs-lookup"><span data-stu-id="742c5-140">Disable https delivery of the custom domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableCustomHttpsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; EnableCustomHttpsAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; EnableCustomHttpsAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.EnableCustomHttpsAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member EnableCustomHttpsAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.EnableCustomHttpsAsync (operations, resourceGroupName, profileName, endpointName, customDomainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;EnableCustomHttpsAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="742c5-141">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="742c5-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="742c5-142">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="742c5-142">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="742c5-143">Name des CDN-Profil, das in der Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="742c5-143">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="742c5-144">Der Name des Endpunkts unter dem Profil, das global eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="742c5-144">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customDomainName">
            <span data-ttu-id="742c5-145">Der Name der benutzerdefinierten Domäne innerhalb eines Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="742c5-145">Name of the custom domain within an endpoint.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="742c5-146">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="742c5-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="742c5-147">Https-Übermittlung, der die benutzerdefinierte Domäne zu aktivieren.</span><span class="sxs-lookup"><span data-stu-id="742c5-147">Enable https delivery of the custom domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; GetAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; GetAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.GetAsync (operations, resourceGroupName, profileName, endpointName, customDomainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="742c5-148">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="742c5-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="742c5-149">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="742c5-149">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="742c5-150">Name des CDN-Profil, das in der Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="742c5-150">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="742c5-151">Der Name des Endpunkts unter dem Profil, das global eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="742c5-151">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customDomainName">
            <span data-ttu-id="742c5-152">Der Name der benutzerdefinierten Domäne innerhalb eines Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="742c5-152">Name of the custom domain within an endpoint.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="742c5-153">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="742c5-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="742c5-154">Ruft die benutzerdefinierte Domäne einer vorhandenen innerhalb eines Endpunkts ab.</span><span class="sxs-lookup"><span data-stu-id="742c5-154">Gets an exisitng custom domain within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByEndpointAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; ListByEndpointAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; ListByEndpointAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.ListByEndpointAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByEndpointAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.ListByEndpointAsync (operations, resourceGroupName, profileName, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;ListByEndpointAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="742c5-155">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="742c5-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="742c5-156">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="742c5-156">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="742c5-157">Name des CDN-Profil, das in der Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="742c5-157">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="742c5-158">Der Name des Endpunkts unter dem Profil, das global eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="742c5-158">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="742c5-159">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="742c5-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="742c5-160">Zeigt eine Liste aller vorhandenen benutzerdefinierten Domänen innerhalb eines Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="742c5-160">Lists all of the existing custom domains within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByEndpointNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; ListByEndpointNextAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; ListByEndpointNextAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.ListByEndpointNextAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByEndpointNextAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.ListByEndpointNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;ListByEndpointNextAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="742c5-161">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="742c5-161">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="742c5-162">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="742c5-162">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="742c5-163">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="742c5-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="742c5-164">Zeigt eine Liste aller vorhandenen benutzerdefinierten Domänen innerhalb eines Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="742c5-164">Lists all of the existing custom domains within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>