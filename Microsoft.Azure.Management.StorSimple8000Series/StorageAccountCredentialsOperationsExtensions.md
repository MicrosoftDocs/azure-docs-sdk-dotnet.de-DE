<Type Name="StorageAccountCredentialsOperationsExtensions" FullName="Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class StorageAccountCredentialsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit StorageAccountCredentialsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module StorageAccountCredentialsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type StorageAccountCredentialsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="22170-101">Erweiterungsmethoden für StorageAccountCredentialsOperations.</span><span class="sxs-lookup"><span data-stu-id="22170-101">Extension methods for StorageAccountCredentialsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential BeginCreateOrUpdate (this Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations operations, string storageAccountCredentialName, Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential BeginCreateOrUpdate(class Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations operations, string storageAccountCredentialName, class Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IStorageAccountCredentialsOperations, storageAccountCredentialName As String, parameters As StorageAccountCredential, resourceGroupName As String, managerName As String) As StorageAccountCredential" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions.BeginCreateOrUpdate (operations, storageAccountCredentialName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations" RefType="this" />
        <Parameter Name="storageAccountCredentialName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22170-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="22170-102">The operations group for this extension method.</span></span>
            </param>
        <param name="storageAccountCredentialName">
            <span data-ttu-id="22170-103">Der Name des Speicherkontos Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="22170-103">The storage account credential name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="22170-104">Der Speicherkonto-Anmeldedaten hinzugefügt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="22170-104">The storage account credential to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="22170-105">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="22170-105">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="22170-106">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="22170-106">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="22170-107">Erstellt oder aktualisiert die Speicherkonto-Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="22170-107">Creates or updates the storage account credential.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations operations, string storageAccountCredentialName, Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations operations, string storageAccountCredentialName, class Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions.BeginCreateOrUpdateAsync (operations, storageAccountCredentialName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations" RefType="this" />
        <Parameter Name="storageAccountCredentialName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22170-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="22170-108">The operations group for this extension method.</span></span>
            </param>
        <param name="storageAccountCredentialName">
            <span data-ttu-id="22170-109">Der Name des Speicherkontos Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="22170-109">The storage account credential name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="22170-110">Der Speicherkonto-Anmeldedaten hinzugefügt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="22170-110">The storage account credential to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="22170-111">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="22170-111">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="22170-112">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="22170-112">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="22170-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="22170-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="22170-114">Erstellt oder aktualisiert die Speicherkonto-Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="22170-114">Creates or updates the storage account credential.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations operations, string storageAccountCredentialName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations operations, string storageAccountCredentialName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IStorageAccountCredentialsOperations, storageAccountCredentialName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions.BeginDelete (operations, storageAccountCredentialName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations" RefType="this" />
        <Parameter Name="storageAccountCredentialName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22170-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="22170-115">The operations group for this extension method.</span></span>
            </param>
        <param name="storageAccountCredentialName">
            <span data-ttu-id="22170-116">Der Name des der Speicherkonto-Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="22170-116">The name of the storage account credential.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="22170-117">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="22170-117">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="22170-118">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="22170-118">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="22170-119">Löscht die Speicherkonto-Anmeldeinformationen an.</span><span class="sxs-lookup"><span data-stu-id="22170-119">Deletes the storage account credential.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations operations, string storageAccountCredentialName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations operations, string storageAccountCredentialName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions.BeginDeleteAsync (operations, storageAccountCredentialName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations" RefType="this" />
        <Parameter Name="storageAccountCredentialName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22170-120">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="22170-120">The operations group for this extension method.</span></span>
            </param>
        <param name="storageAccountCredentialName">
            <span data-ttu-id="22170-121">Der Name des der Speicherkonto-Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="22170-121">The name of the storage account credential.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="22170-122">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="22170-122">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="22170-123">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="22170-123">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="22170-124">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="22170-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="22170-125">Löscht die Speicherkonto-Anmeldeinformationen an.</span><span class="sxs-lookup"><span data-stu-id="22170-125">Deletes the storage account credential.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential CreateOrUpdate (this Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations operations, string storageAccountCredentialName, Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential CreateOrUpdate(class Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations operations, string storageAccountCredentialName, class Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IStorageAccountCredentialsOperations, storageAccountCredentialName As String, parameters As StorageAccountCredential, resourceGroupName As String, managerName As String) As StorageAccountCredential" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions.CreateOrUpdate (operations, storageAccountCredentialName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations" RefType="this" />
        <Parameter Name="storageAccountCredentialName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22170-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="22170-126">The operations group for this extension method.</span></span>
            </param>
        <param name="storageAccountCredentialName">
            <span data-ttu-id="22170-127">Der Name des Speicherkontos Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="22170-127">The storage account credential name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="22170-128">Der Speicherkonto-Anmeldedaten hinzugefügt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="22170-128">The storage account credential to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="22170-129">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="22170-129">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="22170-130">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="22170-130">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="22170-131">Erstellt oder aktualisiert die Speicherkonto-Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="22170-131">Creates or updates the storage account credential.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations operations, string storageAccountCredentialName, Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations operations, string storageAccountCredentialName, class Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions.CreateOrUpdateAsync (operations, storageAccountCredentialName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations" RefType="this" />
        <Parameter Name="storageAccountCredentialName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22170-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="22170-132">The operations group for this extension method.</span></span>
            </param>
        <param name="storageAccountCredentialName">
            <span data-ttu-id="22170-133">Der Name des Speicherkontos Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="22170-133">The storage account credential name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="22170-134">Der Speicherkonto-Anmeldedaten hinzugefügt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="22170-134">The storage account credential to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="22170-135">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="22170-135">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="22170-136">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="22170-136">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="22170-137">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="22170-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="22170-138">Erstellt oder aktualisiert die Speicherkonto-Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="22170-138">Creates or updates the storage account credential.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations operations, string storageAccountCredentialName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations operations, string storageAccountCredentialName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions.Delete(Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IStorageAccountCredentialsOperations, storageAccountCredentialName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions.Delete (operations, storageAccountCredentialName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations" RefType="this" />
        <Parameter Name="storageAccountCredentialName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22170-139">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="22170-139">The operations group for this extension method.</span></span>
            </param>
        <param name="storageAccountCredentialName">
            <span data-ttu-id="22170-140">Der Name des der Speicherkonto-Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="22170-140">The name of the storage account credential.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="22170-141">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="22170-141">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="22170-142">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="22170-142">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="22170-143">Löscht die Speicherkonto-Anmeldeinformationen an.</span><span class="sxs-lookup"><span data-stu-id="22170-143">Deletes the storage account credential.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations operations, string storageAccountCredentialName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations operations, string storageAccountCredentialName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions.DeleteAsync (operations, storageAccountCredentialName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations" RefType="this" />
        <Parameter Name="storageAccountCredentialName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22170-144">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="22170-144">The operations group for this extension method.</span></span>
            </param>
        <param name="storageAccountCredentialName">
            <span data-ttu-id="22170-145">Der Name des der Speicherkonto-Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="22170-145">The name of the storage account credential.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="22170-146">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="22170-146">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="22170-147">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="22170-147">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="22170-148">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="22170-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="22170-149">Löscht die Speicherkonto-Anmeldeinformationen an.</span><span class="sxs-lookup"><span data-stu-id="22170-149">Deletes the storage account credential.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential Get (this Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations operations, string storageAccountCredentialName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential Get(class Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations operations, string storageAccountCredentialName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions.Get(Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IStorageAccountCredentialsOperations, storageAccountCredentialName As String, resourceGroupName As String, managerName As String) As StorageAccountCredential" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions.Get (operations, storageAccountCredentialName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations" RefType="this" />
        <Parameter Name="storageAccountCredentialName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22170-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="22170-150">The operations group for this extension method.</span></span>
            </param>
        <param name="storageAccountCredentialName">
            <span data-ttu-id="22170-151">Der Name des Speicherkonto-Anmeldeinformationen abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="22170-151">The name of storage account credential to be fetched.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="22170-152">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="22170-152">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="22170-153">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="22170-153">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="22170-154">Ruft die Eigenschaften der Name des angegebenen Speicherkontos Anmeldeinformationen ab.</span><span class="sxs-lookup"><span data-stu-id="22170-154">Gets the properties of the specified storage account credential name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt; GetAsync (this Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations operations, string storageAccountCredentialName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt; GetAsync(class Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations operations, string storageAccountCredentialName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions.GetAsync(Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions.GetAsync (operations, storageAccountCredentialName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations" RefType="this" />
        <Parameter Name="storageAccountCredentialName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22170-155">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="22170-155">The operations group for this extension method.</span></span>
            </param>
        <param name="storageAccountCredentialName">
            <span data-ttu-id="22170-156">Der Name des Speicherkonto-Anmeldeinformationen abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="22170-156">The name of storage account credential to be fetched.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="22170-157">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="22170-157">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="22170-158">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="22170-158">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="22170-159">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="22170-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="22170-160">Ruft die Eigenschaften der Name des angegebenen Speicherkontos Anmeldeinformationen ab.</span><span class="sxs-lookup"><span data-stu-id="22170-160">Gets the properties of the specified storage account credential name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByManager">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt; ListByManager (this Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations operations, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt; ListByManager(class Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations operations, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions.ListByManager(Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByManager (operations As IStorageAccountCredentialsOperations, resourceGroupName As String, managerName As String) As IEnumerable(Of StorageAccountCredential)" />
      <MemberSignature Language="F#" Value="static member ListByManager : Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions.ListByManager (operations, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22170-161">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="22170-161">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="22170-162">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="22170-162">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="22170-163">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="22170-163">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="22170-164">Ruft alle Anmeldeinformationen für das Speicherkonto in einem Manager.</span><span class="sxs-lookup"><span data-stu-id="22170-164">Gets all the storage account credentials in a manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByManagerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt;&gt; ListByManagerAsync (this Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations operations, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt;&gt; ListByManagerAsync(class Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations operations, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions.ListByManagerAsync(Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByManagerAsync : Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions.ListByManagerAsync (operations, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.StorageAccountCredentialsOperationsExtensions/&lt;ListByManagerAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22170-165">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="22170-165">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="22170-166">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="22170-166">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="22170-167">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="22170-167">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="22170-168">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="22170-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="22170-169">Ruft alle Anmeldeinformationen für das Speicherkonto in einem Manager.</span><span class="sxs-lookup"><span data-stu-id="22170-169">Gets all the storage account credentials in a manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>