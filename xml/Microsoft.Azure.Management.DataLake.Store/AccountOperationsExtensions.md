<Type Name="AccountOperationsExtensions" FullName="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AccountOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AccountOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AccountOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AccountOperationsExtensions = class" />
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
            <span data-ttu-id="7ca31-101">Erweiterungsmethoden für AccountOperations.</span><span class="sxs-lookup"><span data-stu-id="7ca31-101">Extension methods for AccountOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount BeginCreate (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount BeginCreate(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.BeginCreate(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As IAccountOperations, resourceGroupName As String, name As String, parameters As DataLakeStoreAccount) As DataLakeStoreAccount" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount -&gt; Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.BeginCreate (operations, resourceGroupName, name, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ca31-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7ca31-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ca31-103">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="7ca31-103">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="7ca31-104">Der Name des zu erstellenden Kontos Data Lake-Speicher.</span><span class="sxs-lookup"><span data-stu-id="7ca31-104">The name of the Data Lake Store account to create.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7ca31-105">Der Parameter angegeben, um das Data Lake-Speicher-Konto zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="7ca31-105">Parameters supplied to create the Data Lake Store account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ca31-106">Erstellt das angegebene Data Lake-Speicher-Konto an.</span><span class="sxs-lookup"><span data-stu-id="7ca31-106">Creates the specified Data Lake Store account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; BeginCreateAsync (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; BeginCreateAsync(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions/&lt;BeginCreateAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ca31-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7ca31-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ca31-108">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="7ca31-108">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="7ca31-109">Der Name des zu erstellenden Kontos Data Lake-Speicher.</span><span class="sxs-lookup"><span data-stu-id="7ca31-109">The name of the Data Lake Store account to create.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7ca31-110">Der Parameter angegeben, um das Data Lake-Speicher-Konto zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="7ca31-110">Parameters supplied to create the Data Lake Store account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ca31-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7ca31-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ca31-112">Erstellt das angegebene Data Lake-Speicher-Konto an.</span><span class="sxs-lookup"><span data-stu-id="7ca31-112">Creates the specified Data Lake Store account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.BeginDelete(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IAccountOperations, resourceGroupName As String, name As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.BeginDelete (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ca31-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7ca31-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ca31-114">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="7ca31-114">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="7ca31-115">Der Name des zu löschenden Kontos Data Lake-Speicher.</span><span class="sxs-lookup"><span data-stu-id="7ca31-115">The name of the Data Lake Store account to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ca31-116">Löscht das angegebene Data Lake-Speicher-Konto an.</span><span class="sxs-lookup"><span data-stu-id="7ca31-116">Deletes the specified Data Lake Store account.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions/&lt;BeginDeleteAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ca31-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7ca31-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ca31-118">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="7ca31-118">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="7ca31-119">Der Name des zu löschenden Kontos Data Lake-Speicher.</span><span class="sxs-lookup"><span data-stu-id="7ca31-119">The name of the Data Lake Store account to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ca31-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7ca31-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ca31-121">Löscht das angegebene Data Lake-Speicher-Konto an.</span><span class="sxs-lookup"><span data-stu-id="7ca31-121">Deletes the specified Data Lake Store account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount BeginUpdate (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount BeginUpdate(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdate (operations As IAccountOperations, resourceGroupName As String, name As String, parameters As DataLakeStoreAccountUpdateParameters) As DataLakeStoreAccount" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters -&gt; Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.BeginUpdate (operations, resourceGroupName, name, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ca31-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7ca31-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ca31-123">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="7ca31-123">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="7ca31-124">Der Name des zu aktualisierenden Kontos Data Lake-Speicher.</span><span class="sxs-lookup"><span data-stu-id="7ca31-124">The name of the Data Lake Store account to update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7ca31-125">Der Parameter angegeben, um das Data Lake-Speicher-Konto aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="7ca31-125">Parameters supplied to update the Data Lake Store account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ca31-126">Aktualisiert die angegebene Data Lake-Speicher-Kontoinformationen.</span><span class="sxs-lookup"><span data-stu-id="7ca31-126">Updates the specified Data Lake Store account information.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; BeginUpdateAsync (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; BeginUpdateAsync(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions/&lt;BeginUpdateAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ca31-127">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7ca31-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ca31-128">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="7ca31-128">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="7ca31-129">Der Name des zu aktualisierenden Kontos Data Lake-Speicher.</span><span class="sxs-lookup"><span data-stu-id="7ca31-129">The name of the Data Lake Store account to update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7ca31-130">Der Parameter angegeben, um das Data Lake-Speicher-Konto aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="7ca31-130">Parameters supplied to update the Data Lake Store account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ca31-131">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7ca31-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ca31-132">Aktualisiert die angegebene Data Lake-Speicher-Kontoinformationen.</span><span class="sxs-lookup"><span data-stu-id="7ca31-132">Updates the specified Data Lake Store account information.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount Create (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount Create(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.Create(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IAccountOperations, resourceGroupName As String, name As String, parameters As DataLakeStoreAccount) As DataLakeStoreAccount" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount -&gt; Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.Create (operations, resourceGroupName, name, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ca31-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7ca31-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ca31-134">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="7ca31-134">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="7ca31-135">Der Name des zu erstellenden Kontos Data Lake-Speicher.</span><span class="sxs-lookup"><span data-stu-id="7ca31-135">The name of the Data Lake Store account to create.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7ca31-136">Der Parameter angegeben, um das Data Lake-Speicher-Konto zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="7ca31-136">Parameters supplied to create the Data Lake Store account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ca31-137">Erstellt das angegebene Data Lake-Speicher-Konto an.</span><span class="sxs-lookup"><span data-stu-id="7ca31-137">Creates the specified Data Lake Store account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; CreateAsync (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; CreateAsync(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.CreateAsync(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.CreateAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions/&lt;CreateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ca31-138">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7ca31-138">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ca31-139">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="7ca31-139">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="7ca31-140">Der Name des zu erstellenden Kontos Data Lake-Speicher.</span><span class="sxs-lookup"><span data-stu-id="7ca31-140">The name of the Data Lake Store account to create.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7ca31-141">Der Parameter angegeben, um das Data Lake-Speicher-Konto zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="7ca31-141">Parameters supplied to create the Data Lake Store account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ca31-142">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7ca31-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ca31-143">Erstellt das angegebene Data Lake-Speicher-Konto an.</span><span class="sxs-lookup"><span data-stu-id="7ca31-143">Creates the specified Data Lake Store account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.Delete(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IAccountOperations, resourceGroupName As String, name As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.Delete (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ca31-144">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7ca31-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ca31-145">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="7ca31-145">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="7ca31-146">Der Name des zu löschenden Kontos Data Lake-Speicher.</span><span class="sxs-lookup"><span data-stu-id="7ca31-146">The name of the Data Lake Store account to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ca31-147">Löscht das angegebene Data Lake-Speicher-Konto an.</span><span class="sxs-lookup"><span data-stu-id="7ca31-147">Deletes the specified Data Lake Store account.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.DeleteAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions/&lt;DeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ca31-148">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7ca31-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ca31-149">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="7ca31-149">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="7ca31-150">Der Name des zu löschenden Kontos Data Lake-Speicher.</span><span class="sxs-lookup"><span data-stu-id="7ca31-150">The name of the Data Lake Store account to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ca31-151">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7ca31-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ca31-152">Löscht das angegebene Data Lake-Speicher-Konto an.</span><span class="sxs-lookup"><span data-stu-id="7ca31-152">Deletes the specified Data Lake Store account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableKeyVault">
      <MemberSignature Language="C#" Value="public static void EnableKeyVault (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void EnableKeyVault(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.EnableKeyVault(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub EnableKeyVault (operations As IAccountOperations, resourceGroupName As String, accountName As String)" />
      <MemberSignature Language="F#" Value="static member EnableKeyVault : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.EnableKeyVault (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ca31-153">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7ca31-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ca31-154">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="7ca31-154">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="7ca31-155">Der Name des Kontos Data Lake-Speicher für den Versuch des Schlüsseltresors für aktivieren.</span><span class="sxs-lookup"><span data-stu-id="7ca31-155">The name of the Data Lake Store account to attempt to enable the Key Vault for.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ca31-156">Versucht, einen Benutzer aktivieren verwaltet Key Vault, für die Verschlüsselung des angegebenen Kontos Data Lake-Speicher.</span><span class="sxs-lookup"><span data-stu-id="7ca31-156">Attempts to enable a user managed Key Vault for encryption of the specified Data Lake Store account.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableKeyVaultAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task EnableKeyVaultAsync (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task EnableKeyVaultAsync(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.EnableKeyVaultAsync(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member EnableKeyVaultAsync : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.EnableKeyVaultAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions/&lt;EnableKeyVaultAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ca31-157">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7ca31-157">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ca31-158">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="7ca31-158">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="7ca31-159">Der Name des Kontos Data Lake-Speicher für den Versuch des Schlüsseltresors für aktivieren.</span><span class="sxs-lookup"><span data-stu-id="7ca31-159">The name of the Data Lake Store account to attempt to enable the Key Vault for.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ca31-160">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7ca31-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ca31-161">Versucht, einen Benutzer aktivieren verwaltet Key Vault, für die Verschlüsselung des angegebenen Kontos Data Lake-Speicher.</span><span class="sxs-lookup"><span data-stu-id="7ca31-161">Attempts to enable a user managed Key Vault for encryption of the specified Data Lake Store account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exists">
      <MemberSignature Language="C#" Value="public static bool Exists (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool Exists(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.Exists(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Exists (operations As IAccountOperations, resourceGroupName As String, accountName As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member Exists : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string -&gt; bool" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.Exists (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ca31-162">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7ca31-162">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ca31-163">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="7ca31-163">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="7ca31-164">Der Name des Kontos Data Lake-Speicher abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="7ca31-164">The name of the Data Lake Store account to retrieve.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ca31-165">Ruft das angegebene Data Lake-Speicher-Konto ab.</span><span class="sxs-lookup"><span data-stu-id="7ca31-165">Gets the specified Data Lake Store account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ExistsAsync(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExistsAsync : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ExistsAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions/&lt;ExistsAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ca31-166">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7ca31-166">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ca31-167">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="7ca31-167">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="7ca31-168">Der Name des Kontos Data Lake-Speicher abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="7ca31-168">The name of the Data Lake Store account to retrieve.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ca31-169">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7ca31-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ca31-170">Ruft das angegebene Data Lake-Speicher-Konto ab.</span><span class="sxs-lookup"><span data-stu-id="7ca31-170">Gets the specified Data Lake Store account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirewallRuleExists">
      <MemberSignature Language="C#" Value="public static bool FirewallRuleExists (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string accountName, string firewallRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool FirewallRuleExists(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string accountName, string firewallRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.FirewallRuleExists(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function FirewallRuleExists (operations As IAccountOperations, resourceGroupName As String, accountName As String, firewallRuleName As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member FirewallRuleExists : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * string -&gt; bool" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.FirewallRuleExists (operations, resourceGroupName, accountName, firewallRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ca31-171">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7ca31-171">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ca31-172">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="7ca31-172">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="7ca31-173">Der Name des Data Lake-Speicher-Konto, von dem die Firewall-Regel abgerufen.</span><span class="sxs-lookup"><span data-stu-id="7ca31-173">The name of the Data Lake Store account from which to get the firewall rule.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="7ca31-174">Der Name der Firewallregel abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="7ca31-174">The name of the firewall rule to retrieve.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ca31-175">Ruft die angegebene Data Lake-Speicher-Firewallregel ab.</span><span class="sxs-lookup"><span data-stu-id="7ca31-175">Gets the specified Data Lake Store firewall rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirewallRuleExistsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; FirewallRuleExistsAsync (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string accountName, string firewallRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; FirewallRuleExistsAsync(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string accountName, string firewallRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.FirewallRuleExistsAsync(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member FirewallRuleExistsAsync : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.FirewallRuleExistsAsync (operations, resourceGroupName, accountName, firewallRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions/&lt;FirewallRuleExistsAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ca31-176">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7ca31-176">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ca31-177">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="7ca31-177">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="7ca31-178">Der Name des Data Lake-Speicher-Konto, von dem die Firewall-Regel abgerufen.</span><span class="sxs-lookup"><span data-stu-id="7ca31-178">The name of the Data Lake Store account from which to get the firewall rule.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="7ca31-179">Der Name der Firewallregel abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="7ca31-179">The name of the firewall rule to retrieve.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ca31-180">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7ca31-180">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ca31-181">Ruft die angegebene Data Lake-Speicher-Firewallregel ab.</span><span class="sxs-lookup"><span data-stu-id="7ca31-181">Gets the specified Data Lake Store firewall rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount Get (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount Get(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.Get(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IAccountOperations, resourceGroupName As String, name As String) As DataLakeStoreAccount" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string -&gt; Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.Get (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ca31-182">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7ca31-182">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ca31-183">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="7ca31-183">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="7ca31-184">Der Name des Kontos Data Lake-Speicher abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="7ca31-184">The name of the Data Lake Store account to retrieve.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ca31-185">Ruft das angegebene Data Lake-Speicher-Konto ab.</span><span class="sxs-lookup"><span data-stu-id="7ca31-185">Gets the specified Data Lake Store account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; GetAsync (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; GetAsync(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.GetAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions/&lt;GetAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ca31-186">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7ca31-186">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ca31-187">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="7ca31-187">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="7ca31-188">Der Name des Kontos Data Lake-Speicher abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="7ca31-188">The name of the Data Lake Store account to retrieve.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ca31-189">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7ca31-189">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ca31-190">Ruft das angegebene Data Lake-Speicher-Konto ab.</span><span class="sxs-lookup"><span data-stu-id="7ca31-190">Gets the specified Data Lake Store account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt; List (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt; List(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.List(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IAccountOperations, Optional odataQuery As ODataQuery(Of DataLakeStoreAccount) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of DataLakeStoreAccountBasic)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.List (operations, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ca31-191">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7ca31-191">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="7ca31-192">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="7ca31-192">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="7ca31-193">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="7ca31-193">OData Select statement.</span></span> <span data-ttu-id="7ca31-194">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="7ca31-194">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="7ca31-195">Optional.</span><span class="sxs-lookup"><span data-stu-id="7ca31-195">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="7ca31-196">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="7ca31-196">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="7ca31-197">Optional.</span><span class="sxs-lookup"><span data-stu-id="7ca31-197">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ca31-198">Listet die Data Lake-Speicher-Konten innerhalb des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="7ca31-198">Lists the Data Lake Store accounts within the subscription.</span></span> <span data-ttu-id="7ca31-199">Die Antwort enthält einen Link zur nächsten Seite der Ergebnisse, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="7ca31-199">The response includes a link to the next page of results, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt; ListAsync (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt; ListAsync(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ListAsync (operations, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions/&lt;ListAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ca31-200">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7ca31-200">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="7ca31-201">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="7ca31-201">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="7ca31-202">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="7ca31-202">OData Select statement.</span></span> <span data-ttu-id="7ca31-203">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="7ca31-203">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="7ca31-204">Optional.</span><span class="sxs-lookup"><span data-stu-id="7ca31-204">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="7ca31-205">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="7ca31-205">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="7ca31-206">Optional.</span><span class="sxs-lookup"><span data-stu-id="7ca31-206">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ca31-207">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7ca31-207">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ca31-208">Listet die Data Lake-Speicher-Konten innerhalb des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="7ca31-208">Lists the Data Lake Store accounts within the subscription.</span></span> <span data-ttu-id="7ca31-209">Die Antwort enthält einen Link zur nächsten Seite der Ergebnisse, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="7ca31-209">The response includes a link to the next page of results, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt; ListByResourceGroup (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt; ListByResourceGroup(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IAccountOperations, resourceGroupName As String, Optional odataQuery As ODataQuery(Of DataLakeStoreAccount) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of DataLakeStoreAccountBasic)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ListByResourceGroup (operations, resourceGroupName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ca31-210">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7ca31-210">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ca31-211">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicher-Konten enthält.</span><span class="sxs-lookup"><span data-stu-id="7ca31-211">The name of the Azure resource group that contains the Data Lake Store account(s).</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="7ca31-212">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="7ca31-212">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="7ca31-213">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="7ca31-213">OData Select statement.</span></span> <span data-ttu-id="7ca31-214">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="7ca31-214">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="7ca31-215">Optional.</span><span class="sxs-lookup"><span data-stu-id="7ca31-215">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="7ca31-216">Ein boolescher Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="7ca31-216">A Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="7ca31-217">Optional.</span><span class="sxs-lookup"><span data-stu-id="7ca31-217">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ca31-218">Listet die Data Lake-Speicher-Konten innerhalb einer bestimmten Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="7ca31-218">Lists the Data Lake Store accounts within a specific resource group.</span></span> <span data-ttu-id="7ca31-219">Die Antwort enthält einen Link zur nächsten Seite der Ergebnisse, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="7ca31-219">The response includes a link to the next page of results, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ca31-220">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7ca31-220">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ca31-221">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicher-Konten enthält.</span><span class="sxs-lookup"><span data-stu-id="7ca31-221">The name of the Azure resource group that contains the Data Lake Store account(s).</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="7ca31-222">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="7ca31-222">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="7ca31-223">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="7ca31-223">OData Select statement.</span></span> <span data-ttu-id="7ca31-224">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="7ca31-224">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="7ca31-225">Optional.</span><span class="sxs-lookup"><span data-stu-id="7ca31-225">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="7ca31-226">Ein boolescher Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="7ca31-226">A Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="7ca31-227">Optional.</span><span class="sxs-lookup"><span data-stu-id="7ca31-227">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ca31-228">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7ca31-228">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ca31-229">Listet die Data Lake-Speicher-Konten innerhalb einer bestimmten Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="7ca31-229">Lists the Data Lake Store accounts within a specific resource group.</span></span> <span data-ttu-id="7ca31-230">Die Antwort enthält einen Link zur nächsten Seite der Ergebnisse, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="7ca31-230">The response includes a link to the next page of results, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IAccountOperations, nextPageLink As String) As IPage(Of DataLakeStoreAccountBasic)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ca31-231">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7ca31-231">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7ca31-232">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="7ca31-232">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ca31-233">Listet die Data Lake-Speicher-Konten innerhalb einer bestimmten Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="7ca31-233">Lists the Data Lake Store accounts within a specific resource group.</span></span> <span data-ttu-id="7ca31-234">Die Antwort enthält einen Link zur nächsten Seite der Ergebnisse, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="7ca31-234">The response includes a link to the next page of results, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ca31-235">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7ca31-235">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7ca31-236">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="7ca31-236">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ca31-237">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7ca31-237">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ca31-238">Listet die Data Lake-Speicher-Konten innerhalb einer bestimmten Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="7ca31-238">Lists the Data Lake Store accounts within a specific resource group.</span></span> <span data-ttu-id="7ca31-239">Die Antwort enthält einen Link zur nächsten Seite der Ergebnisse, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="7ca31-239">The response includes a link to the next page of results, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt; ListNext (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt; ListNext(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ListNext(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IAccountOperations, nextPageLink As String) As IPage(Of DataLakeStoreAccountBasic)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ca31-240">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7ca31-240">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7ca31-241">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="7ca31-241">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ca31-242">Listet die Data Lake-Speicher-Konten innerhalb des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="7ca31-242">Lists the Data Lake Store accounts within the subscription.</span></span> <span data-ttu-id="7ca31-243">Die Antwort enthält einen Link zur nächsten Seite der Ergebnisse, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="7ca31-243">The response includes a link to the next page of results, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions/&lt;ListNextAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ca31-244">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7ca31-244">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7ca31-245">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="7ca31-245">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ca31-246">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7ca31-246">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ca31-247">Listet die Data Lake-Speicher-Konten innerhalb des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="7ca31-247">Lists the Data Lake Store accounts within the subscription.</span></span> <span data-ttu-id="7ca31-248">Die Antwort enthält einen Link zur nächsten Seite der Ergebnisse, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="7ca31-248">The response includes a link to the next page of results, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount Update (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount Update(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.Update(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IAccountOperations, resourceGroupName As String, name As String, parameters As DataLakeStoreAccountUpdateParameters) As DataLakeStoreAccount" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters -&gt; Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.Update (operations, resourceGroupName, name, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ca31-249">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7ca31-249">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ca31-250">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="7ca31-250">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="7ca31-251">Der Name des zu aktualisierenden Kontos Data Lake-Speicher.</span><span class="sxs-lookup"><span data-stu-id="7ca31-251">The name of the Data Lake Store account to update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7ca31-252">Der Parameter angegeben, um das Data Lake-Speicher-Konto aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="7ca31-252">Parameters supplied to update the Data Lake Store account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ca31-253">Aktualisiert die angegebene Data Lake-Speicher-Kontoinformationen.</span><span class="sxs-lookup"><span data-stu-id="7ca31-253">Updates the specified Data Lake Store account information.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; UpdateAsync (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; UpdateAsync(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.UpdateAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions/&lt;UpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ca31-254">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7ca31-254">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ca31-255">Der Name des Azure-Ressourcengruppe, die die Data Lake-Speicherkonto enthält.</span><span class="sxs-lookup"><span data-stu-id="7ca31-255">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="7ca31-256">Der Name des zu aktualisierenden Kontos Data Lake-Speicher.</span><span class="sxs-lookup"><span data-stu-id="7ca31-256">The name of the Data Lake Store account to update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7ca31-257">Der Parameter angegeben, um das Data Lake-Speicher-Konto aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="7ca31-257">Parameters supplied to update the Data Lake Store account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ca31-258">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7ca31-258">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ca31-259">Aktualisiert die angegebene Data Lake-Speicher-Kontoinformationen.</span><span class="sxs-lookup"><span data-stu-id="7ca31-259">Updates the specified Data Lake Store account information.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>