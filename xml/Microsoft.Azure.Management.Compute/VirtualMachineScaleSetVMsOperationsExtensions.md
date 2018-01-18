<Type Name="VirtualMachineScaleSetVMsOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualMachineScaleSetVMsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualMachineScaleSetVMsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualMachineScaleSetVMsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetVMsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ef6cd-101">Erweiterungsmethoden für VirtualMachineScaleSetVMsOperations.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-101">Extension methods for VirtualMachineScaleSetVMsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginDeallocate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDeallocate (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDeallocate(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginDeallocate(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDeallocate (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginDeallocate : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginDeallocate (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-103">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-104">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-104">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-105">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-105">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-106">Hebt die Zuordnung einer bestimmten virtuellen Maschine in einem VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-106">Deallocates a specific virtual machine in a VM scale set.</span></span> <span data-ttu-id="ef6cd-107">Der virtuelle Computer heruntergefahren, und die verwendeten Ressourcen frei.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-107">Shuts down the virtual machine and releases the compute resources it uses.</span></span> <span data-ttu-id="ef6cd-108">Sie sind nicht in Rechnung gestellt für Serverressourcen dieser virtuellen Maschine, sobald er freigegeben wird.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-108">You are not billed for the compute resources of this virtual machine once it is deallocated.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeallocateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeallocateAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeallocateAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginDeallocateAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeallocateAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginDeallocateAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;BeginDeallocateAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-110">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-110">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-111">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-111">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-112">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-112">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ef6cd-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-114">Hebt die Zuordnung einer bestimmten virtuellen Maschine in einem VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-114">Deallocates a specific virtual machine in a VM scale set.</span></span> <span data-ttu-id="ef6cd-115">Der virtuelle Computer heruntergefahren, und die verwendeten Ressourcen frei.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-115">Shuts down the virtual machine and releases the compute resources it uses.</span></span> <span data-ttu-id="ef6cd-116">Sie sind nicht in Rechnung gestellt für Serverressourcen dieser virtuellen Maschine, sobald er freigegeben wird.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-116">You are not billed for the compute resources of this virtual machine once it is deallocated.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDelete (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDelete(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginDelete (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-118">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-118">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-119">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-119">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-120">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-120">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-121">Löscht einen virtuellen Computer aus einer VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-121">Deletes a virtual machine from a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-123">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-123">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-124">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-124">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-125">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-125">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ef6cd-126">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-127">Löscht einen virtuellen Computer aus einer VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-127">Deletes a virtual machine from a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPowerOff">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginPowerOff (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginPowerOff(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginPowerOff(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginPowerOff (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginPowerOff : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginPowerOff (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-128">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-129">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-129">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-130">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-130">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-131">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-131">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-132">(Beenden) eine virtuelle Maschine in einer VM Scale Set zum ausschalten.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-132">Power off (stop) a virtual machine in a VM scale set.</span></span> <span data-ttu-id="ef6cd-133">Beachten Sie, dass Ressourcen immer noch angeschlossen sind, und Sie für die Ressourcen in Rechnung gestellt abrufen werden.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-133">Note that resources are still attached and you are getting charged for the resources.</span></span> <span data-ttu-id="ef6cd-134">Stattdessen verwenden freigeben, um Ressourcen freizugeben und Gebühren zu vermeiden.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-134">Instead, use deallocate to release resources and avoid charges.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPowerOffAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginPowerOffAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginPowerOffAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginPowerOffAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginPowerOffAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginPowerOffAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;BeginPowerOffAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-135">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-135">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-136">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-136">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-137">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-137">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-138">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-138">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ef6cd-139">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-140">(Beenden) eine virtuelle Maschine in einer VM Scale Set zum ausschalten.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-140">Power off (stop) a virtual machine in a VM scale set.</span></span> <span data-ttu-id="ef6cd-141">Beachten Sie, dass Ressourcen immer noch angeschlossen sind, und Sie für die Ressourcen in Rechnung gestellt abrufen werden.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-141">Note that resources are still attached and you are getting charged for the resources.</span></span> <span data-ttu-id="ef6cd-142">Stattdessen verwenden freigeben, um Ressourcen freizugeben und Gebühren zu vermeiden.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-142">Instead, use deallocate to release resources and avoid charges.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginReimage">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginReimage (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginReimage(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginReimage(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginReimage (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginReimage : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginReimage (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-144">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-144">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-145">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-145">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-146">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-146">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-147">Reimages (upgrade des Betriebssystems) legen Sie eine bestimmte virtuelle Maschine in einer VM-skalieren.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-147">Reimages (upgrade the operating system) a specific virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginReimageAll">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginReimageAll (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginReimageAll(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginReimageAll(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginReimageAll (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginReimageAll : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginReimageAll (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-148">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-149">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-149">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-150">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-150">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-151">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-151">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-152">Können Sie alle Datenträger (Datenträger einschließlich) ein image in der Instanz von einer VM Scale set.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-152">Allows you to re-image all the disks ( including data disks ) in the a VM scale set instance.</span></span> <span data-ttu-id="ef6cd-153">Dieser Vorgang wird nur für verwaltete Datenträger unterstützt.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-153">This operation is only supported for managed disks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginReimageAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginReimageAllAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginReimageAllAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginReimageAllAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginReimageAllAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginReimageAllAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;BeginReimageAllAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-154">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-154">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-155">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-155">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-156">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-156">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-157">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-157">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ef6cd-158">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-158">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-159">Können Sie alle Datenträger (Datenträger einschließlich) ein image in der Instanz von einer VM Scale set.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-159">Allows you to re-image all the disks ( including data disks ) in the a VM scale set instance.</span></span> <span data-ttu-id="ef6cd-160">Dieser Vorgang wird nur für verwaltete Datenträger unterstützt.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-160">This operation is only supported for managed disks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginReimageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginReimageAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginReimageAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginReimageAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginReimageAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginReimageAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;BeginReimageAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-161">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-161">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-162">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-162">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-163">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-163">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-164">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-164">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ef6cd-165">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-166">Reimages (upgrade des Betriebssystems) legen Sie eine bestimmte virtuelle Maschine in einer VM-skalieren.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-166">Reimages (upgrade the operating system) a specific virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRestart">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginRestart (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginRestart(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginRestart(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginRestart (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginRestart : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginRestart (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-167">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-167">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-168">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-168">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-169">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-169">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-170">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-170">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-171">Startet einen virtuellen Computer in einer VM-Skalierungsgruppe neu.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-171">Restarts a virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRestartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginRestartAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginRestartAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginRestartAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginRestartAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginRestartAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;BeginRestartAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-172">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-172">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-173">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-173">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-174">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-174">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-175">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-175">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ef6cd-176">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-176">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-177">Startet einen virtuellen Computer in einer VM-Skalierungsgruppe neu.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-177">Restarts a virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStart">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginStart (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginStart(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginStart(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginStart (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginStart : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginStart (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-178">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-178">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-179">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-179">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-180">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-180">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-181">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-181">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-182">Startet einen virtuellen Computer in einer VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-182">Starts a virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginStartAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginStartAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginStartAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStartAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginStartAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;BeginStartAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-183">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-183">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-184">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-184">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-185">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-185">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-186">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-186">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ef6cd-187">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-187">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-188">Startet einen virtuellen Computer in einer VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-188">Starts a virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Deallocate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Deallocate (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Deallocate(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.Deallocate(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Deallocate (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Deallocate : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.Deallocate (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-189">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-189">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-190">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-190">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-191">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-191">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-192">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-192">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-193">Hebt die Zuordnung einer bestimmten virtuellen Maschine in einem VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-193">Deallocates a specific virtual machine in a VM scale set.</span></span> <span data-ttu-id="ef6cd-194">Der virtuelle Computer heruntergefahren, und die verwendeten Ressourcen frei.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-194">Shuts down the virtual machine and releases the compute resources it uses.</span></span> <span data-ttu-id="ef6cd-195">Sie sind nicht in Rechnung gestellt für Serverressourcen dieser virtuellen Maschine, sobald er freigegeben wird.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-195">You are not billed for the compute resources of this virtual machine once it is deallocated.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeallocateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeallocateAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeallocateAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.DeallocateAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeallocateAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.DeallocateAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;DeallocateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-196">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-196">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-197">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-197">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-198">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-198">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-199">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-199">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ef6cd-200">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-200">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-201">Hebt die Zuordnung einer bestimmten virtuellen Maschine in einem VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-201">Deallocates a specific virtual machine in a VM scale set.</span></span> <span data-ttu-id="ef6cd-202">Der virtuelle Computer heruntergefahren, und die verwendeten Ressourcen frei.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-202">Shuts down the virtual machine and releases the compute resources it uses.</span></span> <span data-ttu-id="ef6cd-203">Sie sind nicht in Rechnung gestellt für Serverressourcen dieser virtuellen Maschine, sobald er freigegeben wird.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-203">You are not billed for the compute resources of this virtual machine once it is deallocated.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Delete (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Delete(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.Delete(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.Delete (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-204">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-204">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-205">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-205">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-206">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-206">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-207">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-207">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-208">Löscht einen virtuellen Computer aus einer VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-208">Deletes a virtual machine from a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.DeleteAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-209">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-209">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-210">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-210">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-211">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-211">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-212">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-212">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ef6cd-213">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-213">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-214">Löscht einen virtuellen Computer aus einer VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-214">Deletes a virtual machine from a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM Get (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM Get(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.Get(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As VirtualMachineScaleSetVM" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.Get (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-215">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-215">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-216">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-216">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-217">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-217">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-218">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-218">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-219">Ruft eine virtuelle Maschine aus einer VM-Skalierungsgruppe ab.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-219">Gets a virtual machine from a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt; GetAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt; GetAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.GetAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;GetAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-220">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-220">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-221">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-221">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-222">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-222">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-223">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-223">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ef6cd-224">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-224">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-225">Ruft eine virtuelle Maschine aus einer VM-Skalierungsgruppe ab.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-225">Gets a virtual machine from a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetInstanceView">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView GetInstanceView (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView GetInstanceView(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.GetInstanceView(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetInstanceView (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As VirtualMachineScaleSetVMInstanceView" />
      <MemberSignature Language="F#" Value="static member GetInstanceView : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.GetInstanceView (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-226">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-226">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-227">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-227">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-228">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-228">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-229">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-229">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-230">Ruft den Status einer virtuellen Maschine aus einer VM-Skalierungsgruppe ab.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-230">Gets the status of a virtual machine from a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetInstanceViewAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView&gt; GetInstanceViewAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView&gt; GetInstanceViewAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.GetInstanceViewAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetInstanceViewAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.GetInstanceViewAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;GetInstanceViewAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-231">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-231">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-232">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-232">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-233">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-233">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-234">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-234">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ef6cd-235">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-235">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-236">Ruft den Status einer virtuellen Maschine aus einer VM-Skalierungsgruppe ab.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-236">Gets the status of a virtual machine from a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt; List (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string virtualMachineScaleSetName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt; odataQuery = null, string select = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt; List(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string virtualMachineScaleSetName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt; odataQuery, string select) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.List(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM},System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, virtualMachineScaleSetName As String, Optional odataQuery As ODataQuery(Of VirtualMachineScaleSetVM) = null, Optional select As String = null) As IPage(Of VirtualMachineScaleSetVM)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt; * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.List (operations, resourceGroupName, virtualMachineScaleSetName, odataQuery, select)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;" />
        <Parameter Name="select" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-237">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-237">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-238">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-238">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="ef6cd-239">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-239">The name of the VM scale set.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="ef6cd-240">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-240">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="ef6cd-241">Die Listenparameter.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-241">The list parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-242">Ruft eine Liste aller virtuellen Computer in einer VM-Sets ab.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-242">Gets a list of all virtual machines in a VM scale sets.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string virtualMachineScaleSetName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt; odataQuery = null, string select = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string virtualMachineScaleSetName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt; odataQuery, string select, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.ListAsync (operations, resourceGroupName, virtualMachineScaleSetName, odataQuery, select, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;ListAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-243">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-243">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-244">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-244">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="ef6cd-245">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-245">The name of the VM scale set.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="ef6cd-246">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-246">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="ef6cd-247">Die Listenparameter.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-247">The list parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ef6cd-248">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-248">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-249">Ruft eine Liste aller virtuellen Computer in einer VM-Sets ab.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-249">Gets a list of all virtual machines in a VM scale sets.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt; ListNext (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt; ListNext(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.ListNext(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IVirtualMachineScaleSetVMsOperations, nextPageLink As String) As IPage(Of VirtualMachineScaleSetVM)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-250">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-250">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="ef6cd-251">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-251">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-252">Ruft eine Liste aller virtuellen Computer in einer VM-Sets ab.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-252">Gets a list of all virtual machines in a VM scale sets.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;ListNextAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-253">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-253">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="ef6cd-254">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-254">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ef6cd-255">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-255">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-256">Ruft eine Liste aller virtuellen Computer in einer VM-Sets ab.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-256">Gets a list of all virtual machines in a VM scale sets.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PowerOff">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse PowerOff (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse PowerOff(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.PowerOff(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PowerOff (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member PowerOff : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.PowerOff (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-257">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-257">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-258">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-258">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-259">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-259">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-260">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-260">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-261">(Beenden) eine virtuelle Maschine in einer VM Scale Set zum ausschalten.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-261">Power off (stop) a virtual machine in a VM scale set.</span></span> <span data-ttu-id="ef6cd-262">Beachten Sie, dass Ressourcen immer noch angeschlossen sind, und Sie für die Ressourcen in Rechnung gestellt abrufen werden.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-262">Note that resources are still attached and you are getting charged for the resources.</span></span> <span data-ttu-id="ef6cd-263">Stattdessen verwenden freigeben, um Ressourcen freizugeben und Gebühren zu vermeiden.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-263">Instead, use deallocate to release resources and avoid charges.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PowerOffAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; PowerOffAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; PowerOffAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.PowerOffAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PowerOffAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.PowerOffAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;PowerOffAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-264">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-264">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-265">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-265">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-266">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-266">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-267">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-267">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ef6cd-268">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-268">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-269">(Beenden) eine virtuelle Maschine in einer VM Scale Set zum ausschalten.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-269">Power off (stop) a virtual machine in a VM scale set.</span></span> <span data-ttu-id="ef6cd-270">Beachten Sie, dass Ressourcen immer noch angeschlossen sind, und Sie für die Ressourcen in Rechnung gestellt abrufen werden.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-270">Note that resources are still attached and you are getting charged for the resources.</span></span> <span data-ttu-id="ef6cd-271">Stattdessen verwenden freigeben, um Ressourcen freizugeben und Gebühren zu vermeiden.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-271">Instead, use deallocate to release resources and avoid charges.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reimage">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Reimage (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Reimage(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.Reimage(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Reimage (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Reimage : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.Reimage (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-272">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-272">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-273">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-273">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-274">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-274">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-275">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-275">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-276">Reimages (upgrade des Betriebssystems) legen Sie eine bestimmte virtuelle Maschine in einer VM-skalieren.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-276">Reimages (upgrade the operating system) a specific virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReimageAll">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse ReimageAll (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse ReimageAll(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.ReimageAll(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ReimageAll (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member ReimageAll : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.ReimageAll (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-277">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-277">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-278">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-278">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-279">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-279">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-280">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-280">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-281">Können Sie alle Datenträger (Datenträger einschließlich) ein image in der Instanz von einer VM Scale set.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-281">Allows you to re-image all the disks ( including data disks ) in the a VM scale set instance.</span></span> <span data-ttu-id="ef6cd-282">Dieser Vorgang wird nur für verwaltete Datenträger unterstützt.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-282">This operation is only supported for managed disks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReimageAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; ReimageAllAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; ReimageAllAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.ReimageAllAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ReimageAllAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.ReimageAllAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;ReimageAllAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-283">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-283">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-284">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-284">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-285">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-285">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-286">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-286">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ef6cd-287">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-287">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-288">Können Sie alle Datenträger (Datenträger einschließlich) ein image in der Instanz von einer VM Scale set.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-288">Allows you to re-image all the disks ( including data disks ) in the a VM scale set instance.</span></span> <span data-ttu-id="ef6cd-289">Dieser Vorgang wird nur für verwaltete Datenträger unterstützt.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-289">This operation is only supported for managed disks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReimageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; ReimageAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; ReimageAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.ReimageAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ReimageAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.ReimageAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;ReimageAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-290">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-290">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-291">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-291">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-292">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-292">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-293">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-293">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ef6cd-294">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-294">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-295">Reimages (upgrade des Betriebssystems) legen Sie eine bestimmte virtuelle Maschine in einer VM-skalieren.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-295">Reimages (upgrade the operating system) a specific virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Restart">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Restart (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Restart(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.Restart(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Restart (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Restart : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.Restart (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-296">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-296">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-297">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-297">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-298">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-298">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-299">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-299">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-300">Startet einen virtuellen Computer in einer VM-Skalierungsgruppe neu.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-300">Restarts a virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; RestartAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; RestartAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.RestartAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RestartAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.RestartAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;RestartAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-301">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-301">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-302">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-302">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-303">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-303">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-304">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-304">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ef6cd-305">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-305">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-306">Startet einen virtuellen Computer in einer VM-Skalierungsgruppe neu.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-306">Restarts a virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Start (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Start(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.Start(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Start (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Start : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.Start (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-307">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-307">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-308">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-308">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-309">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-309">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-310">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-310">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-311">Startet einen virtuellen Computer in einer VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-311">Starts a virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; StartAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; StartAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.StartAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StartAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.StartAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;StartAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef6cd-312">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-312">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef6cd-313">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-313">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="ef6cd-314">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-314">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="ef6cd-315">Die Instanz-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-315">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ef6cd-316">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-316">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef6cd-317">Startet einen virtuellen Computer in einer VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="ef6cd-317">Starts a virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>