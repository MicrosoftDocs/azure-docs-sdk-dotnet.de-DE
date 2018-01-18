<Type Name="TrustedIdProvidersOperationsExtensions" FullName="Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class TrustedIdProvidersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TrustedIdProvidersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TrustedIdProvidersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type TrustedIdProvidersOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="cf9e6-101">Erweiterungsmethoden für TrustedIdProvidersOperations.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-101">Extension methods for TrustedIdProvidersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider CreateOrUpdate (this Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName, Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider CreateOrUpdate(class Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName, class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ITrustedIdProvidersOperations, resourceGroupName As String, accountName As String, trustedIdProviderName As String, parameters As TrustedIdProvider) As TrustedIdProvider" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations * string * string * string * Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider -&gt; Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider" Usage="Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, accountName, trustedIdProviderName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="trustedIdProviderName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cf9e6-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cf9e6-103">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-103">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="cf9e6-104">Der Name des Data Lake-Speicher-Konto hinzufügen oder ersetzen den vertrauenswürdigen Identitätsanbieter.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-104">The name of the Data Lake Store account to add or replace the trusted identity provider.</span></span>
            </param>
        <param name="trustedIdProviderName">
            <span data-ttu-id="cf9e6-105">Der Name des vertrauenswürdigen Identitätsanbieters.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-105">The name of the trusted identity provider.</span></span> <span data-ttu-id="cf9e6-106">Dies wird zur Differenzierung von Anbietern im Konto verwendet.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-106">This is used for differentiation of providers in the account.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cf9e6-107">Parameter zum Erstellen oder ersetzen den vertrauenswürdigen Identitätsanbieter angegeben.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-107">Parameters supplied to create or replace the trusted identity provider.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf9e6-108">Erstellt oder aktualisiert die angegebenen vertrauenswürdigen Identitätsanbieter.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-108">Creates or updates the specified trusted identity provider.</span></span> <span data-ttu-id="cf9e6-109">Während des Updates wird mit diesem neuen Anbieter mit dem angegebenen Namen der vertrauenswürdigen Identitätsanbieter ersetzt werden</span><span class="sxs-lookup"><span data-stu-id="cf9e6-109">During update, the trusted identity provider with the specified name will be replaced with this new provider</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName, Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName, class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations * string * string * string * Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, accountName, trustedIdProviderName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="trustedIdProviderName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cf9e6-110">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-110">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cf9e6-111">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-111">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="cf9e6-112">Der Name des Data Lake-Speicher-Konto hinzufügen oder ersetzen den vertrauenswürdigen Identitätsanbieter.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-112">The name of the Data Lake Store account to add or replace the trusted identity provider.</span></span>
            </param>
        <param name="trustedIdProviderName">
            <span data-ttu-id="cf9e6-113">Der Name des vertrauenswürdigen Identitätsanbieters.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-113">The name of the trusted identity provider.</span></span> <span data-ttu-id="cf9e6-114">Dies wird zur Differenzierung von Anbietern im Konto verwendet.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-114">This is used for differentiation of providers in the account.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cf9e6-115">Parameter zum Erstellen oder ersetzen den vertrauenswürdigen Identitätsanbieter angegeben.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-115">Parameters supplied to create or replace the trusted identity provider.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cf9e6-116">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf9e6-117">Erstellt oder aktualisiert die angegebenen vertrauenswürdigen Identitätsanbieter.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-117">Creates or updates the specified trusted identity provider.</span></span> <span data-ttu-id="cf9e6-118">Während des Updates wird mit diesem neuen Anbieter mit dem angegebenen Namen der vertrauenswürdigen Identitätsanbieter ersetzt werden</span><span class="sxs-lookup"><span data-stu-id="cf9e6-118">During update, the trusted identity provider with the specified name will be replaced with this new provider</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.Delete(Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ITrustedIdProvidersOperations, resourceGroupName As String, accountName As String, trustedIdProviderName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.Delete (operations, resourceGroupName, accountName, trustedIdProviderName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="trustedIdProviderName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cf9e6-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cf9e6-120">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-120">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="cf9e6-121">Der Name des Kontos Data Lake-Speicher aus der vertrauenswürdigen Identitätsanbieter gelöscht.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-121">The name of the Data Lake Store account from which to delete the trusted identity provider.</span></span>
            </param>
        <param name="trustedIdProviderName">
            <span data-ttu-id="cf9e6-122">Der Name des vertrauenswürdigen Identitätsanbieters zu löschen.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-122">The name of the trusted identity provider to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf9e6-123">Löscht den angegebenen vertrauenswürdigen Identitätsanbieter aus dem angegebenen Data Lake-Speicher-Konto</span><span class="sxs-lookup"><span data-stu-id="cf9e6-123">Deletes the specified trusted identity provider from the specified Data Lake Store account</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, trustedIdProviderName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="trustedIdProviderName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cf9e6-124">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cf9e6-125">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-125">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="cf9e6-126">Der Name des Kontos Data Lake-Speicher aus der vertrauenswürdigen Identitätsanbieter gelöscht.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-126">The name of the Data Lake Store account from which to delete the trusted identity provider.</span></span>
            </param>
        <param name="trustedIdProviderName">
            <span data-ttu-id="cf9e6-127">Der Name des vertrauenswürdigen Identitätsanbieters zu löschen.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-127">The name of the trusted identity provider to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cf9e6-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf9e6-129">Löscht den angegebenen vertrauenswürdigen Identitätsanbieter aus dem angegebenen Data Lake-Speicher-Konto</span><span class="sxs-lookup"><span data-stu-id="cf9e6-129">Deletes the specified trusted identity provider from the specified Data Lake Store account</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider Get (this Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider Get(class Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.Get(Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ITrustedIdProvidersOperations, resourceGroupName As String, accountName As String, trustedIdProviderName As String) As TrustedIdProvider" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider" Usage="Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.Get (operations, resourceGroupName, accountName, trustedIdProviderName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="trustedIdProviderName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cf9e6-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cf9e6-131">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-131">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="cf9e6-132">Der Name des Kontos Data Lake-Speicher aus der vertrauenswürdigen Identitätsanbieter abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-132">The name of the Data Lake Store account from which to get the trusted identity provider.</span></span>
            </param>
        <param name="trustedIdProviderName">
            <span data-ttu-id="cf9e6-133">Der Name des vertrauenswürdigen Identitätsanbieters abrufen.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-133">The name of the trusted identity provider to retrieve.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf9e6-134">Ruft das angegebene Data Lake-Speicher vertrauenswürdigen Identitätsanbieter ab.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-134">Gets the specified Data Lake Store trusted identity provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; GetAsync (this Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; GetAsync(class Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, trustedIdProviderName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="trustedIdProviderName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cf9e6-135">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-135">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cf9e6-136">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-136">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="cf9e6-137">Der Name des Kontos Data Lake-Speicher aus der vertrauenswürdigen Identitätsanbieter abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-137">The name of the Data Lake Store account from which to get the trusted identity provider.</span></span>
            </param>
        <param name="trustedIdProviderName">
            <span data-ttu-id="cf9e6-138">Der Name des vertrauenswürdigen Identitätsanbieters abrufen.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-138">The name of the trusted identity provider to retrieve.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cf9e6-139">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf9e6-140">Ruft das angegebene Data Lake-Speicher vertrauenswürdigen Identitätsanbieter ab.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-140">Gets the specified Data Lake Store trusted identity provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccount">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; ListByAccount (this Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; ListByAccount(class Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.ListByAccount(Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByAccount (operations As ITrustedIdProvidersOperations, resourceGroupName As String, accountName As String) As IPage(Of TrustedIdProvider)" />
      <MemberSignature Language="F#" Value="static member ListByAccount : Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.ListByAccount (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cf9e6-141">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cf9e6-142">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-142">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="cf9e6-143">Der Name des Data Lake-Speicher-Konto, von dem die vertrauenswürdigen Identitätsanbieter abgerufen.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-143">The name of the Data Lake Store account from which to get the trusted identity providers.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf9e6-144">Listet die Data Lake-Speicher vertrauenswürdigen Identitätsanbieter in das angegebene Data Lake-Speicher-Konto an.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-144">Lists the Data Lake Store trusted identity providers within the specified Data Lake Store account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt; ListByAccountAsync (this Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt; ListByAccountAsync(class Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.ListByAccountAsync(Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByAccountAsync : Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.ListByAccountAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions/&lt;ListByAccountAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cf9e6-145">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-145">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cf9e6-146">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-146">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="cf9e6-147">Der Name des Data Lake-Speicher-Konto, von dem die vertrauenswürdigen Identitätsanbieter abgerufen.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-147">The name of the Data Lake Store account from which to get the trusted identity providers.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cf9e6-148">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf9e6-149">Listet die Data Lake-Speicher vertrauenswürdigen Identitätsanbieter in das angegebene Data Lake-Speicher-Konto an.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-149">Lists the Data Lake Store trusted identity providers within the specified Data Lake Store account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; ListByAccountNext (this Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; ListByAccountNext(class Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.ListByAccountNext(Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByAccountNext (operations As ITrustedIdProvidersOperations, nextPageLink As String) As IPage(Of TrustedIdProvider)" />
      <MemberSignature Language="F#" Value="static member ListByAccountNext : Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.ListByAccountNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cf9e6-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-150">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="cf9e6-151">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-151">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf9e6-152">Listet die Data Lake-Speicher vertrauenswürdigen Identitätsanbieter in das angegebene Data Lake-Speicher-Konto an.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-152">Lists the Data Lake Store trusted identity providers within the specified Data Lake Store account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt; ListByAccountNextAsync (this Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt; ListByAccountNextAsync(class Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.ListByAccountNextAsync(Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByAccountNextAsync : Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.ListByAccountNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions/&lt;ListByAccountNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cf9e6-153">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-153">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="cf9e6-154">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-154">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cf9e6-155">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf9e6-156">Listet die Data Lake-Speicher vertrauenswürdigen Identitätsanbieter in das angegebene Data Lake-Speicher-Konto an.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-156">Lists the Data Lake Store trusted identity providers within the specified Data Lake Store account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider Update (this Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName, Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider Update(class Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName, class Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.Update(Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As ITrustedIdProvidersOperations, resourceGroupName As String, accountName As String, trustedIdProviderName As String, Optional parameters As UpdateTrustedIdProviderParameters = null) As TrustedIdProvider" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations * string * string * string * Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters -&gt; Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider" Usage="Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.Update (operations, resourceGroupName, accountName, trustedIdProviderName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="trustedIdProviderName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cf9e6-157">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-157">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cf9e6-158">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-158">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="cf9e6-159">Der Name des Data Lake-Speicher-Kontos, das für die Aktualisierung des vertrauenswürdigen Identitätsanbieters.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-159">The name of the Data Lake Store account to which to update the trusted identity provider.</span></span>
            </param>
        <param name="trustedIdProviderName">
            <span data-ttu-id="cf9e6-160">Der Name des vertrauenswürdigen Identitätsanbieters.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-160">The name of the trusted identity provider.</span></span> <span data-ttu-id="cf9e6-161">Dies wird zur Differenzierung von Anbietern im Konto verwendet.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-161">This is used for differentiation of providers in the account.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cf9e6-162">Der Parameter angegeben wird, um den vertrauenswürdigen Identitätsanbieter zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-162">Parameters supplied to update the trusted identity provider.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf9e6-163">Aktualisiert den angegebenen vertrauenswürdigen Identitätsanbieter an.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-163">Updates the specified trusted identity provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; UpdateAsync (this Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName, Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters parameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; UpdateAsync(class Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName, class Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations * string * string * string * Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, trustedIdProviderName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="trustedIdProviderName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cf9e6-164">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cf9e6-165">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-165">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="cf9e6-166">Der Name des Data Lake-Speicher-Kontos, das für die Aktualisierung des vertrauenswürdigen Identitätsanbieters.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-166">The name of the Data Lake Store account to which to update the trusted identity provider.</span></span>
            </param>
        <param name="trustedIdProviderName">
            <span data-ttu-id="cf9e6-167">Der Name des vertrauenswürdigen Identitätsanbieters.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-167">The name of the trusted identity provider.</span></span> <span data-ttu-id="cf9e6-168">Dies wird zur Differenzierung von Anbietern im Konto verwendet.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-168">This is used for differentiation of providers in the account.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cf9e6-169">Der Parameter angegeben wird, um den vertrauenswürdigen Identitätsanbieter zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-169">Parameters supplied to update the trusted identity provider.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cf9e6-170">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf9e6-171">Aktualisiert den angegebenen vertrauenswürdigen Identitätsanbieter an.</span><span class="sxs-lookup"><span data-stu-id="cf9e6-171">Updates the specified trusted identity provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>