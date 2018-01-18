<Type Name="StorageAccountsOperationsExtensions" FullName="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class StorageAccountsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit StorageAccountsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module StorageAccountsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type StorageAccountsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5c45a-101">Erweiterungsmethoden für StorageAccountsOperations.</span><span class="sxs-lookup"><span data-stu-id="5c45a-101">Extension methods for StorageAccountsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; BeginCreateAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; BeginCreateAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;BeginCreateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5c45a-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5c45a-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5c45a-103">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="5c45a-103">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="5c45a-104">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5c45a-104">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="5c45a-105">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="5c45a-105">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5c45a-106">Die Parameter für das erstellte Konto bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="5c45a-106">The parameters to provide for the created account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5c45a-107">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5c45a-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5c45a-108">Erstellt asynchron ein neues Speicherkonto mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="5c45a-108">Asynchronously creates a new storage account with the specified parameters.</span></span>
            <span data-ttu-id="5c45a-109">Wenn bereits ein Konto erstellt wird, und eine nachfolgende erstellungsanforderung wird, mit verschiedenen Eigenschaften ausgegeben, werden die Kontoeigenschaften aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="5c45a-109">If an account is already created and a subsequent create request is issued with different properties, the account properties will be updated.</span></span> <span data-ttu-id="5c45a-110">Wenn bereits ein Konto erstellt wird, und eine nachfolgende CREATE- oder Update-Anforderung wird, mit dem genau gleichen Satz von Eigenschaften ausgegeben, wird die Anforderung erfolgreich ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="5c45a-110">If an account is already created and a subsequent create or update request is issued with the exact same set of properties, the request will succeed.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner&gt; CheckNameAvailabilityAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner&gt; CheckNameAvailabilityAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.CheckNameAvailabilityAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailabilityAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.CheckNameAvailabilityAsync (operations, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;CheckNameAvailabilityAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5c45a-111">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5c45a-111">The operations group for this extension method.</span></span>
            </param>
        <param name="name"></param>
        <param name="cancellationToken">
            <span data-ttu-id="5c45a-112">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5c45a-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5c45a-113">Überprüft, ob der Name des Speicherkontos ist gültig und wird nicht bereits verwendet.</span><span class="sxs-lookup"><span data-stu-id="5c45a-113">Checks that the storage account name is valid and is not already in use.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; CreateAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; CreateAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.CreateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;CreateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5c45a-114">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5c45a-114">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5c45a-115">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="5c45a-115">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="5c45a-116">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5c45a-116">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="5c45a-117">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="5c45a-117">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5c45a-118">Die Parameter für das erstellte Konto bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="5c45a-118">The parameters to provide for the created account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5c45a-119">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5c45a-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5c45a-120">Erstellt asynchron ein neues Speicherkonto mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="5c45a-120">Asynchronously creates a new storage account with the specified parameters.</span></span>
            <span data-ttu-id="5c45a-121">Wenn bereits ein Konto erstellt wird, und eine nachfolgende erstellungsanforderung wird, mit verschiedenen Eigenschaften ausgegeben, werden die Kontoeigenschaften aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="5c45a-121">If an account is already created and a subsequent create request is issued with different properties, the account properties will be updated.</span></span> <span data-ttu-id="5c45a-122">Wenn bereits ein Konto erstellt wird, und eine nachfolgende CREATE- oder Update-Anforderung wird, mit dem genau gleichen Satz von Eigenschaften ausgegeben, wird die Anforderung erfolgreich ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="5c45a-122">If an account is already created and a subsequent create or update request is issued with the exact same set of properties, the request will succeed.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5c45a-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5c45a-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5c45a-124">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="5c45a-124">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="5c45a-125">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5c45a-125">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="5c45a-126">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="5c45a-126">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5c45a-127">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5c45a-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5c45a-128">Löscht ein Speicherkonto in Microsoft Azure.</span><span class="sxs-lookup"><span data-stu-id="5c45a-128">Deletes a storage account in Microsoft Azure.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPropertiesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; GetPropertiesAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; GetPropertiesAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.GetPropertiesAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetPropertiesAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.GetPropertiesAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;GetPropertiesAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5c45a-129">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5c45a-129">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5c45a-130">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="5c45a-130">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="5c45a-131">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5c45a-131">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="5c45a-132">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="5c45a-132">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5c45a-133">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5c45a-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5c45a-134">Die Eigenschaften für das angegebene Speicherkonto einschließlich, aber nicht beschränkt auf Name, SKU-Name, Speicherort und Kontostatus zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="5c45a-134">Returns the properties for the specified storage account including but not limited to name, SKU name, location, and account status.</span></span> <span data-ttu-id="5c45a-135">Der ListKeys-Vorgang sollte verwendet werden, um Speicherschlüssel abzurufen.</span><span class="sxs-lookup"><span data-stu-id="5c45a-135">The ListKeys operation should be used to retrieve storage keys.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;ListAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5c45a-136">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5c45a-136">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5c45a-137">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5c45a-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5c45a-138">Listet alle Speicherkonten im Abonnement verfügbar.</span><span class="sxs-lookup"><span data-stu-id="5c45a-138">Lists all the storage accounts available under the subscription.</span></span> <span data-ttu-id="5c45a-139">Beachten Sie, dass Speicherschlüssel nicht zurückgegeben werden. Verwenden Sie den ListKeys-Vorgang für diesen ein.</span><span class="sxs-lookup"><span data-stu-id="5c45a-139">Note that storage keys are not returned; use the ListKeys operation for this.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5c45a-140">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5c45a-140">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5c45a-141">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="5c45a-141">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5c45a-142">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5c45a-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5c45a-143">Listet alle Speicherkonten verfügbar sind, unter der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5c45a-143">Lists all the storage accounts available under the given resource group.</span></span>
            <span data-ttu-id="5c45a-144">Beachten Sie, dass Speicherschlüssel nicht zurückgegeben werden. Verwenden Sie den ListKeys-Vorgang für diesen ein.</span><span class="sxs-lookup"><span data-stu-id="5c45a-144">Note that storage keys are not returned; use the ListKeys operation for this.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt; ListKeysAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt; ListKeysAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.ListKeysAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeysAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.ListKeysAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;ListKeysAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5c45a-145">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5c45a-145">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5c45a-146">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="5c45a-146">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="5c45a-147">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5c45a-147">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="5c45a-148">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="5c45a-148">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5c45a-149">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5c45a-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5c45a-150">Listet die Zugriffsschlüssel für das angegebene Speicherkonto.</span><span class="sxs-lookup"><span data-stu-id="5c45a-150">Lists the access keys for the specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt; RegenerateKeyAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt; RegenerateKeyAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.RegenerateKeyAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeyAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.RegenerateKeyAsync (operations, resourceGroupName, accountName, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;RegenerateKeyAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5c45a-151">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5c45a-151">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5c45a-152">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="5c45a-152">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="5c45a-153">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5c45a-153">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="5c45a-154">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="5c45a-154">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="keyName"></param>
        <param name="cancellationToken">
            <span data-ttu-id="5c45a-155">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5c45a-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5c45a-156">Generiert eine die Zugriffsschlüssel für das angegebene Speicherkonto.</span><span class="sxs-lookup"><span data-stu-id="5c45a-156">Regenerates one of the access keys for the specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; UpdateAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; UpdateAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;UpdateAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5c45a-157">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5c45a-157">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5c45a-158">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="5c45a-158">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="5c45a-159">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5c45a-159">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="5c45a-160">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="5c45a-160">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5c45a-161">Die Parameter für die aktualisierte Konto bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="5c45a-161">The parameters to provide for the updated account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5c45a-162">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5c45a-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5c45a-163">Der Update-Vorgang kann verwendet werden, um die SKU, Verschlüsselung, zugriffstarifs oder Tags für ein Speicherkonto zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="5c45a-163">The update operation can be used to update the SKU, encryption, access tier, or tags for a storage account.</span></span> <span data-ttu-id="5c45a-164">Es kann auch verwendet werden, um das Konto zu einer benutzerdefinierten Domäne zuzuordnen.</span><span class="sxs-lookup"><span data-stu-id="5c45a-164">It can also be used to map the account to a custom domain.</span></span> <span data-ttu-id="5c45a-165">Nur eine benutzerdefinierte Domäne wird pro Speicherkonto unterstützt. die Ersetzung/Änderung der benutzerdefinierten Domäne wird nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="5c45a-165">Only one custom domain is supported per storage account; the replacement/change of custom domain is not supported.</span></span> <span data-ttu-id="5c45a-166">Um eine alte benutzerdefinierte Domäne zu ersetzen, muss der alte Wert gelöscht/aufgehoben werden bevor ein neuer Wert festgelegt werden kann.</span><span class="sxs-lookup"><span data-stu-id="5c45a-166">In order to replace an old custom domain, the old value must be cleared/unregistered before a new value can be set.</span></span> <span data-ttu-id="5c45a-167">Das Update von mehreren Eigenschaften wird unterstützt.</span><span class="sxs-lookup"><span data-stu-id="5c45a-167">The update of multiple properties is supported.</span></span> <span data-ttu-id="5c45a-168">Dieser Aufruf wird der Speicherschlüssel für das Konto nicht geändert.</span><span class="sxs-lookup"><span data-stu-id="5c45a-168">This call does not change the storage keys for the account.</span></span> <span data-ttu-id="5c45a-169">Wenn Sie die speicherkontoschlüssel ändern möchten, verwenden Sie die Schlüssel neu generieren-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="5c45a-169">If you want to change the storage account keys, use the regenerate keys operation.</span></span> <span data-ttu-id="5c45a-170">Der Speicherort und den Namen des Speicherkontos können nach der Erstellung nicht geändert werden.</span><span class="sxs-lookup"><span data-stu-id="5c45a-170">The location and name of the storage account cannot be changed after creation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>