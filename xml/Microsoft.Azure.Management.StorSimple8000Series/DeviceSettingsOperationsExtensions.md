<Type Name="DeviceSettingsOperationsExtensions" FullName="Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DeviceSettingsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DeviceSettingsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DeviceSettingsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DeviceSettingsOperationsExtensions = class" />
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
            <span data-ttu-id="6c29b-101">Erweiterungsmethoden für DeviceSettingsOperations.</span><span class="sxs-lookup"><span data-stu-id="6c29b-101">Extension methods for DeviceSettingsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAlertSettings">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings BeginCreateOrUpdateAlertSettings (this Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings BeginCreateOrUpdateAlertSettings(class Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.BeginCreateOrUpdateAlertSettings(Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateAlertSettings (operations As IDeviceSettingsOperations, deviceName As String, parameters As AlertSettings, resourceGroupName As String, managerName As String) As AlertSettings" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAlertSettings : Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings" Usage="Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.BeginCreateOrUpdateAlertSettings (operations, deviceName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c29b-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c29b-102">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6c29b-103">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6c29b-103">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c29b-104">Die Warnungen Einstellungen hinzugefügt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c29b-104">The alert settings to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c29b-105">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6c29b-105">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6c29b-106">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6c29b-106">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c29b-107">Erstellt oder aktualisiert die warnungseinstellungen für das angegebene Gerät.</span><span class="sxs-lookup"><span data-stu-id="6c29b-107">Creates or updates the alert settings of the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAlertSettingsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings&gt; BeginCreateOrUpdateAlertSettingsAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings&gt; BeginCreateOrUpdateAlertSettingsAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.BeginCreateOrUpdateAlertSettingsAsync(Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAlertSettingsAsync : Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.BeginCreateOrUpdateAlertSettingsAsync (operations, deviceName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions/&lt;BeginCreateOrUpdateAlertSettingsAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c29b-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c29b-108">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6c29b-109">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6c29b-109">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c29b-110">Die Warnungen Einstellungen hinzugefügt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c29b-110">The alert settings to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c29b-111">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6c29b-111">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6c29b-112">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6c29b-112">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c29b-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c29b-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c29b-114">Erstellt oder aktualisiert die warnungseinstellungen für das angegebene Gerät.</span><span class="sxs-lookup"><span data-stu-id="6c29b-114">Creates or updates the alert settings of the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateTimeSettings">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings BeginCreateOrUpdateTimeSettings (this Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings BeginCreateOrUpdateTimeSettings(class Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.BeginCreateOrUpdateTimeSettings(Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateTimeSettings (operations As IDeviceSettingsOperations, deviceName As String, parameters As TimeSettings, resourceGroupName As String, managerName As String) As TimeSettings" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateTimeSettings : Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings" Usage="Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.BeginCreateOrUpdateTimeSettings (operations, deviceName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c29b-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c29b-115">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6c29b-116">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6c29b-116">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c29b-117">Die Uhrzeiteinstellungen hinzugefügt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c29b-117">The time settings to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c29b-118">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6c29b-118">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6c29b-119">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6c29b-119">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c29b-120">Erstellt oder aktualisiert die Uhrzeiteinstellungen für das angegebene Gerät.</span><span class="sxs-lookup"><span data-stu-id="6c29b-120">Creates or updates the time settings of the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateTimeSettingsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings&gt; BeginCreateOrUpdateTimeSettingsAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings&gt; BeginCreateOrUpdateTimeSettingsAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.BeginCreateOrUpdateTimeSettingsAsync(Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateTimeSettingsAsync : Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.BeginCreateOrUpdateTimeSettingsAsync (operations, deviceName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions/&lt;BeginCreateOrUpdateTimeSettingsAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c29b-121">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c29b-121">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6c29b-122">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6c29b-122">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c29b-123">Die Uhrzeiteinstellungen hinzugefügt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c29b-123">The time settings to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c29b-124">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6c29b-124">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6c29b-125">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6c29b-125">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c29b-126">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c29b-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c29b-127">Erstellt oder aktualisiert die Uhrzeiteinstellungen für das angegebene Gerät.</span><span class="sxs-lookup"><span data-stu-id="6c29b-127">Creates or updates the time settings of the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSyncRemotemanagementCertificate">
      <MemberSignature Language="C#" Value="public static void BeginSyncRemotemanagementCertificate (this Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginSyncRemotemanagementCertificate(class Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.BeginSyncRemotemanagementCertificate(Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginSyncRemotemanagementCertificate (operations As IDeviceSettingsOperations, deviceName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginSyncRemotemanagementCertificate : Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.BeginSyncRemotemanagementCertificate (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c29b-128">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c29b-128">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6c29b-129">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6c29b-129">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c29b-130">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6c29b-130">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6c29b-131">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6c29b-131">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c29b-132">Synchronisieren Sie die Remoteverwaltung Zertifikat zwischen Gerät und Dienst</span><span class="sxs-lookup"><span data-stu-id="6c29b-132">sync Remote management Certificate between appliance and Service</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSyncRemotemanagementCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginSyncRemotemanagementCertificateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginSyncRemotemanagementCertificateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.BeginSyncRemotemanagementCertificateAsync(Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginSyncRemotemanagementCertificateAsync : Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.BeginSyncRemotemanagementCertificateAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions/&lt;BeginSyncRemotemanagementCertificateAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c29b-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c29b-133">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6c29b-134">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6c29b-134">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c29b-135">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6c29b-135">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6c29b-136">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6c29b-136">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c29b-137">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c29b-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c29b-138">Synchronisieren Sie die Remoteverwaltung Zertifikat zwischen Gerät und Dienst</span><span class="sxs-lookup"><span data-stu-id="6c29b-138">sync Remote management Certificate between appliance and Service</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateNetworkSettings">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings BeginUpdateNetworkSettings (this Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings BeginUpdateNetworkSettings(class Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.BeginUpdateNetworkSettings(Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdateNetworkSettings (operations As IDeviceSettingsOperations, deviceName As String, parameters As NetworkSettingsPatch, resourceGroupName As String, managerName As String) As NetworkSettings" />
      <MemberSignature Language="F#" Value="static member BeginUpdateNetworkSettings : Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings" Usage="Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.BeginUpdateNetworkSettings (operations, deviceName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c29b-139">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c29b-139">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6c29b-140">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6c29b-140">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c29b-141">Die Netzwerkeinstellungen aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="6c29b-141">The network settings to be updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c29b-142">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6c29b-142">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6c29b-143">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6c29b-143">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c29b-144">Aktualisiert die Netzwerkeinstellungen auf dem angegebenen Gerät an.</span><span class="sxs-lookup"><span data-stu-id="6c29b-144">Updates the network settings on the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateNetworkSettingsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings&gt; BeginUpdateNetworkSettingsAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings&gt; BeginUpdateNetworkSettingsAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.BeginUpdateNetworkSettingsAsync(Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateNetworkSettingsAsync : Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.BeginUpdateNetworkSettingsAsync (operations, deviceName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions/&lt;BeginUpdateNetworkSettingsAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c29b-145">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c29b-145">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6c29b-146">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6c29b-146">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c29b-147">Die Netzwerkeinstellungen aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="6c29b-147">The network settings to be updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c29b-148">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6c29b-148">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6c29b-149">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6c29b-149">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c29b-150">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c29b-150">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c29b-151">Aktualisiert die Netzwerkeinstellungen auf dem angegebenen Gerät an.</span><span class="sxs-lookup"><span data-stu-id="6c29b-151">Updates the network settings on the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateSecuritySettings">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings BeginUpdateSecuritySettings (this Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings BeginUpdateSecuritySettings(class Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.BeginUpdateSecuritySettings(Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdateSecuritySettings (operations As IDeviceSettingsOperations, deviceName As String, parameters As SecuritySettingsPatch, resourceGroupName As String, managerName As String) As SecuritySettings" />
      <MemberSignature Language="F#" Value="static member BeginUpdateSecuritySettings : Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings" Usage="Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.BeginUpdateSecuritySettings (operations, deviceName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c29b-152">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c29b-152">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6c29b-153">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6c29b-153">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c29b-154">Die Eigenschaften der Sicherheit, die gepatcht werden.</span><span class="sxs-lookup"><span data-stu-id="6c29b-154">The security settings properties to be patched.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c29b-155">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6c29b-155">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6c29b-156">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6c29b-156">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c29b-157">Patch für die Sicherheitseigenschaften des angegebenen Gerätenamens.</span><span class="sxs-lookup"><span data-stu-id="6c29b-157">Patch Security properties of the specified device name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateSecuritySettingsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings&gt; BeginUpdateSecuritySettingsAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings&gt; BeginUpdateSecuritySettingsAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.BeginUpdateSecuritySettingsAsync(Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateSecuritySettingsAsync : Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.BeginUpdateSecuritySettingsAsync (operations, deviceName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions/&lt;BeginUpdateSecuritySettingsAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c29b-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c29b-158">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6c29b-159">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6c29b-159">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c29b-160">Die Eigenschaften der Sicherheit, die gepatcht werden.</span><span class="sxs-lookup"><span data-stu-id="6c29b-160">The security settings properties to be patched.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c29b-161">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6c29b-161">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6c29b-162">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6c29b-162">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c29b-163">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c29b-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c29b-164">Patch für die Sicherheitseigenschaften des angegebenen Gerätenamens.</span><span class="sxs-lookup"><span data-stu-id="6c29b-164">Patch Security properties of the specified device name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAlertSettings">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings CreateOrUpdateAlertSettings (this Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings CreateOrUpdateAlertSettings(class Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.CreateOrUpdateAlertSettings(Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAlertSettings (operations As IDeviceSettingsOperations, deviceName As String, parameters As AlertSettings, resourceGroupName As String, managerName As String) As AlertSettings" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAlertSettings : Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings" Usage="Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.CreateOrUpdateAlertSettings (operations, deviceName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c29b-165">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c29b-165">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6c29b-166">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6c29b-166">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c29b-167">Die Warnungen Einstellungen hinzugefügt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c29b-167">The alert settings to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c29b-168">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6c29b-168">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6c29b-169">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6c29b-169">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c29b-170">Erstellt oder aktualisiert die warnungseinstellungen für das angegebene Gerät.</span><span class="sxs-lookup"><span data-stu-id="6c29b-170">Creates or updates the alert settings of the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAlertSettingsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings&gt; CreateOrUpdateAlertSettingsAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings&gt; CreateOrUpdateAlertSettingsAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.CreateOrUpdateAlertSettingsAsync(Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAlertSettingsAsync : Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.CreateOrUpdateAlertSettingsAsync (operations, deviceName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions/&lt;CreateOrUpdateAlertSettingsAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c29b-171">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c29b-171">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6c29b-172">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6c29b-172">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c29b-173">Die Warnungen Einstellungen hinzugefügt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c29b-173">The alert settings to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c29b-174">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6c29b-174">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6c29b-175">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6c29b-175">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c29b-176">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c29b-176">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c29b-177">Erstellt oder aktualisiert die warnungseinstellungen für das angegebene Gerät.</span><span class="sxs-lookup"><span data-stu-id="6c29b-177">Creates or updates the alert settings of the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateTimeSettings">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings CreateOrUpdateTimeSettings (this Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings CreateOrUpdateTimeSettings(class Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.CreateOrUpdateTimeSettings(Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateTimeSettings (operations As IDeviceSettingsOperations, deviceName As String, parameters As TimeSettings, resourceGroupName As String, managerName As String) As TimeSettings" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateTimeSettings : Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings" Usage="Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.CreateOrUpdateTimeSettings (operations, deviceName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c29b-178">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c29b-178">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6c29b-179">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6c29b-179">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c29b-180">Die Uhrzeiteinstellungen hinzugefügt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c29b-180">The time settings to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c29b-181">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6c29b-181">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6c29b-182">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6c29b-182">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c29b-183">Erstellt oder aktualisiert die Uhrzeiteinstellungen für das angegebene Gerät.</span><span class="sxs-lookup"><span data-stu-id="6c29b-183">Creates or updates the time settings of the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateTimeSettingsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings&gt; CreateOrUpdateTimeSettingsAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings&gt; CreateOrUpdateTimeSettingsAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.CreateOrUpdateTimeSettingsAsync(Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateTimeSettingsAsync : Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.CreateOrUpdateTimeSettingsAsync (operations, deviceName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions/&lt;CreateOrUpdateTimeSettingsAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c29b-184">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c29b-184">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6c29b-185">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6c29b-185">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c29b-186">Die Uhrzeiteinstellungen hinzugefügt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c29b-186">The time settings to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c29b-187">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6c29b-187">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6c29b-188">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6c29b-188">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c29b-189">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c29b-189">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c29b-190">Erstellt oder aktualisiert die Uhrzeiteinstellungen für das angegebene Gerät.</span><span class="sxs-lookup"><span data-stu-id="6c29b-190">Creates or updates the time settings of the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAlertSettings">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings GetAlertSettings (this Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings GetAlertSettings(class Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.GetAlertSettings(Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAlertSettings (operations As IDeviceSettingsOperations, deviceName As String, resourceGroupName As String, managerName As String) As AlertSettings" />
      <MemberSignature Language="F#" Value="static member GetAlertSettings : Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings" Usage="Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.GetAlertSettings (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c29b-191">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c29b-191">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6c29b-192">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6c29b-192">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c29b-193">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6c29b-193">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6c29b-194">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6c29b-194">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c29b-195">Ruft die warnungseinstellungen für das angegebene Gerät ab.</span><span class="sxs-lookup"><span data-stu-id="6c29b-195">Gets the alert settings of the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAlertSettingsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings&gt; GetAlertSettingsAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings&gt; GetAlertSettingsAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.GetAlertSettingsAsync(Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAlertSettingsAsync : Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.GetAlertSettingsAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions/&lt;GetAlertSettingsAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSettings&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c29b-196">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c29b-196">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6c29b-197">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6c29b-197">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c29b-198">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6c29b-198">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6c29b-199">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6c29b-199">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c29b-200">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c29b-200">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c29b-201">Ruft die warnungseinstellungen für das angegebene Gerät ab.</span><span class="sxs-lookup"><span data-stu-id="6c29b-201">Gets the alert settings of the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNetworkSettings">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings GetNetworkSettings (this Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings GetNetworkSettings(class Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.GetNetworkSettings(Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetNetworkSettings (operations As IDeviceSettingsOperations, deviceName As String, resourceGroupName As String, managerName As String) As NetworkSettings" />
      <MemberSignature Language="F#" Value="static member GetNetworkSettings : Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings" Usage="Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.GetNetworkSettings (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c29b-202">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c29b-202">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6c29b-203">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6c29b-203">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c29b-204">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6c29b-204">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6c29b-205">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6c29b-205">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c29b-206">Ruft die Netzwerkeinstellungen der dem angegebenen Gerät ab.</span><span class="sxs-lookup"><span data-stu-id="6c29b-206">Gets the network settings of the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNetworkSettingsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings&gt; GetNetworkSettingsAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings&gt; GetNetworkSettingsAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.GetNetworkSettingsAsync(Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetNetworkSettingsAsync : Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.GetNetworkSettingsAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions/&lt;GetNetworkSettingsAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c29b-207">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c29b-207">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6c29b-208">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6c29b-208">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c29b-209">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6c29b-209">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6c29b-210">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6c29b-210">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c29b-211">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c29b-211">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c29b-212">Ruft die Netzwerkeinstellungen der dem angegebenen Gerät ab.</span><span class="sxs-lookup"><span data-stu-id="6c29b-212">Gets the network settings of the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecuritySettings">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings GetSecuritySettings (this Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings GetSecuritySettings(class Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.GetSecuritySettings(Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetSecuritySettings (operations As IDeviceSettingsOperations, deviceName As String, resourceGroupName As String, managerName As String) As SecuritySettings" />
      <MemberSignature Language="F#" Value="static member GetSecuritySettings : Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings" Usage="Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.GetSecuritySettings (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c29b-213">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c29b-213">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6c29b-214">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6c29b-214">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c29b-215">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6c29b-215">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6c29b-216">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6c29b-216">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c29b-217">Gibt die Sicherheitseigenschaften des angegebenen Gerätenamens zurück.</span><span class="sxs-lookup"><span data-stu-id="6c29b-217">Returns the Security properties of the specified device name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecuritySettingsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings&gt; GetSecuritySettingsAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings&gt; GetSecuritySettingsAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.GetSecuritySettingsAsync(Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSecuritySettingsAsync : Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.GetSecuritySettingsAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions/&lt;GetSecuritySettingsAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c29b-218">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c29b-218">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6c29b-219">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6c29b-219">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c29b-220">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6c29b-220">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6c29b-221">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6c29b-221">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c29b-222">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c29b-222">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c29b-223">Gibt die Sicherheitseigenschaften des angegebenen Gerätenamens zurück.</span><span class="sxs-lookup"><span data-stu-id="6c29b-223">Returns the Security properties of the specified device name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTimeSettings">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings GetTimeSettings (this Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings GetTimeSettings(class Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.GetTimeSettings(Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTimeSettings (operations As IDeviceSettingsOperations, deviceName As String, resourceGroupName As String, managerName As String) As TimeSettings" />
      <MemberSignature Language="F#" Value="static member GetTimeSettings : Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings" Usage="Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.GetTimeSettings (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c29b-224">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c29b-224">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6c29b-225">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6c29b-225">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c29b-226">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6c29b-226">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6c29b-227">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6c29b-227">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c29b-228">Ruft die Zeit-Einstellungen des angegebenen Geräts ab.</span><span class="sxs-lookup"><span data-stu-id="6c29b-228">Gets the time settings of the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTimeSettingsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings&gt; GetTimeSettingsAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings&gt; GetTimeSettingsAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.GetTimeSettingsAsync(Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTimeSettingsAsync : Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.GetTimeSettingsAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions/&lt;GetTimeSettingsAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c29b-229">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c29b-229">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6c29b-230">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6c29b-230">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c29b-231">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6c29b-231">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6c29b-232">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6c29b-232">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c29b-233">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c29b-233">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c29b-234">Ruft die Zeit-Einstellungen des angegebenen Geräts ab.</span><span class="sxs-lookup"><span data-stu-id="6c29b-234">Gets the time settings of the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SyncRemotemanagementCertificate">
      <MemberSignature Language="C#" Value="public static void SyncRemotemanagementCertificate (this Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void SyncRemotemanagementCertificate(class Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.SyncRemotemanagementCertificate(Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub SyncRemotemanagementCertificate (operations As IDeviceSettingsOperations, deviceName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member SyncRemotemanagementCertificate : Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.SyncRemotemanagementCertificate (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c29b-235">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c29b-235">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6c29b-236">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6c29b-236">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c29b-237">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6c29b-237">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6c29b-238">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6c29b-238">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c29b-239">Synchronisieren Sie die Remoteverwaltung Zertifikat zwischen Gerät und Dienst</span><span class="sxs-lookup"><span data-stu-id="6c29b-239">sync Remote management Certificate between appliance and Service</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SyncRemotemanagementCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SyncRemotemanagementCertificateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SyncRemotemanagementCertificateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.SyncRemotemanagementCertificateAsync(Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SyncRemotemanagementCertificateAsync : Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.SyncRemotemanagementCertificateAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions/&lt;SyncRemotemanagementCertificateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c29b-240">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c29b-240">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6c29b-241">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6c29b-241">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c29b-242">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6c29b-242">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6c29b-243">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6c29b-243">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c29b-244">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c29b-244">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c29b-245">Synchronisieren Sie die Remoteverwaltung Zertifikat zwischen Gerät und Dienst</span><span class="sxs-lookup"><span data-stu-id="6c29b-245">sync Remote management Certificate between appliance and Service</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateNetworkSettings">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings UpdateNetworkSettings (this Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings UpdateNetworkSettings(class Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.UpdateNetworkSettings(Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateNetworkSettings (operations As IDeviceSettingsOperations, deviceName As String, parameters As NetworkSettingsPatch, resourceGroupName As String, managerName As String) As NetworkSettings" />
      <MemberSignature Language="F#" Value="static member UpdateNetworkSettings : Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings" Usage="Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.UpdateNetworkSettings (operations, deviceName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c29b-246">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c29b-246">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6c29b-247">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6c29b-247">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c29b-248">Die Netzwerkeinstellungen aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="6c29b-248">The network settings to be updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c29b-249">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6c29b-249">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6c29b-250">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6c29b-250">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c29b-251">Aktualisiert die Netzwerkeinstellungen auf dem angegebenen Gerät an.</span><span class="sxs-lookup"><span data-stu-id="6c29b-251">Updates the network settings on the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateNetworkSettingsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings&gt; UpdateNetworkSettingsAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings&gt; UpdateNetworkSettingsAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.UpdateNetworkSettingsAsync(Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateNetworkSettingsAsync : Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.UpdateNetworkSettingsAsync (operations, deviceName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions/&lt;UpdateNetworkSettingsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c29b-252">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c29b-252">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6c29b-253">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6c29b-253">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c29b-254">Die Netzwerkeinstellungen aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="6c29b-254">The network settings to be updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c29b-255">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6c29b-255">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6c29b-256">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6c29b-256">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c29b-257">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c29b-257">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c29b-258">Aktualisiert die Netzwerkeinstellungen auf dem angegebenen Gerät an.</span><span class="sxs-lookup"><span data-stu-id="6c29b-258">Updates the network settings on the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSecuritySettings">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings UpdateSecuritySettings (this Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings UpdateSecuritySettings(class Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.UpdateSecuritySettings(Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateSecuritySettings (operations As IDeviceSettingsOperations, deviceName As String, parameters As SecuritySettingsPatch, resourceGroupName As String, managerName As String) As SecuritySettings" />
      <MemberSignature Language="F#" Value="static member UpdateSecuritySettings : Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings" Usage="Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.UpdateSecuritySettings (operations, deviceName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c29b-259">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c29b-259">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6c29b-260">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6c29b-260">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c29b-261">Die Eigenschaften der Sicherheit, die gepatcht werden.</span><span class="sxs-lookup"><span data-stu-id="6c29b-261">The security settings properties to be patched.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c29b-262">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6c29b-262">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6c29b-263">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6c29b-263">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c29b-264">Patch für die Sicherheitseigenschaften des angegebenen Gerätenamens.</span><span class="sxs-lookup"><span data-stu-id="6c29b-264">Patch Security properties of the specified device name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSecuritySettingsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings&gt; UpdateSecuritySettingsAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings&gt; UpdateSecuritySettingsAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations operations, string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.UpdateSecuritySettingsAsync(Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateSecuritySettingsAsync : Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions.UpdateSecuritySettingsAsync (operations, deviceName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DeviceSettingsOperationsExtensions/&lt;UpdateSecuritySettingsAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettings&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDeviceSettingsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c29b-265">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c29b-265">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6c29b-266">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6c29b-266">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c29b-267">Die Eigenschaften der Sicherheit, die gepatcht werden.</span><span class="sxs-lookup"><span data-stu-id="6c29b-267">The security settings properties to be patched.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c29b-268">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6c29b-268">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6c29b-269">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6c29b-269">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c29b-270">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c29b-270">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c29b-271">Patch für die Sicherheitseigenschaften des angegebenen Gerätenamens.</span><span class="sxs-lookup"><span data-stu-id="6c29b-271">Patch Security properties of the specified device name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>