<Type Name="VirtualMachineExtensionsOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtensionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualMachineExtensionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualMachineExtensionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtensionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualMachineExtensionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualMachineExtensionsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f6350-101">Erweiterungsmethoden für VirtualMachineExtensionsOperations.</span><span class="sxs-lookup"><span data-stu-id="f6350-101">Extension methods for VirtualMachineExtensionsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner extensionParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner extensionParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtensionsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionsOperations * string * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtensionsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, vmName, vmExtensionName, extensionParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtensionsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="vmExtensionName" Type="System.String" />
        <Parameter Name="extensionParameters" Type="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f6350-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f6350-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f6350-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="f6350-103">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="f6350-104">Der Name des virtuellen Computers, auf dem die Erweiterung verwendet werden soll, erstellen oder aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="f6350-104">The name of the virtual machine where the extension should be create or updated.</span></span>
            </param>
        <param name="vmExtensionName">
            <span data-ttu-id="f6350-105">Der Name der Erweiterung des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="f6350-105">The name of the virtual machine extension.</span></span>
            </param>
        <param name="extensionParameters">
            <span data-ttu-id="f6350-106">Parameter für die Erweiterung zum Erstellen eines virtuellen Computers zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="f6350-106">Parameters supplied to the Create Virtual Machine Extension operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f6350-107">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f6350-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f6350-108">Der Vorgang zum Erstellen oder aktualisieren Sie die Erweiterung.</span><span class="sxs-lookup"><span data-stu-id="f6350-108">The operation to create or update the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtensionsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtensionsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, vmName, vmExtensionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtensionsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="vmExtensionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f6350-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f6350-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f6350-110">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="f6350-110">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="f6350-111">Der Name des virtuellen Computers, auf dem die Erweiterung gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f6350-111">The name of the virtual machine where the extension should be deleted.</span></span>
            </param>
        <param name="vmExtensionName">
            <span data-ttu-id="f6350-112">Der Name der Erweiterung des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="f6350-112">The name of the virtual machine extension.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f6350-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f6350-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f6350-114">Der Vorgang zum Löschen der Erweiterungs.</span><span class="sxs-lookup"><span data-stu-id="f6350-114">The operation to delete the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner extensionParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner extensionParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtensionsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionsOperations * string * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtensionsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, vmName, vmExtensionName, extensionParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtensionsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="vmExtensionName" Type="System.String" />
        <Parameter Name="extensionParameters" Type="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f6350-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f6350-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f6350-116">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="f6350-116">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="f6350-117">Der Name des virtuellen Computers, auf dem die Erweiterung verwendet werden soll, erstellen oder aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="f6350-117">The name of the virtual machine where the extension should be create or updated.</span></span>
            </param>
        <param name="vmExtensionName">
            <span data-ttu-id="f6350-118">Der Name der Erweiterung des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="f6350-118">The name of the virtual machine extension.</span></span>
            </param>
        <param name="extensionParameters">
            <span data-ttu-id="f6350-119">Parameter für die Erweiterung zum Erstellen eines virtuellen Computers zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="f6350-119">Parameters supplied to the Create Virtual Machine Extension operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f6350-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f6350-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f6350-121">Der Vorgang zum Erstellen oder aktualisieren Sie die Erweiterung.</span><span class="sxs-lookup"><span data-stu-id="f6350-121">The operation to create or update the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeleteAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeleteAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtensionsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtensionsOperationsExtensions.DeleteAsync (operations, resourceGroupName, vmName, vmExtensionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtensionsOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="vmExtensionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f6350-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f6350-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f6350-123">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="f6350-123">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="f6350-124">Der Name des virtuellen Computers, auf dem die Erweiterung gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f6350-124">The name of the virtual machine where the extension should be deleted.</span></span>
            </param>
        <param name="vmExtensionName">
            <span data-ttu-id="f6350-125">Der Name der Erweiterung des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="f6350-125">The name of the virtual machine extension.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f6350-126">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f6350-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f6350-127">Der Vorgang zum Löschen der Erweiterungs.</span><span class="sxs-lookup"><span data-stu-id="f6350-127">The operation to delete the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner&gt; GetAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner&gt; GetAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtensionsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtensionsOperationsExtensions.GetAsync (operations, resourceGroupName, vmName, vmExtensionName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtensionsOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="vmExtensionName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f6350-128">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f6350-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f6350-129">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="f6350-129">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="f6350-130">Der Name des virtuellen Computers an, die die Erweiterung enthält.</span><span class="sxs-lookup"><span data-stu-id="f6350-130">The name of the virtual machine containing the extension.</span></span>
            </param>
        <param name="vmExtensionName">
            <span data-ttu-id="f6350-131">Der Name der Erweiterung des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="f6350-131">The name of the virtual machine extension.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="f6350-132">Der erweitern-Ausdruck auf die Operation angewendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="f6350-132">The expand expression to apply on the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f6350-133">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f6350-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f6350-134">Der Vorgang die Erweiterung abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="f6350-134">The operation to get the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>