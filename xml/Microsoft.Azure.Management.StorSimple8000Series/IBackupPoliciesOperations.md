<Type Name="IBackupPoliciesOperations" FullName="Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations">
  <TypeSignature Language="C#" Value="public interface IBackupPoliciesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IBackupPoliciesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IBackupPoliciesOperations" />
  <TypeSignature Language="F#" Value="type IBackupPoliciesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e655c-101">BackupPoliciesOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="e655c-101">BackupPoliciesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BackupNowWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BackupNowWithHttpMessagesAsync (string deviceName, string backupPolicyName, string backupType, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BackupNowWithHttpMessagesAsync(string deviceName, string backupPolicyName, string backupType, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations.BackupNowWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BackupNowWithHttpMessagesAsync : string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iBackupPoliciesOperations.BackupNowWithHttpMessagesAsync (deviceName, backupPolicyName, backupType, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupType" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="e655c-102">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="e655c-102">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="e655c-103">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="e655c-103">The backup policy name.</span></span>
            </param>
        <param name="backupType">
            <span data-ttu-id="e655c-104">Die Art der Sicherung.</span><span class="sxs-lookup"><span data-stu-id="e655c-104">The backup Type.</span></span> <span data-ttu-id="e655c-105">Dies kann CloudSnapshot oder LocalSnapshot sein.</span><span class="sxs-lookup"><span data-stu-id="e655c-105">This can be cloudSnapshot or localSnapshot.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e655c-106">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="e655c-106">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="e655c-107">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="e655c-107">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e655c-108">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="e655c-108">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e655c-109">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e655c-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e655c-110">Sichern Sie nun die Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="e655c-110">Backup the backup policy now.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e655c-111">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="e655c-111">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e655c-112">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="e655c-112">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginBackupNowWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginBackupNowWithHttpMessagesAsync (string deviceName, string backupPolicyName, string backupType, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginBackupNowWithHttpMessagesAsync(string deviceName, string backupPolicyName, string backupType, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations.BeginBackupNowWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginBackupNowWithHttpMessagesAsync : string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iBackupPoliciesOperations.BeginBackupNowWithHttpMessagesAsync (deviceName, backupPolicyName, backupType, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupType" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="e655c-113">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="e655c-113">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="e655c-114">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="e655c-114">The backup policy name.</span></span>
            </param>
        <param name="backupType">
            <span data-ttu-id="e655c-115">Die Art der Sicherung.</span><span class="sxs-lookup"><span data-stu-id="e655c-115">The backup Type.</span></span> <span data-ttu-id="e655c-116">Dies kann CloudSnapshot oder LocalSnapshot sein.</span><span class="sxs-lookup"><span data-stu-id="e655c-116">This can be cloudSnapshot or localSnapshot.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e655c-117">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="e655c-117">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="e655c-118">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="e655c-118">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e655c-119">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="e655c-119">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e655c-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e655c-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e655c-121">Sichern Sie nun die Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="e655c-121">Backup the backup policy now.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e655c-122">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="e655c-122">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e655c-123">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="e655c-123">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string deviceName, string backupPolicyName, Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string deviceName, string backupPolicyName, class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt;" Usage="iBackupPoliciesOperations.BeginCreateOrUpdateWithHttpMessagesAsync (deviceName, backupPolicyName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="e655c-124">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="e655c-124">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="e655c-125">Der Name der Sicherungsrichtlinie erstellt/aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="e655c-125">The name of the backup policy to be created/updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e655c-126">Die Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="e655c-126">The backup policy.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e655c-127">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="e655c-127">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="e655c-128">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="e655c-128">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e655c-129">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="e655c-129">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e655c-130">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e655c-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e655c-131">Erstellt oder aktualisiert die Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="e655c-131">Creates or updates the backup policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e655c-132">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="e655c-132">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e655c-133">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="e655c-133">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e655c-134">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="e655c-134">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string deviceName, string backupPolicyName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string deviceName, string backupPolicyName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iBackupPoliciesOperations.BeginDeleteWithHttpMessagesAsync (deviceName, backupPolicyName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="e655c-135">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="e655c-135">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="e655c-136">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="e655c-136">The name of the backup policy.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e655c-137">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="e655c-137">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="e655c-138">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="e655c-138">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e655c-139">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="e655c-139">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e655c-140">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e655c-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e655c-141">Löscht die Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="e655c-141">Deletes the backup policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e655c-142">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="e655c-142">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e655c-143">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="e655c-143">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string deviceName, string backupPolicyName, Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string deviceName, string backupPolicyName, class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt;" Usage="iBackupPoliciesOperations.CreateOrUpdateWithHttpMessagesAsync (deviceName, backupPolicyName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="e655c-144">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="e655c-144">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="e655c-145">Der Name der Sicherungsrichtlinie erstellt/aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="e655c-145">The name of the backup policy to be created/updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e655c-146">Die Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="e655c-146">The backup policy.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e655c-147">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="e655c-147">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="e655c-148">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="e655c-148">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e655c-149">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="e655c-149">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e655c-150">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e655c-150">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e655c-151">Erstellt oder aktualisiert die Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="e655c-151">Creates or updates the backup policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e655c-152">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="e655c-152">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e655c-153">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="e655c-153">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e655c-154">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="e655c-154">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string deviceName, string backupPolicyName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string deviceName, string backupPolicyName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iBackupPoliciesOperations.DeleteWithHttpMessagesAsync (deviceName, backupPolicyName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="e655c-155">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="e655c-155">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="e655c-156">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="e655c-156">The name of the backup policy.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e655c-157">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="e655c-157">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="e655c-158">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="e655c-158">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e655c-159">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="e655c-159">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e655c-160">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e655c-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e655c-161">Löscht die Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="e655c-161">Deletes the backup policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e655c-162">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="e655c-162">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e655c-163">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="e655c-163">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt; GetWithHttpMessagesAsync (string deviceName, string backupPolicyName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt; GetWithHttpMessagesAsync(string deviceName, string backupPolicyName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt;" Usage="iBackupPoliciesOperations.GetWithHttpMessagesAsync (deviceName, backupPolicyName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="e655c-164">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="e655c-164">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="e655c-165">Der Name der Sicherungsrichtlinie abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="e655c-165">The name of backup policy to be fetched.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e655c-166">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="e655c-166">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="e655c-167">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="e655c-167">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e655c-168">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="e655c-168">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e655c-169">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e655c-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e655c-170">Ruft die Eigenschaften des angegebenen Namens ab.</span><span class="sxs-lookup"><span data-stu-id="e655c-170">Gets the properties of the specified backup policy name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e655c-171">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="e655c-171">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e655c-172">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="e655c-172">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e655c-173">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="e655c-173">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByDeviceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt;&gt; ListByDeviceWithHttpMessagesAsync (string deviceName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt;&gt; ListByDeviceWithHttpMessagesAsync(string deviceName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations.ListByDeviceWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByDeviceWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt;&gt;" Usage="iBackupPoliciesOperations.ListByDeviceWithHttpMessagesAsync (deviceName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="e655c-174">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="e655c-174">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e655c-175">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="e655c-175">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="e655c-176">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="e655c-176">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e655c-177">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="e655c-177">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e655c-178">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e655c-178">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e655c-179">Ruft alle Sicherungsrichtlinien in einem Gerät ab.</span><span class="sxs-lookup"><span data-stu-id="e655c-179">Gets all the backup policies in a device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e655c-180">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="e655c-180">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e655c-181">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="e655c-181">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e655c-182">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="e655c-182">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>