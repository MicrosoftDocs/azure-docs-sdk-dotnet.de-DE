<Type Name="VirtualMachineScaleSetExtensionsOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualMachineScaleSetExtensionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualMachineScaleSetExtensionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualMachineScaleSetExtensionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetExtensionsOperationsExtensions = class" />
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
            <span data-ttu-id="b8e7a-101">Erweiterungsmethoden für VirtualMachineScaleSetExtensionsOperations.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-101">Extension methods for VirtualMachineScaleSetExtensionsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension BeginCreateOrUpdate (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations operations, string resourceGroupName, string vmScaleSetName, string vmssExtensionName, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension extensionParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension BeginCreateOrUpdate(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations operations, string resourceGroupName, string vmScaleSetName, string vmssExtensionName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension extensionParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IVirtualMachineScaleSetExtensionsOperations, resourceGroupName As String, vmScaleSetName As String, vmssExtensionName As String, extensionParameters As VirtualMachineScaleSetExtension) As VirtualMachineScaleSetExtension" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations * string * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, vmScaleSetName, vmssExtensionName, extensionParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="vmssExtensionName" Type="System.String" />
        <Parameter Name="extensionParameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b8e7a-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b8e7a-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-103">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="b8e7a-104">Der Name der VM Skala festlegen, in dem die Erweiterung verwendet werden soll, erstellen oder aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-104">The name of the VM scale set where the extension should be create or updated.</span></span>
            </param>
        <param name="vmssExtensionName">
            <span data-ttu-id="b8e7a-105">Legen Sie der Namen der VM Skala Erweiterung.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-105">The name of the VM scale set extension.</span></span>
            </param>
        <param name="extensionParameters">
            <span data-ttu-id="b8e7a-106">Parameter und der VM erstellen Skala angegeben festgelegt Betrieb der Erweiterung.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-106">Parameters supplied to the Create VM scale set Extension operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b8e7a-107">Der Vorgang zum Erstellen oder Aktualisieren einer Erweiterungs.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-107">The operation to create or update an extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations operations, string resourceGroupName, string vmScaleSetName, string vmssExtensionName, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension extensionParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations operations, string resourceGroupName, string vmScaleSetName, string vmssExtensionName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension extensionParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations * string * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, vmScaleSetName, vmssExtensionName, extensionParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="vmssExtensionName" Type="System.String" />
        <Parameter Name="extensionParameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b8e7a-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b8e7a-109">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-109">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="b8e7a-110">Der Name der VM Skala festlegen, in dem die Erweiterung verwendet werden soll, erstellen oder aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-110">The name of the VM scale set where the extension should be create or updated.</span></span>
            </param>
        <param name="vmssExtensionName">
            <span data-ttu-id="b8e7a-111">Legen Sie der Namen der VM Skala Erweiterung.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-111">The name of the VM scale set extension.</span></span>
            </param>
        <param name="extensionParameters">
            <span data-ttu-id="b8e7a-112">Parameter und der VM erstellen Skala angegeben festgelegt Betrieb der Erweiterung.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-112">Parameters supplied to the Create VM scale set Extension operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b8e7a-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b8e7a-114">Der Vorgang zum Erstellen oder Aktualisieren einer Erweiterungs.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-114">The operation to create or update an extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDelete (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations operations, string resourceGroupName, string vmScaleSetName, string vmssExtensionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDelete(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations operations, string resourceGroupName, string vmScaleSetName, string vmssExtensionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As IVirtualMachineScaleSetExtensionsOperations, resourceGroupName As String, vmScaleSetName As String, vmssExtensionName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions.BeginDelete (operations, resourceGroupName, vmScaleSetName, vmssExtensionName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="vmssExtensionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b8e7a-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b8e7a-116">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-116">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="b8e7a-117">Der Name des der VM-Skalierungsgruppe, in dem die Erweiterung gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-117">The name of the VM scale set where the extension should be deleted.</span></span>
            </param>
        <param name="vmssExtensionName">
            <span data-ttu-id="b8e7a-118">Legen Sie der Namen der VM Skala Erweiterung.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-118">The name of the VM scale set extension.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b8e7a-119">Der Vorgang zum Löschen der Erweiterungs.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-119">The operation to delete the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations operations, string resourceGroupName, string vmScaleSetName, string vmssExtensionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations operations, string resourceGroupName, string vmScaleSetName, string vmssExtensionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, vmScaleSetName, vmssExtensionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="vmssExtensionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b8e7a-120">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-120">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b8e7a-121">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-121">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="b8e7a-122">Der Name des der VM-Skalierungsgruppe, in dem die Erweiterung gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-122">The name of the VM scale set where the extension should be deleted.</span></span>
            </param>
        <param name="vmssExtensionName">
            <span data-ttu-id="b8e7a-123">Legen Sie der Namen der VM Skala Erweiterung.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-123">The name of the VM scale set extension.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b8e7a-124">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b8e7a-125">Der Vorgang zum Löschen der Erweiterungs.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-125">The operation to delete the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension CreateOrUpdate (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations operations, string resourceGroupName, string vmScaleSetName, string vmssExtensionName, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension extensionParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension CreateOrUpdate(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations operations, string resourceGroupName, string vmScaleSetName, string vmssExtensionName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension extensionParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IVirtualMachineScaleSetExtensionsOperations, resourceGroupName As String, vmScaleSetName As String, vmssExtensionName As String, extensionParameters As VirtualMachineScaleSetExtension) As VirtualMachineScaleSetExtension" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations * string * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, vmScaleSetName, vmssExtensionName, extensionParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="vmssExtensionName" Type="System.String" />
        <Parameter Name="extensionParameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b8e7a-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b8e7a-127">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-127">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="b8e7a-128">Der Name der VM Skala festlegen, in dem die Erweiterung verwendet werden soll, erstellen oder aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-128">The name of the VM scale set where the extension should be create or updated.</span></span>
            </param>
        <param name="vmssExtensionName">
            <span data-ttu-id="b8e7a-129">Legen Sie der Namen der VM Skala Erweiterung.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-129">The name of the VM scale set extension.</span></span>
            </param>
        <param name="extensionParameters">
            <span data-ttu-id="b8e7a-130">Parameter und der VM erstellen Skala angegeben festgelegt Betrieb der Erweiterung.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-130">Parameters supplied to the Create VM scale set Extension operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b8e7a-131">Der Vorgang zum Erstellen oder Aktualisieren einer Erweiterungs.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-131">The operation to create or update an extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations operations, string resourceGroupName, string vmScaleSetName, string vmssExtensionName, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension extensionParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations operations, string resourceGroupName, string vmScaleSetName, string vmssExtensionName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension extensionParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations * string * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, vmScaleSetName, vmssExtensionName, extensionParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="vmssExtensionName" Type="System.String" />
        <Parameter Name="extensionParameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b8e7a-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b8e7a-133">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-133">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="b8e7a-134">Der Name der VM Skala festlegen, in dem die Erweiterung verwendet werden soll, erstellen oder aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-134">The name of the VM scale set where the extension should be create or updated.</span></span>
            </param>
        <param name="vmssExtensionName">
            <span data-ttu-id="b8e7a-135">Legen Sie der Namen der VM Skala Erweiterung.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-135">The name of the VM scale set extension.</span></span>
            </param>
        <param name="extensionParameters">
            <span data-ttu-id="b8e7a-136">Parameter und der VM erstellen Skala angegeben festgelegt Betrieb der Erweiterung.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-136">Parameters supplied to the Create VM scale set Extension operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b8e7a-137">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b8e7a-138">Der Vorgang zum Erstellen oder Aktualisieren einer Erweiterungs.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-138">The operation to create or update an extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Delete (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations operations, string resourceGroupName, string vmScaleSetName, string vmssExtensionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Delete(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations operations, string resourceGroupName, string vmScaleSetName, string vmssExtensionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions.Delete(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IVirtualMachineScaleSetExtensionsOperations, resourceGroupName As String, vmScaleSetName As String, vmssExtensionName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions.Delete (operations, resourceGroupName, vmScaleSetName, vmssExtensionName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="vmssExtensionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b8e7a-139">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-139">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b8e7a-140">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-140">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="b8e7a-141">Der Name des der VM-Skalierungsgruppe, in dem die Erweiterung gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-141">The name of the VM scale set where the extension should be deleted.</span></span>
            </param>
        <param name="vmssExtensionName">
            <span data-ttu-id="b8e7a-142">Legen Sie der Namen der VM Skala Erweiterung.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-142">The name of the VM scale set extension.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b8e7a-143">Der Vorgang zum Löschen der Erweiterungs.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-143">The operation to delete the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations operations, string resourceGroupName, string vmScaleSetName, string vmssExtensionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations operations, string resourceGroupName, string vmScaleSetName, string vmssExtensionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions.DeleteAsync (operations, resourceGroupName, vmScaleSetName, vmssExtensionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="vmssExtensionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b8e7a-144">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b8e7a-145">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-145">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="b8e7a-146">Der Name des der VM-Skalierungsgruppe, in dem die Erweiterung gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-146">The name of the VM scale set where the extension should be deleted.</span></span>
            </param>
        <param name="vmssExtensionName">
            <span data-ttu-id="b8e7a-147">Legen Sie der Namen der VM Skala Erweiterung.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-147">The name of the VM scale set extension.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b8e7a-148">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b8e7a-149">Der Vorgang zum Löschen der Erweiterungs.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-149">The operation to delete the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension Get (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations operations, string resourceGroupName, string vmScaleSetName, string vmssExtensionName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension Get(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations operations, string resourceGroupName, string vmScaleSetName, string vmssExtensionName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions.Get(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IVirtualMachineScaleSetExtensionsOperations, resourceGroupName As String, vmScaleSetName As String, vmssExtensionName As String, Optional expand As String = null) As VirtualMachineScaleSetExtension" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions.Get (operations, resourceGroupName, vmScaleSetName, vmssExtensionName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="vmssExtensionName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b8e7a-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b8e7a-151">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-151">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="b8e7a-152">Der Name der VM Skala festgelegt, die die Erweiterung enthält.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-152">The name of the VM scale set containing the extension.</span></span>
            </param>
        <param name="vmssExtensionName">
            <span data-ttu-id="b8e7a-153">Legen Sie der Namen der VM Skala Erweiterung.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-153">The name of the VM scale set extension.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="b8e7a-154">Der erweitern-Ausdruck auf die Operation angewendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-154">The expand expression to apply on the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b8e7a-155">Der Vorgang die Erweiterung abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-155">The operation to get the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt; GetAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations operations, string resourceGroupName, string vmScaleSetName, string vmssExtensionName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt; GetAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations operations, string resourceGroupName, string vmScaleSetName, string vmssExtensionName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions.GetAsync (operations, resourceGroupName, vmScaleSetName, vmssExtensionName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="vmssExtensionName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b8e7a-156">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-156">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b8e7a-157">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-157">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="b8e7a-158">Der Name der VM Skala festgelegt, die die Erweiterung enthält.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-158">The name of the VM scale set containing the extension.</span></span>
            </param>
        <param name="vmssExtensionName">
            <span data-ttu-id="b8e7a-159">Legen Sie der Namen der VM Skala Erweiterung.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-159">The name of the VM scale set extension.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="b8e7a-160">Der erweitern-Ausdruck auf die Operation angewendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-160">The expand expression to apply on the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b8e7a-161">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b8e7a-162">Der Vorgang die Erweiterung abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-162">The operation to get the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt; List (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations operations, string resourceGroupName, string vmScaleSetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt; List(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations operations, string resourceGroupName, string vmScaleSetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions.List(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IVirtualMachineScaleSetExtensionsOperations, resourceGroupName As String, vmScaleSetName As String) As IPage(Of VirtualMachineScaleSetExtension)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions.List (operations, resourceGroupName, vmScaleSetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b8e7a-163">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b8e7a-164">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-164">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="b8e7a-165">Der Name der VM Skala festgelegt, die die Erweiterung enthält.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-165">The name of the VM scale set containing the extension.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b8e7a-166">Ruft eine Liste aller Erweiterungen in einer VM-Skalierungsgruppe ab.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-166">Gets a list of all extensions in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations operations, string resourceGroupName, string vmScaleSetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations operations, string resourceGroupName, string vmScaleSetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions.ListAsync (operations, resourceGroupName, vmScaleSetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions/&lt;ListAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b8e7a-167">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-167">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b8e7a-168">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-168">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="b8e7a-169">Der Name der VM Skala festgelegt, die die Erweiterung enthält.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-169">The name of the VM scale set containing the extension.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b8e7a-170">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b8e7a-171">Ruft eine Liste aller Erweiterungen in einer VM-Skalierungsgruppe ab.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-171">Gets a list of all extensions in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt; ListNext (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt; ListNext(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions.ListNext(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IVirtualMachineScaleSetExtensionsOperations, nextPageLink As String) As IPage(Of VirtualMachineScaleSetExtension)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b8e7a-172">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-172">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="b8e7a-173">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-173">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b8e7a-174">Ruft eine Liste aller Erweiterungen in einer VM-Skalierungsgruppe ab.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-174">Gets a list of all extensions in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetExtensionsOperationsExtensions/&lt;ListNextAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b8e7a-175">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-175">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="b8e7a-176">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-176">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b8e7a-177">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b8e7a-178">Ruft eine Liste aller Erweiterungen in einer VM-Skalierungsgruppe ab.</span><span class="sxs-lookup"><span data-stu-id="b8e7a-178">Gets a list of all extensions in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>