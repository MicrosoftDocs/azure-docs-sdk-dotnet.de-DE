<Type Name="StorageAccountsOperationsExtensions" FullName="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class StorageAccountsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit StorageAccountsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module StorageAccountsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type StorageAccountsOperationsExtensions = class" />
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
            <span data-ttu-id="1a8fb-101">Erweiterungsmethoden für StorageAccountsOperations.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-101">Extension methods for StorageAccountsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public static void Add (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Add(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.Add(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Add (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, storageAccountName As String, parameters As AddStorageAccountParameters)" />
      <MemberSignature Language="F#" Value="static member Add : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.Add (operations, resourceGroupName, accountName, storageAccountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8fb-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8fb-103">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-103">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1a8fb-104">Der Name des Data Lake Analytics-Kontos, das dem Azure Storage-Konto hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-104">The name of the Data Lake Analytics account to which to add the Azure Storage account.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="1a8fb-105">Der Name des Azure Storage-Konto hinzufügen</span><span class="sxs-lookup"><span data-stu-id="1a8fb-105">The name of the Azure Storage account to add</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1a8fb-106">Die Parameter, die den Zugriffsschlüssel und ein optionales Suffix für das Azure-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-106">The parameters containing the access key and optional suffix for the Azure Storage Account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8fb-107">Aktualisiert das angegebene Data Lake Analytics-Konto um ein Azure Storage-Konto hinzuzufügen.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-107">Updates the specified Data Lake Analytics account to add an Azure Storage account.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task AddAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task AddAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.AddAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.AddAsync (operations, resourceGroupName, accountName, storageAccountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;AddAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8fb-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8fb-109">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-109">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1a8fb-110">Der Name des Data Lake Analytics-Kontos, das dem Azure Storage-Konto hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-110">The name of the Data Lake Analytics account to which to add the Azure Storage account.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="1a8fb-111">Der Name des Azure Storage-Konto hinzufügen</span><span class="sxs-lookup"><span data-stu-id="1a8fb-111">The name of the Azure Storage account to add</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1a8fb-112">Die Parameter, die den Zugriffsschlüssel und ein optionales Suffix für das Azure-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-112">The parameters containing the access key and optional suffix for the Azure Storage Account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1a8fb-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8fb-114">Aktualisiert das angegebene Data Lake Analytics-Konto um ein Azure Storage-Konto hinzuzufügen.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-114">Updates the specified Data Lake Analytics account to add an Azure Storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.Delete(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, storageAccountName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.Delete (operations, resourceGroupName, accountName, storageAccountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8fb-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8fb-116">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-116">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1a8fb-117">Der Name des Data Lake Analytics-Kontos aus dem Azure Storage-Konto entfernt werden soll.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-117">The name of the Data Lake Analytics account from which to remove the Azure Storage account.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="1a8fb-118">Der Name des Azure Storage-Kontos entfernen</span><span class="sxs-lookup"><span data-stu-id="1a8fb-118">The name of the Azure Storage account to remove</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8fb-119">Aktualisiert das angegebene Data Lake Analytics-Konto um ein Azure Storage-Konto zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-119">Updates the specified Data Lake Analytics account to remove an Azure Storage account.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, storageAccountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8fb-120">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-120">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8fb-121">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-121">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1a8fb-122">Der Name des Data Lake Analytics-Kontos aus dem Azure Storage-Konto entfernt werden soll.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-122">The name of the Data Lake Analytics account from which to remove the Azure Storage account.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="1a8fb-123">Der Name des Azure Storage-Kontos entfernen</span><span class="sxs-lookup"><span data-stu-id="1a8fb-123">The name of the Azure Storage account to remove</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1a8fb-124">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8fb-125">Aktualisiert das angegebene Data Lake Analytics-Konto um ein Azure Storage-Konto zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-125">Updates the specified Data Lake Analytics account to remove an Azure Storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo Get (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo Get(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.Get(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, storageAccountName As String) As StorageAccountInfo" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.Get (operations, resourceGroupName, accountName, storageAccountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8fb-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8fb-127">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-127">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1a8fb-128">Der Name des Data Lake Analytics-Kontos aus der Azure-Speicher-Kontodetails abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-128">The name of the Data Lake Analytics account from which to retrieve Azure storage account details.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="1a8fb-129">Der Name des Azure Storage-Kontos für die beim Abrufen von Details.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-129">The name of the Azure Storage account for which to retrieve the details.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8fb-130">Ruft die angegebene Azure Storage-Konto, mit dem angegebenen Data Lake Analytics-Konto verknüpft.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-130">Gets the specified Azure Storage account linked to the given Data Lake Analytics account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; GetAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; GetAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, storageAccountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8fb-131">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-131">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8fb-132">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-132">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1a8fb-133">Der Name des Data Lake Analytics-Kontos aus der Azure-Speicher-Kontodetails abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-133">The name of the Data Lake Analytics account from which to retrieve Azure storage account details.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="1a8fb-134">Der Name des Azure Storage-Kontos für die beim Abrufen von Details.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-134">The name of the Azure Storage account for which to retrieve the details.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1a8fb-135">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8fb-136">Ruft die angegebene Azure Storage-Konto, mit dem angegebenen Data Lake Analytics-Konto verknüpft.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-136">Gets the specified Azure Storage account linked to the given Data Lake Analytics account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStorageContainer">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer GetStorageContainer (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, string containerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer GetStorageContainer(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, string containerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.GetStorageContainer(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetStorageContainer (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, storageAccountName As String, containerName As String) As StorageContainer" />
      <MemberSignature Language="F#" Value="static member GetStorageContainer : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.GetStorageContainer (operations, resourceGroupName, accountName, storageAccountName, containerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8fb-137">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8fb-138">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-138">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1a8fb-139">Der Name des Data Lake Analytics-Kontos für das Blob-Container abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-139">The name of the Data Lake Analytics account for which to retrieve blob container.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="1a8fb-140">Der Name des Azure-Speicherkonto aus dem Blob-Containers abgerufen.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-140">The name of the Azure storage account from which to retrieve the blob container.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="1a8fb-141">Der Name des Azure-Speichercontainers abrufen</span><span class="sxs-lookup"><span data-stu-id="1a8fb-141">The name of the Azure storage container to retrieve</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8fb-142">Ruft den angegebenen Azure-Speicher-Container, die der angegebene Data Lake Analytics und Azure Storage-Konten zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-142">Gets the specified Azure Storage container associated with the given Data Lake Analytics and Azure Storage accounts.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStorageContainerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt; GetStorageContainerAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, string containerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt; GetStorageContainerAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, string containerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.GetStorageContainerAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetStorageContainerAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.GetStorageContainerAsync (operations, resourceGroupName, accountName, storageAccountName, containerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;GetStorageContainerAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8fb-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8fb-144">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-144">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1a8fb-145">Der Name des Data Lake Analytics-Kontos für das Blob-Container abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-145">The name of the Data Lake Analytics account for which to retrieve blob container.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="1a8fb-146">Der Name des Azure-Speicherkonto aus dem Blob-Containers abgerufen.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-146">The name of the Azure storage account from which to retrieve the blob container.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="1a8fb-147">Der Name des Azure-Speichercontainers abrufen</span><span class="sxs-lookup"><span data-stu-id="1a8fb-147">The name of the Azure storage container to retrieve</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1a8fb-148">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8fb-149">Ruft den angegebenen Azure-Speicher-Container, die der angegebene Data Lake Analytics und Azure Storage-Konten zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-149">Gets the specified Azure Storage container associated with the given Data Lake Analytics and Azure Storage accounts.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccount">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; ListByAccount (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; ListByAccount(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListByAccount(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByAccount (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, Optional odataQuery As ODataQuery(Of StorageAccountInfo) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of StorageAccountInfo)" />
      <MemberSignature Language="F#" Value="static member ListByAccount : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListByAccount (operations, resourceGroupName, accountName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8fb-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8fb-151">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-151">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1a8fb-152">Der Name des Data Lake Analytics-Kontos für den Azure Storage-Konten aufgelistet.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-152">The name of the Data Lake Analytics account for which to list Azure Storage accounts.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="1a8fb-153">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-153">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="1a8fb-154">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-154">OData Select statement.</span></span> <span data-ttu-id="1a8fb-155">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-155">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="1a8fb-156">Optional.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-156">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="1a8fb-157">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="1a8fb-157">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="1a8fb-158">Optional.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-158">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8fb-159">Ruft ab der ersten Seite des Azure-Speicherkonten, wenn vorhanden, um das angegebene Data Lake Analytics-Konto verknüpft.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-159">Gets the first page of Azure Storage accounts, if any, linked to the specified Data Lake Analytics account.</span></span> <span data-ttu-id="1a8fb-160">Die Antwort enthält einen Link zur nächsten Seite, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-160">The response includes a link to the next page, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt; ListByAccountAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt; ListByAccountAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListByAccountAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByAccountAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListByAccountAsync (operations, resourceGroupName, accountName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;ListByAccountAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8fb-161">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-161">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8fb-162">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-162">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1a8fb-163">Der Name des Data Lake Analytics-Kontos für den Azure Storage-Konten aufgelistet.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-163">The name of the Data Lake Analytics account for which to list Azure Storage accounts.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="1a8fb-164">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-164">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="1a8fb-165">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-165">OData Select statement.</span></span> <span data-ttu-id="1a8fb-166">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-166">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="1a8fb-167">Optional.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-167">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="1a8fb-168">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="1a8fb-168">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="1a8fb-169">Optional.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-169">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1a8fb-170">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8fb-171">Ruft ab der ersten Seite des Azure-Speicherkonten, wenn vorhanden, um das angegebene Data Lake Analytics-Konto verknüpft.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-171">Gets the first page of Azure Storage accounts, if any, linked to the specified Data Lake Analytics account.</span></span> <span data-ttu-id="1a8fb-172">Die Antwort enthält einen Link zur nächsten Seite, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-172">The response includes a link to the next page, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; ListByAccountNext (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; ListByAccountNext(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListByAccountNext(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByAccountNext (operations As IStorageAccountsOperations, nextPageLink As String) As IPage(Of StorageAccountInfo)" />
      <MemberSignature Language="F#" Value="static member ListByAccountNext : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListByAccountNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8fb-173">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-173">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1a8fb-174">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-174">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8fb-175">Ruft ab der ersten Seite des Azure-Speicherkonten, wenn vorhanden, um das angegebene Data Lake Analytics-Konto verknüpft.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-175">Gets the first page of Azure Storage accounts, if any, linked to the specified Data Lake Analytics account.</span></span> <span data-ttu-id="1a8fb-176">Die Antwort enthält einen Link zur nächsten Seite, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-176">The response includes a link to the next page, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt; ListByAccountNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt; ListByAccountNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListByAccountNextAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByAccountNextAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListByAccountNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;ListByAccountNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8fb-177">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-177">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1a8fb-178">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-178">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1a8fb-179">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-179">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8fb-180">Ruft ab der ersten Seite des Azure-Speicherkonten, wenn vorhanden, um das angegebene Data Lake Analytics-Konto verknüpft.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-180">Gets the first page of Azure Storage accounts, if any, linked to the specified Data Lake Analytics account.</span></span> <span data-ttu-id="1a8fb-181">Die Antwort enthält einen Link zur nächsten Seite, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-181">The response includes a link to the next page, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSasTokens">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt; ListSasTokens (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, string containerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt; ListSasTokens(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, string containerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListSasTokens(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListSasTokens (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, storageAccountName As String, containerName As String) As IPage(Of SasTokenInfo)" />
      <MemberSignature Language="F#" Value="static member ListSasTokens : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListSasTokens (operations, resourceGroupName, accountName, storageAccountName, containerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8fb-182">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-182">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8fb-183">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-183">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1a8fb-184">Der Name des Data Lake Analytics-Kontos, das aus dem Azure Storage-Konto-SAS-Token angefordert wird.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-184">The name of the Data Lake Analytics account from which an Azure Storage account's SAS token is being requested.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="1a8fb-185">Der Name des Azure-Speicherkonto für das das SAS-Token angefordert wird.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-185">The name of the Azure storage account for which the SAS token is being requested.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="1a8fb-186">Der Name des Azure-Speichercontainers an, für die das SAS-Token angefordert wird.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-186">The name of the Azure storage container for which the SAS token is being requested.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8fb-187">Ruft das SAS-Token, die die angegebene Data Lake Analytics und Azure Storage-Konto und Container Kombination zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-187">Gets the SAS token associated with the specified Data Lake Analytics and Azure Storage account and container combination.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSasTokensAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt; ListSasTokensAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, string containerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt; ListSasTokensAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, string containerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListSasTokensAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSasTokensAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListSasTokensAsync (operations, resourceGroupName, accountName, storageAccountName, containerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;ListSasTokensAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8fb-188">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-188">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8fb-189">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-189">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1a8fb-190">Der Name des Data Lake Analytics-Kontos, das aus dem Azure Storage-Konto-SAS-Token angefordert wird.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-190">The name of the Data Lake Analytics account from which an Azure Storage account's SAS token is being requested.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="1a8fb-191">Der Name des Azure-Speicherkonto für das das SAS-Token angefordert wird.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-191">The name of the Azure storage account for which the SAS token is being requested.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="1a8fb-192">Der Name des Azure-Speichercontainers an, für die das SAS-Token angefordert wird.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-192">The name of the Azure storage container for which the SAS token is being requested.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1a8fb-193">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-193">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8fb-194">Ruft das SAS-Token, die die angegebene Data Lake Analytics und Azure Storage-Konto und Container Kombination zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-194">Gets the SAS token associated with the specified Data Lake Analytics and Azure Storage account and container combination.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSasTokensNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt; ListSasTokensNext (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt; ListSasTokensNext(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListSasTokensNext(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListSasTokensNext (operations As IStorageAccountsOperations, nextPageLink As String) As IPage(Of SasTokenInfo)" />
      <MemberSignature Language="F#" Value="static member ListSasTokensNext : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListSasTokensNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8fb-195">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-195">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1a8fb-196">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-196">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8fb-197">Ruft das SAS-Token, die die angegebene Data Lake Analytics und Azure Storage-Konto und Container Kombination zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-197">Gets the SAS token associated with the specified Data Lake Analytics and Azure Storage account and container combination.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSasTokensNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt; ListSasTokensNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt; ListSasTokensNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListSasTokensNextAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSasTokensNextAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListSasTokensNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;ListSasTokensNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8fb-198">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-198">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1a8fb-199">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-199">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1a8fb-200">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-200">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8fb-201">Ruft das SAS-Token, die die angegebene Data Lake Analytics und Azure Storage-Konto und Container Kombination zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-201">Gets the SAS token associated with the specified Data Lake Analytics and Azure Storage account and container combination.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListStorageContainers">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt; ListStorageContainers (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt; ListStorageContainers(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListStorageContainers(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListStorageContainers (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, storageAccountName As String) As IPage(Of StorageContainer)" />
      <MemberSignature Language="F#" Value="static member ListStorageContainers : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListStorageContainers (operations, resourceGroupName, accountName, storageAccountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8fb-202">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-202">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8fb-203">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-203">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1a8fb-204">Der Name des Data Lake Analytics-Kontos für den auf Azure-Speicher-Blob-Listencontainer.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-204">The name of the Data Lake Analytics account for which to list Azure Storage blob containers.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="1a8fb-205">Der Name des Azure-Speicherkonto aus dem Blob-Container aufgelistet.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-205">The name of the Azure storage account from which to list blob containers.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8fb-206">Listet die Azure-Speichercontainer, soweit vorhanden, die der angegebenen Kombination der Data Lake Analytics und Azure Storage-Konto zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-206">Lists the Azure Storage containers, if any, associated with the specified Data Lake Analytics and Azure Storage account combination.</span></span> <span data-ttu-id="1a8fb-207">Die Antwort enthält einen Link zur nächsten Seite der Ergebnisse, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-207">The response includes a link to the next page of results, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListStorageContainersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt; ListStorageContainersAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt; ListStorageContainersAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListStorageContainersAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListStorageContainersAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListStorageContainersAsync (operations, resourceGroupName, accountName, storageAccountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;ListStorageContainersAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8fb-208">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-208">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8fb-209">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-209">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1a8fb-210">Der Name des Data Lake Analytics-Kontos für den auf Azure-Speicher-Blob-Listencontainer.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-210">The name of the Data Lake Analytics account for which to list Azure Storage blob containers.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="1a8fb-211">Der Name des Azure-Speicherkonto aus dem Blob-Container aufgelistet.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-211">The name of the Azure storage account from which to list blob containers.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1a8fb-212">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-212">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8fb-213">Listet die Azure-Speichercontainer, soweit vorhanden, die der angegebenen Kombination der Data Lake Analytics und Azure Storage-Konto zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-213">Lists the Azure Storage containers, if any, associated with the specified Data Lake Analytics and Azure Storage account combination.</span></span> <span data-ttu-id="1a8fb-214">Die Antwort enthält einen Link zur nächsten Seite der Ergebnisse, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-214">The response includes a link to the next page of results, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListStorageContainersNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt; ListStorageContainersNext (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt; ListStorageContainersNext(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListStorageContainersNext(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListStorageContainersNext (operations As IStorageAccountsOperations, nextPageLink As String) As IPage(Of StorageContainer)" />
      <MemberSignature Language="F#" Value="static member ListStorageContainersNext : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListStorageContainersNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8fb-215">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-215">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1a8fb-216">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-216">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8fb-217">Listet die Azure-Speichercontainer, soweit vorhanden, die der angegebenen Kombination der Data Lake Analytics und Azure Storage-Konto zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-217">Lists the Azure Storage containers, if any, associated with the specified Data Lake Analytics and Azure Storage account combination.</span></span> <span data-ttu-id="1a8fb-218">Die Antwort enthält einen Link zur nächsten Seite der Ergebnisse, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-218">The response includes a link to the next page of results, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListStorageContainersNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt; ListStorageContainersNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt; ListStorageContainersNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListStorageContainersNextAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListStorageContainersNextAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListStorageContainersNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;ListStorageContainersNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8fb-219">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-219">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1a8fb-220">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-220">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1a8fb-221">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-221">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8fb-222">Listet die Azure-Speichercontainer, soweit vorhanden, die der angegebenen Kombination der Data Lake Analytics und Azure Storage-Konto zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-222">Lists the Azure Storage containers, if any, associated with the specified Data Lake Analytics and Azure Storage account combination.</span></span> <span data-ttu-id="1a8fb-223">Die Antwort enthält einen Link zur nächsten Seite der Ergebnisse, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-223">The response includes a link to the next page of results, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static void Update (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Update(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.Update(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Update (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, storageAccountName As String, Optional parameters As UpdateStorageAccountParameters = null)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.Update (operations, resourceGroupName, accountName, storageAccountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8fb-224">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-224">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8fb-225">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-225">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1a8fb-226">Der Name des Data Lake Analytics-Konto so ändern Sie Speicherkonten in</span><span class="sxs-lookup"><span data-stu-id="1a8fb-226">The name of the Data Lake Analytics account to modify storage accounts in</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="1a8fb-227">Azure Storage-Kontos ändern</span><span class="sxs-lookup"><span data-stu-id="1a8fb-227">The Azure Storage account to modify</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1a8fb-228">Die Parameter, enthält das Zugriffsschlüssel und das Suffix, um das Speicherkonto mit, zu aktualisieren, sofern vorhanden.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-228">The parameters containing the access key and suffix to update the storage account with, if any.</span></span> <span data-ttu-id="1a8fb-229">Übergeben nichts führt keine Änderung.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-229">Passing nothing results in no change.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8fb-230">Aktualisiert das Data Lake Analytics-Konto, um die Azure-Speicher-Blob-Kontodetails, wie z. B. die Zugriffstaste und/oder-Suffix ersetzen.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-230">Updates the Data Lake Analytics account to replace Azure Storage blob account details, such as the access key and/or suffix.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UpdateAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters parameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UpdateAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, storageAccountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8fb-231">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-231">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8fb-232">Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-232">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1a8fb-233">Der Name des Data Lake Analytics-Konto so ändern Sie Speicherkonten in</span><span class="sxs-lookup"><span data-stu-id="1a8fb-233">The name of the Data Lake Analytics account to modify storage accounts in</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="1a8fb-234">Azure Storage-Kontos ändern</span><span class="sxs-lookup"><span data-stu-id="1a8fb-234">The Azure Storage account to modify</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1a8fb-235">Die Parameter, enthält das Zugriffsschlüssel und das Suffix, um das Speicherkonto mit, zu aktualisieren, sofern vorhanden.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-235">The parameters containing the access key and suffix to update the storage account with, if any.</span></span> <span data-ttu-id="1a8fb-236">Übergeben nichts führt keine Änderung.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-236">Passing nothing results in no change.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1a8fb-237">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-237">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8fb-238">Aktualisiert das Data Lake Analytics-Konto, um die Azure-Speicher-Blob-Kontodetails, wie z. B. die Zugriffstaste und/oder-Suffix ersetzen.</span><span class="sxs-lookup"><span data-stu-id="1a8fb-238">Updates the Data Lake Analytics account to replace Azure Storage blob account details, such as the access key and/or suffix.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>