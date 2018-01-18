<Type Name="DevicesOperationsExtensions" FullName="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DevicesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DevicesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DevicesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DevicesOperationsExtensions = class" />
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
            <span data-ttu-id="6a9f3-101">Erweiterungsmethoden für DevicesOperations.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-101">Extension methods for DevicesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AuthorizeForServiceEncryptionKeyRollover">
      <MemberSignature Language="C#" Value="public static void AuthorizeForServiceEncryptionKeyRollover (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void AuthorizeForServiceEncryptionKeyRollover(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.AuthorizeForServiceEncryptionKeyRollover(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub AuthorizeForServiceEncryptionKeyRollover (operations As IDevicesOperations, deviceName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member AuthorizeForServiceEncryptionKeyRollover : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.AuthorizeForServiceEncryptionKeyRollover (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-102">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-103">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-103">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-104">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-104">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-105">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-105">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-106">Das angegebene Gerät für den Dienst Rollover des datenverschlüsselungsschlüssels wird autorisiert.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-106">Authorizes the specified device for service data encryption key rollover.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthorizeForServiceEncryptionKeyRolloverAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task AuthorizeForServiceEncryptionKeyRolloverAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task AuthorizeForServiceEncryptionKeyRolloverAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.AuthorizeForServiceEncryptionKeyRolloverAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AuthorizeForServiceEncryptionKeyRolloverAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.AuthorizeForServiceEncryptionKeyRolloverAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;AuthorizeForServiceEncryptionKeyRolloverAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-107">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-108">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-108">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-109">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-109">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-110">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-110">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6a9f3-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-112">Das angegebene Gerät für den Dienst Rollover des datenverschlüsselungsschlüssels wird autorisiert.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-112">Authorizes the specified device for service data encryption key rollover.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginConfigure">
      <MemberSignature Language="C#" Value="public static void BeginConfigure (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginConfigure(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, class Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginConfigure(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginConfigure (operations As IDevicesOperations, parameters As ConfigureDeviceRequest, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginConfigure : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginConfigure (operations, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-113">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6a9f3-114">Die minimale Eigenschaften ein Geräts zu konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-114">The minimal properties to configure a device.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-115">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-115">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-116">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-116">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-117">Minimale Setup vor der Verwendung des Geräts abzuschließen.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-117">Complete minimal setup before using the device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginConfigureAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginConfigureAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginConfigureAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, class Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginConfigureAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginConfigureAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginConfigureAsync (operations, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;BeginConfigureAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-118">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-118">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6a9f3-119">Die minimale Eigenschaften ein Geräts zu konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-119">The minimal properties to configure a device.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-120">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-120">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-121">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-121">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6a9f3-122">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-123">Minimale Setup vor der Verwendung des Geräts abzuschließen.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-123">Complete minimal setup before using the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeactivate">
      <MemberSignature Language="C#" Value="public static void BeginDeactivate (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDeactivate(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginDeactivate(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDeactivate (operations As IDevicesOperations, deviceName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDeactivate : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginDeactivate (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-124">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-124">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-125">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-125">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-126">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-126">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-127">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-127">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-128">Das Gerät wird deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-128">Deactivates the device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeactivateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeactivateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeactivateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginDeactivateAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeactivateAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginDeactivateAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;BeginDeactivateAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-129">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-129">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-130">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-130">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-131">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-131">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-132">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-132">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6a9f3-133">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-134">Das Gerät wird deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-134">Deactivates the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IDevicesOperations, deviceName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginDelete (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-135">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-135">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-136">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-136">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-137">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-137">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-138">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-138">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-139">Löscht das Gerät.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-139">Deletes the device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginDeleteAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-140">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-140">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-141">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-141">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-142">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-142">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-143">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-143">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6a9f3-144">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-145">Löscht das Gerät.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-145">Deletes the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFailover">
      <MemberSignature Language="C#" Value="public static void BeginFailover (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string sourceDeviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginFailover(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string sourceDeviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginFailover(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginFailover (operations As IDevicesOperations, sourceDeviceName As String, parameters As FailoverRequest, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginFailover : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginFailover (operations, sourceDeviceName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="sourceDeviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-146">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-146">The operations group for this extension method.</span></span>
            </param>
        <param name="sourceDeviceName">
            <span data-ttu-id="6a9f3-147">Der Gerätename für die Quelle für den Failover ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-147">The source device name on which failover is performed.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6a9f3-148">FailoverRequest, enthält das Quellgerät und die Liste der volumecontainer Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-148">FailoverRequest containing the source device and the list of volume containers to be failed over.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-149">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-149">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-150">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-150">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-151">Failover einen Satz von volumecontainer aus einem angegebenen Quellgerät auf einem Zielgerät.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-151">Failovers a set of volume containers from a specified source device to a target device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFailoverAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginFailoverAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string sourceDeviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginFailoverAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string sourceDeviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginFailoverAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginFailoverAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginFailoverAsync (operations, sourceDeviceName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;BeginFailoverAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="sourceDeviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-152">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-152">The operations group for this extension method.</span></span>
            </param>
        <param name="sourceDeviceName">
            <span data-ttu-id="6a9f3-153">Der Gerätename für die Quelle für den Failover ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-153">The source device name on which failover is performed.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6a9f3-154">FailoverRequest, enthält das Quellgerät und die Liste der volumecontainer Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-154">FailoverRequest containing the source device and the list of volume containers to be failed over.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-155">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-155">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-156">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-156">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6a9f3-157">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-158">Failover einen Satz von volumecontainer aus einem angegebenen Quellgerät auf einem Zielgerät.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-158">Failovers a set of volume containers from a specified source device to a target device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginInstallUpdates">
      <MemberSignature Language="C#" Value="public static void BeginInstallUpdates (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginInstallUpdates(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginInstallUpdates(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginInstallUpdates (operations As IDevicesOperations, deviceName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginInstallUpdates : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginInstallUpdates (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-159">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-159">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-160">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-160">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-161">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-161">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-162">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-162">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-163">Heruntergeladen und installiert die Updates auf dem Gerät.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-163">Downloads and installs the updates on the device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginInstallUpdatesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginInstallUpdatesAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginInstallUpdatesAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginInstallUpdatesAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginInstallUpdatesAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginInstallUpdatesAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;BeginInstallUpdatesAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-164">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-164">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-165">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-165">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-166">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-166">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-167">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-167">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6a9f3-168">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-169">Heruntergeladen und installiert die Updates auf dem Gerät.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-169">Downloads and installs the updates on the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginScanForUpdates">
      <MemberSignature Language="C#" Value="public static void BeginScanForUpdates (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginScanForUpdates(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginScanForUpdates(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginScanForUpdates (operations As IDevicesOperations, deviceName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginScanForUpdates : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginScanForUpdates (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-170">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-170">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-171">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-171">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-172">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-172">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-173">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-173">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-174">Sucht nach Updates auf dem Gerät.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-174">Scans for updates on the device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginScanForUpdatesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginScanForUpdatesAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginScanForUpdatesAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginScanForUpdatesAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginScanForUpdatesAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginScanForUpdatesAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;BeginScanForUpdatesAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-175">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-175">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-176">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-176">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-177">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-177">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-178">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-178">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6a9f3-179">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-179">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-180">Sucht nach Updates auf dem Gerät.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-180">Scans for updates on the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Configure">
      <MemberSignature Language="C#" Value="public static void Configure (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Configure(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, class Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.Configure(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Configure (operations As IDevicesOperations, parameters As ConfigureDeviceRequest, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Configure : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.Configure (operations, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-181">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-181">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6a9f3-182">Die minimale Eigenschaften ein Geräts zu konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-182">The minimal properties to configure a device.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-183">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-183">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-184">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-184">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-185">Minimale Setup vor der Verwendung des Geräts abzuschließen.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-185">Complete minimal setup before using the device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigureAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ConfigureAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ConfigureAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, class Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ConfigureAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ConfigureAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ConfigureAsync (operations, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;ConfigureAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-186">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-186">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6a9f3-187">Die minimale Eigenschaften ein Geräts zu konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-187">The minimal properties to configure a device.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-188">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-188">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-189">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-189">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6a9f3-190">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-191">Minimale Setup vor der Verwendung des Geräts abzuschließen.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-191">Complete minimal setup before using the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Deactivate">
      <MemberSignature Language="C#" Value="public static void Deactivate (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Deactivate(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.Deactivate(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Deactivate (operations As IDevicesOperations, deviceName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Deactivate : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.Deactivate (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-192">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-192">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-193">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-193">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-194">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-194">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-195">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-195">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-196">Das Gerät wird deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-196">Deactivates the device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeactivateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeactivateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeactivateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.DeactivateAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeactivateAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.DeactivateAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;DeactivateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-197">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-197">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-198">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-198">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-199">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-199">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-200">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-200">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6a9f3-201">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-201">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-202">Das Gerät wird deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-202">Deactivates the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.Delete(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IDevicesOperations, deviceName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.Delete (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-203">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-203">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-204">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-204">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-205">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-205">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-206">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-206">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-207">Löscht das Gerät.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-207">Deletes the device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.DeleteAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-208">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-208">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-209">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-209">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-210">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-210">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-211">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-211">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6a9f3-212">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-212">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-213">Löscht das Gerät.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-213">Deletes the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Failover">
      <MemberSignature Language="C#" Value="public static void Failover (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string sourceDeviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Failover(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string sourceDeviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.Failover(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Failover (operations As IDevicesOperations, sourceDeviceName As String, parameters As FailoverRequest, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Failover : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.Failover (operations, sourceDeviceName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="sourceDeviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-214">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-214">The operations group for this extension method.</span></span>
            </param>
        <param name="sourceDeviceName">
            <span data-ttu-id="6a9f3-215">Der Gerätename für die Quelle für den Failover ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-215">The source device name on which failover is performed.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6a9f3-216">FailoverRequest, enthält das Quellgerät und die Liste der volumecontainer Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-216">FailoverRequest containing the source device and the list of volume containers to be failed over.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-217">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-217">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-218">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-218">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-219">Failover einen Satz von volumecontainer aus einem angegebenen Quellgerät auf einem Zielgerät.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-219">Failovers a set of volume containers from a specified source device to a target device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task FailoverAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string sourceDeviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task FailoverAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string sourceDeviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.FailoverAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member FailoverAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.FailoverAsync (operations, sourceDeviceName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;FailoverAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="sourceDeviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-220">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-220">The operations group for this extension method.</span></span>
            </param>
        <param name="sourceDeviceName">
            <span data-ttu-id="6a9f3-221">Der Gerätename für die Quelle für den Failover ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-221">The source device name on which failover is performed.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6a9f3-222">FailoverRequest, enthält das Quellgerät und die Liste der volumecontainer Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-222">FailoverRequest containing the source device and the list of volume containers to be failed over.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-223">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-223">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-224">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-224">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6a9f3-225">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-225">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-226">Failover einen Satz von volumecontainer aus einem angegebenen Quellgerät auf einem Zielgerät.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-226">Failovers a set of volume containers from a specified source device to a target device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.Device Get (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.Device Get(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.Get(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDevicesOperations, deviceName As String, resourceGroupName As String, managerName As String, Optional expand As String = null) As Device" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Device" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.Get (operations, deviceName, resourceGroupName, managerName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.Device</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-227">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-227">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-228">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-228">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-229">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-229">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-230">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-230">The manager name</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="6a9f3-231">$ Geben erweitern = Details, um weitere Felder, die im Zusammenhang mit dem Gerät oder $ Auffüllen erweitern = Rolloverdetails zusätzliche Felder, die im Zusammenhang mit dem Dienst Rollover des datenverschlüsselungsschlüssels auf Gerät ausgefüllt werden</span><span class="sxs-lookup"><span data-stu-id="6a9f3-231">Specify $expand=details to populate additional fields related to the device or $expand=rolloverdetails to populate additional fields related to the service data encryption key rollover on device</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-232">Gibt die Eigenschaften des angegebenen Geräts zurück.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-232">Returns the properties of the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt; GetAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt; GetAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.GetAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.GetAsync (operations, deviceName, resourceGroupName, managerName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-233">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-233">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-234">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-234">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-235">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-235">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-236">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-236">The manager name</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="6a9f3-237">$ Geben erweitern = Details, um weitere Felder, die im Zusammenhang mit dem Gerät oder $ Auffüllen erweitern = Rolloverdetails zusätzliche Felder, die im Zusammenhang mit dem Dienst Rollover des datenverschlüsselungsschlüssels auf Gerät ausgefüllt werden</span><span class="sxs-lookup"><span data-stu-id="6a9f3-237">Specify $expand=details to populate additional fields related to the device or $expand=rolloverdetails to populate additional fields related to the service data encryption key rollover on device</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6a9f3-238">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-238">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-239">Gibt die Eigenschaften des angegebenen Geräts zurück.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-239">Returns the properties of the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetUpdateSummary">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.Updates GetUpdateSummary (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.Updates GetUpdateSummary(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.GetUpdateSummary(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetUpdateSummary (operations As IDevicesOperations, deviceName As String, resourceGroupName As String, managerName As String) As Updates" />
      <MemberSignature Language="F#" Value="static member GetUpdateSummary : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Updates" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.GetUpdateSummary (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.Updates</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-240">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-240">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-241">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-241">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-242">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-242">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-243">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-243">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-244">Gibt das Update des angegebenen Gerätenamens Zusammenfassung.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-244">Returns the update summary of the specified device name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetUpdateSummaryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Updates&gt; GetUpdateSummaryAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Updates&gt; GetUpdateSummaryAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.GetUpdateSummaryAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetUpdateSummaryAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Updates&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.GetUpdateSummaryAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;GetUpdateSummaryAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Updates&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-245">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-245">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-246">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-246">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-247">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-247">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-248">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-248">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6a9f3-249">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-249">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-250">Gibt das Update des angegebenen Gerätenamens Zusammenfassung.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-250">Returns the update summary of the specified device name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstallUpdates">
      <MemberSignature Language="C#" Value="public static void InstallUpdates (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void InstallUpdates(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.InstallUpdates(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub InstallUpdates (operations As IDevicesOperations, deviceName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member InstallUpdates : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.InstallUpdates (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-251">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-251">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-252">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-252">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-253">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-253">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-254">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-254">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-255">Heruntergeladen und installiert die Updates auf dem Gerät.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-255">Downloads and installs the updates on the device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstallUpdatesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task InstallUpdatesAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task InstallUpdatesAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.InstallUpdatesAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member InstallUpdatesAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.InstallUpdatesAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;InstallUpdatesAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-256">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-256">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-257">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-257">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-258">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-258">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-259">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-259">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6a9f3-260">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-260">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-261">Heruntergeladen und installiert die Updates auf dem Gerät.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-261">Downloads and installs the updates on the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByManager">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt; ListByManager (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string resourceGroupName, string managerName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt; ListByManager(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string resourceGroupName, string managerName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListByManager(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByManager (operations As IDevicesOperations, resourceGroupName As String, managerName As String, Optional expand As String = null) As IEnumerable(Of Device)" />
      <MemberSignature Language="F#" Value="static member ListByManager : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListByManager (operations, resourceGroupName, managerName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-262">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-262">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-263">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-263">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-264">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-264">The manager name</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="6a9f3-265">$ Geben erweitern = Details, um weitere Felder, die im Zusammenhang mit dem Gerät oder $ Auffüllen erweitern = Rolloverdetails zusätzliche Felder, die im Zusammenhang mit dem Dienst Rollover des datenverschlüsselungsschlüssels auf Gerät ausgefüllt werden</span><span class="sxs-lookup"><span data-stu-id="6a9f3-265">Specify $expand=details to populate additional fields related to the device or $expand=rolloverdetails to populate additional fields related to the service data encryption key rollover on device</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-266">Gibt die Liste der Geräte für den angegebenen Manager zurück.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-266">Returns the list of devices for the specified manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByManagerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt;&gt; ListByManagerAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string resourceGroupName, string managerName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt;&gt; ListByManagerAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string resourceGroupName, string managerName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListByManagerAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByManagerAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListByManagerAsync (operations, resourceGroupName, managerName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;ListByManagerAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-267">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-267">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-268">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-268">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-269">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-269">The manager name</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="6a9f3-270">$ Geben erweitern = Details, um weitere Felder, die im Zusammenhang mit dem Gerät oder $ Auffüllen erweitern = Rolloverdetails zusätzliche Felder, die im Zusammenhang mit dem Dienst Rollover des datenverschlüsselungsschlüssels auf Gerät ausgefüllt werden</span><span class="sxs-lookup"><span data-stu-id="6a9f3-270">Specify $expand=details to populate additional fields related to the device or $expand=rolloverdetails to populate additional fields related to the service data encryption key rollover on device</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6a9f3-271">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-271">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-272">Gibt die Liste der Geräte für den angegebenen Manager zurück.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-272">Returns the list of devices for the specified manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFailoverSets">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSet&gt; ListFailoverSets (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSet&gt; ListFailoverSets(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListFailoverSets(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListFailoverSets (operations As IDevicesOperations, deviceName As String, resourceGroupName As String, managerName As String) As IEnumerable(Of FailoverSet)" />
      <MemberSignature Language="F#" Value="static member ListFailoverSets : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSet&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListFailoverSets (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-273">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-273">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-274">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-274">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-275">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-275">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-276">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-276">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-277">Gibt alle failoversätze für ein bestimmtes Gerät und ihre Berechtigung für die Einbeziehung in die ein Failover zurück.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-277">Returns all failover sets for a given device and their eligibility for participating in a failover.</span></span> <span data-ttu-id="6a9f3-278">Ein failoversatz bezieht sich auf einen Satz von volumecontainer aus, die als einzelne Einheit die Datenintegrität Failover werden müssen.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-278">A failover set refers to a set of volume containers that need to be failed-over as a single unit to maintain data integrity.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFailoverSetsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSet&gt;&gt; ListFailoverSetsAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSet&gt;&gt; ListFailoverSetsAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListFailoverSetsAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListFailoverSetsAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSet&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListFailoverSetsAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;ListFailoverSetsAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSet&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-279">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-279">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-280">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-280">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-281">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-281">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-282">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-282">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6a9f3-283">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-283">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-284">Gibt alle failoversätze für ein bestimmtes Gerät und ihre Berechtigung für die Einbeziehung in die ein Failover zurück.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-284">Returns all failover sets for a given device and their eligibility for participating in a failover.</span></span> <span data-ttu-id="6a9f3-285">Ein failoversatz bezieht sich auf einen Satz von volumecontainer aus, die als einzelne Einheit die Datenintegrität Failover werden müssen.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-285">A failover set refers to a set of volume containers that need to be failed-over as a single unit to maintain data integrity.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFailoverTargets">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget&gt; ListFailoverTargets (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string sourceDeviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.ListFailoverTargetsRequest parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget&gt; ListFailoverTargets(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string sourceDeviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.ListFailoverTargetsRequest parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListFailoverTargets(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.ListFailoverTargetsRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListFailoverTargets (operations As IDevicesOperations, sourceDeviceName As String, parameters As ListFailoverTargetsRequest, resourceGroupName As String, managerName As String) As IEnumerable(Of FailoverTarget)" />
      <MemberSignature Language="F#" Value="static member ListFailoverTargets : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.ListFailoverTargetsRequest * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListFailoverTargets (operations, sourceDeviceName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="sourceDeviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ListFailoverTargetsRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-286">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-286">The operations group for this extension method.</span></span>
            </param>
        <param name="sourceDeviceName">
            <span data-ttu-id="6a9f3-287">Der Gerätename für die Quelle für den Failover ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-287">The source device name on which failover is performed.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6a9f3-288">ListFailoverTargetsRequest mit der Liste der volumecontainer Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-288">ListFailoverTargetsRequest containing the list of volume containers to be failed over.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-289">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-289">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-290">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-290">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-291">Wenn Sie eine Liste der volumecontainer für Failover von einem Quellgerät ausgeführt werden, gibt diese Methode das Ergebnis Eligibility als failoverziel, für alle Geräte unter dieser Ressource.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-291">Given a list of volume containers to be failed over from a source device, this method returns the eligibility result, as a failover target, for all devices under that resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFailoverTargetsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget&gt;&gt; ListFailoverTargetsAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string sourceDeviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.ListFailoverTargetsRequest parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget&gt;&gt; ListFailoverTargetsAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string sourceDeviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.ListFailoverTargetsRequest parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListFailoverTargetsAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.ListFailoverTargetsRequest,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListFailoverTargetsAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.ListFailoverTargetsRequest * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListFailoverTargetsAsync (operations, sourceDeviceName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;ListFailoverTargetsAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="sourceDeviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ListFailoverTargetsRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-292">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-292">The operations group for this extension method.</span></span>
            </param>
        <param name="sourceDeviceName">
            <span data-ttu-id="6a9f3-293">Der Gerätename für die Quelle für den Failover ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-293">The source device name on which failover is performed.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6a9f3-294">ListFailoverTargetsRequest mit der Liste der volumecontainer Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-294">ListFailoverTargetsRequest containing the list of volume containers to be failed over.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-295">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-295">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-296">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-296">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6a9f3-297">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-297">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-298">Wenn Sie eine Liste der volumecontainer für Failover von einem Quellgerät ausgeführt werden, gibt diese Methode das Ergebnis Eligibility als failoverziel, für alle Geräte unter dieser Ressource.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-298">Given a list of volume containers to be failed over from a source device, this method returns the eligibility result, as a failover target, for all devices under that resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinition">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt; ListMetricDefinition (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt; ListMetricDefinition(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListMetricDefinition(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetricDefinition (operations As IDevicesOperations, deviceName As String, resourceGroupName As String, managerName As String) As IEnumerable(Of MetricDefinition)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefinition : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListMetricDefinition (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-299">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-299">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-300">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-300">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-301">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-301">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-302">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-302">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-303">Ruft die metrikdefinitionen für das angegebene Gerät ab.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-303">Gets the metric definitions for the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinitionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt; ListMetricDefinitionAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt; ListMetricDefinitionAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListMetricDefinitionAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefinitionAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListMetricDefinitionAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;ListMetricDefinitionAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-304">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-304">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-305">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-305">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-306">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-306">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-307">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-307">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6a9f3-308">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-308">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-309">Ruft die metrikdefinitionen für das angegebene Gerät ab.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-309">Gets the metric definitions for the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetrics">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt; ListMetrics (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt; ListMetrics(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListMetrics(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetrics (operations As IDevicesOperations, odataQuery As ODataQuery(Of MetricFilter), deviceName As String, resourceGroupName As String, managerName As String) As IEnumerable(Of Metrics)" />
      <MemberSignature Language="F#" Value="static member ListMetrics : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListMetrics (operations, odataQuery, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt;" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-310">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-310">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="6a9f3-311">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-311">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-312">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-312">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-313">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-313">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-314">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-314">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-315">Ruft die Metriken für das angegebene Gerät ab.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-315">Gets the metrics for the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt; ListMetricsAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt; ListMetricsAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListMetricsAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter},System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListMetricsAsync (operations, odataQuery, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;ListMetricsAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt;" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-316">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-316">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="6a9f3-317">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-317">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-318">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-318">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-319">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-319">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-320">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-320">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6a9f3-321">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-321">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-322">Ruft die Metriken für das angegebene Gerät ab.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-322">Gets the metrics for the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScanForUpdates">
      <MemberSignature Language="C#" Value="public static void ScanForUpdates (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ScanForUpdates(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ScanForUpdates(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub ScanForUpdates (operations As IDevicesOperations, deviceName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member ScanForUpdates : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ScanForUpdates (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-323">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-323">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-324">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-324">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-325">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-325">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-326">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-326">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-327">Sucht nach Updates auf dem Gerät.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-327">Scans for updates on the device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScanForUpdatesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ScanForUpdatesAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ScanForUpdatesAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ScanForUpdatesAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ScanForUpdatesAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ScanForUpdatesAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;ScanForUpdatesAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-328">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-328">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-329">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-329">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-330">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-330">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-331">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-331">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6a9f3-332">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-332">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-333">Sucht nach Updates auf dem Gerät.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-333">Scans for updates on the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.Device Update (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.DevicePatch parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.Device Update(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.DevicePatch parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.Update(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.DevicePatch,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IDevicesOperations, deviceName As String, parameters As DevicePatch, resourceGroupName As String, managerName As String) As Device" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.DevicePatch * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Device" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.Update (operations, deviceName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.Device</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.DevicePatch" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-334">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-334">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-335">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-335">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6a9f3-336">Patch für die Darstellung des Geräts.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-336">Patch representation of the device.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-337">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-337">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-338">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-338">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-339">Patches für das Gerät.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-339">Patches the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt; UpdateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.DevicePatch parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt; UpdateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.DevicePatch parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.DevicePatch,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.DevicePatch * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.UpdateAsync (operations, deviceName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;UpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.DevicePatch" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a9f3-340">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-340">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="6a9f3-341">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="6a9f3-341">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6a9f3-342">Patch für die Darstellung des Geräts.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-342">Patch representation of the device.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a9f3-343">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="6a9f3-343">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6a9f3-344">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="6a9f3-344">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6a9f3-345">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-345">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a9f3-346">Patches für das Gerät.</span><span class="sxs-lookup"><span data-stu-id="6a9f3-346">Patches the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>