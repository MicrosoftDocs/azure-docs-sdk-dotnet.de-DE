<Type Name="CatalogOperationsExtensions" FullName="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class CatalogOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CatalogOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CatalogOperationsExtensions" />
  <TypeSignature Language="F#" Value="type CatalogOperationsExtensions = class" />
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
            <span data-ttu-id="9d89e-101">Erweiterungsmethoden für CatalogOperations.</span><span class="sxs-lookup"><span data-stu-id="9d89e-101">Extension methods for CatalogOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateCredential">
      <MemberSignature Language="C#" Value="public static void CreateCredential (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void CreateCredential(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.CreateCredential(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub CreateCredential (operations As ICatalogOperations, accountName As String, databaseName As String, credentialName As String, parameters As DataLakeAnalyticsCatalogCredentialCreateParameters)" />
      <MemberSignature Language="F#" Value="static member CreateCredential : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.CreateCredential (operations, accountName, databaseName, credentialName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="credentialName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-102">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-103">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-103">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-104">Der Name der Datenbank, in der Sie die Anmeldeinformationen erstellen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-104">The name of the database in which to create the credential.</span></span> <span data-ttu-id="9d89e-105">Hinweis: Dies ist keine Namen einer externen Datenbank, sondern der Name einer vorhandenen U-SQL-Datenbank, die das neue Objekt mit Anmeldeinformationen enthalten soll.</span><span class="sxs-lookup"><span data-stu-id="9d89e-105">Note: This is NOT an external database name, but the name of an existing U-SQL database that should contain the new credential object.</span></span>
            </param>
        <param name="credentialName">
            <span data-ttu-id="9d89e-106">Der Name der Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-106">The name of the credential.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9d89e-107">Die Parameter erforderlich, um die Anmeldeinformationen (Name und Kennwort) erstellen</span><span class="sxs-lookup"><span data-stu-id="9d89e-107">The parameters required to create the credential (name and password)</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-108">Die angegebene Anmeldeinformationen für die Verwendung erstellt mit externen Datenquellen in der angegebenen Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9d89e-108">Creates the specified credential for use with external data sources in the specified database.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCredentialAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CreateCredentialAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CreateCredentialAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.CreateCredentialAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateCredentialAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.CreateCredentialAsync (operations, accountName, databaseName, credentialName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;CreateCredentialAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="credentialName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-109">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-110">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-110">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-111">Der Name der Datenbank, in der Sie die Anmeldeinformationen erstellen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-111">The name of the database in which to create the credential.</span></span> <span data-ttu-id="9d89e-112">Hinweis: Dies ist keine Namen einer externen Datenbank, sondern der Name einer vorhandenen U-SQL-Datenbank, die das neue Objekt mit Anmeldeinformationen enthalten soll.</span><span class="sxs-lookup"><span data-stu-id="9d89e-112">Note: This is NOT an external database name, but the name of an existing U-SQL database that should contain the new credential object.</span></span>
            </param>
        <param name="credentialName">
            <span data-ttu-id="9d89e-113">Der Name der Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-113">The name of the credential.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9d89e-114">Die Parameter erforderlich, um die Anmeldeinformationen (Name und Kennwort) erstellen</span><span class="sxs-lookup"><span data-stu-id="9d89e-114">The parameters required to create the credential (name and password)</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-116">Die angegebene Anmeldeinformationen für die Verwendung erstellt mit externen Datenquellen in der angegebenen Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9d89e-116">Creates the specified credential for use with external data sources in the specified database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSecret">
      <MemberSignature Language="C#" Value="public static void CreateSecret (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void CreateSecret(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.CreateSecret(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub CreateSecret (operations As ICatalogOperations, accountName As String, databaseName As String, secretName As String, parameters As DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters)" />
      <MemberSignature Language="F#" Value="static member CreateSecret : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.CreateSecret (operations, accountName, databaseName, secretName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-117">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-118">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-118">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-119">Der Name der Datenbank, in dem den geheime Schlüssel erstellt.</span><span class="sxs-lookup"><span data-stu-id="9d89e-119">The name of the database in which to create the secret.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="9d89e-120">Der Name des geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="9d89e-120">The name of the secret.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9d89e-121">Die Parameter erforderlich, um den geheimen Schlüssel (Namen und Kennwort) erstellen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-121">The parameters required to create the secret (name and password)</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-122">Den angegebene geheime Schlüssel für die Verwendung erstellt mit externen Datenquellen in der angegebenen Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9d89e-122">Creates the specified secret for use with external data sources in the specified database.</span></span> <span data-ttu-id="9d89e-123">Dies ist veraltet und wird in der nächsten Version entfernt.</span><span class="sxs-lookup"><span data-stu-id="9d89e-123">This is deprecated and will be removed in the next release.</span></span> <span data-ttu-id="9d89e-124">Verwenden Sie stattdessen CreateCredential.</span><span class="sxs-lookup"><span data-stu-id="9d89e-124">Please use CreateCredential instead.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CreateSecretAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CreateSecretAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.CreateSecretAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateSecretAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.CreateSecretAsync (operations, accountName, databaseName, secretName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;CreateSecretAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-125">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-125">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-126">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-126">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-127">Der Name der Datenbank, in dem den geheime Schlüssel erstellt.</span><span class="sxs-lookup"><span data-stu-id="9d89e-127">The name of the database in which to create the secret.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="9d89e-128">Der Name des geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="9d89e-128">The name of the secret.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9d89e-129">Die Parameter erforderlich, um den geheimen Schlüssel (Namen und Kennwort) erstellen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-129">The parameters required to create the secret (name and password)</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-130">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-131">Den angegebene geheime Schlüssel für die Verwendung erstellt mit externen Datenquellen in der angegebenen Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9d89e-131">Creates the specified secret for use with external data sources in the specified database.</span></span> <span data-ttu-id="9d89e-132">Dies ist veraltet und wird in der nächsten Version entfernt.</span><span class="sxs-lookup"><span data-stu-id="9d89e-132">This is deprecated and will be removed in the next release.</span></span> <span data-ttu-id="9d89e-133">Verwenden Sie stattdessen CreateCredential.</span><span class="sxs-lookup"><span data-stu-id="9d89e-133">Please use CreateCredential instead.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAllSecrets">
      <MemberSignature Language="C#" Value="public static void DeleteAllSecrets (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteAllSecrets(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.DeleteAllSecrets(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteAllSecrets (operations As ICatalogOperations, accountName As String, databaseName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteAllSecrets : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.DeleteAllSecrets (operations, accountName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-134">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-134">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-135">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-135">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-136">Der Name der Datenbank, die den geheimen Schlüssel enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-136">The name of the database containing the secret.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-137">Löscht alle geheimen Schlüssel in der angegebenen Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9d89e-137">Deletes all secrets in the specified database.</span></span> <span data-ttu-id="9d89e-138">Dies ist veraltet und wird in der nächsten Version entfernt.</span><span class="sxs-lookup"><span data-stu-id="9d89e-138">This is deprecated and will be removed in the next release.</span></span> <span data-ttu-id="9d89e-139">In der Zukunft nur löschen Sie einzelne DeleteCredential mit Anmeldeinformationen</span><span class="sxs-lookup"><span data-stu-id="9d89e-139">In the future, please only drop individual credentials using DeleteCredential</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAllSecretsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAllSecretsAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAllSecretsAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.DeleteAllSecretsAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAllSecretsAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.DeleteAllSecretsAsync (operations, accountName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;DeleteAllSecretsAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-140">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-140">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-141">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-141">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-142">Der Name der Datenbank, die den geheimen Schlüssel enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-142">The name of the database containing the secret.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-143">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-144">Löscht alle geheimen Schlüssel in der angegebenen Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9d89e-144">Deletes all secrets in the specified database.</span></span> <span data-ttu-id="9d89e-145">Dies ist veraltet und wird in der nächsten Version entfernt.</span><span class="sxs-lookup"><span data-stu-id="9d89e-145">This is deprecated and will be removed in the next release.</span></span> <span data-ttu-id="9d89e-146">In der Zukunft nur löschen Sie einzelne DeleteCredential mit Anmeldeinformationen</span><span class="sxs-lookup"><span data-stu-id="9d89e-146">In the future, please only drop individual credentials using DeleteCredential</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCredential">
      <MemberSignature Language="C#" Value="public static void DeleteCredential (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters parameters = null, Nullable&lt;bool&gt; cascade = false);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteCredential(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters parameters, valuetype System.Nullable`1&lt;bool&gt; cascade) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.DeleteCredential(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteCredential (operations As ICatalogOperations, accountName As String, databaseName As String, credentialName As String, Optional parameters As DataLakeAnalyticsCatalogCredentialDeleteParameters = null, Optional cascade As Nullable(Of Boolean) = false)" />
      <MemberSignature Language="F#" Value="static member DeleteCredential : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters * Nullable&lt;bool&gt; -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.DeleteCredential (operations, accountName, databaseName, credentialName, parameters, cascade)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="credentialName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters" />
        <Parameter Name="cascade" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-147">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-147">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-148">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-148">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-149">Der Name der Datenbank, die die Anmeldeinformationen enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-149">The name of the database containing the credential.</span></span>
            </param>
        <param name="credentialName">
            <span data-ttu-id="9d89e-150">Der Name der Anmeldeinformationen löschen</span><span class="sxs-lookup"><span data-stu-id="9d89e-150">The name of the credential to delete</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9d89e-151">Die Parameter für Anmeldeinformationen zu löschen, wenn der aktuelle Benutzer nicht Besitzer des Kontos ist.</span><span class="sxs-lookup"><span data-stu-id="9d89e-151">The parameters to delete a credential if the current user is not the account owner.</span></span>
            </param>
        <param name="cascade">
            <span data-ttu-id="9d89e-152">Gibt an, ob der Löschvorgang einen Löschweitergabe werden sollen (Dadurch werden alle Ressourcen, die abhängig von den Anmeldeinformationen als auch die Anmeldeinformationen gelöscht) oder nicht.</span><span class="sxs-lookup"><span data-stu-id="9d89e-152">Indicates if the delete should be a cascading delete (which deletes all resources dependent on the credential as well as the credential) or not.</span></span> <span data-ttu-id="9d89e-153">Wenn "false" fehl, wenn alle Vertrauensstellungen der vertrauenden Seite zu den Anmeldeinformationen für Ressourcen vorhanden sind.</span><span class="sxs-lookup"><span data-stu-id="9d89e-153">If false will fail if there are any resources relying on the credential.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-154">Löscht die angegebene Anmeldeinformationen in der angegebenen Datenbank</span><span class="sxs-lookup"><span data-stu-id="9d89e-154">Deletes the specified credential in the specified database</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCredentialAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteCredentialAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters parameters = null, Nullable&lt;bool&gt; cascade = false, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteCredentialAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters parameters, valuetype System.Nullable`1&lt;bool&gt; cascade, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.DeleteCredentialAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteCredentialAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.DeleteCredentialAsync (operations, accountName, databaseName, credentialName, parameters, cascade, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;DeleteCredentialAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="credentialName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters" />
        <Parameter Name="cascade" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-155">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-155">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-156">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-156">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-157">Der Name der Datenbank, die die Anmeldeinformationen enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-157">The name of the database containing the credential.</span></span>
            </param>
        <param name="credentialName">
            <span data-ttu-id="9d89e-158">Der Name der Anmeldeinformationen löschen</span><span class="sxs-lookup"><span data-stu-id="9d89e-158">The name of the credential to delete</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9d89e-159">Die Parameter für Anmeldeinformationen zu löschen, wenn der aktuelle Benutzer nicht Besitzer des Kontos ist.</span><span class="sxs-lookup"><span data-stu-id="9d89e-159">The parameters to delete a credential if the current user is not the account owner.</span></span>
            </param>
        <param name="cascade">
            <span data-ttu-id="9d89e-160">Gibt an, ob der Löschvorgang einen Löschweitergabe werden sollen (Dadurch werden alle Ressourcen, die abhängig von den Anmeldeinformationen als auch die Anmeldeinformationen gelöscht) oder nicht.</span><span class="sxs-lookup"><span data-stu-id="9d89e-160">Indicates if the delete should be a cascading delete (which deletes all resources dependent on the credential as well as the credential) or not.</span></span> <span data-ttu-id="9d89e-161">Wenn "false" fehl, wenn alle Vertrauensstellungen der vertrauenden Seite zu den Anmeldeinformationen für Ressourcen vorhanden sind.</span><span class="sxs-lookup"><span data-stu-id="9d89e-161">If false will fail if there are any resources relying on the credential.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-162">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-163">Löscht die angegebene Anmeldeinformationen in der angegebenen Datenbank</span><span class="sxs-lookup"><span data-stu-id="9d89e-163">Deletes the specified credential in the specified database</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteSecret">
      <MemberSignature Language="C#" Value="public static void DeleteSecret (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteSecret(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.DeleteSecret(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteSecret (operations As ICatalogOperations, accountName As String, databaseName As String, secretName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteSecret : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.DeleteSecret (operations, accountName, databaseName, secretName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-164">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-164">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-165">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-165">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-166">Der Name der Datenbank, die den geheimen Schlüssel enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-166">The name of the database containing the secret.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="9d89e-167">Der Name des geheimen Schlüssels löschen</span><span class="sxs-lookup"><span data-stu-id="9d89e-167">The name of the secret to delete</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-168">Löscht den angegebenen Schlüssel in der angegebenen Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9d89e-168">Deletes the specified secret in the specified database.</span></span> <span data-ttu-id="9d89e-169">Dies ist veraltet und wird in der nächsten Version entfernt.</span><span class="sxs-lookup"><span data-stu-id="9d89e-169">This is deprecated and will be removed in the next release.</span></span> <span data-ttu-id="9d89e-170">Verwenden Sie stattdessen DeleteCredential.</span><span class="sxs-lookup"><span data-stu-id="9d89e-170">Please use DeleteCredential instead.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteSecretAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteSecretAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.DeleteSecretAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteSecretAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.DeleteSecretAsync (operations, accountName, databaseName, secretName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;DeleteSecretAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-171">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-171">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-172">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-172">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-173">Der Name der Datenbank, die den geheimen Schlüssel enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-173">The name of the database containing the secret.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="9d89e-174">Der Name des geheimen Schlüssels löschen</span><span class="sxs-lookup"><span data-stu-id="9d89e-174">The name of the secret to delete</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-175">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-175">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-176">Löscht den angegebenen Schlüssel in der angegebenen Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9d89e-176">Deletes the specified secret in the specified database.</span></span> <span data-ttu-id="9d89e-177">Dies ist veraltet und wird in der nächsten Version entfernt.</span><span class="sxs-lookup"><span data-stu-id="9d89e-177">This is deprecated and will be removed in the next release.</span></span> <span data-ttu-id="9d89e-178">Verwenden Sie stattdessen DeleteCredential.</span><span class="sxs-lookup"><span data-stu-id="9d89e-178">Please use DeleteCredential instead.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAssembly">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly GetAssembly (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string assemblyName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly GetAssembly(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string assemblyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetAssembly(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAssembly (operations As ICatalogOperations, accountName As String, databaseName As String, assemblyName As String) As USqlAssembly" />
      <MemberSignature Language="F#" Value="static member GetAssembly : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetAssembly (operations, accountName, databaseName, assemblyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="assemblyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-179">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-179">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-180">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-180">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-181">Der Name der Datenbank, die die Assembly enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-181">The name of the database containing the assembly.</span></span>
            </param>
        <param name="assemblyName">
            <span data-ttu-id="9d89e-182">Der Name der Assembly.</span><span class="sxs-lookup"><span data-stu-id="9d89e-182">The name of the assembly.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-183">Ruft die angegebene Assembly aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-183">Retrieves the specified assembly from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAssemblyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt; GetAssemblyAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string assemblyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt; GetAssemblyAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string assemblyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetAssemblyAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAssemblyAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetAssemblyAsync (operations, accountName, databaseName, assemblyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;GetAssemblyAsync&gt;d__61))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="assemblyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-184">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-184">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-185">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-185">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-186">Der Name der Datenbank, die die Assembly enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-186">The name of the database containing the assembly.</span></span>
            </param>
        <param name="assemblyName">
            <span data-ttu-id="9d89e-187">Der Name der Assembly.</span><span class="sxs-lookup"><span data-stu-id="9d89e-187">The name of the assembly.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-188">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-189">Ruft die angegebene Assembly aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-189">Retrieves the specified assembly from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCredential">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential GetCredential (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential GetCredential(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetCredential(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCredential (operations As ICatalogOperations, accountName As String, databaseName As String, credentialName As String) As USqlCredential" />
      <MemberSignature Language="F#" Value="static member GetCredential : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetCredential (operations, accountName, databaseName, credentialName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="credentialName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-190">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-190">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-191">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-191">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-192">Der Name der Datenbank, die das Schema enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-192">The name of the database containing the schema.</span></span>
            </param>
        <param name="credentialName">
            <span data-ttu-id="9d89e-193">Der Name der Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-193">The name of the credential.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-194">Ruft die angegebenen Anmeldeinformationen aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-194">Retrieves the specified credential from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCredentialAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt; GetCredentialAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt; GetCredentialAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetCredentialAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCredentialAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetCredentialAsync (operations, accountName, databaseName, credentialName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;GetCredentialAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="credentialName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-195">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-195">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-196">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-196">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-197">Der Name der Datenbank, die das Schema enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-197">The name of the database containing the schema.</span></span>
            </param>
        <param name="credentialName">
            <span data-ttu-id="9d89e-198">Der Name der Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-198">The name of the credential.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-199">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-200">Ruft die angegebenen Anmeldeinformationen aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-200">Retrieves the specified credential from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatabase">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase GetDatabase (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase GetDatabase(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetDatabase(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetDatabase (operations As ICatalogOperations, accountName As String, databaseName As String) As USqlDatabase" />
      <MemberSignature Language="F#" Value="static member GetDatabase : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetDatabase (operations, accountName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-201">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-201">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-202">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-202">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-203">Der Name der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9d89e-203">The name of the database.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-204">Ruft die angegebene Datenbank aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-204">Retrieves the specified database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatabaseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt; GetDatabaseAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt; GetDatabaseAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetDatabaseAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDatabaseAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetDatabaseAsync (operations, accountName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;GetDatabaseAsync&gt;d__77))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-205">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-205">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-206">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-206">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-207">Der Name der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9d89e-207">The name of the database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-208">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-208">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-209">Ruft die angegebene Datenbank aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-209">Retrieves the specified database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetExternalDataSource">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource GetExternalDataSource (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string externalDataSourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource GetExternalDataSource(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string externalDataSourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetExternalDataSource(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetExternalDataSource (operations As ICatalogOperations, accountName As String, databaseName As String, externalDataSourceName As String) As USqlExternalDataSource" />
      <MemberSignature Language="F#" Value="static member GetExternalDataSource : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetExternalDataSource (operations, accountName, databaseName, externalDataSourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="externalDataSourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-210">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-210">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-211">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-211">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-212">Der Name der Datenbank mit der externen Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="9d89e-212">The name of the database containing the external data source.</span></span>
            </param>
        <param name="externalDataSourceName">
            <span data-ttu-id="9d89e-213">Der Name der externen Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="9d89e-213">The name of the external data source.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-214">Ruft die angegebene externe Datenquelle aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-214">Retrieves the specified external data source from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetExternalDataSourceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt; GetExternalDataSourceAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string externalDataSourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt; GetExternalDataSourceAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string externalDataSourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetExternalDataSourceAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetExternalDataSourceAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetExternalDataSourceAsync (operations, accountName, databaseName, externalDataSourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;GetExternalDataSourceAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="externalDataSourceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-215">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-215">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-216">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-216">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-217">Der Name der Datenbank mit der externen Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="9d89e-217">The name of the database containing the external data source.</span></span>
            </param>
        <param name="externalDataSourceName">
            <span data-ttu-id="9d89e-218">Der Name der externen Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="9d89e-218">The name of the external data source.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-219">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-219">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-220">Ruft die angegebene externe Datenquelle aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-220">Retrieves the specified external data source from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPackage">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage GetPackage (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string packageName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage GetPackage(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string packageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetPackage(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetPackage (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, packageName As String) As USqlPackage" />
      <MemberSignature Language="F#" Value="static member GetPackage : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetPackage (operations, accountName, databaseName, schemaName, packageName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="packageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-221">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-221">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-222">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-222">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-223">Der Name der Datenbank, die das Paket enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-223">The name of the database containing the package.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-224">Der Name des Schemas, die das Paket enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-224">The name of the schema containing the package.</span></span>
            </param>
        <param name="packageName">
            <span data-ttu-id="9d89e-225">Der Name des Pakets.</span><span class="sxs-lookup"><span data-stu-id="9d89e-225">The name of the package.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-226">Ruft das angegebene Paket aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-226">Retrieves the specified package from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPackageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt; GetPackageAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string packageName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt; GetPackageAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string packageName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetPackageAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetPackageAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetPackageAsync (operations, accountName, databaseName, schemaName, packageName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;GetPackageAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="packageName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-227">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-227">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-228">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-228">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-229">Der Name der Datenbank, die das Paket enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-229">The name of the database containing the package.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-230">Der Name des Schemas, die das Paket enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-230">The name of the schema containing the package.</span></span>
            </param>
        <param name="packageName">
            <span data-ttu-id="9d89e-231">Der Name des Pakets.</span><span class="sxs-lookup"><span data-stu-id="9d89e-231">The name of the package.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-232">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-232">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-233">Ruft das angegebene Paket aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-233">Retrieves the specified package from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProcedure">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure GetProcedure (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string procedureName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure GetProcedure(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string procedureName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetProcedure(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetProcedure (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, procedureName As String) As USqlProcedure" />
      <MemberSignature Language="F#" Value="static member GetProcedure : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetProcedure (operations, accountName, databaseName, schemaName, procedureName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="procedureName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-234">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-234">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-235">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-235">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-236">Der Name der Datenbank, die die Prozedur enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-236">The name of the database containing the procedure.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-237">Der Name des Schemas, die die Prozedur enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-237">The name of the schema containing the procedure.</span></span>
            </param>
        <param name="procedureName">
            <span data-ttu-id="9d89e-238">Der Name der Prozedur.</span><span class="sxs-lookup"><span data-stu-id="9d89e-238">The name of the procedure.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-239">Ruft die angegebene Prozedur aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-239">Retrieves the specified procedure from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProcedureAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt; GetProcedureAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string procedureName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt; GetProcedureAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string procedureName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetProcedureAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetProcedureAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetProcedureAsync (operations, accountName, databaseName, schemaName, procedureName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;GetProcedureAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="procedureName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-240">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-240">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-241">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-241">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-242">Der Name der Datenbank, die die Prozedur enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-242">The name of the database containing the procedure.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-243">Der Name des Schemas, die die Prozedur enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-243">The name of the schema containing the procedure.</span></span>
            </param>
        <param name="procedureName">
            <span data-ttu-id="9d89e-244">Der Name der Prozedur.</span><span class="sxs-lookup"><span data-stu-id="9d89e-244">The name of the procedure.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-245">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-245">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-246">Ruft die angegebene Prozedur aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-246">Retrieves the specified procedure from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSchema">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema GetSchema (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema GetSchema(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetSchema(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetSchema (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String) As USqlSchema" />
      <MemberSignature Language="F#" Value="static member GetSchema : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetSchema (operations, accountName, databaseName, schemaName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-247">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-247">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-248">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-248">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-249">Der Name der Datenbank, die das Schema enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-249">The name of the database containing the schema.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-250">Der Name des Schemas.</span><span class="sxs-lookup"><span data-stu-id="9d89e-250">The name of the schema.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-251">Ruft das angegebene Schema aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-251">Retrieves the specified schema from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSchemaAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt; GetSchemaAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt; GetSchemaAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetSchemaAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSchemaAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetSchemaAsync (operations, accountName, databaseName, schemaName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;GetSchemaAsync&gt;d__65))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-252">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-252">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-253">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-253">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-254">Der Name der Datenbank, die das Schema enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-254">The name of the database containing the schema.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-255">Der Name des Schemas.</span><span class="sxs-lookup"><span data-stu-id="9d89e-255">The name of the schema.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-256">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-256">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-257">Ruft das angegebene Schema aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-257">Retrieves the specified schema from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecret">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret GetSecret (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret GetSecret(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetSecret(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetSecret (operations As ICatalogOperations, accountName As String, databaseName As String, secretName As String) As USqlSecret" />
      <MemberSignature Language="F#" Value="static member GetSecret : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetSecret (operations, accountName, databaseName, secretName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-258">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-258">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-259">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-259">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-260">Der Name der Datenbank, die den geheimen Schlüssel enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-260">The name of the database containing the secret.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="9d89e-261">Der Name des abzurufenden geheimen Schlüssels</span><span class="sxs-lookup"><span data-stu-id="9d89e-261">The name of the secret to get</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-262">Ruft den angegebenen Schlüssel in der angegebenen Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9d89e-262">Gets the specified secret in the specified database.</span></span> <span data-ttu-id="9d89e-263">Dies ist veraltet und wird in der nächsten Version entfernt.</span><span class="sxs-lookup"><span data-stu-id="9d89e-263">This is deprecated and will be removed in the next release.</span></span> <span data-ttu-id="9d89e-264">Verwenden Sie stattdessen von GetCredential.</span><span class="sxs-lookup"><span data-stu-id="9d89e-264">Please use GetCredential instead.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret&gt; GetSecretAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret&gt; GetSecretAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetSecretAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSecretAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetSecretAsync (operations, accountName, databaseName, secretName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;GetSecretAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-265">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-265">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-266">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-266">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-267">Der Name der Datenbank, die den geheimen Schlüssel enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-267">The name of the database containing the secret.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="9d89e-268">Der Name des abzurufenden geheimen Schlüssels</span><span class="sxs-lookup"><span data-stu-id="9d89e-268">The name of the secret to get</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-269">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-269">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-270">Ruft den angegebenen Schlüssel in der angegebenen Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9d89e-270">Gets the specified secret in the specified database.</span></span> <span data-ttu-id="9d89e-271">Dies ist veraltet und wird in der nächsten Version entfernt.</span><span class="sxs-lookup"><span data-stu-id="9d89e-271">This is deprecated and will be removed in the next release.</span></span> <span data-ttu-id="9d89e-272">Verwenden Sie stattdessen von GetCredential.</span><span class="sxs-lookup"><span data-stu-id="9d89e-272">Please use GetCredential instead.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTable">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable GetTable (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable GetTable(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTable(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTable (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, tableName As String) As USqlTable" />
      <MemberSignature Language="F#" Value="static member GetTable : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTable (operations, accountName, databaseName, schemaName, tableName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-273">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-273">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-274">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-274">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-275">Der Name der Datenbank, die die Tabelle enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-275">The name of the database containing the table.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-276">Der Name des Schemas, die die Tabelle enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-276">The name of the schema containing the table.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="9d89e-277">Der Name der Tabelle.</span><span class="sxs-lookup"><span data-stu-id="9d89e-277">The name of the table.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-278">Ruft die angegebene Tabelle aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-278">Retrieves the specified table from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; GetTableAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; GetTableAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTableAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTableAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTableAsync (operations, accountName, databaseName, schemaName, tableName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;GetTableAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-279">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-279">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-280">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-280">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-281">Der Name der Datenbank, die die Tabelle enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-281">The name of the database containing the table.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-282">Der Name des Schemas, die die Tabelle enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-282">The name of the schema containing the table.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="9d89e-283">Der Name der Tabelle.</span><span class="sxs-lookup"><span data-stu-id="9d89e-283">The name of the table.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-284">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-284">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-285">Ruft die angegebene Tabelle aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-285">Retrieves the specified table from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTablePartition">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition GetTablePartition (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, string partitionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition GetTablePartition(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, string partitionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTablePartition(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTablePartition (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, tableName As String, partitionName As String) As USqlTablePartition" />
      <MemberSignature Language="F#" Value="static member GetTablePartition : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTablePartition (operations, accountName, databaseName, schemaName, tableName, partitionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="partitionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-286">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-286">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-287">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-287">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-288">Der Name der Datenbank, die die Partition enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-288">The name of the database containing the partition.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-289">Der Name des Schemas, die die Partition enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-289">The name of the schema containing the partition.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="9d89e-290">Der Name der Tabelle, die die Partition enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-290">The name of the table containing the partition.</span></span>
            </param>
        <param name="partitionName">
            <span data-ttu-id="9d89e-291">Der Name der Tabellenpartition.</span><span class="sxs-lookup"><span data-stu-id="9d89e-291">The name of the table partition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-292">Ruft die angegebene Tabellenpartition aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-292">Retrieves the specified table partition from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTablePartitionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt; GetTablePartitionAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, string partitionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt; GetTablePartitionAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, string partitionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTablePartitionAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTablePartitionAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTablePartitionAsync (operations, accountName, databaseName, schemaName, tableName, partitionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;GetTablePartitionAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="partitionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-293">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-293">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-294">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-294">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-295">Der Name der Datenbank, die die Partition enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-295">The name of the database containing the partition.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-296">Der Name des Schemas, die die Partition enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-296">The name of the schema containing the partition.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="9d89e-297">Der Name der Tabelle, die die Partition enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-297">The name of the table containing the partition.</span></span>
            </param>
        <param name="partitionName">
            <span data-ttu-id="9d89e-298">Der Name der Tabellenpartition.</span><span class="sxs-lookup"><span data-stu-id="9d89e-298">The name of the table partition.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-299">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-299">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-300">Ruft die angegebene Tabellenpartition aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-300">Retrieves the specified table partition from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTableStatistic">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics GetTableStatistic (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, string statisticsName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics GetTableStatistic(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, string statisticsName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTableStatistic(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTableStatistic (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, tableName As String, statisticsName As String) As USqlTableStatistics" />
      <MemberSignature Language="F#" Value="static member GetTableStatistic : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTableStatistic (operations, accountName, databaseName, schemaName, tableName, statisticsName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="statisticsName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-301">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-301">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-302">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-302">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-303">Der Name der Datenbank, die die Statistik enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-303">The name of the database containing the statistics.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-304">Der Name des Schemas, das Statistiken enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-304">The name of the schema containing the statistics.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="9d89e-305">Der Name der Tabelle, die die Statistik enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-305">The name of the table containing the statistics.</span></span>
            </param>
        <param name="statisticsName">
            <span data-ttu-id="9d89e-306">Der Name der Tabellenstatistiken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-306">The name of the table statistics.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-307">Ruft die Statistiken für die angegebene Tabelle aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-307">Retrieves the specified table statistics from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTableStatisticAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; GetTableStatisticAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, string statisticsName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; GetTableStatisticAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, string statisticsName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTableStatisticAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTableStatisticAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTableStatisticAsync (operations, accountName, databaseName, schemaName, tableName, statisticsName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;GetTableStatisticAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="statisticsName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-308">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-308">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-309">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-309">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-310">Der Name der Datenbank, die die Statistik enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-310">The name of the database containing the statistics.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-311">Der Name des Schemas, das Statistiken enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-311">The name of the schema containing the statistics.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="9d89e-312">Der Name der Tabelle, die die Statistik enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-312">The name of the table containing the statistics.</span></span>
            </param>
        <param name="statisticsName">
            <span data-ttu-id="9d89e-313">Der Name der Tabellenstatistiken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-313">The name of the table statistics.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-314">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-314">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-315">Ruft die Statistiken für die angegebene Tabelle aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-315">Retrieves the specified table statistics from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTableType">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType GetTableType (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType GetTableType(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTableType(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTableType (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, tableTypeName As String) As USqlTableType" />
      <MemberSignature Language="F#" Value="static member GetTableType : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTableType (operations, accountName, databaseName, schemaName, tableTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-316">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-316">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-317">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-317">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-318">Der Name der Datenbank mit den Tabellentyp.</span><span class="sxs-lookup"><span data-stu-id="9d89e-318">The name of the database containing the table type.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-319">Der Name des Schemas, die den "Table" enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-319">The name of the schema containing the table type.</span></span>
            </param>
        <param name="tableTypeName">
            <span data-ttu-id="9d89e-320">Der Name des Tabellentyps abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="9d89e-320">The name of the table type to retrieve.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-321">Ruft den angegebenen Tabellentyp aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-321">Retrieves the specified table type from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTableTypeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt; GetTableTypeAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableTypeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt; GetTableTypeAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTableTypeAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTableTypeAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTableTypeAsync (operations, accountName, databaseName, schemaName, tableTypeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;GetTableTypeAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-322">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-322">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-323">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-323">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-324">Der Name der Datenbank mit den Tabellentyp.</span><span class="sxs-lookup"><span data-stu-id="9d89e-324">The name of the database containing the table type.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-325">Der Name des Schemas, die den "Table" enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-325">The name of the schema containing the table type.</span></span>
            </param>
        <param name="tableTypeName">
            <span data-ttu-id="9d89e-326">Der Name des Tabellentyps abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="9d89e-326">The name of the table type to retrieve.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-327">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-327">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-328">Ruft den angegebenen Tabellentyp aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-328">Retrieves the specified table type from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTableValuedFunction">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction GetTableValuedFunction (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableValuedFunctionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction GetTableValuedFunction(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableValuedFunctionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTableValuedFunction(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTableValuedFunction (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, tableValuedFunctionName As String) As USqlTableValuedFunction" />
      <MemberSignature Language="F#" Value="static member GetTableValuedFunction : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTableValuedFunction (operations, accountName, databaseName, schemaName, tableValuedFunctionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableValuedFunctionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-329">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-329">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-330">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-330">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-331">Der Name der Datenbank, die die Tabellenwertfunktion enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-331">The name of the database containing the table valued function.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-332">Der Name des Schemas, die die Tabellenwertfunktion enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-332">The name of the schema containing the table valued function.</span></span>
            </param>
        <param name="tableValuedFunctionName">
            <span data-ttu-id="9d89e-333">Der Name der tablevaluedfunction.</span><span class="sxs-lookup"><span data-stu-id="9d89e-333">The name of the tableValuedFunction.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-334">Ruft die angegebene Tabellenwertfunktion aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-334">Retrieves the specified table valued function from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTableValuedFunctionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; GetTableValuedFunctionAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableValuedFunctionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; GetTableValuedFunctionAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableValuedFunctionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTableValuedFunctionAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTableValuedFunctionAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTableValuedFunctionAsync (operations, accountName, databaseName, schemaName, tableValuedFunctionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;GetTableValuedFunctionAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableValuedFunctionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-335">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-335">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-336">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-336">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-337">Der Name der Datenbank, die die Tabellenwertfunktion enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-337">The name of the database containing the table valued function.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-338">Der Name des Schemas, die die Tabellenwertfunktion enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-338">The name of the schema containing the table valued function.</span></span>
            </param>
        <param name="tableValuedFunctionName">
            <span data-ttu-id="9d89e-339">Der Name der tablevaluedfunction.</span><span class="sxs-lookup"><span data-stu-id="9d89e-339">The name of the tableValuedFunction.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-340">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-340">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-341">Ruft die angegebene Tabellenwertfunktion aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-341">Retrieves the specified table valued function from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetView">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView GetView (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string viewName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView GetView(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string viewName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetView(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetView (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, viewName As String) As USqlView" />
      <MemberSignature Language="F#" Value="static member GetView : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetView (operations, accountName, databaseName, schemaName, viewName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="viewName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-342">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-342">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-343">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-343">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-344">Der Name der Datenbank, die die Sicht enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-344">The name of the database containing the view.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-345">Der Name des Schemas, die die Sicht enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-345">The name of the schema containing the view.</span></span>
            </param>
        <param name="viewName">
            <span data-ttu-id="9d89e-346">Der Name der Sicht.</span><span class="sxs-lookup"><span data-stu-id="9d89e-346">The name of the view.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-347">Ruft die angegebene Ansicht aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-347">Retrieves the specified view from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetViewAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; GetViewAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string viewName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; GetViewAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string viewName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetViewAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetViewAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetViewAsync (operations, accountName, databaseName, schemaName, viewName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;GetViewAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="viewName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-348">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-348">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-349">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-349">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-350">Der Name der Datenbank, die die Sicht enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-350">The name of the database containing the view.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-351">Der Name des Schemas, die die Sicht enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-351">The name of the schema containing the view.</span></span>
            </param>
        <param name="viewName">
            <span data-ttu-id="9d89e-352">Der Name der Sicht.</span><span class="sxs-lookup"><span data-stu-id="9d89e-352">The name of the view.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-353">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-353">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-354">Ruft die angegebene Ansicht aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-354">Retrieves the specified view from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAssemblies">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt; ListAssemblies (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt; ListAssemblies(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListAssemblies(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAssemblies (operations As ICatalogOperations, accountName As String, databaseName As String, Optional odataQuery As ODataQuery(Of USqlAssembly) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlAssemblyClr)" />
      <MemberSignature Language="F#" Value="static member ListAssemblies : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListAssemblies (operations, accountName, databaseName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-355">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-355">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-356">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-356">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-357">Der Name der Datenbank, die die Assembly enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-357">The name of the database containing the assembly.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-358">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-358">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-359">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-359">OData Select statement.</span></span> <span data-ttu-id="9d89e-360">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-360">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-361">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-361">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-362">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-362">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-363">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-363">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-364">Ruft die Liste der Assemblys aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-364">Retrieves the list of assemblies from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAssembliesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;&gt; ListAssembliesAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;&gt; ListAssembliesAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListAssembliesAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAssembliesAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListAssembliesAsync (operations, accountName, databaseName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListAssembliesAsync&gt;d__63))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-365">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-365">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-366">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-366">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-367">Der Name der Datenbank, die die Assembly enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-367">The name of the database containing the assembly.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-368">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-368">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-369">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-369">OData Select statement.</span></span> <span data-ttu-id="9d89e-370">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-370">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-371">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-371">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-372">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-372">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-373">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-373">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-374">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-374">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-375">Ruft die Liste der Assemblys aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-375">Retrieves the list of assemblies from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAssembliesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt; ListAssembliesNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt; ListAssembliesNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListAssembliesNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAssembliesNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlAssemblyClr)" />
      <MemberSignature Language="F#" Value="static member ListAssembliesNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListAssembliesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-376">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-376">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-377">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-377">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-378">Ruft die Liste der Assemblys aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-378">Retrieves the list of assemblies from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAssembliesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;&gt; ListAssembliesNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;&gt; ListAssembliesNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListAssembliesNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAssembliesNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListAssembliesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListAssembliesNextAsync&gt;d__105))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-379">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-379">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-380">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-380">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-381">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-381">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-382">Ruft die Liste der Assemblys aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-382">Retrieves the list of assemblies from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCredentials">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt; ListCredentials (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt; ListCredentials(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListCredentials(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListCredentials (operations As ICatalogOperations, accountName As String, databaseName As String, Optional odataQuery As ODataQuery(Of USqlCredential) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlCredential)" />
      <MemberSignature Language="F#" Value="static member ListCredentials : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListCredentials (operations, accountName, databaseName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-383">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-383">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-384">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-384">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-385">Der Name der Datenbank, die das Schema enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-385">The name of the database containing the schema.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-386">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-386">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-387">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-387">OData Select statement.</span></span> <span data-ttu-id="9d89e-388">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-388">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-389">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-389">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-390">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-390">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-391">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-391">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-392">Die Liste der Anmeldeinformationen aus dem Data Lake Analytics-Katalog abgerufen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-392">Retrieves the list of credentials from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCredentialsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;&gt; ListCredentialsAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;&gt; ListCredentialsAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListCredentialsAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListCredentialsAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListCredentialsAsync (operations, accountName, databaseName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListCredentialsAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-393">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-393">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-394">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-394">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-395">Der Name der Datenbank, die das Schema enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-395">The name of the database containing the schema.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-396">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-396">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-397">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-397">OData Select statement.</span></span> <span data-ttu-id="9d89e-398">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-398">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-399">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-399">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-400">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-400">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-401">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-401">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-402">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-402">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-403">Die Liste der Anmeldeinformationen aus dem Data Lake Analytics-Katalog abgerufen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-403">Retrieves the list of credentials from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCredentialsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt; ListCredentialsNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt; ListCredentialsNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListCredentialsNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListCredentialsNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlCredential)" />
      <MemberSignature Language="F#" Value="static member ListCredentialsNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListCredentialsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-404">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-404">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-405">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-405">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-406">Die Liste der Anmeldeinformationen aus dem Data Lake Analytics-Katalog abgerufen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-406">Retrieves the list of credentials from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCredentialsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;&gt; ListCredentialsNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;&gt; ListCredentialsNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListCredentialsNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListCredentialsNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListCredentialsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListCredentialsNextAsync&gt;d__81))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-407">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-407">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-408">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-408">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-409">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-409">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-410">Die Liste der Anmeldeinformationen aus dem Data Lake Analytics-Katalog abgerufen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-410">Retrieves the list of credentials from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDatabases">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt; ListDatabases (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt; ListDatabases(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListDatabases(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListDatabases (operations As ICatalogOperations, accountName As String, Optional odataQuery As ODataQuery(Of USqlDatabase) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlDatabase)" />
      <MemberSignature Language="F#" Value="static member ListDatabases : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListDatabases (operations, accountName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-411">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-411">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-412">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-412">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-413">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-413">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-414">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-414">OData Select statement.</span></span> <span data-ttu-id="9d89e-415">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-415">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-416">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-416">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-417">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-417">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-418">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-418">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-419">Ruft die Liste der Datenbanken des Data Lake Analytics-Katalogs ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-419">Retrieves the list of databases from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDatabasesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;&gt; ListDatabasesAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;&gt; ListDatabasesAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListDatabasesAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListDatabasesAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListDatabasesAsync (operations, accountName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListDatabasesAsync&gt;d__79))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-420">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-420">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-421">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-421">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-422">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-422">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-423">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-423">OData Select statement.</span></span> <span data-ttu-id="9d89e-424">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-424">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-425">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-425">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-426">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-426">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-427">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-427">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-428">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-428">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-429">Ruft die Liste der Datenbanken des Data Lake Analytics-Katalogs ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-429">Retrieves the list of databases from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDatabasesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt; ListDatabasesNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt; ListDatabasesNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListDatabasesNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListDatabasesNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlDatabase)" />
      <MemberSignature Language="F#" Value="static member ListDatabasesNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListDatabasesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-430">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-430">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-431">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-431">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-432">Ruft die Liste der Datenbanken des Data Lake Analytics-Katalogs ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-432">Retrieves the list of databases from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDatabasesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;&gt; ListDatabasesNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;&gt; ListDatabasesNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListDatabasesNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListDatabasesNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListDatabasesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListDatabasesNextAsync&gt;d__117))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-433">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-433">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-434">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-434">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-435">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-435">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-436">Ruft die Liste der Datenbanken des Data Lake Analytics-Katalogs ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-436">Retrieves the list of databases from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListExternalDataSources">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt; ListExternalDataSources (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt; ListExternalDataSources(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListExternalDataSources(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListExternalDataSources (operations As ICatalogOperations, accountName As String, databaseName As String, Optional odataQuery As ODataQuery(Of USqlExternalDataSource) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlExternalDataSource)" />
      <MemberSignature Language="F#" Value="static member ListExternalDataSources : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListExternalDataSources (operations, accountName, databaseName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-437">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-437">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-438">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-438">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-439">Der Name der Datenbank mit den externen Datenquellen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-439">The name of the database containing the external data sources.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-440">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-440">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-441">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-441">OData Select statement.</span></span> <span data-ttu-id="9d89e-442">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-442">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-443">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-443">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-444">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-444">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-445">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-445">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-446">Die Liste der externen Datenquellen aus dem Data Lake Analytics-Katalog abgerufen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-446">Retrieves the list of external data sources from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListExternalDataSourcesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;&gt; ListExternalDataSourcesAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;&gt; ListExternalDataSourcesAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListExternalDataSourcesAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListExternalDataSourcesAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListExternalDataSourcesAsync (operations, accountName, databaseName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListExternalDataSourcesAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-447">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-447">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-448">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-448">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-449">Der Name der Datenbank mit den externen Datenquellen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-449">The name of the database containing the external data sources.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-450">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-450">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-451">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-451">OData Select statement.</span></span> <span data-ttu-id="9d89e-452">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-452">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-453">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-453">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-454">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-454">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-455">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-455">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-456">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-456">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-457">Die Liste der externen Datenquellen aus dem Data Lake Analytics-Katalog abgerufen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-457">Retrieves the list of external data sources from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListExternalDataSourcesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt; ListExternalDataSourcesNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt; ListExternalDataSourcesNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListExternalDataSourcesNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListExternalDataSourcesNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlExternalDataSource)" />
      <MemberSignature Language="F#" Value="static member ListExternalDataSourcesNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListExternalDataSourcesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-458">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-458">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-459">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-459">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-460">Die Liste der externen Datenquellen aus dem Data Lake Analytics-Katalog abgerufen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-460">Retrieves the list of external data sources from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListExternalDataSourcesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;&gt; ListExternalDataSourcesNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;&gt; ListExternalDataSourcesNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListExternalDataSourcesNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListExternalDataSourcesNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListExternalDataSourcesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListExternalDataSourcesNextAsync&gt;d__83))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-461">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-461">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-462">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-462">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-463">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-463">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-464">Die Liste der externen Datenquellen aus dem Data Lake Analytics-Katalog abgerufen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-464">Retrieves the list of external data sources from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPackages">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt; ListPackages (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt; ListPackages(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListPackages(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListPackages (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, Optional odataQuery As ODataQuery(Of USqlPackage) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlPackage)" />
      <MemberSignature Language="F#" Value="static member ListPackages : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListPackages (operations, accountName, databaseName, schemaName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-465">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-465">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-466">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-466">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-467">Der Name der Datenbank, die die Pakete enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-467">The name of the database containing the packages.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-468">Der Name des Schemas, die Pakete enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-468">The name of the schema containing the packages.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-469">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-469">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-470">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-470">OData Select statement.</span></span> <span data-ttu-id="9d89e-471">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-471">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-472">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-472">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-473">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-473">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-474">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-474">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-475">Ruft die Liste der Pakete aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-475">Retrieves the list of packages from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPackagesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;&gt; ListPackagesAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;&gt; ListPackagesAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListPackagesAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListPackagesAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListPackagesAsync (operations, accountName, databaseName, schemaName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListPackagesAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-476">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-476">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-477">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-477">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-478">Der Name der Datenbank, die die Pakete enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-478">The name of the database containing the packages.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-479">Der Name des Schemas, die Pakete enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-479">The name of the schema containing the packages.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-480">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-480">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-481">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-481">OData Select statement.</span></span> <span data-ttu-id="9d89e-482">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-482">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-483">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-483">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-484">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-484">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-485">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-485">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-486">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-486">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-487">Ruft die Liste der Pakete aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-487">Retrieves the list of packages from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPackagesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt; ListPackagesNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt; ListPackagesNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListPackagesNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListPackagesNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlPackage)" />
      <MemberSignature Language="F#" Value="static member ListPackagesNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListPackagesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-488">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-488">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-489">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-489">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-490">Ruft die Liste der Pakete aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-490">Retrieves the list of packages from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPackagesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;&gt; ListPackagesNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;&gt; ListPackagesNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListPackagesNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListPackagesNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListPackagesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListPackagesNextAsync&gt;d__93))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-491">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-491">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-492">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-492">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-493">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-493">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-494">Ruft die Liste der Pakete aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-494">Retrieves the list of packages from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListProcedures">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt; ListProcedures (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt; ListProcedures(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListProcedures(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListProcedures (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, Optional odataQuery As ODataQuery(Of USqlProcedure) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlProcedure)" />
      <MemberSignature Language="F#" Value="static member ListProcedures : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListProcedures (operations, accountName, databaseName, schemaName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-495">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-495">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-496">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-496">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-497">Der Name der Datenbank mit den Verfahren.</span><span class="sxs-lookup"><span data-stu-id="9d89e-497">The name of the database containing the procedures.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-498">Der Name des Schemas, die Prozeduren enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-498">The name of the schema containing the procedures.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-499">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-499">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-500">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-500">OData Select statement.</span></span> <span data-ttu-id="9d89e-501">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-501">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-502">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-502">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-503">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-503">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-504">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-504">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-505">Ruft die Liste der Verfahren aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-505">Retrieves the list of procedures from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListProceduresAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;&gt; ListProceduresAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;&gt; ListProceduresAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListProceduresAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListProceduresAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListProceduresAsync (operations, accountName, databaseName, schemaName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListProceduresAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-506">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-506">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-507">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-507">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-508">Der Name der Datenbank mit den Verfahren.</span><span class="sxs-lookup"><span data-stu-id="9d89e-508">The name of the database containing the procedures.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-509">Der Name des Schemas, die Prozeduren enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-509">The name of the schema containing the procedures.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-510">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-510">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-511">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-511">OData Select statement.</span></span> <span data-ttu-id="9d89e-512">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-512">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-513">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-513">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-514">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-514">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-515">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-515">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-516">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-516">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-517">Ruft die Liste der Verfahren aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-517">Retrieves the list of procedures from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListProceduresNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt; ListProceduresNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt; ListProceduresNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListProceduresNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListProceduresNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlProcedure)" />
      <MemberSignature Language="F#" Value="static member ListProceduresNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListProceduresNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-518">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-518">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-519">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-519">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-520">Ruft die Liste der Verfahren aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-520">Retrieves the list of procedures from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListProceduresNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;&gt; ListProceduresNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;&gt; ListProceduresNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListProceduresNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListProceduresNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListProceduresNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListProceduresNextAsync&gt;d__85))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-521">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-521">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-522">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-522">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-523">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-523">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-524">Ruft die Liste der Verfahren aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-524">Retrieves the list of procedures from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSchemas">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt; ListSchemas (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt; ListSchemas(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListSchemas(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListSchemas (operations As ICatalogOperations, accountName As String, databaseName As String, Optional odataQuery As ODataQuery(Of USqlSchema) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlSchema)" />
      <MemberSignature Language="F#" Value="static member ListSchemas : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListSchemas (operations, accountName, databaseName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-525">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-525">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-526">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-526">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-527">Der Name der Datenbank, die das Schema enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-527">The name of the database containing the schema.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-528">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-528">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-529">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-529">OData Select statement.</span></span> <span data-ttu-id="9d89e-530">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-530">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-531">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-531">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-532">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-532">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-533">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-533">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-534">Ruft die Liste der Schemas aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-534">Retrieves the list of schemas from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSchemasAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;&gt; ListSchemasAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;&gt; ListSchemasAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListSchemasAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSchemasAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListSchemasAsync (operations, accountName, databaseName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListSchemasAsync&gt;d__67))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-535">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-535">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-536">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-536">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-537">Der Name der Datenbank, die das Schema enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-537">The name of the database containing the schema.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-538">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-538">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-539">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-539">OData Select statement.</span></span> <span data-ttu-id="9d89e-540">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-540">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-541">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-541">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-542">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-542">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-543">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-543">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-544">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-544">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-545">Ruft die Liste der Schemas aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-545">Retrieves the list of schemas from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSchemasNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt; ListSchemasNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt; ListSchemasNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListSchemasNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListSchemasNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlSchema)" />
      <MemberSignature Language="F#" Value="static member ListSchemasNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListSchemasNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-546">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-546">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-547">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-547">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-548">Ruft die Liste der Schemas aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-548">Retrieves the list of schemas from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSchemasNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;&gt; ListSchemasNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;&gt; ListSchemasNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListSchemasNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSchemasNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListSchemasNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListSchemasNextAsync&gt;d__107))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-549">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-549">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-550">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-550">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-551">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-551">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-552">Ruft die Liste der Schemas aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-552">Retrieves the list of schemas from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablePartitions">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt; ListTablePartitions (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt; ListTablePartitions(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablePartitions(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTablePartitions (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, tableName As String, Optional odataQuery As ODataQuery(Of USqlTablePartition) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlTablePartition)" />
      <MemberSignature Language="F#" Value="static member ListTablePartitions : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablePartitions (operations, accountName, databaseName, schemaName, tableName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-553">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-553">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-554">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-554">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-555">Der Name der Datenbank, die die Partitionen enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-555">The name of the database containing the partitions.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-556">Der Name des Schemas, das die Partitionen enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-556">The name of the schema containing the partitions.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="9d89e-557">Der Name der Tabelle, die die Partitionen enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-557">The name of the table containing the partitions.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-558">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-558">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-559">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-559">OData Select statement.</span></span> <span data-ttu-id="9d89e-560">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-560">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-561">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-561">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-562">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-562">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-563">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-563">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-564">Die Liste der Tabellenpartitionen aus dem Data Lake Analytics-Katalog abgerufen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-564">Retrieves the list of table partitions from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablePartitionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;&gt; ListTablePartitionsAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;&gt; ListTablePartitionsAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablePartitionsAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTablePartitionsAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablePartitionsAsync (operations, accountName, databaseName, schemaName, tableName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTablePartitionsAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-565">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-565">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-566">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-566">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-567">Der Name der Datenbank, die die Partitionen enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-567">The name of the database containing the partitions.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-568">Der Name des Schemas, das die Partitionen enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-568">The name of the schema containing the partitions.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="9d89e-569">Der Name der Tabelle, die die Partitionen enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-569">The name of the table containing the partitions.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-570">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-570">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-571">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-571">OData Select statement.</span></span> <span data-ttu-id="9d89e-572">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-572">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-573">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-573">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-574">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-574">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-575">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-575">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-576">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-576">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-577">Die Liste der Tabellenpartitionen aus dem Data Lake Analytics-Katalog abgerufen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-577">Retrieves the list of table partitions from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablePartitionsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt; ListTablePartitionsNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt; ListTablePartitionsNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablePartitionsNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTablePartitionsNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlTablePartition)" />
      <MemberSignature Language="F#" Value="static member ListTablePartitionsNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablePartitionsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-578">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-578">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-579">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-579">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-580">Die Liste der Tabellenpartitionen aus dem Data Lake Analytics-Katalog abgerufen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-580">Retrieves the list of table partitions from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablePartitionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;&gt; ListTablePartitionsNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;&gt; ListTablePartitionsNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablePartitionsNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTablePartitionsNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablePartitionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTablePartitionsNextAsync&gt;d__99))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-581">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-581">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-582">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-582">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-583">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-583">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-584">Die Liste der Tabellenpartitionen aus dem Data Lake Analytics-Katalog abgerufen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-584">Retrieves the list of table partitions from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTables">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; ListTables (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, Nullable&lt;bool&gt; basic = false);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; ListTables(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Nullable`1&lt;bool&gt; basic) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTables(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable},System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTables (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, Optional odataQuery As ODataQuery(Of USqlTable) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null, Optional basic As Nullable(Of Boolean) = false) As IPage(Of USqlTable)" />
      <MemberSignature Language="F#" Value="static member ListTables : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTables (operations, accountName, databaseName, schemaName, odataQuery, select, count, basic)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="basic" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-585">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-585">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-586">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-586">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-587">Der Name der Datenbank, die die Tabellen enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-587">The name of the database containing the tables.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-588">Der Name des Schemas mit den Tabellen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-588">The name of the schema containing the tables.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-589">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-589">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-590">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-590">OData Select statement.</span></span> <span data-ttu-id="9d89e-591">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-591">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-592">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-592">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-593">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-593">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-594">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-594">Optional.</span></span>
            </param>
        <param name="basic">
            <span data-ttu-id="9d89e-595">Die grundlegende Option gibt an, welche Ebene der Informationen, die beim Auflisten von Tabellen zurückgegeben wird.</span><span class="sxs-lookup"><span data-stu-id="9d89e-595">The basic switch indicates what level of information to return when listing tables.</span></span> <span data-ttu-id="9d89e-596">Wenn die Standardauthentifizierung ist "true" werden nur Database_name, Schema_name, Table_name und Version für jede Tabelle andernfalls alle Tabellenmetadaten wird zurückgegeben, zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="9d89e-596">When basic is true, only database_name, schema_name, table_name and version are returned for each table, otherwise all table metadata is returned.</span></span> <span data-ttu-id="9d89e-597">Standardmäßig ist es "false".</span><span class="sxs-lookup"><span data-stu-id="9d89e-597">By default, it is false.</span></span> <span data-ttu-id="9d89e-598">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-598">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-599">Ruft die Liste der Tabellen aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-599">Retrieves the list of tables from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt; ListTablesAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, Nullable&lt;bool&gt; basic = false, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt; ListTablesAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Nullable`1&lt;bool&gt; basic, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablesAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable},System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTablesAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablesAsync (operations, accountName, databaseName, schemaName, odataQuery, select, count, basic, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTablesAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="basic" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-600">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-600">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-601">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-601">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-602">Der Name der Datenbank, die die Tabellen enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-602">The name of the database containing the tables.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-603">Der Name des Schemas mit den Tabellen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-603">The name of the schema containing the tables.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-604">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-604">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-605">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-605">OData Select statement.</span></span> <span data-ttu-id="9d89e-606">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-606">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-607">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-607">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-608">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-608">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-609">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-609">Optional.</span></span>
            </param>
        <param name="basic">
            <span data-ttu-id="9d89e-610">Die grundlegende Option gibt an, welche Ebene der Informationen, die beim Auflisten von Tabellen zurückgegeben wird.</span><span class="sxs-lookup"><span data-stu-id="9d89e-610">The basic switch indicates what level of information to return when listing tables.</span></span> <span data-ttu-id="9d89e-611">Wenn die Standardauthentifizierung ist "true" werden nur Database_name, Schema_name, Table_name und Version für jede Tabelle andernfalls alle Tabellenmetadaten wird zurückgegeben, zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="9d89e-611">When basic is true, only database_name, schema_name, table_name and version are returned for each table, otherwise all table metadata is returned.</span></span> <span data-ttu-id="9d89e-612">Standardmäßig ist es "false".</span><span class="sxs-lookup"><span data-stu-id="9d89e-612">By default, it is false.</span></span> <span data-ttu-id="9d89e-613">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-613">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-614">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-614">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-615">Ruft die Liste der Tabellen aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-615">Retrieves the list of tables from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesByDatabase">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; ListTablesByDatabase (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, Nullable&lt;bool&gt; basic = false);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; ListTablesByDatabase(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Nullable`1&lt;bool&gt; basic) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablesByDatabase(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable},System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTablesByDatabase (operations As ICatalogOperations, accountName As String, databaseName As String, Optional odataQuery As ODataQuery(Of USqlTable) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null, Optional basic As Nullable(Of Boolean) = false) As IPage(Of USqlTable)" />
      <MemberSignature Language="F#" Value="static member ListTablesByDatabase : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablesByDatabase (operations, accountName, databaseName, odataQuery, select, count, basic)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="basic" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-616">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-616">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-617">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-617">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-618">Der Name der Datenbank, die die Tabellen enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-618">The name of the database containing the tables.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-619">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-619">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-620">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-620">OData Select statement.</span></span> <span data-ttu-id="9d89e-621">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-621">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-622">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-622">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-623">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-623">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-624">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-624">Optional.</span></span>
            </param>
        <param name="basic">
            <span data-ttu-id="9d89e-625">Die grundlegende Option gibt an, welche Ebene der Informationen, die beim Auflisten von Tabellen zurückgegeben wird.</span><span class="sxs-lookup"><span data-stu-id="9d89e-625">The basic switch indicates what level of information to return when listing tables.</span></span> <span data-ttu-id="9d89e-626">Wenn die Standardauthentifizierung ist "true" werden nur Database_name, Schema_name, Table_name und Version für jede Tabelle andernfalls alle Tabellenmetadaten wird zurückgegeben, zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="9d89e-626">When basic is true, only database_name, schema_name, table_name and version are returned for each table, otherwise all table metadata is returned.</span></span> <span data-ttu-id="9d89e-627">Standardmäßig ist es "false"</span><span class="sxs-lookup"><span data-stu-id="9d89e-627">By default, it is false</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-628">Ruft die Liste aller Tabellen in einer Datenbank aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-628">Retrieves the list of all tables in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesByDatabaseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt; ListTablesByDatabaseAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, Nullable&lt;bool&gt; basic = false, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt; ListTablesByDatabaseAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Nullable`1&lt;bool&gt; basic, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablesByDatabaseAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable},System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTablesByDatabaseAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablesByDatabaseAsync (operations, accountName, databaseName, odataQuery, select, count, basic, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTablesByDatabaseAsync&gt;d__71))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="basic" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-629">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-629">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-630">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-630">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-631">Der Name der Datenbank, die die Tabellen enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-631">The name of the database containing the tables.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-632">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-632">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-633">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-633">OData Select statement.</span></span> <span data-ttu-id="9d89e-634">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-634">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-635">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-635">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-636">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-636">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-637">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-637">Optional.</span></span>
            </param>
        <param name="basic">
            <span data-ttu-id="9d89e-638">Die grundlegende Option gibt an, welche Ebene der Informationen, die beim Auflisten von Tabellen zurückgegeben wird.</span><span class="sxs-lookup"><span data-stu-id="9d89e-638">The basic switch indicates what level of information to return when listing tables.</span></span> <span data-ttu-id="9d89e-639">Wenn die Standardauthentifizierung ist "true" werden nur Database_name, Schema_name, Table_name und Version für jede Tabelle andernfalls alle Tabellenmetadaten wird zurückgegeben, zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="9d89e-639">When basic is true, only database_name, schema_name, table_name and version are returned for each table, otherwise all table metadata is returned.</span></span> <span data-ttu-id="9d89e-640">Standardmäßig ist es "false"</span><span class="sxs-lookup"><span data-stu-id="9d89e-640">By default, it is false</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-641">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-641">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-642">Ruft die Liste aller Tabellen in einer Datenbank aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-642">Retrieves the list of all tables in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesByDatabaseNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; ListTablesByDatabaseNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; ListTablesByDatabaseNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablesByDatabaseNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTablesByDatabaseNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlTable)" />
      <MemberSignature Language="F#" Value="static member ListTablesByDatabaseNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablesByDatabaseNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-643">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-643">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-644">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-644">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-645">Ruft die Liste aller Tabellen in einer Datenbank aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-645">Retrieves the list of all tables in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesByDatabaseNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt; ListTablesByDatabaseNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt; ListTablesByDatabaseNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablesByDatabaseNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTablesByDatabaseNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablesByDatabaseNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTablesByDatabaseNextAsync&gt;d__111))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-646">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-646">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-647">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-647">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-648">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-648">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-649">Ruft die Liste aller Tabellen in einer Datenbank aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-649">Retrieves the list of all tables in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; ListTablesNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; ListTablesNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablesNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTablesNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlTable)" />
      <MemberSignature Language="F#" Value="static member ListTablesNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-650">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-650">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-651">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-651">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-652">Ruft die Liste der Tabellen aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-652">Retrieves the list of tables from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt; ListTablesNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt; ListTablesNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablesNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTablesNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTablesNextAsync&gt;d__87))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-653">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-653">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-654">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-654">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-655">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-655">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-656">Ruft die Liste der Tabellen aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-656">Retrieves the list of tables from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatistics">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; ListTableStatistics (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; ListTableStatistics(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatistics(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTableStatistics (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, tableName As String, Optional odataQuery As ODataQuery(Of USqlTableStatistics) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlTableStatistics)" />
      <MemberSignature Language="F#" Value="static member ListTableStatistics : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatistics (operations, accountName, databaseName, schemaName, tableName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-657">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-657">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-658">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-658">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-659">Der Name der Datenbank, die die Statistik enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-659">The name of the database containing the statistics.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-660">Der Name des Schemas, das Statistiken enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-660">The name of the schema containing the statistics.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="9d89e-661">Der Name der Tabelle, die die Statistik enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-661">The name of the table containing the statistics.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-662">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-662">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-663">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-663">OData Select statement.</span></span> <span data-ttu-id="9d89e-664">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-664">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-665">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-665">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-666">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-666">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-667">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-667">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-668">Ruft die Liste von Tabellenstatistiken aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-668">Retrieves the list of table statistics from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatisticsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt; ListTableStatisticsAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt; ListTableStatisticsAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTableStatisticsAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsAsync (operations, accountName, databaseName, schemaName, tableName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTableStatisticsAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-669">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-669">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-670">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-670">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-671">Der Name der Datenbank, die die Statistik enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-671">The name of the database containing the statistics.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-672">Der Name des Schemas, das Statistiken enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-672">The name of the schema containing the statistics.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="9d89e-673">Der Name der Tabelle, die die Statistik enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-673">The name of the table containing the statistics.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-674">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-674">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-675">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-675">OData Select statement.</span></span> <span data-ttu-id="9d89e-676">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-676">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-677">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-677">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-678">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-678">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-679">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-679">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-680">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-680">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-681">Ruft die Liste von Tabellenstatistiken aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-681">Retrieves the list of table statistics from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatisticsByDatabase">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; ListTableStatisticsByDatabase (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; ListTableStatisticsByDatabase(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabase(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTableStatisticsByDatabase (operations As ICatalogOperations, accountName As String, databaseName As String, Optional odataQuery As ODataQuery(Of USqlTableStatistics) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlTableStatistics)" />
      <MemberSignature Language="F#" Value="static member ListTableStatisticsByDatabase : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabase (operations, accountName, databaseName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-682">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-682">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-683">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-683">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-684">Der Name der Datenbank, die die Tabellenstatistik enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-684">The name of the database containing the table statistics.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-685">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-685">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-686">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-686">OData Select statement.</span></span> <span data-ttu-id="9d89e-687">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-687">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-688">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-688">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-689">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-689">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-690">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-690">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-691">Ruft die Liste aller Statistiken in einer Datenbank aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-691">Retrieves the list of all statistics in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatisticsByDatabaseAndSchema">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; ListTableStatisticsByDatabaseAndSchema (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; ListTableStatisticsByDatabaseAndSchema(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabaseAndSchema(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTableStatisticsByDatabaseAndSchema (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, Optional odataQuery As ODataQuery(Of USqlTableStatistics) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlTableStatistics)" />
      <MemberSignature Language="F#" Value="static member ListTableStatisticsByDatabaseAndSchema : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabaseAndSchema (operations, accountName, databaseName, schemaName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-692">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-692">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-693">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-693">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-694">Der Name der Datenbank, die die Statistik enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-694">The name of the database containing the statistics.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-695">Der Name des Schemas, das Statistiken enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-695">The name of the schema containing the statistics.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-696">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-696">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-697">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-697">OData Select statement.</span></span> <span data-ttu-id="9d89e-698">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-698">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-699">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-699">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-700">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-700">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-701">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-701">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-702">Die Liste der Statistiken für alle Tabellen in das angegebene Schema aus dem Data Lake Analytics-Katalog abgerufen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-702">Retrieves the list of all table statistics within the specified schema from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatisticsByDatabaseAndSchemaAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt; ListTableStatisticsByDatabaseAndSchemaAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt; ListTableStatisticsByDatabaseAndSchemaAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabaseAndSchemaAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTableStatisticsByDatabaseAndSchemaAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabaseAndSchemaAsync (operations, accountName, databaseName, schemaName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTableStatisticsByDatabaseAndSchemaAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-703">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-703">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-704">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-704">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-705">Der Name der Datenbank, die die Statistik enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-705">The name of the database containing the statistics.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-706">Der Name des Schemas, das Statistiken enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-706">The name of the schema containing the statistics.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-707">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-707">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-708">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-708">OData Select statement.</span></span> <span data-ttu-id="9d89e-709">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-709">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-710">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-710">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-711">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-711">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-712">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-712">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-713">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-713">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-714">Die Liste der Statistiken für alle Tabellen in das angegebene Schema aus dem Data Lake Analytics-Katalog abgerufen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-714">Retrieves the list of all table statistics within the specified schema from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatisticsByDatabaseAndSchemaNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; ListTableStatisticsByDatabaseAndSchemaNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; ListTableStatisticsByDatabaseAndSchemaNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabaseAndSchemaNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTableStatisticsByDatabaseAndSchemaNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlTableStatistics)" />
      <MemberSignature Language="F#" Value="static member ListTableStatisticsByDatabaseAndSchemaNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabaseAndSchemaNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-715">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-715">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-716">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-716">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-717">Die Liste der Statistiken für alle Tabellen in das angegebene Schema aus dem Data Lake Analytics-Katalog abgerufen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-717">Retrieves the list of all table statistics within the specified schema from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatisticsByDatabaseAndSchemaNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt; ListTableStatisticsByDatabaseAndSchemaNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt; ListTableStatisticsByDatabaseAndSchemaNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabaseAndSchemaNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTableStatisticsByDatabaseAndSchemaNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabaseAndSchemaNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTableStatisticsByDatabaseAndSchemaNextAsync&gt;d__89))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-718">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-718">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-719">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-719">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-720">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-720">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-721">Die Liste der Statistiken für alle Tabellen in das angegebene Schema aus dem Data Lake Analytics-Katalog abgerufen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-721">Retrieves the list of all table statistics within the specified schema from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatisticsByDatabaseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt; ListTableStatisticsByDatabaseAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt; ListTableStatisticsByDatabaseAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabaseAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTableStatisticsByDatabaseAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabaseAsync (operations, accountName, databaseName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTableStatisticsByDatabaseAsync&gt;d__69))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-722">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-722">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-723">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-723">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-724">Der Name der Datenbank, die die Tabellenstatistik enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-724">The name of the database containing the table statistics.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-725">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-725">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-726">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-726">OData Select statement.</span></span> <span data-ttu-id="9d89e-727">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-727">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-728">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-728">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-729">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-729">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-730">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-730">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-731">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-731">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-732">Ruft die Liste aller Statistiken in einer Datenbank aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-732">Retrieves the list of all statistics in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatisticsByDatabaseNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; ListTableStatisticsByDatabaseNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; ListTableStatisticsByDatabaseNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabaseNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTableStatisticsByDatabaseNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlTableStatistics)" />
      <MemberSignature Language="F#" Value="static member ListTableStatisticsByDatabaseNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabaseNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-733">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-733">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-734">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-734">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-735">Ruft die Liste aller Statistiken in einer Datenbank aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-735">Retrieves the list of all statistics in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatisticsByDatabaseNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt; ListTableStatisticsByDatabaseNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt; ListTableStatisticsByDatabaseNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabaseNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTableStatisticsByDatabaseNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabaseNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTableStatisticsByDatabaseNextAsync&gt;d__109))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-736">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-736">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-737">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-737">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-738">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-738">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-739">Ruft die Liste aller Statistiken in einer Datenbank aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-739">Retrieves the list of all statistics in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatisticsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; ListTableStatisticsNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; ListTableStatisticsNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTableStatisticsNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlTableStatistics)" />
      <MemberSignature Language="F#" Value="static member ListTableStatisticsNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-740">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-740">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-741">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-741">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-742">Ruft die Liste von Tabellenstatistiken aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-742">Retrieves the list of table statistics from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatisticsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt; ListTableStatisticsNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt; ListTableStatisticsNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTableStatisticsNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTableStatisticsNextAsync&gt;d__97))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-743">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-743">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-744">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-744">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-745">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-745">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-746">Ruft die Liste von Tabellenstatistiken aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-746">Retrieves the list of table statistics from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableTypes">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt; ListTableTypes (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt; ListTableTypes(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableTypes(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTableTypes (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, Optional odataQuery As ODataQuery(Of USqlTableType) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlTableType)" />
      <MemberSignature Language="F#" Value="static member ListTableTypes : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableTypes (operations, accountName, databaseName, schemaName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-747">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-747">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-748">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-748">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-749">Der Name der Datenbank, die die Tabellentypen enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-749">The name of the database containing the table types.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-750">Der Name des Schemas, die die Tabellentypen enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-750">The name of the schema containing the table types.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-751">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-751">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-752">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-752">OData Select statement.</span></span> <span data-ttu-id="9d89e-753">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-753">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-754">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-754">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-755">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-755">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-756">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-756">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-757">Die Liste der Tabellen aus dem Data Lake Analytics-Katalog abgerufen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-757">Retrieves the list of table types from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableTypesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;&gt; ListTableTypesAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;&gt; ListTableTypesAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableTypesAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTableTypesAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableTypesAsync (operations, accountName, databaseName, schemaName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTableTypesAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-758">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-758">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-759">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-759">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-760">Der Name der Datenbank, die die Tabellentypen enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-760">The name of the database containing the table types.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-761">Der Name des Schemas, die die Tabellentypen enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-761">The name of the schema containing the table types.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-762">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-762">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-763">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-763">OData Select statement.</span></span> <span data-ttu-id="9d89e-764">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-764">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-765">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-765">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-766">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-766">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-767">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-767">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-768">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-768">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-769">Die Liste der Tabellen aus dem Data Lake Analytics-Katalog abgerufen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-769">Retrieves the list of table types from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableTypesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt; ListTableTypesNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt; ListTableTypesNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableTypesNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTableTypesNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlTableType)" />
      <MemberSignature Language="F#" Value="static member ListTableTypesNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableTypesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-770">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-770">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-771">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-771">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-772">Die Liste der Tabellen aus dem Data Lake Analytics-Katalog abgerufen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-772">Retrieves the list of table types from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableTypesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;&gt; ListTableTypesNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;&gt; ListTableTypesNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableTypesNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTableTypesNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableTypesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTableTypesNextAsync&gt;d__91))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-773">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-773">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-774">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-774">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-775">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-775">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-776">Die Liste der Tabellen aus dem Data Lake Analytics-Katalog abgerufen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-776">Retrieves the list of table types from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableValuedFunctions">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; ListTableValuedFunctions (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; ListTableValuedFunctions(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctions(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTableValuedFunctions (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, Optional odataQuery As ODataQuery(Of USqlTableValuedFunction) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlTableValuedFunction)" />
      <MemberSignature Language="F#" Value="static member ListTableValuedFunctions : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctions (operations, accountName, databaseName, schemaName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-777">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-777">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-778">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-778">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-779">Der Name der Datenbank, die die Tabellenwertfunktionen enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-779">The name of the database containing the table valued functions.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-780">Der Name des Schemas, die die Tabellenwertfunktionen enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-780">The name of the schema containing the table valued functions.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-781">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-781">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-782">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-782">OData Select statement.</span></span> <span data-ttu-id="9d89e-783">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-783">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-784">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-784">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-785">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-785">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-786">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-786">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-787">Ruft die Liste von Tabellenwertfunktionen aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-787">Retrieves the list of table valued functions from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableValuedFunctionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt; ListTableValuedFunctionsAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt; ListTableValuedFunctionsAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctionsAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTableValuedFunctionsAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctionsAsync (operations, accountName, databaseName, schemaName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTableValuedFunctionsAsync&gt;d__59))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-788">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-788">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-789">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-789">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-790">Der Name der Datenbank, die die Tabellenwertfunktionen enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-790">The name of the database containing the table valued functions.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-791">Der Name des Schemas, die die Tabellenwertfunktionen enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-791">The name of the schema containing the table valued functions.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-792">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-792">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-793">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-793">OData Select statement.</span></span> <span data-ttu-id="9d89e-794">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-794">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-795">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-795">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-796">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-796">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-797">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-797">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-798">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-798">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-799">Ruft die Liste von Tabellenwertfunktionen aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-799">Retrieves the list of table valued functions from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableValuedFunctionsByDatabase">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; ListTableValuedFunctionsByDatabase (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; ListTableValuedFunctionsByDatabase(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctionsByDatabase(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTableValuedFunctionsByDatabase (operations As ICatalogOperations, accountName As String, databaseName As String, Optional odataQuery As ODataQuery(Of USqlTableValuedFunction) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlTableValuedFunction)" />
      <MemberSignature Language="F#" Value="static member ListTableValuedFunctionsByDatabase : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctionsByDatabase (operations, accountName, databaseName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-800">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-800">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-801">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-801">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-802">Der Name der Datenbank, die die Tabellenwertfunktionen enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-802">The name of the database containing the table valued functions.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-803">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-803">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-804">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-804">OData Select statement.</span></span> <span data-ttu-id="9d89e-805">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-805">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-806">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-806">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-807">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-807">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-808">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-808">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-809">Ruft die Liste aller Tabellenwert-Funktionen in einer Datenbank aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-809">Retrieves the list of all table valued functions in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableValuedFunctionsByDatabaseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt; ListTableValuedFunctionsByDatabaseAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt; ListTableValuedFunctionsByDatabaseAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctionsByDatabaseAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTableValuedFunctionsByDatabaseAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctionsByDatabaseAsync (operations, accountName, databaseName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTableValuedFunctionsByDatabaseAsync&gt;d__73))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-810">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-810">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-811">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-811">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-812">Der Name der Datenbank, die die Tabellenwertfunktionen enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-812">The name of the database containing the table valued functions.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-813">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-813">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-814">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-814">OData Select statement.</span></span> <span data-ttu-id="9d89e-815">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-815">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-816">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-816">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-817">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-817">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-818">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-818">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-819">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-819">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-820">Ruft die Liste aller Tabellenwert-Funktionen in einer Datenbank aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-820">Retrieves the list of all table valued functions in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableValuedFunctionsByDatabaseNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; ListTableValuedFunctionsByDatabaseNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; ListTableValuedFunctionsByDatabaseNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctionsByDatabaseNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTableValuedFunctionsByDatabaseNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlTableValuedFunction)" />
      <MemberSignature Language="F#" Value="static member ListTableValuedFunctionsByDatabaseNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctionsByDatabaseNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-821">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-821">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-822">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-822">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-823">Ruft die Liste aller Tabellenwert-Funktionen in einer Datenbank aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-823">Retrieves the list of all table valued functions in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableValuedFunctionsByDatabaseNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt; ListTableValuedFunctionsByDatabaseNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt; ListTableValuedFunctionsByDatabaseNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctionsByDatabaseNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTableValuedFunctionsByDatabaseNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctionsByDatabaseNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTableValuedFunctionsByDatabaseNextAsync&gt;d__113))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-824">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-824">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-825">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-825">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-826">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-826">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-827">Ruft die Liste aller Tabellenwert-Funktionen in einer Datenbank aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-827">Retrieves the list of all table valued functions in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableValuedFunctionsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; ListTableValuedFunctionsNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; ListTableValuedFunctionsNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctionsNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTableValuedFunctionsNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlTableValuedFunction)" />
      <MemberSignature Language="F#" Value="static member ListTableValuedFunctionsNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctionsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-828">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-828">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-829">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-829">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-830">Ruft die Liste von Tabellenwertfunktionen aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-830">Retrieves the list of table valued functions from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableValuedFunctionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt; ListTableValuedFunctionsNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt; ListTableValuedFunctionsNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctionsNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTableValuedFunctionsNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTableValuedFunctionsNextAsync&gt;d__103))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-831">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-831">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-832">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-832">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-833">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-833">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-834">Ruft die Liste von Tabellenwertfunktionen aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-834">Retrieves the list of table valued functions from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTypes">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt; ListTypes (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt; ListTypes(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTypes(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTypes (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, Optional odataQuery As ODataQuery(Of USqlType) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlType)" />
      <MemberSignature Language="F#" Value="static member ListTypes : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTypes (operations, accountName, databaseName, schemaName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-835">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-835">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-836">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-836">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-837">Der Name der Datenbank, die die Typen enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-837">The name of the database containing the types.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-838">Der Name des Schemas, die die Typen enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-838">The name of the schema containing the types.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-839">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-839">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-840">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-840">OData Select statement.</span></span> <span data-ttu-id="9d89e-841">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-841">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-842">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-842">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-843">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-843">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-844">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-844">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-845">Ruft die Liste der Typen in die angegebene Datenbank und das Schema des Data Lake Analytics-Katalogs ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-845">Retrieves the list of types within the specified database and schema from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTypesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;&gt; ListTypesAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;&gt; ListTypesAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTypesAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTypesAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTypesAsync (operations, accountName, databaseName, schemaName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTypesAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-846">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-846">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-847">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-847">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-848">Der Name der Datenbank, die die Typen enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-848">The name of the database containing the types.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-849">Der Name des Schemas, die die Typen enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-849">The name of the schema containing the types.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-850">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-850">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-851">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-851">OData Select statement.</span></span> <span data-ttu-id="9d89e-852">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-852">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-853">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-853">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-854">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-854">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-855">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-855">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-856">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-856">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-857">Ruft die Liste der Typen in die angegebene Datenbank und das Schema des Data Lake Analytics-Katalogs ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-857">Retrieves the list of types within the specified database and schema from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTypesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt; ListTypesNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt; ListTypesNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTypesNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTypesNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlType)" />
      <MemberSignature Language="F#" Value="static member ListTypesNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTypesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-858">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-858">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-859">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-859">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-860">Ruft die Liste der Typen in die angegebene Datenbank und das Schema des Data Lake Analytics-Katalogs ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-860">Retrieves the list of types within the specified database and schema from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTypesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;&gt; ListTypesNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;&gt; ListTypesNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTypesNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTypesNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTypesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTypesNextAsync&gt;d__101))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-861">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-861">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-862">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-862">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-863">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-863">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-864">Ruft die Liste der Typen in die angegebene Datenbank und das Schema des Data Lake Analytics-Katalogs ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-864">Retrieves the list of types within the specified database and schema from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListViews">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; ListViews (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; ListViews(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViews(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListViews (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, Optional odataQuery As ODataQuery(Of USqlView) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlView)" />
      <MemberSignature Language="F#" Value="static member ListViews : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViews (operations, accountName, databaseName, schemaName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-865">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-865">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-866">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-866">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-867">Der Name der Datenbank, die die Ansichten enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-867">The name of the database containing the views.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-868">Der Name des Schemas, die die Ansichten enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-868">The name of the schema containing the views.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-869">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-869">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-870">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-870">OData Select statement.</span></span> <span data-ttu-id="9d89e-871">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-871">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-872">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-872">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-873">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-873">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-874">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-874">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-875">Ruft die Liste der Ansichten aus der Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-875">Retrieves the list of views from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListViewsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt; ListViewsAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt; ListViewsAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViewsAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListViewsAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViewsAsync (operations, accountName, databaseName, schemaName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListViewsAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-876">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-876">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-877">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-877">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-878">Der Name der Datenbank, die die Ansichten enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-878">The name of the database containing the views.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="9d89e-879">Der Name des Schemas, die die Ansichten enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-879">The name of the schema containing the views.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-880">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-880">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-881">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-881">OData Select statement.</span></span> <span data-ttu-id="9d89e-882">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-882">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-883">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-883">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-884">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-884">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-885">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-885">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-886">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-886">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-887">Ruft die Liste der Ansichten aus der Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-887">Retrieves the list of views from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListViewsByDatabase">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; ListViewsByDatabase (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; ListViewsByDatabase(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViewsByDatabase(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListViewsByDatabase (operations As ICatalogOperations, accountName As String, databaseName As String, Optional odataQuery As ODataQuery(Of USqlView) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlView)" />
      <MemberSignature Language="F#" Value="static member ListViewsByDatabase : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViewsByDatabase (operations, accountName, databaseName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-888">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-888">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-889">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-889">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-890">Der Name der Datenbank, die die Ansichten enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-890">The name of the database containing the views.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-891">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-891">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-892">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-892">OData Select statement.</span></span> <span data-ttu-id="9d89e-893">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-893">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-894">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-894">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-895">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-895">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-896">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-896">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-897">Ruft die Liste aller Sichten in einer Datenbank aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-897">Retrieves the list of all views in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListViewsByDatabaseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt; ListViewsByDatabaseAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt; ListViewsByDatabaseAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViewsByDatabaseAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListViewsByDatabaseAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViewsByDatabaseAsync (operations, accountName, databaseName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListViewsByDatabaseAsync&gt;d__75))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-898">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-898">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-899">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-899">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-900">Der Name der Datenbank, die die Ansichten enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-900">The name of the database containing the views.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9d89e-901">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9d89e-901">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9d89e-902">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="9d89e-902">OData Select statement.</span></span> <span data-ttu-id="9d89e-903">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="9d89e-903">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="9d89e-904">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-904">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="9d89e-905">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="9d89e-905">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="9d89e-906">Optional.</span><span class="sxs-lookup"><span data-stu-id="9d89e-906">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-907">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-907">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-908">Ruft die Liste aller Sichten in einer Datenbank aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-908">Retrieves the list of all views in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListViewsByDatabaseNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; ListViewsByDatabaseNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; ListViewsByDatabaseNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViewsByDatabaseNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListViewsByDatabaseNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlView)" />
      <MemberSignature Language="F#" Value="static member ListViewsByDatabaseNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViewsByDatabaseNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-909">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-909">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-910">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-910">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-911">Ruft die Liste aller Sichten in einer Datenbank aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-911">Retrieves the list of all views in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListViewsByDatabaseNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt; ListViewsByDatabaseNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt; ListViewsByDatabaseNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViewsByDatabaseNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListViewsByDatabaseNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViewsByDatabaseNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListViewsByDatabaseNextAsync&gt;d__115))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-912">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-912">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-913">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-913">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-914">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-914">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-915">Ruft die Liste aller Sichten in einer Datenbank aus dem Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-915">Retrieves the list of all views in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListViewsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; ListViewsNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; ListViewsNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViewsNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListViewsNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlView)" />
      <MemberSignature Language="F#" Value="static member ListViewsNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViewsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-916">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-916">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-917">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-917">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-918">Ruft die Liste der Ansichten aus der Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-918">Retrieves the list of views from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListViewsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt; ListViewsNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt; ListViewsNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViewsNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListViewsNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViewsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListViewsNextAsync&gt;d__95))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-919">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-919">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d89e-920">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9d89e-920">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-921">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-921">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-922">Ruft die Liste der Ansichten aus der Data Lake Analytics-Katalog ab.</span><span class="sxs-lookup"><span data-stu-id="9d89e-922">Retrieves the list of views from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCredential">
      <MemberSignature Language="C#" Value="public static void UpdateCredential (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void UpdateCredential(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.UpdateCredential(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub UpdateCredential (operations As ICatalogOperations, accountName As String, databaseName As String, credentialName As String, parameters As DataLakeAnalyticsCatalogCredentialUpdateParameters)" />
      <MemberSignature Language="F#" Value="static member UpdateCredential : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.UpdateCredential (operations, accountName, databaseName, credentialName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="credentialName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-923">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-923">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-924">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-924">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-925">Der Name der Datenbank, die die Anmeldeinformationen enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-925">The name of the database containing the credential.</span></span>
            </param>
        <param name="credentialName">
            <span data-ttu-id="9d89e-926">Der Name der Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-926">The name of the credential.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9d89e-927">Die Parameter erforderlich, um die Anmeldeinformationen (Name und Kennwort) ändern.</span><span class="sxs-lookup"><span data-stu-id="9d89e-927">The parameters required to modify the credential (name and password)</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-928">Ändert die angegebene Anmeldeinformationen für die Verwendung mit externen Datenquellen in der angegebenen Datenbank</span><span class="sxs-lookup"><span data-stu-id="9d89e-928">Modifies the specified credential for use with external data sources in the specified database</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCredentialAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UpdateCredentialAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UpdateCredentialAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.UpdateCredentialAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateCredentialAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.UpdateCredentialAsync (operations, accountName, databaseName, credentialName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;UpdateCredentialAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="credentialName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-929">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-929">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-930">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-930">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-931">Der Name der Datenbank, die die Anmeldeinformationen enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-931">The name of the database containing the credential.</span></span>
            </param>
        <param name="credentialName">
            <span data-ttu-id="9d89e-932">Der Name der Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="9d89e-932">The name of the credential.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9d89e-933">Die Parameter erforderlich, um die Anmeldeinformationen (Name und Kennwort) ändern.</span><span class="sxs-lookup"><span data-stu-id="9d89e-933">The parameters required to modify the credential (name and password)</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-934">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-934">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-935">Ändert die angegebene Anmeldeinformationen für die Verwendung mit externen Datenquellen in der angegebenen Datenbank</span><span class="sxs-lookup"><span data-stu-id="9d89e-935">Modifies the specified credential for use with external data sources in the specified database</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSecret">
      <MemberSignature Language="C#" Value="public static void UpdateSecret (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void UpdateSecret(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.UpdateSecret(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub UpdateSecret (operations As ICatalogOperations, accountName As String, databaseName As String, secretName As String, parameters As DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters)" />
      <MemberSignature Language="F#" Value="static member UpdateSecret : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.UpdateSecret (operations, accountName, databaseName, secretName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-936">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-936">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-937">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-937">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-938">Der Name der Datenbank, die den geheimen Schlüssel enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-938">The name of the database containing the secret.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="9d89e-939">Der Name des geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="9d89e-939">The name of the secret.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9d89e-940">Die Parameter erforderlich, um den geheimen Schlüssel (Namen und Kennwort) ändern.</span><span class="sxs-lookup"><span data-stu-id="9d89e-940">The parameters required to modify the secret (name and password)</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-941">Ändert die angegebene geheime Schlüssel für die Verwendung mit externen Datenquellen in der angegebenen Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9d89e-941">Modifies the specified secret for use with external data sources in the specified database.</span></span> <span data-ttu-id="9d89e-942">Dies ist veraltet und wird in der nächsten Version entfernt.</span><span class="sxs-lookup"><span data-stu-id="9d89e-942">This is deprecated and will be removed in the next release.</span></span> <span data-ttu-id="9d89e-943">Verwenden Sie stattdessen UpdateCredential.</span><span class="sxs-lookup"><span data-stu-id="9d89e-943">Please use UpdateCredential instead.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UpdateSecretAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UpdateSecretAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.UpdateSecretAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateSecretAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.UpdateSecretAsync (operations, accountName, databaseName, secretName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;UpdateSecretAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d89e-944">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9d89e-944">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d89e-945">Nach dem Ausführen von Katalogoperationen Azure Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="9d89e-945">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9d89e-946">Der Name der Datenbank, die den geheimen Schlüssel enthält.</span><span class="sxs-lookup"><span data-stu-id="9d89e-946">The name of the database containing the secret.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="9d89e-947">Der Name des geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="9d89e-947">The name of the secret.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9d89e-948">Die Parameter erforderlich, um den geheimen Schlüssel (Namen und Kennwort) ändern.</span><span class="sxs-lookup"><span data-stu-id="9d89e-948">The parameters required to modify the secret (name and password)</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d89e-949">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9d89e-949">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d89e-950">Ändert die angegebene geheime Schlüssel für die Verwendung mit externen Datenquellen in der angegebenen Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9d89e-950">Modifies the specified secret for use with external data sources in the specified database.</span></span> <span data-ttu-id="9d89e-951">Dies ist veraltet und wird in der nächsten Version entfernt.</span><span class="sxs-lookup"><span data-stu-id="9d89e-951">This is deprecated and will be removed in the next release.</span></span> <span data-ttu-id="9d89e-952">Verwenden Sie stattdessen UpdateCredential.</span><span class="sxs-lookup"><span data-stu-id="9d89e-952">Please use UpdateCredential instead.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>