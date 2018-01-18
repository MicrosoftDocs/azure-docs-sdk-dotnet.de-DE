<Type Name="StorageAccountsOperationsExtensions" FullName="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class StorageAccountsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit StorageAccountsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module StorageAccountsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type StorageAccountsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d545e-101">Erweiterungsmethoden für StorageAccountsOperations.</span><span class="sxs-lookup"><span data-stu-id="d545e-101">Extension methods for StorageAccountsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Storage.Models.StorageAccount BeginCreate (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Storage.Models.StorageAccount BeginCreate(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.BeginCreate(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, parameters As StorageAccountCreateParameters) As StorageAccount" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters -&gt; Microsoft.Azure.Management.Storage.Models.StorageAccount" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.BeginCreate (operations, resourceGroupName, accountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.StorageAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d545e-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d545e-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d545e-103">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="d545e-103">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="d545e-104">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="d545e-104">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d545e-105">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="d545e-105">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="d545e-106">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="d545e-106">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d545e-107">Die Parameter für das erstellte Konto bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="d545e-107">The parameters to provide for the created account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d545e-108">Erstellt asynchron ein neues Speicherkonto mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="d545e-108">Asynchronously creates a new storage account with the specified parameters.</span></span>
            <span data-ttu-id="d545e-109">Wenn bereits ein Konto erstellt wird, und eine nachfolgende erstellungsanforderung wird, mit verschiedenen Eigenschaften ausgegeben, werden die Kontoeigenschaften aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="d545e-109">If an account is already created and a subsequent create request is issued with different properties, the account properties will be updated.</span></span> <span data-ttu-id="d545e-110">Wenn bereits ein Konto erstellt wird, und eine nachfolgende CREATE- oder Update-Anforderung wird, mit dem genau gleichen Satz von Eigenschaften ausgegeben, wird die Anforderung erfolgreich ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="d545e-110">If an account is already created and a subsequent create or update request is issued with the exact same set of properties, the request will succeed.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; BeginCreateAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; BeginCreateAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;BeginCreateAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d545e-111">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d545e-111">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d545e-112">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="d545e-112">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="d545e-113">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="d545e-113">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d545e-114">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="d545e-114">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="d545e-115">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="d545e-115">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d545e-116">Die Parameter für das erstellte Konto bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="d545e-116">The parameters to provide for the created account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d545e-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d545e-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d545e-118">Erstellt asynchron ein neues Speicherkonto mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="d545e-118">Asynchronously creates a new storage account with the specified parameters.</span></span>
            <span data-ttu-id="d545e-119">Wenn bereits ein Konto erstellt wird, und eine nachfolgende erstellungsanforderung wird, mit verschiedenen Eigenschaften ausgegeben, werden die Kontoeigenschaften aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="d545e-119">If an account is already created and a subsequent create request is issued with different properties, the account properties will be updated.</span></span> <span data-ttu-id="d545e-120">Wenn bereits ein Konto erstellt wird, und eine nachfolgende CREATE- oder Update-Anforderung wird, mit dem genau gleichen Satz von Eigenschaften ausgegeben, wird die Anforderung erfolgreich ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="d545e-120">If an account is already created and a subsequent create or update request is issued with the exact same set of properties, the request will succeed.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult CheckNameAvailability (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult CheckNameAvailability(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.CheckNameAvailability(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckNameAvailability (operations As IStorageAccountsOperations, name As String) As CheckNameAvailabilityResult" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailability : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string -&gt; Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.CheckNameAvailability (operations, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d545e-121">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d545e-121">The operations group for this extension method.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="d545e-122">Der Name des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="d545e-122">The storage account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d545e-123">Überprüft, ob der Name des Speicherkontos ist gültig und wird nicht bereits verwendet.</span><span class="sxs-lookup"><span data-stu-id="d545e-123">Checks that the storage account name is valid and is not already in use.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult&gt; CheckNameAvailabilityAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult&gt; CheckNameAvailabilityAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.CheckNameAvailabilityAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailabilityAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.CheckNameAvailabilityAsync (operations, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;CheckNameAvailabilityAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d545e-124">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d545e-124">The operations group for this extension method.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="d545e-125">Der Name des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="d545e-125">The storage account name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d545e-126">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d545e-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d545e-127">Überprüft, ob der Name des Speicherkontos ist gültig und wird nicht bereits verwendet.</span><span class="sxs-lookup"><span data-stu-id="d545e-127">Checks that the storage account name is valid and is not already in use.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Storage.Models.StorageAccount Create (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Storage.Models.StorageAccount Create(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.Create(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, parameters As StorageAccountCreateParameters) As StorageAccount" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters -&gt; Microsoft.Azure.Management.Storage.Models.StorageAccount" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.Create (operations, resourceGroupName, accountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.StorageAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d545e-128">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d545e-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d545e-129">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="d545e-129">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="d545e-130">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="d545e-130">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d545e-131">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="d545e-131">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="d545e-132">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="d545e-132">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d545e-133">Die Parameter für das erstellte Konto bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="d545e-133">The parameters to provide for the created account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d545e-134">Erstellt asynchron ein neues Speicherkonto mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="d545e-134">Asynchronously creates a new storage account with the specified parameters.</span></span>
            <span data-ttu-id="d545e-135">Wenn bereits ein Konto erstellt wird, und eine nachfolgende erstellungsanforderung wird, mit verschiedenen Eigenschaften ausgegeben, werden die Kontoeigenschaften aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="d545e-135">If an account is already created and a subsequent create request is issued with different properties, the account properties will be updated.</span></span> <span data-ttu-id="d545e-136">Wenn bereits ein Konto erstellt wird, und eine nachfolgende CREATE- oder Update-Anforderung wird, mit dem genau gleichen Satz von Eigenschaften ausgegeben, wird die Anforderung erfolgreich ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="d545e-136">If an account is already created and a subsequent create or update request is issued with the exact same set of properties, the request will succeed.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; CreateAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; CreateAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.CreateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;CreateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d545e-137">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d545e-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d545e-138">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="d545e-138">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="d545e-139">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="d545e-139">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d545e-140">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="d545e-140">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="d545e-141">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="d545e-141">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d545e-142">Die Parameter für das erstellte Konto bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="d545e-142">The parameters to provide for the created account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d545e-143">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d545e-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d545e-144">Erstellt asynchron ein neues Speicherkonto mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="d545e-144">Asynchronously creates a new storage account with the specified parameters.</span></span>
            <span data-ttu-id="d545e-145">Wenn bereits ein Konto erstellt wird, und eine nachfolgende erstellungsanforderung wird, mit verschiedenen Eigenschaften ausgegeben, werden die Kontoeigenschaften aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="d545e-145">If an account is already created and a subsequent create request is issued with different properties, the account properties will be updated.</span></span> <span data-ttu-id="d545e-146">Wenn bereits ein Konto erstellt wird, und eine nachfolgende CREATE- oder Update-Anforderung wird, mit dem genau gleichen Satz von Eigenschaften ausgegeben, wird die Anforderung erfolgreich ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="d545e-146">If an account is already created and a subsequent create or update request is issued with the exact same set of properties, the request will succeed.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.Delete(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.Delete (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d545e-147">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d545e-147">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d545e-148">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="d545e-148">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="d545e-149">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="d545e-149">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d545e-150">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="d545e-150">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="d545e-151">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="d545e-151">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d545e-152">Löscht ein Speicherkonto in Microsoft Azure.</span><span class="sxs-lookup"><span data-stu-id="d545e-152">Deletes a storage account in Microsoft Azure.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d545e-153">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d545e-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d545e-154">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="d545e-154">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="d545e-155">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="d545e-155">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d545e-156">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="d545e-156">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="d545e-157">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="d545e-157">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d545e-158">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d545e-158">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d545e-159">Löscht ein Speicherkonto in Microsoft Azure.</span><span class="sxs-lookup"><span data-stu-id="d545e-159">Deletes a storage account in Microsoft Azure.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Storage.Models.StorageAccount GetProperties (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Storage.Models.StorageAccount GetProperties(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.GetProperties(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetProperties (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String) As StorageAccount" />
      <MemberSignature Language="F#" Value="static member GetProperties : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string -&gt; Microsoft.Azure.Management.Storage.Models.StorageAccount" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.GetProperties (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.StorageAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d545e-160">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d545e-160">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d545e-161">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="d545e-161">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="d545e-162">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="d545e-162">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d545e-163">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="d545e-163">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="d545e-164">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="d545e-164">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d545e-165">Die Eigenschaften für das angegebene Speicherkonto einschließlich, aber nicht beschränkt auf Name, SKU-Name, Speicherort und Kontostatus zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="d545e-165">Returns the properties for the specified storage account including but not limited to name, SKU name, location, and account status.</span></span> <span data-ttu-id="d545e-166">Der ListKeys-Vorgang sollte verwendet werden, um Speicherschlüssel abzurufen.</span><span class="sxs-lookup"><span data-stu-id="d545e-166">The ListKeys operation should be used to retrieve storage keys.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPropertiesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; GetPropertiesAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; GetPropertiesAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.GetPropertiesAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetPropertiesAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.GetPropertiesAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;GetPropertiesAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d545e-167">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d545e-167">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d545e-168">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="d545e-168">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="d545e-169">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="d545e-169">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d545e-170">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="d545e-170">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="d545e-171">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="d545e-171">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d545e-172">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d545e-172">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d545e-173">Die Eigenschaften für das angegebene Speicherkonto einschließlich, aber nicht beschränkt auf Name, SKU-Name, Speicherort und Kontostatus zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="d545e-173">Returns the properties for the specified storage account including but not limited to name, SKU name, location, and account status.</span></span> <span data-ttu-id="d545e-174">Der ListKeys-Vorgang sollte verwendet werden, um Speicherschlüssel abzurufen.</span><span class="sxs-lookup"><span data-stu-id="d545e-174">The ListKeys operation should be used to retrieve storage keys.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; List (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; List(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.List(Microsoft.Azure.Management.Storage.IStorageAccountsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IStorageAccountsOperations) As IEnumerable(Of StorageAccount)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Storage.IStorageAccountsOperations -&gt; seq&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d545e-175">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d545e-175">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d545e-176">Listet alle Speicherkonten im Abonnement verfügbar.</span><span class="sxs-lookup"><span data-stu-id="d545e-176">Lists all the storage accounts available under the subscription.</span></span> <span data-ttu-id="d545e-177">Beachten Sie, dass Speicherschlüssel nicht zurückgegeben werden. Verwenden Sie den ListKeys-Vorgang für diesen ein.</span><span class="sxs-lookup"><span data-stu-id="d545e-177">Note that storage keys are not returned; use the ListKeys operation for this.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAccountSAS">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Storage.Models.ListAccountSasResponse ListAccountSAS (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.AccountSasParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Storage.Models.ListAccountSasResponse ListAccountSAS(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.AccountSasParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListAccountSAS(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.AccountSasParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAccountSAS (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, parameters As AccountSasParameters) As ListAccountSasResponse" />
      <MemberSignature Language="F#" Value="static member ListAccountSAS : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.AccountSasParameters -&gt; Microsoft.Azure.Management.Storage.Models.ListAccountSasResponse" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListAccountSAS (operations, resourceGroupName, accountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.ListAccountSasResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.AccountSasParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d545e-178">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d545e-178">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d545e-179">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="d545e-179">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="d545e-180">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="d545e-180">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d545e-181">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="d545e-181">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="d545e-182">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="d545e-182">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d545e-183">Die Parameter zum Auflisten von SAS-Anmeldeinformationen für das Speicherkonto angeben.</span><span class="sxs-lookup"><span data-stu-id="d545e-183">The parameters to provide to list SAS credentials for the storage account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d545e-184">Auflisten von SAS-Anmeldeinformationen eines Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="d545e-184">List SAS credentials of a storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAccountSASAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.ListAccountSasResponse&gt; ListAccountSASAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.AccountSasParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Models.ListAccountSasResponse&gt; ListAccountSASAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.AccountSasParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListAccountSASAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.AccountSasParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAccountSASAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.AccountSasParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.ListAccountSasResponse&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListAccountSASAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;ListAccountSASAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.ListAccountSasResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.AccountSasParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d545e-185">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d545e-185">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d545e-186">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="d545e-186">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="d545e-187">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="d545e-187">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d545e-188">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="d545e-188">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="d545e-189">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="d545e-189">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d545e-190">Die Parameter zum Auflisten von SAS-Anmeldeinformationen für das Speicherkonto angeben.</span><span class="sxs-lookup"><span data-stu-id="d545e-190">The parameters to provide to list SAS credentials for the storage account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d545e-191">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d545e-191">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d545e-192">Auflisten von SAS-Anmeldeinformationen eines Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="d545e-192">List SAS credentials of a storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt; ListAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt; ListAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d545e-193">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d545e-193">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d545e-194">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d545e-194">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d545e-195">Listet alle Speicherkonten im Abonnement verfügbar.</span><span class="sxs-lookup"><span data-stu-id="d545e-195">Lists all the storage accounts available under the subscription.</span></span> <span data-ttu-id="d545e-196">Beachten Sie, dass Speicherschlüssel nicht zurückgegeben werden. Verwenden Sie den ListKeys-Vorgang für diesen ein.</span><span class="sxs-lookup"><span data-stu-id="d545e-196">Note that storage keys are not returned; use the ListKeys operation for this.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; ListByResourceGroup (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; ListByResourceGroup(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IStorageAccountsOperations, resourceGroupName As String) As IEnumerable(Of StorageAccount)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string -&gt; seq&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d545e-197">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d545e-197">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d545e-198">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="d545e-198">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="d545e-199">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="d545e-199">The name is case insensitive.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d545e-200">Listet alle Speicherkonten verfügbar sind, unter der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="d545e-200">Lists all the storage accounts available under the given resource group.</span></span>
            <span data-ttu-id="d545e-201">Beachten Sie, dass Speicherschlüssel nicht zurückgegeben werden. Verwenden Sie den ListKeys-Vorgang für diesen ein.</span><span class="sxs-lookup"><span data-stu-id="d545e-201">Note that storage keys are not returned; use the ListKeys operation for this.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d545e-202">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d545e-202">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d545e-203">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="d545e-203">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="d545e-204">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="d545e-204">The name is case insensitive.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d545e-205">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d545e-205">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d545e-206">Listet alle Speicherkonten verfügbar sind, unter der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="d545e-206">Lists all the storage accounts available under the given resource group.</span></span>
            <span data-ttu-id="d545e-207">Beachten Sie, dass Speicherschlüssel nicht zurückgegeben werden. Verwenden Sie den ListKeys-Vorgang für diesen ein.</span><span class="sxs-lookup"><span data-stu-id="d545e-207">Note that storage keys are not returned; use the ListKeys operation for this.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult ListKeys (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult ListKeys(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListKeys(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListKeys (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String) As StorageAccountListKeysResult" />
      <MemberSignature Language="F#" Value="static member ListKeys : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string -&gt; Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListKeys (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d545e-208">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d545e-208">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d545e-209">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="d545e-209">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="d545e-210">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="d545e-210">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d545e-211">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="d545e-211">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="d545e-212">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="d545e-212">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d545e-213">Listet die Zugriffsschlüssel für das angegebene Speicherkonto.</span><span class="sxs-lookup"><span data-stu-id="d545e-213">Lists the access keys for the specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt; ListKeysAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt; ListKeysAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListKeysAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeysAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListKeysAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;ListKeysAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d545e-214">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d545e-214">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d545e-215">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="d545e-215">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="d545e-216">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="d545e-216">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d545e-217">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="d545e-217">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="d545e-218">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="d545e-218">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d545e-219">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d545e-219">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d545e-220">Listet die Zugriffsschlüssel für das angegebene Speicherkonto.</span><span class="sxs-lookup"><span data-stu-id="d545e-220">Lists the access keys for the specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListServiceSAS">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Storage.Models.ListServiceSasResponse ListServiceSAS (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.ServiceSasParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Storage.Models.ListServiceSasResponse ListServiceSAS(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.ServiceSasParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListServiceSAS(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.ServiceSasParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListServiceSAS (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, parameters As ServiceSasParameters) As ListServiceSasResponse" />
      <MemberSignature Language="F#" Value="static member ListServiceSAS : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.ServiceSasParameters -&gt; Microsoft.Azure.Management.Storage.Models.ListServiceSasResponse" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListServiceSAS (operations, resourceGroupName, accountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.ListServiceSasResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.ServiceSasParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d545e-221">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d545e-221">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d545e-222">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="d545e-222">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="d545e-223">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="d545e-223">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d545e-224">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="d545e-224">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="d545e-225">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="d545e-225">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d545e-226">Die Parameter für Liste SAS-Anmeldeinformationen bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="d545e-226">The parameters to provide to list service SAS credentials.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d545e-227">Auflisten einer bestimmten Ressource SAS-Anmeldeinformationen an.</span><span class="sxs-lookup"><span data-stu-id="d545e-227">List service SAS credentials of a specific resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListServiceSASAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.ListServiceSasResponse&gt; ListServiceSASAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.ServiceSasParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Models.ListServiceSasResponse&gt; ListServiceSASAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.ServiceSasParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListServiceSASAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.ServiceSasParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListServiceSASAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.ServiceSasParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.ListServiceSasResponse&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListServiceSASAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;ListServiceSASAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.ListServiceSasResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.ServiceSasParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d545e-228">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d545e-228">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d545e-229">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="d545e-229">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="d545e-230">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="d545e-230">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d545e-231">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="d545e-231">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="d545e-232">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="d545e-232">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d545e-233">Die Parameter für Liste SAS-Anmeldeinformationen bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="d545e-233">The parameters to provide to list service SAS credentials.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d545e-234">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d545e-234">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d545e-235">Auflisten einer bestimmten Ressource SAS-Anmeldeinformationen an.</span><span class="sxs-lookup"><span data-stu-id="d545e-235">List service SAS credentials of a specific resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult RegenerateKey (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult RegenerateKey(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.RegenerateKey(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateKey (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, keyName As String) As StorageAccountListKeysResult" />
      <MemberSignature Language="F#" Value="static member RegenerateKey : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * string -&gt; Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.RegenerateKey (operations, resourceGroupName, accountName, keyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d545e-236">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d545e-236">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d545e-237">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="d545e-237">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="d545e-238">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="d545e-238">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d545e-239">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="d545e-239">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="d545e-240">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="d545e-240">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="d545e-241">Der Name des Speicherschlüssel, die neu generierten, möglichen Werten sein soll, sind key1, key2.</span><span class="sxs-lookup"><span data-stu-id="d545e-241">The name of storage keys that want to be regenerated, possible vaules are key1, key2.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d545e-242">Generiert eine die Zugriffsschlüssel für das angegebene Speicherkonto.</span><span class="sxs-lookup"><span data-stu-id="d545e-242">Regenerates one of the access keys for the specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt; RegenerateKeyAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt; RegenerateKeyAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.RegenerateKeyAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeyAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.RegenerateKeyAsync (operations, resourceGroupName, accountName, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;RegenerateKeyAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d545e-243">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d545e-243">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d545e-244">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="d545e-244">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="d545e-245">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="d545e-245">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d545e-246">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="d545e-246">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="d545e-247">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="d545e-247">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="d545e-248">Der Name des Speicherschlüssel, die neu generierten, möglichen Werten sein soll, sind key1, key2.</span><span class="sxs-lookup"><span data-stu-id="d545e-248">The name of storage keys that want to be regenerated, possible vaules are key1, key2.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d545e-249">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d545e-249">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d545e-250">Generiert eine die Zugriffsschlüssel für das angegebene Speicherkonto.</span><span class="sxs-lookup"><span data-stu-id="d545e-250">Regenerates one of the access keys for the specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Storage.Models.StorageAccount Update (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Storage.Models.StorageAccount Update(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.Update(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, parameters As StorageAccountUpdateParameters) As StorageAccount" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters -&gt; Microsoft.Azure.Management.Storage.Models.StorageAccount" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.Update (operations, resourceGroupName, accountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.StorageAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d545e-251">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d545e-251">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d545e-252">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="d545e-252">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="d545e-253">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="d545e-253">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d545e-254">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="d545e-254">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="d545e-255">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="d545e-255">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d545e-256">Die Parameter für die aktualisierte Konto bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="d545e-256">The parameters to provide for the updated account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d545e-257">Der Update-Vorgang kann verwendet werden, um die SKU, Verschlüsselung, zugriffstarifs oder Tags für ein Speicherkonto zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="d545e-257">The update operation can be used to update the SKU, encryption, access tier, or tags for a storage account.</span></span> <span data-ttu-id="d545e-258">Es kann auch verwendet werden, um das Konto zu einer benutzerdefinierten Domäne zuzuordnen.</span><span class="sxs-lookup"><span data-stu-id="d545e-258">It can also be used to map the account to a custom domain.</span></span> <span data-ttu-id="d545e-259">Nur eine benutzerdefinierte Domäne wird pro Speicherkonto unterstützt. die Ersetzung/Änderung der benutzerdefinierten Domäne wird nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="d545e-259">Only one custom domain is supported per storage account; the replacement/change of custom domain is not supported.</span></span> <span data-ttu-id="d545e-260">Um eine alte benutzerdefinierte Domäne zu ersetzen, muss der alte Wert gelöscht/aufgehoben werden bevor ein neuer Wert festgelegt werden kann.</span><span class="sxs-lookup"><span data-stu-id="d545e-260">In order to replace an old custom domain, the old value must be cleared/unregistered before a new value can be set.</span></span> <span data-ttu-id="d545e-261">Das Update von mehreren Eigenschaften wird unterstützt.</span><span class="sxs-lookup"><span data-stu-id="d545e-261">The update of multiple properties is supported.</span></span> <span data-ttu-id="d545e-262">Dieser Aufruf wird der Speicherschlüssel für das Konto nicht geändert.</span><span class="sxs-lookup"><span data-stu-id="d545e-262">This call does not change the storage keys for the account.</span></span> <span data-ttu-id="d545e-263">Wenn Sie die speicherkontoschlüssel ändern möchten, verwenden Sie die Schlüssel neu generieren-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="d545e-263">If you want to change the storage account keys, use the regenerate keys operation.</span></span> <span data-ttu-id="d545e-264">Der Speicherort und den Namen des Speicherkontos können nach der Erstellung nicht geändert werden.</span><span class="sxs-lookup"><span data-stu-id="d545e-264">The location and name of the storage account cannot be changed after creation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; UpdateAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; UpdateAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;UpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d545e-265">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d545e-265">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d545e-266">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="d545e-266">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="d545e-267">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="d545e-267">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d545e-268">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="d545e-268">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="d545e-269">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="d545e-269">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d545e-270">Die Parameter für die aktualisierte Konto bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="d545e-270">The parameters to provide for the updated account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d545e-271">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d545e-271">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d545e-272">Der Update-Vorgang kann verwendet werden, um die SKU, Verschlüsselung, zugriffstarifs oder Tags für ein Speicherkonto zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="d545e-272">The update operation can be used to update the SKU, encryption, access tier, or tags for a storage account.</span></span> <span data-ttu-id="d545e-273">Es kann auch verwendet werden, um das Konto zu einer benutzerdefinierten Domäne zuzuordnen.</span><span class="sxs-lookup"><span data-stu-id="d545e-273">It can also be used to map the account to a custom domain.</span></span> <span data-ttu-id="d545e-274">Nur eine benutzerdefinierte Domäne wird pro Speicherkonto unterstützt. die Ersetzung/Änderung der benutzerdefinierten Domäne wird nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="d545e-274">Only one custom domain is supported per storage account; the replacement/change of custom domain is not supported.</span></span> <span data-ttu-id="d545e-275">Um eine alte benutzerdefinierte Domäne zu ersetzen, muss der alte Wert gelöscht/aufgehoben werden bevor ein neuer Wert festgelegt werden kann.</span><span class="sxs-lookup"><span data-stu-id="d545e-275">In order to replace an old custom domain, the old value must be cleared/unregistered before a new value can be set.</span></span> <span data-ttu-id="d545e-276">Das Update von mehreren Eigenschaften wird unterstützt.</span><span class="sxs-lookup"><span data-stu-id="d545e-276">The update of multiple properties is supported.</span></span> <span data-ttu-id="d545e-277">Dieser Aufruf wird der Speicherschlüssel für das Konto nicht geändert.</span><span class="sxs-lookup"><span data-stu-id="d545e-277">This call does not change the storage keys for the account.</span></span> <span data-ttu-id="d545e-278">Wenn Sie die speicherkontoschlüssel ändern möchten, verwenden Sie die Schlüssel neu generieren-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="d545e-278">If you want to change the storage account keys, use the regenerate keys operation.</span></span> <span data-ttu-id="d545e-279">Der Speicherort und den Namen des Speicherkontos können nach der Erstellung nicht geändert werden.</span><span class="sxs-lookup"><span data-stu-id="d545e-279">The location and name of the storage account cannot be changed after creation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>