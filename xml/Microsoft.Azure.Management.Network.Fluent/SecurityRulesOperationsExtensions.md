<Type Name="SecurityRulesOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class SecurityRulesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SecurityRulesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module SecurityRulesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type SecurityRulesOperationsExtensions = class" />
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
            <span data-ttu-id="82932-101">Erweiterungsmethoden für SecurityRulesOperations.</span><span class="sxs-lookup"><span data-stu-id="82932-101">Extension methods for SecurityRulesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, string securityRuleName, Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner securityRuleParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, string securityRuleName, class Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner securityRuleParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, networkSecurityGroupName, securityRuleName, securityRuleParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="securityRuleName" Type="System.String" />
        <Parameter Name="securityRuleParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="82932-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="82932-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="82932-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="82932-103">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="82932-104">Der Name der Netzwerksicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="82932-104">The name of the network security group.</span></span>
            </param>
        <param name="securityRuleName">
            <span data-ttu-id="82932-105">Der Name der Sicherheitsregel.</span><span class="sxs-lookup"><span data-stu-id="82932-105">The name of the security rule.</span></span>
            </param>
        <param name="securityRuleParameters">
            <span data-ttu-id="82932-106">Parameter für das Erstellen oder aktualisieren Sicherheit Regel Netzwerkvorgang angegebene.</span><span class="sxs-lookup"><span data-stu-id="82932-106">Parameters supplied to the create or update network security rule operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="82932-107">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="82932-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="82932-108">Erstellt oder aktualisiert eine Sicherheitsregel in der angegebenen Netzwerksicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="82932-108">Creates or updates a security rule in the specified network security group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, string securityRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, string securityRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, networkSecurityGroupName, securityRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="securityRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="82932-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="82932-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="82932-110">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="82932-110">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="82932-111">Der Name der Netzwerksicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="82932-111">The name of the network security group.</span></span>
            </param>
        <param name="securityRuleName">
            <span data-ttu-id="82932-112">Der Name der Sicherheitsregel.</span><span class="sxs-lookup"><span data-stu-id="82932-112">The name of the security rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="82932-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="82932-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="82932-114">Löscht die angegebene netzwerksicherheitsregel an.</span><span class="sxs-lookup"><span data-stu-id="82932-114">Deletes the specified network security rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, string securityRuleName, Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner securityRuleParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, string securityRuleName, class Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner securityRuleParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, networkSecurityGroupName, securityRuleName, securityRuleParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="securityRuleName" Type="System.String" />
        <Parameter Name="securityRuleParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="82932-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="82932-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="82932-116">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="82932-116">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="82932-117">Der Name der Netzwerksicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="82932-117">The name of the network security group.</span></span>
            </param>
        <param name="securityRuleName">
            <span data-ttu-id="82932-118">Der Name der Sicherheitsregel.</span><span class="sxs-lookup"><span data-stu-id="82932-118">The name of the security rule.</span></span>
            </param>
        <param name="securityRuleParameters">
            <span data-ttu-id="82932-119">Parameter für das Erstellen oder aktualisieren Sicherheit Regel Netzwerkvorgang angegebene.</span><span class="sxs-lookup"><span data-stu-id="82932-119">Parameters supplied to the create or update network security rule operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="82932-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="82932-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="82932-121">Erstellt oder aktualisiert eine Sicherheitsregel in der angegebenen Netzwerksicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="82932-121">Creates or updates a security rule in the specified network security group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, string securityRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, string securityRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions.DeleteAsync (operations, resourceGroupName, networkSecurityGroupName, securityRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions/&lt;DeleteAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="securityRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="82932-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="82932-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="82932-123">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="82932-123">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="82932-124">Der Name der Netzwerksicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="82932-124">The name of the network security group.</span></span>
            </param>
        <param name="securityRuleName">
            <span data-ttu-id="82932-125">Der Name der Sicherheitsregel.</span><span class="sxs-lookup"><span data-stu-id="82932-125">The name of the security rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="82932-126">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="82932-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="82932-127">Löscht die angegebene netzwerksicherheitsregel an.</span><span class="sxs-lookup"><span data-stu-id="82932-127">Deletes the specified network security rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, string securityRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, string securityRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions.GetAsync (operations, resourceGroupName, networkSecurityGroupName, securityRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="securityRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="82932-128">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="82932-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="82932-129">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="82932-129">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="82932-130">Der Name der Netzwerksicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="82932-130">The name of the network security group.</span></span>
            </param>
        <param name="securityRuleName">
            <span data-ttu-id="82932-131">Der Name der Sicherheitsregel.</span><span class="sxs-lookup"><span data-stu-id="82932-131">The name of the security rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="82932-132">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="82932-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="82932-133">Abrufen der angegebenen netzwerksicherheitsregel an.</span><span class="sxs-lookup"><span data-stu-id="82932-133">Get the specified network security rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions.ListAsync (operations, resourceGroupName, networkSecurityGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="82932-134">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="82932-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="82932-135">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="82932-135">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="82932-136">Der Name der Netzwerksicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="82932-136">The name of the network security group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="82932-137">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="82932-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="82932-138">Ruft alle Sicherheitsregeln in einer Netzwerksicherheitsgruppe an.</span><span class="sxs-lookup"><span data-stu-id="82932-138">Gets all security rules in a network security group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions/&lt;ListNextAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="82932-139">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="82932-139">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="82932-140">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="82932-140">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="82932-141">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="82932-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="82932-142">Ruft alle Sicherheitsregeln in einer Netzwerksicherheitsgruppe an.</span><span class="sxs-lookup"><span data-stu-id="82932-142">Gets all security rules in a network security group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>