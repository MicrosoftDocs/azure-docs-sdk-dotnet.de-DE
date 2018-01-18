<Type Name="IBackupSchedulesOperations" FullName="Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations">
  <TypeSignature Language="C#" Value="public interface IBackupSchedulesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IBackupSchedulesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IBackupSchedulesOperations" />
  <TypeSignature Language="F#" Value="type IBackupSchedulesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b9323-101">BackupSchedulesOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="b9323-101">BackupSchedulesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string deviceName, string backupPolicyName, string backupScheduleName, Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string deviceName, string backupPolicyName, string backupScheduleName, class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt;" Usage="iBackupSchedulesOperations.BeginCreateOrUpdateWithHttpMessagesAsync (deviceName, backupPolicyName, backupScheduleName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="b9323-102">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="b9323-102">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="b9323-103">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="b9323-103">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="b9323-104">Der Name des Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="b9323-104">The backup schedule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b9323-105">Der Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="b9323-105">The backup schedule.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b9323-106">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b9323-106">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="b9323-107">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="b9323-107">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b9323-108">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="b9323-108">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b9323-109">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b9323-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b9323-110">Erstellt oder aktualisiert den Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="b9323-110">Creates or updates the backup schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b9323-111">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="b9323-111">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b9323-112">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="b9323-112">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b9323-113">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="b9323-113">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iBackupSchedulesOperations.BeginDeleteWithHttpMessagesAsync (deviceName, backupPolicyName, backupScheduleName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
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
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="b9323-114">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="b9323-114">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="b9323-115">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="b9323-115">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="b9323-116">Der Name der Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="b9323-116">The name the backup schedule.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b9323-117">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b9323-117">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="b9323-118">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="b9323-118">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b9323-119">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="b9323-119">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b9323-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b9323-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b9323-121">Löscht den Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="b9323-121">Deletes the backup schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b9323-122">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="b9323-122">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b9323-123">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="b9323-123">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string deviceName, string backupPolicyName, string backupScheduleName, Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string deviceName, string backupPolicyName, string backupScheduleName, class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt;" Usage="iBackupSchedulesOperations.CreateOrUpdateWithHttpMessagesAsync (deviceName, backupPolicyName, backupScheduleName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="b9323-124">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="b9323-124">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="b9323-125">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="b9323-125">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="b9323-126">Der Name des Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="b9323-126">The backup schedule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b9323-127">Der Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="b9323-127">The backup schedule.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b9323-128">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b9323-128">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="b9323-129">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="b9323-129">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b9323-130">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="b9323-130">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b9323-131">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b9323-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b9323-132">Erstellt oder aktualisiert den Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="b9323-132">Creates or updates the backup schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b9323-133">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="b9323-133">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b9323-134">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="b9323-134">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b9323-135">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="b9323-135">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iBackupSchedulesOperations.DeleteWithHttpMessagesAsync (deviceName, backupPolicyName, backupScheduleName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
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
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="b9323-136">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="b9323-136">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="b9323-137">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="b9323-137">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="b9323-138">Der Name der Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="b9323-138">The name the backup schedule.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b9323-139">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b9323-139">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="b9323-140">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="b9323-140">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b9323-141">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="b9323-141">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b9323-142">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b9323-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b9323-143">Löscht den Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="b9323-143">Deletes the backup schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b9323-144">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="b9323-144">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b9323-145">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="b9323-145">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt; GetWithHttpMessagesAsync (string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt; GetWithHttpMessagesAsync(string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt;" Usage="iBackupSchedulesOperations.GetWithHttpMessagesAsync (deviceName, backupPolicyName, backupScheduleName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="b9323-146">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="b9323-146">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="b9323-147">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="b9323-147">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="b9323-148">Der Name der Sicherungszeitplan abgerufen werden sollen</span><span class="sxs-lookup"><span data-stu-id="b9323-148">The name of the backup schedule to be fetched</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b9323-149">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b9323-149">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="b9323-150">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="b9323-150">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b9323-151">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="b9323-151">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b9323-152">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b9323-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b9323-153">Ruft die Eigenschaften des angegebenen Sicherungszeitplan Namens ab.</span><span class="sxs-lookup"><span data-stu-id="b9323-153">Gets the properties of the specified backup schedule name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b9323-154">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="b9323-154">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b9323-155">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="b9323-155">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b9323-156">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="b9323-156">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByBackupPolicyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt;&gt; ListByBackupPolicyWithHttpMessagesAsync (string deviceName, string backupPolicyName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt;&gt; ListByBackupPolicyWithHttpMessagesAsync(string deviceName, string backupPolicyName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations.ListByBackupPolicyWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByBackupPolicyWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt;&gt;" Usage="iBackupSchedulesOperations.ListByBackupPolicyWithHttpMessagesAsync (deviceName, backupPolicyName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt;&gt;</ReturnType>
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
            <span data-ttu-id="b9323-157">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="b9323-157">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="b9323-158">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="b9323-158">The backup policy name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b9323-159">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b9323-159">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="b9323-160">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="b9323-160">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b9323-161">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="b9323-161">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b9323-162">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b9323-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b9323-163">Ruft alle Sicherungszeitpläne in einer Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="b9323-163">Gets all the backup schedules in a backup policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b9323-164">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="b9323-164">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b9323-165">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="b9323-165">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b9323-166">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="b9323-166">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>