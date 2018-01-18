<Type Name="IStorageAccountsOperations" FullName="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations">
  <TypeSignature Language="C#" Value="public interface IStorageAccountsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStorageAccountsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStorageAccountsOperations" />
  <TypeSignature Language="F#" Value="type IStorageAccountsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="64a03-101">StorageAccountsOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="64a03-101">StorageAccountsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; BeginCreateWithHttpMessagesAsync (string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; BeginCreateWithHttpMessagesAsync(string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations.BeginCreateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;" Usage="iStorageAccountsOperations.BeginCreateWithHttpMessagesAsync (resourceGroupName, accountName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="64a03-102">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="64a03-102">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="64a03-103">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="64a03-103">The name of the storage account within the specified resource group.</span></span> <span data-ttu-id="64a03-104">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="64a03-104">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="64a03-105">Die Parameter für das erstellte Konto bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="64a03-105">The parameters to provide for the created account.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="64a03-106">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="64a03-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a03-107">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="64a03-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a03-108">Erstellt asynchron ein neues Speicherkonto mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="64a03-108">Asynchronously creates a new storage account with the specified parameters.</span></span> <span data-ttu-id="64a03-109">Wenn bereits ein Konto erstellt wird, und eine nachfolgende erstellungsanforderung wird, mit verschiedenen Eigenschaften ausgegeben, werden die Kontoeigenschaften aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="64a03-109">If an account is already created and a subsequent create request is issued with different properties, the account properties will be updated.</span></span> <span data-ttu-id="64a03-110">Wenn bereits ein Konto erstellt wird, und eine nachfolgende CREATE- oder Update-Anforderung wird, mit dem genau gleichen Satz von Eigenschaften ausgegeben, wird die Anforderung erfolgreich ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="64a03-110">If an account is already created and a subsequent create or update request is issued with the exact same set of properties, the request will succeed.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="64a03-111">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="64a03-111">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="64a03-112">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="64a03-112">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="64a03-113">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="64a03-113">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner&gt;&gt; CheckNameAvailabilityWithHttpMessagesAsync (string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner&gt;&gt; CheckNameAvailabilityWithHttpMessagesAsync(string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations.CheckNameAvailabilityWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckNameAvailabilityWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner&gt;&gt;" Usage="iStorageAccountsOperations.CheckNameAvailabilityWithHttpMessagesAsync (name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name"></param>
        <param name="customHeaders">
            <span data-ttu-id="64a03-114">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="64a03-114">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a03-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="64a03-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a03-116">Überprüft, ob der Name des Speicherkontos ist gültig und wird nicht bereits verwendet.</span><span class="sxs-lookup"><span data-stu-id="64a03-116">Checks that the storage account name is valid and is not already in use.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="64a03-117">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="64a03-117">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="64a03-118">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="64a03-118">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="64a03-119">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="64a03-119">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; CreateWithHttpMessagesAsync (string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; CreateWithHttpMessagesAsync(string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations.CreateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;" Usage="iStorageAccountsOperations.CreateWithHttpMessagesAsync (resourceGroupName, accountName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="64a03-120">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="64a03-120">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="64a03-121">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="64a03-121">The name of the storage account within the specified resource group.</span></span> <span data-ttu-id="64a03-122">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="64a03-122">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="64a03-123">Die Parameter für das erstellte Konto bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="64a03-123">The parameters to provide for the created account.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="64a03-124">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="64a03-124">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a03-125">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="64a03-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a03-126">Erstellt asynchron ein neues Speicherkonto mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="64a03-126">Asynchronously creates a new storage account with the specified parameters.</span></span> <span data-ttu-id="64a03-127">Wenn bereits ein Konto erstellt wird, und eine nachfolgende erstellungsanforderung wird, mit verschiedenen Eigenschaften ausgegeben, werden die Kontoeigenschaften aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="64a03-127">If an account is already created and a subsequent create request is issued with different properties, the account properties will be updated.</span></span> <span data-ttu-id="64a03-128">Wenn bereits ein Konto erstellt wird, und eine nachfolgende CREATE- oder Update-Anforderung wird, mit dem genau gleichen Satz von Eigenschaften ausgegeben, wird die Anforderung erfolgreich ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="64a03-128">If an account is already created and a subsequent create or update request is issued with the exact same set of properties, the request will succeed.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="64a03-129">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="64a03-129">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="64a03-130">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="64a03-130">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="64a03-131">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="64a03-131">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string accountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string accountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iStorageAccountsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, accountName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="64a03-132">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="64a03-132">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="64a03-133">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="64a03-133">The name of the storage account within the specified resource group.</span></span> <span data-ttu-id="64a03-134">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="64a03-134">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="64a03-135">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="64a03-135">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a03-136">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="64a03-136">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a03-137">Löscht ein Speicherkonto in Microsoft Azure.</span><span class="sxs-lookup"><span data-stu-id="64a03-137">Deletes a storage account in Microsoft Azure.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="64a03-138">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="64a03-138">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="64a03-139">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="64a03-139">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPropertiesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; GetPropertiesWithHttpMessagesAsync (string resourceGroupName, string accountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; GetPropertiesWithHttpMessagesAsync(string resourceGroupName, string accountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations.GetPropertiesWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPropertiesWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;" Usage="iStorageAccountsOperations.GetPropertiesWithHttpMessagesAsync (resourceGroupName, accountName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="64a03-140">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="64a03-140">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="64a03-141">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="64a03-141">The name of the storage account within the specified resource group.</span></span> <span data-ttu-id="64a03-142">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="64a03-142">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="64a03-143">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="64a03-143">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a03-144">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="64a03-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a03-145">Die Eigenschaften für das angegebene Speicherkonto einschließlich, aber nicht beschränkt auf Name, SKU-Name, Speicherort und Kontostatus zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="64a03-145">Returns the properties for the specified storage account including but not limited to name, SKU name, location, and account status.</span></span>
            <span data-ttu-id="64a03-146">Der ListKeys-Vorgang sollte verwendet werden, um Speicherschlüssel abzurufen.</span><span class="sxs-lookup"><span data-stu-id="64a03-146">The ListKeys operation should be used to retrieve storage keys.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="64a03-147">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="64a03-147">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="64a03-148">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="64a03-148">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="64a03-149">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="64a03-149">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations.ListByResourceGroupWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;&gt;" Usage="iStorageAccountsOperations.ListByResourceGroupWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="64a03-150">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="64a03-150">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="64a03-151">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="64a03-151">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a03-152">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="64a03-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a03-153">Listet alle Speicherkonten verfügbar sind, unter der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="64a03-153">Lists all the storage accounts available under the given resource group.</span></span> <span data-ttu-id="64a03-154">Beachten Sie, dass Speicherschlüssel nicht zurückgegeben werden. Verwenden Sie den ListKeys-Vorgang für diesen ein.</span><span class="sxs-lookup"><span data-stu-id="64a03-154">Note that storage keys are not returned; use the ListKeys operation for this.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="64a03-155">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="64a03-155">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="64a03-156">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="64a03-156">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="64a03-157">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="64a03-157">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListKeysWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;&gt; ListKeysWithHttpMessagesAsync (string resourceGroupName, string accountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;&gt; ListKeysWithHttpMessagesAsync(string resourceGroupName, string accountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations.ListKeysWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListKeysWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;&gt;" Usage="iStorageAccountsOperations.ListKeysWithHttpMessagesAsync (resourceGroupName, accountName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="64a03-158">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="64a03-158">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="64a03-159">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="64a03-159">The name of the storage account within the specified resource group.</span></span> <span data-ttu-id="64a03-160">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="64a03-160">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="64a03-161">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="64a03-161">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a03-162">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="64a03-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a03-163">Listet die Zugriffsschlüssel für das angegebene Speicherkonto.</span><span class="sxs-lookup"><span data-stu-id="64a03-163">Lists the access keys for the specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="64a03-164">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="64a03-164">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="64a03-165">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="64a03-165">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="64a03-166">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="64a03-166">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;&gt; ListWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;&gt; ListWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations.ListWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;&gt;" Usage="iStorageAccountsOperations.ListWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="64a03-167">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="64a03-167">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a03-168">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="64a03-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a03-169">Listet alle Speicherkonten im Abonnement verfügbar.</span><span class="sxs-lookup"><span data-stu-id="64a03-169">Lists all the storage accounts available under the subscription.</span></span>
            <span data-ttu-id="64a03-170">Beachten Sie, dass Speicherschlüssel nicht zurückgegeben werden. Verwenden Sie den ListKeys-Vorgang für diesen ein.</span><span class="sxs-lookup"><span data-stu-id="64a03-170">Note that storage keys are not returned; use the ListKeys operation for this.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="64a03-171">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="64a03-171">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="64a03-172">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="64a03-172">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="64a03-173">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="64a03-173">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;&gt; RegenerateKeyWithHttpMessagesAsync (string resourceGroupName, string accountName, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;&gt; RegenerateKeyWithHttpMessagesAsync(string resourceGroupName, string accountName, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations.RegenerateKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegenerateKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;&gt;" Usage="iStorageAccountsOperations.RegenerateKeyWithHttpMessagesAsync (resourceGroupName, accountName, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="64a03-174">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="64a03-174">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="64a03-175">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="64a03-175">The name of the storage account within the specified resource group.</span></span> <span data-ttu-id="64a03-176">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="64a03-176">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="keyName"></param>
        <param name="customHeaders">
            <span data-ttu-id="64a03-177">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="64a03-177">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a03-178">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="64a03-178">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a03-179">Generiert eine die Zugriffsschlüssel für das angegebene Speicherkonto.</span><span class="sxs-lookup"><span data-stu-id="64a03-179">Regenerates one of the access keys for the specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="64a03-180">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="64a03-180">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="64a03-181">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="64a03-181">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="64a03-182">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="64a03-182">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations.UpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;" Usage="iStorageAccountsOperations.UpdateWithHttpMessagesAsync (resourceGroupName, accountName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="64a03-183">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="64a03-183">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="64a03-184">Der Name des Speicherkontos innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="64a03-184">The name of the storage account within the specified resource group.</span></span> <span data-ttu-id="64a03-185">Speicherkontonamen müssen zwischen 3 und 24 Zeichen lang sein und dürfen nur Zahlen und Kleinbuchstaben enthalten.</span><span class="sxs-lookup"><span data-stu-id="64a03-185">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="64a03-186">Die Parameter für die aktualisierte Konto bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="64a03-186">The parameters to provide for the updated account.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="64a03-187">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="64a03-187">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a03-188">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="64a03-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a03-189">Der Update-Vorgang kann verwendet werden, um die SKU, Verschlüsselung, zugriffstarifs oder Tags für ein Speicherkonto zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="64a03-189">The update operation can be used to update the SKU, encryption, access tier, or tags for a storage account.</span></span> <span data-ttu-id="64a03-190">Es kann auch verwendet werden, um das Konto zu einer benutzerdefinierten Domäne zuzuordnen.</span><span class="sxs-lookup"><span data-stu-id="64a03-190">It can also be used to map the account to a custom domain.</span></span> <span data-ttu-id="64a03-191">Nur eine benutzerdefinierte Domäne wird pro Speicherkonto unterstützt. die Ersetzung/Änderung der benutzerdefinierten Domäne wird nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="64a03-191">Only one custom domain is supported per storage account; the replacement/change of custom domain is not supported.</span></span> <span data-ttu-id="64a03-192">Um eine alte benutzerdefinierte Domäne zu ersetzen, muss der alte Wert gelöscht/aufgehoben werden bevor ein neuer Wert festgelegt werden kann.</span><span class="sxs-lookup"><span data-stu-id="64a03-192">In order to replace an old custom domain, the old value must be cleared/unregistered before a new value can be set.</span></span> <span data-ttu-id="64a03-193">Das Update von mehreren Eigenschaften wird unterstützt.</span><span class="sxs-lookup"><span data-stu-id="64a03-193">The update of multiple properties is supported.</span></span> <span data-ttu-id="64a03-194">Dieser Aufruf wird der Speicherschlüssel für das Konto nicht geändert.</span><span class="sxs-lookup"><span data-stu-id="64a03-194">This call does not change the storage keys for the account.</span></span> <span data-ttu-id="64a03-195">Wenn Sie die speicherkontoschlüssel ändern möchten, verwenden Sie die Schlüssel neu generieren-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="64a03-195">If you want to change the storage account keys, use the regenerate keys operation.</span></span>
            <span data-ttu-id="64a03-196">Der Speicherort und den Namen des Speicherkontos können nach der Erstellung nicht geändert werden.</span><span class="sxs-lookup"><span data-stu-id="64a03-196">The location and name of the storage account cannot be changed after creation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="64a03-197">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="64a03-197">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="64a03-198">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="64a03-198">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="64a03-199">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="64a03-199">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>