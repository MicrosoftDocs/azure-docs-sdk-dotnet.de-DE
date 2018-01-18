<Type Name="IDeviceSettingsOperations" FullName="Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations">
  <TypeSignature Language="C#" Value="public interface IDeviceSettingsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDeviceSettingsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDeviceSettingsOperations" />
  <TypeSignature Language="F#" Value="type IDeviceSettingsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5fa91-101">DeviceSettingsOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="5fa91-101">DeviceSettingsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAlertSettingsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings&gt;&gt; BeginCreateOrUpdateAlertSettingsWithHttpMessagesAsync (string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings&gt;&gt; BeginCreateOrUpdateAlertSettingsWithHttpMessagesAsync(string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations.BeginCreateOrUpdateAlertSettingsWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateAlertSettingsWithHttpMessagesAsync : string * Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings&gt;&gt;" Usage="iDeviceSettingsOperations.BeginCreateOrUpdateAlertSettingsWithHttpMessagesAsync (deviceName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="5fa91-102">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="5fa91-102">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5fa91-103">Die Warnungen Einstellungen hinzugefügt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="5fa91-103">The alert settings to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5fa91-104">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5fa91-104">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="5fa91-105">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="5fa91-105">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5fa91-106">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5fa91-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5fa91-107">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5fa91-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5fa91-108">Erstellt oder aktualisiert die warnungseinstellungen für das angegebene Gerät.</span><span class="sxs-lookup"><span data-stu-id="5fa91-108">Creates or updates the alert settings of the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5fa91-109">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="5fa91-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5fa91-110">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="5fa91-110">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5fa91-111">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5fa91-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateTimeSettingsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings&gt;&gt; BeginCreateOrUpdateTimeSettingsWithHttpMessagesAsync (string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings&gt;&gt; BeginCreateOrUpdateTimeSettingsWithHttpMessagesAsync(string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations.BeginCreateOrUpdateTimeSettingsWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateTimeSettingsWithHttpMessagesAsync : string * Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings&gt;&gt;" Usage="iDeviceSettingsOperations.BeginCreateOrUpdateTimeSettingsWithHttpMessagesAsync (deviceName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="5fa91-112">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="5fa91-112">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5fa91-113">Die Uhrzeiteinstellungen hinzugefügt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="5fa91-113">The time settings to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5fa91-114">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5fa91-114">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="5fa91-115">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="5fa91-115">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5fa91-116">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5fa91-116">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5fa91-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5fa91-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5fa91-118">Erstellt oder aktualisiert die Uhrzeiteinstellungen für das angegebene Gerät.</span><span class="sxs-lookup"><span data-stu-id="5fa91-118">Creates or updates the time settings of the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5fa91-119">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="5fa91-119">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5fa91-120">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="5fa91-120">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5fa91-121">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5fa91-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginSyncRemotemanagementCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginSyncRemotemanagementCertificateWithHttpMessagesAsync (string deviceName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginSyncRemotemanagementCertificateWithHttpMessagesAsync(string deviceName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations.BeginSyncRemotemanagementCertificateWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginSyncRemotemanagementCertificateWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDeviceSettingsOperations.BeginSyncRemotemanagementCertificateWithHttpMessagesAsync (deviceName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
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
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="5fa91-122">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="5fa91-122">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5fa91-123">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5fa91-123">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="5fa91-124">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="5fa91-124">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5fa91-125">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5fa91-125">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5fa91-126">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5fa91-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5fa91-127">Synchronisieren Sie die Remoteverwaltung Zertifikat zwischen Gerät und Dienst</span><span class="sxs-lookup"><span data-stu-id="5fa91-127">sync Remote management Certificate between appliance and Service</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5fa91-128">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="5fa91-128">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5fa91-129">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5fa91-129">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateNetworkSettingsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings&gt;&gt; BeginUpdateNetworkSettingsWithHttpMessagesAsync (string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings&gt;&gt; BeginUpdateNetworkSettingsWithHttpMessagesAsync(string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations.BeginUpdateNetworkSettingsWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateNetworkSettingsWithHttpMessagesAsync : string * Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings&gt;&gt;" Usage="iDeviceSettingsOperations.BeginUpdateNetworkSettingsWithHttpMessagesAsync (deviceName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="5fa91-130">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="5fa91-130">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5fa91-131">Die Netzwerkeinstellungen aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="5fa91-131">The network settings to be updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5fa91-132">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5fa91-132">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="5fa91-133">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="5fa91-133">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5fa91-134">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5fa91-134">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5fa91-135">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5fa91-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5fa91-136">Aktualisiert die Netzwerkeinstellungen auf dem angegebenen Gerät an.</span><span class="sxs-lookup"><span data-stu-id="5fa91-136">Updates the network settings on the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5fa91-137">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="5fa91-137">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5fa91-138">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="5fa91-138">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5fa91-139">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5fa91-139">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateSecuritySettingsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings&gt;&gt; BeginUpdateSecuritySettingsWithHttpMessagesAsync (string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings&gt;&gt; BeginUpdateSecuritySettingsWithHttpMessagesAsync(string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations.BeginUpdateSecuritySettingsWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateSecuritySettingsWithHttpMessagesAsync : string * Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings&gt;&gt;" Usage="iDeviceSettingsOperations.BeginUpdateSecuritySettingsWithHttpMessagesAsync (deviceName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="5fa91-140">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="5fa91-140">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5fa91-141">Die Eigenschaften der Sicherheit, die gepatcht werden.</span><span class="sxs-lookup"><span data-stu-id="5fa91-141">The security settings properties to be patched.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5fa91-142">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5fa91-142">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="5fa91-143">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="5fa91-143">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5fa91-144">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5fa91-144">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5fa91-145">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5fa91-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5fa91-146">Patch für die Sicherheitseigenschaften des angegebenen Gerätenamens.</span><span class="sxs-lookup"><span data-stu-id="5fa91-146">Patch Security properties of the specified device name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5fa91-147">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="5fa91-147">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5fa91-148">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="5fa91-148">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5fa91-149">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5fa91-149">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAlertSettingsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings&gt;&gt; CreateOrUpdateAlertSettingsWithHttpMessagesAsync (string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings&gt;&gt; CreateOrUpdateAlertSettingsWithHttpMessagesAsync(string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations.CreateOrUpdateAlertSettingsWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAlertSettingsWithHttpMessagesAsync : string * Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings&gt;&gt;" Usage="iDeviceSettingsOperations.CreateOrUpdateAlertSettingsWithHttpMessagesAsync (deviceName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="5fa91-150">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="5fa91-150">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5fa91-151">Die Warnungen Einstellungen hinzugefügt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="5fa91-151">The alert settings to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5fa91-152">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5fa91-152">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="5fa91-153">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="5fa91-153">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5fa91-154">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5fa91-154">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5fa91-155">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5fa91-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5fa91-156">Erstellt oder aktualisiert die warnungseinstellungen für das angegebene Gerät.</span><span class="sxs-lookup"><span data-stu-id="5fa91-156">Creates or updates the alert settings of the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5fa91-157">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="5fa91-157">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5fa91-158">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="5fa91-158">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5fa91-159">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5fa91-159">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateTimeSettingsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings&gt;&gt; CreateOrUpdateTimeSettingsWithHttpMessagesAsync (string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings&gt;&gt; CreateOrUpdateTimeSettingsWithHttpMessagesAsync(string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations.CreateOrUpdateTimeSettingsWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateTimeSettingsWithHttpMessagesAsync : string * Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings&gt;&gt;" Usage="iDeviceSettingsOperations.CreateOrUpdateTimeSettingsWithHttpMessagesAsync (deviceName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="5fa91-160">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="5fa91-160">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5fa91-161">Die Uhrzeiteinstellungen hinzugefügt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="5fa91-161">The time settings to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5fa91-162">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5fa91-162">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="5fa91-163">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="5fa91-163">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5fa91-164">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5fa91-164">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5fa91-165">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5fa91-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5fa91-166">Erstellt oder aktualisiert die Uhrzeiteinstellungen für das angegebene Gerät.</span><span class="sxs-lookup"><span data-stu-id="5fa91-166">Creates or updates the time settings of the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5fa91-167">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="5fa91-167">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5fa91-168">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="5fa91-168">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5fa91-169">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5fa91-169">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetAlertSettingsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings&gt;&gt; GetAlertSettingsWithHttpMessagesAsync (string deviceName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings&gt;&gt; GetAlertSettingsWithHttpMessagesAsync(string deviceName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations.GetAlertSettingsWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAlertSettingsWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings&gt;&gt;" Usage="iDeviceSettingsOperations.GetAlertSettingsWithHttpMessagesAsync (deviceName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings&gt;&gt;</ReturnType>
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
            <span data-ttu-id="5fa91-170">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="5fa91-170">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5fa91-171">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5fa91-171">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="5fa91-172">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="5fa91-172">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5fa91-173">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5fa91-173">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5fa91-174">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5fa91-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5fa91-175">Ruft die warnungseinstellungen für das angegebene Gerät ab.</span><span class="sxs-lookup"><span data-stu-id="5fa91-175">Gets the alert settings of the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5fa91-176">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="5fa91-176">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5fa91-177">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="5fa91-177">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5fa91-178">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5fa91-178">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNetworkSettingsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings&gt;&gt; GetNetworkSettingsWithHttpMessagesAsync (string deviceName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings&gt;&gt; GetNetworkSettingsWithHttpMessagesAsync(string deviceName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations.GetNetworkSettingsWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetNetworkSettingsWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings&gt;&gt;" Usage="iDeviceSettingsOperations.GetNetworkSettingsWithHttpMessagesAsync (deviceName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings&gt;&gt;</ReturnType>
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
            <span data-ttu-id="5fa91-179">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="5fa91-179">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5fa91-180">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5fa91-180">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="5fa91-181">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="5fa91-181">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5fa91-182">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5fa91-182">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5fa91-183">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5fa91-183">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5fa91-184">Ruft die Netzwerkeinstellungen der dem angegebenen Gerät ab.</span><span class="sxs-lookup"><span data-stu-id="5fa91-184">Gets the network settings of the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5fa91-185">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="5fa91-185">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5fa91-186">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="5fa91-186">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5fa91-187">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5fa91-187">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetSecuritySettingsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings&gt;&gt; GetSecuritySettingsWithHttpMessagesAsync (string deviceName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings&gt;&gt; GetSecuritySettingsWithHttpMessagesAsync(string deviceName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations.GetSecuritySettingsWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSecuritySettingsWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings&gt;&gt;" Usage="iDeviceSettingsOperations.GetSecuritySettingsWithHttpMessagesAsync (deviceName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings&gt;&gt;</ReturnType>
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
            <span data-ttu-id="5fa91-188">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="5fa91-188">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5fa91-189">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5fa91-189">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="5fa91-190">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="5fa91-190">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5fa91-191">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5fa91-191">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5fa91-192">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5fa91-192">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5fa91-193">Gibt die Sicherheitseigenschaften des angegebenen Gerätenamens zurück.</span><span class="sxs-lookup"><span data-stu-id="5fa91-193">Returns the Security properties of the specified device name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5fa91-194">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="5fa91-194">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5fa91-195">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="5fa91-195">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5fa91-196">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5fa91-196">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetTimeSettingsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings&gt;&gt; GetTimeSettingsWithHttpMessagesAsync (string deviceName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings&gt;&gt; GetTimeSettingsWithHttpMessagesAsync(string deviceName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations.GetTimeSettingsWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetTimeSettingsWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings&gt;&gt;" Usage="iDeviceSettingsOperations.GetTimeSettingsWithHttpMessagesAsync (deviceName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings&gt;&gt;</ReturnType>
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
            <span data-ttu-id="5fa91-197">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="5fa91-197">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5fa91-198">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5fa91-198">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="5fa91-199">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="5fa91-199">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5fa91-200">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5fa91-200">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5fa91-201">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5fa91-201">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5fa91-202">Ruft die Zeit-Einstellungen des angegebenen Geräts ab.</span><span class="sxs-lookup"><span data-stu-id="5fa91-202">Gets the time settings of the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5fa91-203">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="5fa91-203">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5fa91-204">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="5fa91-204">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5fa91-205">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5fa91-205">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="SyncRemotemanagementCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; SyncRemotemanagementCertificateWithHttpMessagesAsync (string deviceName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; SyncRemotemanagementCertificateWithHttpMessagesAsync(string deviceName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations.SyncRemotemanagementCertificateWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SyncRemotemanagementCertificateWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDeviceSettingsOperations.SyncRemotemanagementCertificateWithHttpMessagesAsync (deviceName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
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
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="5fa91-206">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="5fa91-206">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5fa91-207">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5fa91-207">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="5fa91-208">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="5fa91-208">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5fa91-209">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5fa91-209">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5fa91-210">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5fa91-210">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5fa91-211">Synchronisieren Sie die Remoteverwaltung Zertifikat zwischen Gerät und Dienst</span><span class="sxs-lookup"><span data-stu-id="5fa91-211">sync Remote management Certificate between appliance and Service</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5fa91-212">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="5fa91-212">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5fa91-213">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5fa91-213">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateNetworkSettingsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings&gt;&gt; UpdateNetworkSettingsWithHttpMessagesAsync (string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings&gt;&gt; UpdateNetworkSettingsWithHttpMessagesAsync(string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations.UpdateNetworkSettingsWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateNetworkSettingsWithHttpMessagesAsync : string * Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings&gt;&gt;" Usage="iDeviceSettingsOperations.UpdateNetworkSettingsWithHttpMessagesAsync (deviceName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="5fa91-214">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="5fa91-214">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5fa91-215">Die Netzwerkeinstellungen aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="5fa91-215">The network settings to be updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5fa91-216">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5fa91-216">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="5fa91-217">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="5fa91-217">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5fa91-218">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5fa91-218">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5fa91-219">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5fa91-219">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5fa91-220">Aktualisiert die Netzwerkeinstellungen auf dem angegebenen Gerät an.</span><span class="sxs-lookup"><span data-stu-id="5fa91-220">Updates the network settings on the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5fa91-221">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="5fa91-221">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5fa91-222">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="5fa91-222">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5fa91-223">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5fa91-223">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateSecuritySettingsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings&gt;&gt; UpdateSecuritySettingsWithHttpMessagesAsync (string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings&gt;&gt; UpdateSecuritySettingsWithHttpMessagesAsync(string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations.UpdateSecuritySettingsWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateSecuritySettingsWithHttpMessagesAsync : string * Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings&gt;&gt;" Usage="iDeviceSettingsOperations.UpdateSecuritySettingsWithHttpMessagesAsync (deviceName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="5fa91-224">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="5fa91-224">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5fa91-225">Die Eigenschaften der Sicherheit, die gepatcht werden.</span><span class="sxs-lookup"><span data-stu-id="5fa91-225">The security settings properties to be patched.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5fa91-226">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5fa91-226">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="5fa91-227">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="5fa91-227">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5fa91-228">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5fa91-228">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5fa91-229">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5fa91-229">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5fa91-230">Patch für die Sicherheitseigenschaften des angegebenen Gerätenamens.</span><span class="sxs-lookup"><span data-stu-id="5fa91-230">Patch Security properties of the specified device name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5fa91-231">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="5fa91-231">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5fa91-232">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="5fa91-232">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5fa91-233">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5fa91-233">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>