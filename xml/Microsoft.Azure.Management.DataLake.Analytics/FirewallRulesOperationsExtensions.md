<Type Name="FirewallRulesOperationsExtensions" FullName="Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class FirewallRulesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit FirewallRulesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module FirewallRulesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type FirewallRulesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fece6-101">Erweiterungsmethoden für FirewallRulesOperations.</span><span class="sxs-lookup"><span data-stu-id="fece6-101">Extension methods for FirewallRulesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule CreateOrUpdate (this Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule CreateOrUpdate(class Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, class Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IFirewallRulesOperations, resourceGroupName As String, accountName As String, firewallRuleName As String, parameters As FirewallRule) As FirewallRule" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule" Usage="Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, accountName, firewallRuleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fece6-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fece6-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fece6-103">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="fece6-103">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="fece6-104">Der Name des Data Lake Analytics-Konto hinzufügen oder ersetzen die Firewall-Regel.</span><span class="sxs-lookup"><span data-stu-id="fece6-104">The name of the Data Lake Analytics account to add or replace the firewall rule.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="fece6-105">Der Name der Firewallregel erstellen oder aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="fece6-105">The name of the firewall rule to create or update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fece6-106">Parameter zum Erstellen oder aktualisieren die Firewall-Regel angegeben.</span><span class="sxs-lookup"><span data-stu-id="fece6-106">Parameters supplied to create or update the firewall rule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fece6-107">Erstellt oder aktualisiert die angegebene Firewall-Regel.</span><span class="sxs-lookup"><span data-stu-id="fece6-107">Creates or updates the specified firewall rule.</span></span> <span data-ttu-id="fece6-108">Während des Updates wird durch diese neue Firewallregel Firewallregel mit dem angegebenen Namen ersetzt.</span><span class="sxs-lookup"><span data-stu-id="fece6-108">During update, the firewall rule with the specified name will be replaced with this new firewall rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, class Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, accountName, firewallRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fece6-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fece6-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fece6-110">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="fece6-110">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="fece6-111">Der Name des Data Lake Analytics-Konto hinzufügen oder ersetzen die Firewall-Regel.</span><span class="sxs-lookup"><span data-stu-id="fece6-111">The name of the Data Lake Analytics account to add or replace the firewall rule.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="fece6-112">Der Name der Firewallregel erstellen oder aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="fece6-112">The name of the firewall rule to create or update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fece6-113">Parameter zum Erstellen oder aktualisieren die Firewall-Regel angegeben.</span><span class="sxs-lookup"><span data-stu-id="fece6-113">Parameters supplied to create or update the firewall rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fece6-114">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fece6-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fece6-115">Erstellt oder aktualisiert die angegebene Firewall-Regel.</span><span class="sxs-lookup"><span data-stu-id="fece6-115">Creates or updates the specified firewall rule.</span></span> <span data-ttu-id="fece6-116">Während des Updates wird durch diese neue Firewallregel Firewallregel mit dem angegebenen Namen ersetzt.</span><span class="sxs-lookup"><span data-stu-id="fece6-116">During update, the firewall rule with the specified name will be replaced with this new firewall rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions.Delete(Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IFirewallRulesOperations, resourceGroupName As String, accountName As String, firewallRuleName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions.Delete (operations, resourceGroupName, accountName, firewallRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fece6-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fece6-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fece6-118">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="fece6-118">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="fece6-119">Der Name des Data Lake Analytics-Kontos aus dem Löschen der Firewallregel.</span><span class="sxs-lookup"><span data-stu-id="fece6-119">The name of the Data Lake Analytics account from which to delete the firewall rule.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="fece6-120">Der Name der Firewallregel löschen.</span><span class="sxs-lookup"><span data-stu-id="fece6-120">The name of the firewall rule to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fece6-121">Löscht die angegebene Firewall-Regel aus dem angegebenen Data Lake Analytics-Konto</span><span class="sxs-lookup"><span data-stu-id="fece6-121">Deletes the specified firewall rule from the specified Data Lake Analytics account</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, firewallRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fece6-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fece6-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fece6-123">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="fece6-123">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="fece6-124">Der Name des Data Lake Analytics-Kontos aus dem Löschen der Firewallregel.</span><span class="sxs-lookup"><span data-stu-id="fece6-124">The name of the Data Lake Analytics account from which to delete the firewall rule.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="fece6-125">Der Name der Firewallregel löschen.</span><span class="sxs-lookup"><span data-stu-id="fece6-125">The name of the firewall rule to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fece6-126">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fece6-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fece6-127">Löscht die angegebene Firewall-Regel aus dem angegebenen Data Lake Analytics-Konto</span><span class="sxs-lookup"><span data-stu-id="fece6-127">Deletes the specified firewall rule from the specified Data Lake Analytics account</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule Get (this Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule Get(class Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions.Get(Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IFirewallRulesOperations, resourceGroupName As String, accountName As String, firewallRuleName As String) As FirewallRule" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule" Usage="Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions.Get (operations, resourceGroupName, accountName, firewallRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fece6-128">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fece6-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fece6-129">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="fece6-129">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="fece6-130">Der Name des Data Lake Analytics-Kontos, von dem die Firewall-Regel abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="fece6-130">The name of the Data Lake Analytics account from which to get the firewall rule.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="fece6-131">Der Name der Firewallregel abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="fece6-131">The name of the firewall rule to retrieve.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fece6-132">Ruft die angegebene Data Lake Analytics-Firewallregel ab.</span><span class="sxs-lookup"><span data-stu-id="fece6-132">Gets the specified Data Lake Analytics firewall rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt; GetAsync (this Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt; GetAsync(class Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, firewallRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fece6-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fece6-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fece6-134">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="fece6-134">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="fece6-135">Der Name des Data Lake Analytics-Kontos, von dem die Firewall-Regel abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="fece6-135">The name of the Data Lake Analytics account from which to get the firewall rule.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="fece6-136">Der Name der Firewallregel abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="fece6-136">The name of the firewall rule to retrieve.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fece6-137">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fece6-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fece6-138">Ruft die angegebene Data Lake Analytics-Firewallregel ab.</span><span class="sxs-lookup"><span data-stu-id="fece6-138">Gets the specified Data Lake Analytics firewall rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccount">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt; ListByAccount (this Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt; ListByAccount(class Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions.ListByAccount(Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByAccount (operations As IFirewallRulesOperations, resourceGroupName As String, accountName As String) As IPage(Of FirewallRule)" />
      <MemberSignature Language="F#" Value="static member ListByAccount : Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions.ListByAccount (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fece6-139">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fece6-139">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fece6-140">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="fece6-140">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="fece6-141">Der Name des Data Lake Analytics-Kontos, von dem die Firewall-Regeln abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="fece6-141">The name of the Data Lake Analytics account from which to get the firewall rules.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fece6-142">Listet die Data Lake Analytics-Firewall-Regeln in das angegebene Data Lake Analytics-Konto an.</span><span class="sxs-lookup"><span data-stu-id="fece6-142">Lists the Data Lake Analytics firewall rules within the specified Data Lake Analytics account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt;&gt; ListByAccountAsync (this Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt;&gt; ListByAccountAsync(class Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions.ListByAccountAsync(Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByAccountAsync : Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions.ListByAccountAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions/&lt;ListByAccountAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fece6-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fece6-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fece6-144">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="fece6-144">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="fece6-145">Der Name des Data Lake Analytics-Kontos, von dem die Firewall-Regeln abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="fece6-145">The name of the Data Lake Analytics account from which to get the firewall rules.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fece6-146">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fece6-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fece6-147">Listet die Data Lake Analytics-Firewall-Regeln in das angegebene Data Lake Analytics-Konto an.</span><span class="sxs-lookup"><span data-stu-id="fece6-147">Lists the Data Lake Analytics firewall rules within the specified Data Lake Analytics account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt; ListByAccountNext (this Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt; ListByAccountNext(class Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions.ListByAccountNext(Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByAccountNext (operations As IFirewallRulesOperations, nextPageLink As String) As IPage(Of FirewallRule)" />
      <MemberSignature Language="F#" Value="static member ListByAccountNext : Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions.ListByAccountNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fece6-148">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fece6-148">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="fece6-149">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="fece6-149">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fece6-150">Listet die Data Lake Analytics-Firewall-Regeln in das angegebene Data Lake Analytics-Konto an.</span><span class="sxs-lookup"><span data-stu-id="fece6-150">Lists the Data Lake Analytics firewall rules within the specified Data Lake Analytics account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt;&gt; ListByAccountNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt;&gt; ListByAccountNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions.ListByAccountNextAsync(Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByAccountNextAsync : Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions.ListByAccountNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions/&lt;ListByAccountNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fece6-151">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fece6-151">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="fece6-152">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="fece6-152">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fece6-153">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fece6-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fece6-154">Listet die Data Lake Analytics-Firewall-Regeln in das angegebene Data Lake Analytics-Konto an.</span><span class="sxs-lookup"><span data-stu-id="fece6-154">Lists the Data Lake Analytics firewall rules within the specified Data Lake Analytics account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule Update (this Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateFirewallRuleParameters parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule Update(class Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, class Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateFirewallRuleParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions.Update(Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateFirewallRuleParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IFirewallRulesOperations, resourceGroupName As String, accountName As String, firewallRuleName As String, Optional parameters As UpdateFirewallRuleParameters = null) As FirewallRule" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateFirewallRuleParameters -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule" Usage="Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions.Update (operations, resourceGroupName, accountName, firewallRuleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateFirewallRuleParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fece6-155">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fece6-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fece6-156">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="fece6-156">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="fece6-157">Der Name des Data Lake Analytics-Kontos, das für die Aktualisierung der Firewallregel.</span><span class="sxs-lookup"><span data-stu-id="fece6-157">The name of the Data Lake Analytics account to which to update the firewall rule.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="fece6-158">Der Name der Firewallregel aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="fece6-158">The name of the firewall rule to update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fece6-159">Der Parameter angegeben, um die Firewall-Regel aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="fece6-159">Parameters supplied to update the firewall rule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fece6-160">Aktualisiert die angegebene Firewall-Regel an.</span><span class="sxs-lookup"><span data-stu-id="fece6-160">Updates the specified firewall rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt; UpdateAsync (this Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateFirewallRuleParameters parameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt; UpdateAsync(class Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, class Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateFirewallRuleParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateFirewallRuleParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateFirewallRuleParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, firewallRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.FirewallRulesOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateFirewallRuleParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fece6-161">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fece6-161">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fece6-162">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="fece6-162">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="fece6-163">Der Name des Data Lake Analytics-Kontos, das für die Aktualisierung der Firewallregel.</span><span class="sxs-lookup"><span data-stu-id="fece6-163">The name of the Data Lake Analytics account to which to update the firewall rule.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="fece6-164">Der Name der Firewallregel aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="fece6-164">The name of the firewall rule to update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fece6-165">Der Parameter angegeben, um die Firewall-Regel aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="fece6-165">Parameters supplied to update the firewall rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fece6-166">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fece6-166">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fece6-167">Aktualisiert die angegebene Firewall-Regel an.</span><span class="sxs-lookup"><span data-stu-id="fece6-167">Updates the specified firewall rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>