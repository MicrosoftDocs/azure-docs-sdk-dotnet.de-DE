<Type Name="HardwareComponentGroupsOperationsExtensions" FullName="Microsoft.Azure.Management.StorSimple8000Series.HardwareComponentGroupsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class HardwareComponentGroupsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit HardwareComponentGroupsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.HardwareComponentGroupsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module HardwareComponentGroupsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type HardwareComponentGroupsOperationsExtensions = class" />
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
            <span data-ttu-id="85992-101">Erweiterungsmethoden für HardwareComponentGroupsOperations.</span><span class="sxs-lookup"><span data-stu-id="85992-101">Extension methods for HardwareComponentGroupsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginChangeControllerPowerState">
      <MemberSignature Language="C#" Value="public static void BeginChangeControllerPowerState (this Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations operations, string deviceName, string hardwareComponentGroupName, Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginChangeControllerPowerState(class Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations operations, string deviceName, string hardwareComponentGroupName, class Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.HardwareComponentGroupsOperationsExtensions.BeginChangeControllerPowerState(Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginChangeControllerPowerState (operations As IHardwareComponentGroupsOperations, deviceName As String, hardwareComponentGroupName As String, parameters As ControllerPowerStateChangeRequest, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginChangeControllerPowerState : Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.HardwareComponentGroupsOperationsExtensions.BeginChangeControllerPowerState (operations, deviceName, hardwareComponentGroupName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="hardwareComponentGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="85992-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="85992-102">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="85992-103">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="85992-103">The device name</span></span>
            </param>
        <param name="hardwareComponentGroupName">
            <span data-ttu-id="85992-104">Der Gruppenname der Hardware-Komponente.</span><span class="sxs-lookup"><span data-stu-id="85992-104">The hardware component group name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="85992-105">Der Zustand des Controllers Power-änderungsanforderung.</span><span class="sxs-lookup"><span data-stu-id="85992-105">The controller power state change request.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="85992-106">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="85992-106">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="85992-107">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="85992-107">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="85992-108">Ändert den Energiezustand des Controllers an.</span><span class="sxs-lookup"><span data-stu-id="85992-108">Changes the power state of the controller.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginChangeControllerPowerStateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginChangeControllerPowerStateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations operations, string deviceName, string hardwareComponentGroupName, Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginChangeControllerPowerStateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations operations, string deviceName, string hardwareComponentGroupName, class Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.HardwareComponentGroupsOperationsExtensions.BeginChangeControllerPowerStateAsync(Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginChangeControllerPowerStateAsync : Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.HardwareComponentGroupsOperationsExtensions.BeginChangeControllerPowerStateAsync (operations, deviceName, hardwareComponentGroupName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.HardwareComponentGroupsOperationsExtensions/&lt;BeginChangeControllerPowerStateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="hardwareComponentGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="85992-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="85992-109">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="85992-110">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="85992-110">The device name</span></span>
            </param>
        <param name="hardwareComponentGroupName">
            <span data-ttu-id="85992-111">Der Gruppenname der Hardware-Komponente.</span><span class="sxs-lookup"><span data-stu-id="85992-111">The hardware component group name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="85992-112">Der Zustand des Controllers Power-änderungsanforderung.</span><span class="sxs-lookup"><span data-stu-id="85992-112">The controller power state change request.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="85992-113">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="85992-113">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="85992-114">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="85992-114">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="85992-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="85992-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="85992-116">Ändert den Energiezustand des Controllers an.</span><span class="sxs-lookup"><span data-stu-id="85992-116">Changes the power state of the controller.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeControllerPowerState">
      <MemberSignature Language="C#" Value="public static void ChangeControllerPowerState (this Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations operations, string deviceName, string hardwareComponentGroupName, Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ChangeControllerPowerState(class Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations operations, string deviceName, string hardwareComponentGroupName, class Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.HardwareComponentGroupsOperationsExtensions.ChangeControllerPowerState(Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub ChangeControllerPowerState (operations As IHardwareComponentGroupsOperations, deviceName As String, hardwareComponentGroupName As String, parameters As ControllerPowerStateChangeRequest, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member ChangeControllerPowerState : Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.HardwareComponentGroupsOperationsExtensions.ChangeControllerPowerState (operations, deviceName, hardwareComponentGroupName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="hardwareComponentGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="85992-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="85992-117">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="85992-118">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="85992-118">The device name</span></span>
            </param>
        <param name="hardwareComponentGroupName">
            <span data-ttu-id="85992-119">Der Gruppenname der Hardware-Komponente.</span><span class="sxs-lookup"><span data-stu-id="85992-119">The hardware component group name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="85992-120">Der Zustand des Controllers Power-änderungsanforderung.</span><span class="sxs-lookup"><span data-stu-id="85992-120">The controller power state change request.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="85992-121">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="85992-121">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="85992-122">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="85992-122">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="85992-123">Ändert den Energiezustand des Controllers an.</span><span class="sxs-lookup"><span data-stu-id="85992-123">Changes the power state of the controller.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeControllerPowerStateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ChangeControllerPowerStateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations operations, string deviceName, string hardwareComponentGroupName, Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ChangeControllerPowerStateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations operations, string deviceName, string hardwareComponentGroupName, class Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.HardwareComponentGroupsOperationsExtensions.ChangeControllerPowerStateAsync(Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ChangeControllerPowerStateAsync : Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.HardwareComponentGroupsOperationsExtensions.ChangeControllerPowerStateAsync (operations, deviceName, hardwareComponentGroupName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.HardwareComponentGroupsOperationsExtensions/&lt;ChangeControllerPowerStateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="hardwareComponentGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="85992-124">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="85992-124">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="85992-125">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="85992-125">The device name</span></span>
            </param>
        <param name="hardwareComponentGroupName">
            <span data-ttu-id="85992-126">Der Gruppenname der Hardware-Komponente.</span><span class="sxs-lookup"><span data-stu-id="85992-126">The hardware component group name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="85992-127">Der Zustand des Controllers Power-änderungsanforderung.</span><span class="sxs-lookup"><span data-stu-id="85992-127">The controller power state change request.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="85992-128">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="85992-128">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="85992-129">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="85992-129">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="85992-130">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="85992-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="85992-131">Ändert den Energiezustand des Controllers an.</span><span class="sxs-lookup"><span data-stu-id="85992-131">Changes the power state of the controller.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDevice">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup&gt; ListByDevice (this Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup&gt; ListByDevice(class Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.HardwareComponentGroupsOperationsExtensions.ListByDevice(Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDevice (operations As IHardwareComponentGroupsOperations, deviceName As String, resourceGroupName As String, managerName As String) As IEnumerable(Of HardwareComponentGroup)" />
      <MemberSignature Language="F#" Value="static member ListByDevice : Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.HardwareComponentGroupsOperationsExtensions.ListByDevice (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="85992-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="85992-132">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="85992-133">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="85992-133">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="85992-134">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="85992-134">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="85992-135">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="85992-135">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="85992-136">Listet die Komponentengruppen Hardware auf Geräteebene.</span><span class="sxs-lookup"><span data-stu-id="85992-136">Lists the hardware component groups at device-level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDeviceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup&gt;&gt; ListByDeviceAsync (this Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup&gt;&gt; ListByDeviceAsync(class Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.HardwareComponentGroupsOperationsExtensions.ListByDeviceAsync(Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDeviceAsync : Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.HardwareComponentGroupsOperationsExtensions.ListByDeviceAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.HardwareComponentGroupsOperationsExtensions/&lt;ListByDeviceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="85992-137">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="85992-137">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="85992-138">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="85992-138">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="85992-139">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="85992-139">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="85992-140">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="85992-140">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="85992-141">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="85992-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="85992-142">Listet die Komponentengruppen Hardware auf Geräteebene.</span><span class="sxs-lookup"><span data-stu-id="85992-142">Lists the hardware component groups at device-level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>