<Type Name="IotHubResourceOperationsExtensions" FullName="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class IotHubResourceOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit IotHubResourceOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module IotHubResourceOperationsExtensions" />
  <TypeSignature Language="F#" Value="type IotHubResourceOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="617c9-101">Erweiterungsmethoden für IotHubResourceOperations.</span><span class="sxs-lookup"><span data-stu-id="617c9-101">Extension methods for IotHubResourceOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.IotHubDescription BeginCreateOrUpdate (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.IotHub.Models.IotHubDescription iotHubDescription, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.IotHubDescription BeginCreateOrUpdate(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.IotHub.Models.IotHubDescription iotHubDescription, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.IotHubDescription,System.String)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * Microsoft.Azure.Management.IotHub.Models.IotHubDescription * string -&gt; Microsoft.Azure.Management.IotHub.Models.IotHubDescription" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, resourceName, iotHubDescription, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.IotHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="iotHubDescription" Type="Microsoft.Azure.Management.IotHub.Models.IotHubDescription" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-103">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-103">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-104">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-104">The name of the IoT hub.</span></span>
            </param>
        <param name="iotHubDescription">
            <span data-ttu-id="617c9-105">Der IoT Hub-Metadaten und Sicherheitsmetadaten.</span><span class="sxs-lookup"><span data-stu-id="617c9-105">The IoT hub metadata and security metadata.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="617c9-106">ETag der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-106">ETag of the IoT Hub.</span></span> <span data-ttu-id="617c9-107">Geben Sie zum Erstellen einer neuen IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-107">Do not specify for creating a brand new IoT Hub.</span></span>
            <span data-ttu-id="617c9-108">Zum Aktualisieren eines vorhandenen IoT Hub erforderlich.</span><span class="sxs-lookup"><span data-stu-id="617c9-108">Required to update an existing IoT Hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-109">Erstellen Sie oder aktualisieren Sie die Metadaten eines IoT Hubs.</span><span class="sxs-lookup"><span data-stu-id="617c9-109">Create or update the metadata of an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-110">Erstellen Sie oder aktualisieren Sie die Metadaten eines Iot Hubs.</span><span class="sxs-lookup"><span data-stu-id="617c9-110">Create or update the metadata of an Iot hub.</span></span> <span data-ttu-id="617c9-111">Zum Ändern einer Eigenschaft das übliche Muster ist die IoT Hub-Metadaten und Sicherheitsmetadaten abzurufen, und kombinieren sie Sie dann die geänderte Werte in einen neuen Text IoT Hub zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="617c9-111">The usual pattern to modify a property is to retrieve the IoT hub metadata and security metadata, and then combine them with the modified values in a new body to update the IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.IotHub.Models.IotHubDescription iotHubDescription, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.IotHub.Models.IotHubDescription iotHubDescription, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.IotHubDescription,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * Microsoft.Azure.Management.IotHub.Models.IotHubDescription * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, resourceName, iotHubDescription, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="iotHubDescription" Type="Microsoft.Azure.Management.IotHub.Models.IotHubDescription" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-112">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-112">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-113">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-113">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-114">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-114">The name of the IoT hub.</span></span>
            </param>
        <param name="iotHubDescription">
            <span data-ttu-id="617c9-115">Der IoT Hub-Metadaten und Sicherheitsmetadaten.</span><span class="sxs-lookup"><span data-stu-id="617c9-115">The IoT hub metadata and security metadata.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="617c9-116">ETag der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-116">ETag of the IoT Hub.</span></span> <span data-ttu-id="617c9-117">Geben Sie zum Erstellen einer neuen IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-117">Do not specify for creating a brand new IoT Hub.</span></span>
            <span data-ttu-id="617c9-118">Zum Aktualisieren eines vorhandenen IoT Hub erforderlich.</span><span class="sxs-lookup"><span data-stu-id="617c9-118">Required to update an existing IoT Hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="617c9-119">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="617c9-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-120">Erstellen Sie oder aktualisieren Sie die Metadaten eines IoT Hubs.</span><span class="sxs-lookup"><span data-stu-id="617c9-120">Create or update the metadata of an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-121">Erstellen Sie oder aktualisieren Sie die Metadaten eines Iot Hubs.</span><span class="sxs-lookup"><span data-stu-id="617c9-121">Create or update the metadata of an Iot hub.</span></span> <span data-ttu-id="617c9-122">Zum Ändern einer Eigenschaft das übliche Muster ist die IoT Hub-Metadaten und Sicherheitsmetadaten abzurufen, und kombinieren sie Sie dann die geänderte Werte in einen neuen Text IoT Hub zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="617c9-122">The usual pattern to modify a property is to retrieve the IoT hub metadata and security metadata, and then combine them with the modified values in a new body to update the IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static object BeginDelete (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object BeginDelete(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.BeginDelete(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String) As Object" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string -&gt; obj" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.BeginDelete (operations, resourceGroupName, resourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-124">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-124">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-125">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-125">The name of the IoT hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-126">Löschen Sie einen IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-126">Delete an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-127">Löschen Sie einen IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-127">Delete an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; BeginDeleteAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; BeginDeleteAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, resourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;BeginDeleteAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-128">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-129">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-129">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-130">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-130">The name of the IoT hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="617c9-131">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="617c9-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-132">Löschen Sie einen IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-132">Delete an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-133">Löschen Sie einen IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-133">Delete an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo CheckNameAvailability (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, Microsoft.Azure.Management.IotHub.Models.OperationInputs operationInputs);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo CheckNameAvailability(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, class Microsoft.Azure.Management.IotHub.Models.OperationInputs operationInputs) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.CheckNameAvailability(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,Microsoft.Azure.Management.IotHub.Models.OperationInputs)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailability : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * Microsoft.Azure.Management.IotHub.Models.OperationInputs -&gt; Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.CheckNameAvailability (operations, operationInputs)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="operationInputs" Type="Microsoft.Azure.Management.IotHub.Models.OperationInputs" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-134">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-134">The operations group for this extension method.</span></span>
            </param>
        <param name="operationInputs">
            <span data-ttu-id="617c9-135">Legen Sie den Namensparameter in der Struktur OperationInputs auf den Namen des IoT Hub zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="617c9-135">Set the name parameter in the OperationInputs structure to the name of the IoT hub to check.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-136">Überprüfen Sie, ob ein IoT Hub-Name verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="617c9-136">Check if an IoT hub name is available.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-137">Überprüfen Sie, ob ein IoT Hub-Name verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="617c9-137">Check if an IoT hub name is available.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo&gt; CheckNameAvailabilityAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, Microsoft.Azure.Management.IotHub.Models.OperationInputs operationInputs, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo&gt; CheckNameAvailabilityAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, class Microsoft.Azure.Management.IotHub.Models.OperationInputs operationInputs, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.CheckNameAvailabilityAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,Microsoft.Azure.Management.IotHub.Models.OperationInputs,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailabilityAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * Microsoft.Azure.Management.IotHub.Models.OperationInputs * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.CheckNameAvailabilityAsync (operations, operationInputs, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;CheckNameAvailabilityAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="operationInputs" Type="Microsoft.Azure.Management.IotHub.Models.OperationInputs" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-138">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-138">The operations group for this extension method.</span></span>
            </param>
        <param name="operationInputs">
            <span data-ttu-id="617c9-139">Legen Sie den Namensparameter in der Struktur OperationInputs auf den Namen des IoT Hub zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="617c9-139">Set the name parameter in the OperationInputs structure to the name of the IoT hub to check.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="617c9-140">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="617c9-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-141">Überprüfen Sie, ob ein IoT Hub-Name verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="617c9-141">Check if an IoT hub name is available.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-142">Überprüfen Sie, ob ein IoT Hub-Name verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="617c9-142">Check if an IoT hub name is available.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHubConsumerGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo CreateEventHubConsumerGroup (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo CreateEventHubConsumerGroup(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.CreateEventHubConsumerGroup(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateEventHubConsumerGroup (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String, eventHubEndpointName As String, name As String) As EventHubConsumerGroupInfo" />
      <MemberSignature Language="F#" Value="static member CreateEventHubConsumerGroup : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * string * string -&gt; Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.CreateEventHubConsumerGroup (operations, resourceGroupName, resourceName, eventHubEndpointName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="eventHubEndpointName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-144">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-144">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-145">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-145">The name of the IoT hub.</span></span>
            </param>
        <param name="eventHubEndpointName">
            <span data-ttu-id="617c9-146">Der Name des Endpunkts Event Hub-kompatiblen IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-146">The name of the Event Hub-compatible endpoint in the IoT hub.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="617c9-147">Der Name der Gruppe "Consumer" hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="617c9-147">The name of the consumer group to add.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-148">Hinzufügen einer consumergruppe an einen Event Hub-kompatiblen Endpunkt in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-148">Add a consumer group to an Event Hub-compatible endpoint in an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-149">Hinzufügen einer consumergruppe an einen Event Hub-kompatiblen Endpunkt in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-149">Add a consumer group to an Event Hub-compatible endpoint in an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHubConsumerGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo&gt; CreateEventHubConsumerGroupAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo&gt; CreateEventHubConsumerGroupAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.CreateEventHubConsumerGroupAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateEventHubConsumerGroupAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.CreateEventHubConsumerGroupAsync (operations, resourceGroupName, resourceName, eventHubEndpointName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;CreateEventHubConsumerGroupAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="eventHubEndpointName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-151">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-151">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-152">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-152">The name of the IoT hub.</span></span>
            </param>
        <param name="eventHubEndpointName">
            <span data-ttu-id="617c9-153">Der Name des Endpunkts Event Hub-kompatiblen IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-153">The name of the Event Hub-compatible endpoint in the IoT hub.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="617c9-154">Der Name der Gruppe "Consumer" hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="617c9-154">The name of the consumer group to add.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="617c9-155">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="617c9-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-156">Hinzufügen einer consumergruppe an einen Event Hub-kompatiblen Endpunkt in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-156">Add a consumer group to an Event Hub-compatible endpoint in an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-157">Hinzufügen einer consumergruppe an einen Event Hub-kompatiblen Endpunkt in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-157">Add a consumer group to an Event Hub-compatible endpoint in an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.IotHubDescription CreateOrUpdate (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.IotHub.Models.IotHubDescription iotHubDescription, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.IotHubDescription CreateOrUpdate(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.IotHub.Models.IotHubDescription iotHubDescription, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.IotHubDescription,System.String)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * Microsoft.Azure.Management.IotHub.Models.IotHubDescription * string -&gt; Microsoft.Azure.Management.IotHub.Models.IotHubDescription" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, resourceName, iotHubDescription, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.IotHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="iotHubDescription" Type="Microsoft.Azure.Management.IotHub.Models.IotHubDescription" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-159">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-159">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-160">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-160">The name of the IoT hub.</span></span>
            </param>
        <param name="iotHubDescription">
            <span data-ttu-id="617c9-161">Der IoT Hub-Metadaten und Sicherheitsmetadaten.</span><span class="sxs-lookup"><span data-stu-id="617c9-161">The IoT hub metadata and security metadata.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="617c9-162">ETag der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-162">ETag of the IoT Hub.</span></span> <span data-ttu-id="617c9-163">Geben Sie zum Erstellen einer neuen IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-163">Do not specify for creating a brand new IoT Hub.</span></span>
            <span data-ttu-id="617c9-164">Zum Aktualisieren eines vorhandenen IoT Hub erforderlich.</span><span class="sxs-lookup"><span data-stu-id="617c9-164">Required to update an existing IoT Hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-165">Erstellen Sie oder aktualisieren Sie die Metadaten eines IoT Hubs.</span><span class="sxs-lookup"><span data-stu-id="617c9-165">Create or update the metadata of an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-166">Erstellen Sie oder aktualisieren Sie die Metadaten eines Iot Hubs.</span><span class="sxs-lookup"><span data-stu-id="617c9-166">Create or update the metadata of an Iot hub.</span></span> <span data-ttu-id="617c9-167">Zum Ändern einer Eigenschaft das übliche Muster ist die IoT Hub-Metadaten und Sicherheitsmetadaten abzurufen, und kombinieren sie Sie dann die geänderte Werte in einen neuen Text IoT Hub zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="617c9-167">The usual pattern to modify a property is to retrieve the IoT hub metadata and security metadata, and then combine them with the modified values in a new body to update the IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.IotHub.Models.IotHubDescription iotHubDescription, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.IotHub.Models.IotHubDescription iotHubDescription, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.IotHubDescription,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * Microsoft.Azure.Management.IotHub.Models.IotHubDescription * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, resourceName, iotHubDescription, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="iotHubDescription" Type="Microsoft.Azure.Management.IotHub.Models.IotHubDescription" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-168">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-168">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-169">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-169">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-170">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-170">The name of the IoT hub.</span></span>
            </param>
        <param name="iotHubDescription">
            <span data-ttu-id="617c9-171">Der IoT Hub-Metadaten und Sicherheitsmetadaten.</span><span class="sxs-lookup"><span data-stu-id="617c9-171">The IoT hub metadata and security metadata.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="617c9-172">ETag der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-172">ETag of the IoT Hub.</span></span> <span data-ttu-id="617c9-173">Geben Sie zum Erstellen einer neuen IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-173">Do not specify for creating a brand new IoT Hub.</span></span>
            <span data-ttu-id="617c9-174">Zum Aktualisieren eines vorhandenen IoT Hub erforderlich.</span><span class="sxs-lookup"><span data-stu-id="617c9-174">Required to update an existing IoT Hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="617c9-175">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="617c9-175">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-176">Erstellen Sie oder aktualisieren Sie die Metadaten eines IoT Hubs.</span><span class="sxs-lookup"><span data-stu-id="617c9-176">Create or update the metadata of an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-177">Erstellen Sie oder aktualisieren Sie die Metadaten eines Iot Hubs.</span><span class="sxs-lookup"><span data-stu-id="617c9-177">Create or update the metadata of an Iot hub.</span></span> <span data-ttu-id="617c9-178">Zum Ändern einer Eigenschaft das übliche Muster ist die IoT Hub-Metadaten und Sicherheitsmetadaten abzurufen, und kombinieren sie Sie dann die geänderte Werte in einen neuen Text IoT Hub zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="617c9-178">The usual pattern to modify a property is to retrieve the IoT hub metadata and security metadata, and then combine them with the modified values in a new body to update the IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static object Delete (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object Delete(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.Delete(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String) As Object" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string -&gt; obj" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.Delete (operations, resourceGroupName, resourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-179">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-179">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-180">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-180">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-181">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-181">The name of the IoT hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-182">Löschen Sie einen IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-182">Delete an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-183">Löschen Sie einen IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-183">Delete an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; DeleteAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; DeleteAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.DeleteAsync (operations, resourceGroupName, resourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-184">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-184">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-185">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-185">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-186">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-186">The name of the IoT hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="617c9-187">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="617c9-187">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-188">Löschen Sie einen IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-188">Delete an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-189">Löschen Sie einen IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-189">Delete an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteEventHubConsumerGroup">
      <MemberSignature Language="C#" Value="public static void DeleteEventHubConsumerGroup (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteEventHubConsumerGroup(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.DeleteEventHubConsumerGroup(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteEventHubConsumerGroup (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String, eventHubEndpointName As String, name As String)" />
      <MemberSignature Language="F#" Value="static member DeleteEventHubConsumerGroup : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.DeleteEventHubConsumerGroup (operations, resourceGroupName, resourceName, eventHubEndpointName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="eventHubEndpointName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-190">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-191">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-191">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-192">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-192">The name of the IoT hub.</span></span>
            </param>
        <param name="eventHubEndpointName">
            <span data-ttu-id="617c9-193">Der Name des Endpunkts Event Hub-kompatiblen IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-193">The name of the Event Hub-compatible endpoint in the IoT hub.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="617c9-194">Der Name des zu löschenden consumergruppe.</span><span class="sxs-lookup"><span data-stu-id="617c9-194">The name of the consumer group to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-195">Löschen einer consumergruppe von einem Event Hub-kompatiblen Endpunkt in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-195">Delete a consumer group from an Event Hub-compatible endpoint in an IoT hub.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="617c9-196">Löschen einer consumergruppe von einem Event Hub-kompatiblen Endpunkt in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-196">Delete a consumer group from an Event Hub-compatible endpoint in an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteEventHubConsumerGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteEventHubConsumerGroupAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteEventHubConsumerGroupAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.DeleteEventHubConsumerGroupAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteEventHubConsumerGroupAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.DeleteEventHubConsumerGroupAsync (operations, resourceGroupName, resourceName, eventHubEndpointName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;DeleteEventHubConsumerGroupAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="eventHubEndpointName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-197">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-197">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-198">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-198">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-199">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-199">The name of the IoT hub.</span></span>
            </param>
        <param name="eventHubEndpointName">
            <span data-ttu-id="617c9-200">Der Name des Endpunkts Event Hub-kompatiblen IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-200">The name of the Event Hub-compatible endpoint in the IoT hub.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="617c9-201">Der Name des zu löschenden consumergruppe.</span><span class="sxs-lookup"><span data-stu-id="617c9-201">The name of the consumer group to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="617c9-202">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="617c9-202">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-203">Löschen einer consumergruppe von einem Event Hub-kompatiblen Endpunkt in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-203">Delete a consumer group from an Event Hub-compatible endpoint in an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-204">Löschen einer consumergruppe von einem Event Hub-kompatiblen Endpunkt in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-204">Delete a consumer group from an Event Hub-compatible endpoint in an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportDevices">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.JobResponse ExportDevices (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest exportDevicesParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.JobResponse ExportDevices(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest exportDevicesParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ExportDevices(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ExportDevices (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String, exportDevicesParameters As ExportDevicesRequest) As JobResponse" />
      <MemberSignature Language="F#" Value="static member ExportDevices : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest -&gt; Microsoft.Azure.Management.IotHub.Models.JobResponse" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ExportDevices (operations, resourceGroupName, resourceName, exportDevicesParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.JobResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="exportDevicesParameters" Type="Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-205">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-205">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-206">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-206">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-207">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-207">The name of the IoT hub.</span></span>
            </param>
        <param name="exportDevicesParameters">
            <span data-ttu-id="617c9-208">Die Parameter, mit die den Exportvorgang für Geräte angegeben.</span><span class="sxs-lookup"><span data-stu-id="617c9-208">The parameters that specify the export devices operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-209">Exportiert alle geräteidentitäten in der IoT Hub-Identity-Registrierung in einer Azure-Speicher-Blob-Container.</span><span class="sxs-lookup"><span data-stu-id="617c9-209">Exports all the device identities in the IoT hub identity registry to an Azure Storage blob container.</span></span> <span data-ttu-id="617c9-210">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span><span class="sxs-lookup"><span data-stu-id="617c9-210">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-211">Exportiert alle geräteidentitäten in der IoT Hub-Identity-Registrierung in einer Azure-Speicher-Blob-Container.</span><span class="sxs-lookup"><span data-stu-id="617c9-211">Exports all the device identities in the IoT hub identity registry to an Azure Storage blob container.</span></span> <span data-ttu-id="617c9-212">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span><span class="sxs-lookup"><span data-stu-id="617c9-212">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportDevicesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt; ExportDevicesAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest exportDevicesParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.JobResponse&gt; ExportDevicesAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest exportDevicesParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ExportDevicesAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExportDevicesAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ExportDevicesAsync (operations, resourceGroupName, resourceName, exportDevicesParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;ExportDevicesAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="exportDevicesParameters" Type="Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-213">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-213">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-214">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-214">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-215">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-215">The name of the IoT hub.</span></span>
            </param>
        <param name="exportDevicesParameters">
            <span data-ttu-id="617c9-216">Die Parameter, mit die den Exportvorgang für Geräte angegeben.</span><span class="sxs-lookup"><span data-stu-id="617c9-216">The parameters that specify the export devices operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="617c9-217">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="617c9-217">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-218">Exportiert alle geräteidentitäten in der IoT Hub-Identity-Registrierung in einer Azure-Speicher-Blob-Container.</span><span class="sxs-lookup"><span data-stu-id="617c9-218">Exports all the device identities in the IoT hub identity registry to an Azure Storage blob container.</span></span> <span data-ttu-id="617c9-219">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span><span class="sxs-lookup"><span data-stu-id="617c9-219">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-220">Exportiert alle geräteidentitäten in der IoT Hub-Identity-Registrierung in einer Azure-Speicher-Blob-Container.</span><span class="sxs-lookup"><span data-stu-id="617c9-220">Exports all the device identities in the IoT hub identity registry to an Azure Storage blob container.</span></span> <span data-ttu-id="617c9-221">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span><span class="sxs-lookup"><span data-stu-id="617c9-221">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.IotHubDescription Get (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.IotHubDescription Get(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.Get(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String) As IotHubDescription" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string -&gt; Microsoft.Azure.Management.IotHub.Models.IotHubDescription" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.Get (operations, resourceGroupName, resourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.IotHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-222">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-222">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-223">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-223">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-224">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-224">The name of the IoT hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-225">Abrufen der zugehörigen nicht sicherheitsrelevantes Metadaten eines IoT Hubs.</span><span class="sxs-lookup"><span data-stu-id="617c9-225">Get the non-security related metadata of an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-226">Abrufen der zugehörigen nicht sicherheitsrelevantes Metadaten eines IoT Hubs.</span><span class="sxs-lookup"><span data-stu-id="617c9-226">Get the non-security related metadata of an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt; GetAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt; GetAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetAsync (operations, resourceGroupName, resourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-227">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-227">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-228">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-228">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-229">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-229">The name of the IoT hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="617c9-230">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="617c9-230">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-231">Abrufen der zugehörigen nicht sicherheitsrelevantes Metadaten eines IoT Hubs.</span><span class="sxs-lookup"><span data-stu-id="617c9-231">Get the non-security related metadata of an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-232">Abrufen der zugehörigen nicht sicherheitsrelevantes Metadaten eines IoT Hubs.</span><span class="sxs-lookup"><span data-stu-id="617c9-232">Get the non-security related metadata of an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEventHubConsumerGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo GetEventHubConsumerGroup (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo GetEventHubConsumerGroup(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetEventHubConsumerGroup(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetEventHubConsumerGroup (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String, eventHubEndpointName As String, name As String) As EventHubConsumerGroupInfo" />
      <MemberSignature Language="F#" Value="static member GetEventHubConsumerGroup : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * string * string -&gt; Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetEventHubConsumerGroup (operations, resourceGroupName, resourceName, eventHubEndpointName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="eventHubEndpointName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-233">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-233">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-234">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-234">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-235">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-235">The name of the IoT hub.</span></span>
            </param>
        <param name="eventHubEndpointName">
            <span data-ttu-id="617c9-236">Der Name des Endpunkts Event Hub-kompatiblen IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-236">The name of the Event Hub-compatible endpoint in the IoT hub.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="617c9-237">Der Name des abzurufenden consumergruppe.</span><span class="sxs-lookup"><span data-stu-id="617c9-237">The name of the consumer group to retrieve.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-238">Ruft eine consumergruppe vom Event Hub-kompatibles Gerät-zu-Cloud-Endpunkt für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="617c9-238">Get a consumer group from the Event Hub-compatible device-to-cloud endpoint for an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-239">Ruft eine consumergruppe vom Event Hub-kompatibles Gerät-zu-Cloud-Endpunkt für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="617c9-239">Get a consumer group from the Event Hub-compatible device-to-cloud endpoint for an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEventHubConsumerGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo&gt; GetEventHubConsumerGroupAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo&gt; GetEventHubConsumerGroupAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetEventHubConsumerGroupAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetEventHubConsumerGroupAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetEventHubConsumerGroupAsync (operations, resourceGroupName, resourceName, eventHubEndpointName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;GetEventHubConsumerGroupAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="eventHubEndpointName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-240">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-240">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-241">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-241">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-242">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-242">The name of the IoT hub.</span></span>
            </param>
        <param name="eventHubEndpointName">
            <span data-ttu-id="617c9-243">Der Name des Endpunkts Event Hub-kompatiblen IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-243">The name of the Event Hub-compatible endpoint in the IoT hub.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="617c9-244">Der Name des abzurufenden consumergruppe.</span><span class="sxs-lookup"><span data-stu-id="617c9-244">The name of the consumer group to retrieve.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="617c9-245">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="617c9-245">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-246">Ruft eine consumergruppe vom Event Hub-kompatibles Gerät-zu-Cloud-Endpunkt für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="617c9-246">Get a consumer group from the Event Hub-compatible device-to-cloud endpoint for an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-247">Ruft eine consumergruppe vom Event Hub-kompatibles Gerät-zu-Cloud-Endpunkt für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="617c9-247">Get a consumer group from the Event Hub-compatible device-to-cloud endpoint for an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.JobResponse GetJob (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.JobResponse GetJob(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetJob(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetJob (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String, jobId As String) As JobResponse" />
      <MemberSignature Language="F#" Value="static member GetJob : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * string -&gt; Microsoft.Azure.Management.IotHub.Models.JobResponse" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetJob (operations, resourceGroupName, resourceName, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.JobResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-248">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-248">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-249">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-249">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-250">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-250">The name of the IoT hub.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="617c9-251">Der Auftragsbezeichner.</span><span class="sxs-lookup"><span data-stu-id="617c9-251">The job identifier.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-252">Abrufen von Details eines Auftrags von einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-252">Get the details of a job from an IoT hub.</span></span> <span data-ttu-id="617c9-253">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span><span class="sxs-lookup"><span data-stu-id="617c9-253">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-254">Abrufen von Details eines Auftrags von einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-254">Get the details of a job from an IoT hub.</span></span> <span data-ttu-id="617c9-255">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span><span class="sxs-lookup"><span data-stu-id="617c9-255">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt; GetJobAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string jobId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.JobResponse&gt; GetJobAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetJobAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetJobAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetJobAsync (operations, resourceGroupName, resourceName, jobId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;GetJobAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-256">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-256">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-257">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-257">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-258">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-258">The name of the IoT hub.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="617c9-259">Der Auftragsbezeichner.</span><span class="sxs-lookup"><span data-stu-id="617c9-259">The job identifier.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="617c9-260">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="617c9-260">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-261">Abrufen von Details eines Auftrags von einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-261">Get the details of a job from an IoT hub.</span></span> <span data-ttu-id="617c9-262">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span><span class="sxs-lookup"><span data-stu-id="617c9-262">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-263">Abrufen von Details eines Auftrags von einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-263">Get the details of a job from an IoT hub.</span></span> <span data-ttu-id="617c9-264">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span><span class="sxs-lookup"><span data-stu-id="617c9-264">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeysForKeyName">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule GetKeysForKeyName (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule GetKeysForKeyName(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetKeysForKeyName(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetKeysForKeyName (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String, keyName As String) As SharedAccessSignatureAuthorizationRule" />
      <MemberSignature Language="F#" Value="static member GetKeysForKeyName : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * string -&gt; Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetKeysForKeyName (operations, resourceGroupName, resourceName, keyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-265">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-265">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-266">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-266">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-267">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-267">The name of the IoT hub.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="617c9-268">Der Name der Richtlinie für freigegebenen Zugriff.</span><span class="sxs-lookup"><span data-stu-id="617c9-268">The name of the shared access policy.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-269">Abrufen einer SAS-Richtlinie nach Namen von einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-269">Get a shared access policy by name from an IoT hub.</span></span> <span data-ttu-id="617c9-270">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span><span class="sxs-lookup"><span data-stu-id="617c9-270">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-271">Abrufen einer SAS-Richtlinie nach Namen von einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-271">Get a shared access policy by name from an IoT hub.</span></span> <span data-ttu-id="617c9-272">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span><span class="sxs-lookup"><span data-stu-id="617c9-272">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeysForKeyNameAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt; GetKeysForKeyNameAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt; GetKeysForKeyNameAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetKeysForKeyNameAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetKeysForKeyNameAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetKeysForKeyNameAsync (operations, resourceGroupName, resourceName, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;GetKeysForKeyNameAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-273">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-273">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-274">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-274">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-275">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-275">The name of the IoT hub.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="617c9-276">Der Name der Richtlinie für freigegebenen Zugriff.</span><span class="sxs-lookup"><span data-stu-id="617c9-276">The name of the shared access policy.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="617c9-277">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="617c9-277">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-278">Abrufen einer SAS-Richtlinie nach Namen von einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-278">Get a shared access policy by name from an IoT hub.</span></span> <span data-ttu-id="617c9-279">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span><span class="sxs-lookup"><span data-stu-id="617c9-279">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-280">Abrufen einer SAS-Richtlinie nach Namen von einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-280">Get a shared access policy by name from an IoT hub.</span></span> <span data-ttu-id="617c9-281">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span><span class="sxs-lookup"><span data-stu-id="617c9-281">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetQuotaMetrics">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt; GetQuotaMetrics (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt; GetQuotaMetrics(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetQuotaMetrics(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetQuotaMetrics (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String) As IPage(Of IotHubQuotaMetricInfo)" />
      <MemberSignature Language="F#" Value="static member GetQuotaMetrics : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetQuotaMetrics (operations, resourceGroupName, resourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-282">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-282">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-283">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-283">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-284">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-284">The name of the IoT hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-285">Ruft die Metriken Kontingent für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="617c9-285">Get the quota metrics for an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-286">Ruft die Metriken Kontingent für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="617c9-286">Get the quota metrics for an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetQuotaMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;&gt; GetQuotaMetricsAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;&gt; GetQuotaMetricsAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetQuotaMetricsAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetQuotaMetricsAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetQuotaMetricsAsync (operations, resourceGroupName, resourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;GetQuotaMetricsAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-287">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-287">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-288">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-288">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-289">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-289">The name of the IoT hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="617c9-290">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="617c9-290">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-291">Ruft die Metriken Kontingent für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="617c9-291">Get the quota metrics for an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-292">Ruft die Metriken Kontingent für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="617c9-292">Get the quota metrics for an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetQuotaMetricsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt; GetQuotaMetricsNext (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt; GetQuotaMetricsNext(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetQuotaMetricsNext(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetQuotaMetricsNext (operations As IIotHubResourceOperations, nextPageLink As String) As IPage(Of IotHubQuotaMetricInfo)" />
      <MemberSignature Language="F#" Value="static member GetQuotaMetricsNext : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetQuotaMetricsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-293">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-293">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="617c9-294">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="617c9-294">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-295">Ruft die Metriken Kontingent für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="617c9-295">Get the quota metrics for an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-296">Ruft die Metriken Kontingent für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="617c9-296">Get the quota metrics for an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetQuotaMetricsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;&gt; GetQuotaMetricsNextAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;&gt; GetQuotaMetricsNextAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetQuotaMetricsNextAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetQuotaMetricsNextAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetQuotaMetricsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;GetQuotaMetricsNextAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-297">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-297">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="617c9-298">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="617c9-298">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="617c9-299">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="617c9-299">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-300">Ruft die Metriken Kontingent für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="617c9-300">Get the quota metrics for an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-301">Ruft die Metriken Kontingent für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="617c9-301">Get the quota metrics for an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStats">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.RegistryStatistics GetStats (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.RegistryStatistics GetStats(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetStats(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetStats (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String) As RegistryStatistics" />
      <MemberSignature Language="F#" Value="static member GetStats : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string -&gt; Microsoft.Azure.Management.IotHub.Models.RegistryStatistics" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetStats (operations, resourceGroupName, resourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.RegistryStatistics</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-302">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-302">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-303">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-303">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-304">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-304">The name of the IoT hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-305">Die Statistik von einem IoT Hub abrufen.</span><span class="sxs-lookup"><span data-stu-id="617c9-305">Get the statistics from an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-306">Die Statistik von einem IoT Hub abrufen.</span><span class="sxs-lookup"><span data-stu-id="617c9-306">Get the statistics from an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.RegistryStatistics&gt; GetStatsAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.RegistryStatistics&gt; GetStatsAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetStatsAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetStatsAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.RegistryStatistics&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetStatsAsync (operations, resourceGroupName, resourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;GetStatsAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.RegistryStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-307">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-307">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-308">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-308">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-309">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-309">The name of the IoT hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="617c9-310">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="617c9-310">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-311">Die Statistik von einem IoT Hub abrufen.</span><span class="sxs-lookup"><span data-stu-id="617c9-311">Get the statistics from an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-312">Die Statistik von einem IoT Hub abrufen.</span><span class="sxs-lookup"><span data-stu-id="617c9-312">Get the statistics from an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetValidSkus">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt; GetValidSkus (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt; GetValidSkus(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetValidSkus(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetValidSkus (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String) As IPage(Of IotHubSkuDescription)" />
      <MemberSignature Language="F#" Value="static member GetValidSkus : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetValidSkus (operations, resourceGroupName, resourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-313">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-313">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-314">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-314">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-315">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-315">The name of the IoT hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-316">Ruft die Liste der gültigen SKUs für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="617c9-316">Get the list of valid SKUs for an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-317">Ruft die Liste der gültigen SKUs für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="617c9-317">Get the list of valid SKUs for an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetValidSkusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;&gt; GetValidSkusAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;&gt; GetValidSkusAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetValidSkusAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetValidSkusAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetValidSkusAsync (operations, resourceGroupName, resourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;GetValidSkusAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-318">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-318">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-319">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-319">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-320">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-320">The name of the IoT hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="617c9-321">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="617c9-321">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-322">Ruft die Liste der gültigen SKUs für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="617c9-322">Get the list of valid SKUs for an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-323">Ruft die Liste der gültigen SKUs für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="617c9-323">Get the list of valid SKUs for an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetValidSkusNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt; GetValidSkusNext (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt; GetValidSkusNext(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetValidSkusNext(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetValidSkusNext (operations As IIotHubResourceOperations, nextPageLink As String) As IPage(Of IotHubSkuDescription)" />
      <MemberSignature Language="F#" Value="static member GetValidSkusNext : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetValidSkusNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-324">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-324">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="617c9-325">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="617c9-325">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-326">Ruft die Liste der gültigen SKUs für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="617c9-326">Get the list of valid SKUs for an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-327">Ruft die Liste der gültigen SKUs für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="617c9-327">Get the list of valid SKUs for an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetValidSkusNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;&gt; GetValidSkusNextAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;&gt; GetValidSkusNextAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetValidSkusNextAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetValidSkusNextAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetValidSkusNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;GetValidSkusNextAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-328">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-328">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="617c9-329">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="617c9-329">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="617c9-330">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="617c9-330">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-331">Ruft die Liste der gültigen SKUs für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="617c9-331">Get the list of valid SKUs for an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-332">Ruft die Liste der gültigen SKUs für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="617c9-332">Get the list of valid SKUs for an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportDevices">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.JobResponse ImportDevices (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.IotHub.Models.ImportDevicesRequest importDevicesParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.JobResponse ImportDevices(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.IotHub.Models.ImportDevicesRequest importDevicesParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ImportDevices(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.ImportDevicesRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ImportDevices (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String, importDevicesParameters As ImportDevicesRequest) As JobResponse" />
      <MemberSignature Language="F#" Value="static member ImportDevices : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * Microsoft.Azure.Management.IotHub.Models.ImportDevicesRequest -&gt; Microsoft.Azure.Management.IotHub.Models.JobResponse" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ImportDevices (operations, resourceGroupName, resourceName, importDevicesParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.JobResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="importDevicesParameters" Type="Microsoft.Azure.Management.IotHub.Models.ImportDevicesRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-333">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-333">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-334">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-334">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-335">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-335">The name of the IoT hub.</span></span>
            </param>
        <param name="importDevicesParameters">
            <span data-ttu-id="617c9-336">Die Parameter, die den Importvorgang für die Geräte angeben.</span><span class="sxs-lookup"><span data-stu-id="617c9-336">The parameters that specify the import devices operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-337">Importieren, aktualisieren oder Löschen von geräteidentitäten in der IoT Hub-Identity-Registrierung aus einem Blob.</span><span class="sxs-lookup"><span data-stu-id="617c9-337">Import, update, or delete device identities in the IoT hub identity registry from a blob.</span></span> <span data-ttu-id="617c9-338">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span><span class="sxs-lookup"><span data-stu-id="617c9-338">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-339">Importieren, aktualisieren oder Löschen von geräteidentitäten in der IoT Hub-Identity-Registrierung aus einem Blob.</span><span class="sxs-lookup"><span data-stu-id="617c9-339">Import, update, or delete device identities in the IoT hub identity registry from a blob.</span></span> <span data-ttu-id="617c9-340">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span><span class="sxs-lookup"><span data-stu-id="617c9-340">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportDevicesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt; ImportDevicesAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.IotHub.Models.ImportDevicesRequest importDevicesParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.JobResponse&gt; ImportDevicesAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.IotHub.Models.ImportDevicesRequest importDevicesParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ImportDevicesAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.ImportDevicesRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ImportDevicesAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * Microsoft.Azure.Management.IotHub.Models.ImportDevicesRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ImportDevicesAsync (operations, resourceGroupName, resourceName, importDevicesParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;ImportDevicesAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="importDevicesParameters" Type="Microsoft.Azure.Management.IotHub.Models.ImportDevicesRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-341">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-341">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-342">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-342">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-343">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-343">The name of the IoT hub.</span></span>
            </param>
        <param name="importDevicesParameters">
            <span data-ttu-id="617c9-344">Die Parameter, die den Importvorgang für die Geräte angeben.</span><span class="sxs-lookup"><span data-stu-id="617c9-344">The parameters that specify the import devices operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="617c9-345">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="617c9-345">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-346">Importieren, aktualisieren oder Löschen von geräteidentitäten in der IoT Hub-Identity-Registrierung aus einem Blob.</span><span class="sxs-lookup"><span data-stu-id="617c9-346">Import, update, or delete device identities in the IoT hub identity registry from a blob.</span></span> <span data-ttu-id="617c9-347">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span><span class="sxs-lookup"><span data-stu-id="617c9-347">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-348">Importieren, aktualisieren oder Löschen von geräteidentitäten in der IoT Hub-Identity-Registrierung aus einem Blob.</span><span class="sxs-lookup"><span data-stu-id="617c9-348">Import, update, or delete device identities in the IoT hub identity registry from a blob.</span></span> <span data-ttu-id="617c9-349">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span><span class="sxs-lookup"><span data-stu-id="617c9-349">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt; ListByResourceGroup (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt; ListByResourceGroup(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IIotHubResourceOperations, resourceGroupName As String) As IPage(Of IotHubDescription)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-350">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-350">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-351">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-351">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-352">Ruft alle IoT Hubs in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="617c9-352">Get all the IoT hubs in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-353">Ruft alle IoT Hubs in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="617c9-353">Get all the IoT hubs in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-354">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-354">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-355">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-355">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="617c9-356">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="617c9-356">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-357">Ruft alle IoT Hubs in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="617c9-357">Get all the IoT hubs in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-358">Ruft alle IoT Hubs in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="617c9-358">Get all the IoT hubs in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IIotHubResourceOperations, nextPageLink As String) As IPage(Of IotHubDescription)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-359">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-359">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="617c9-360">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="617c9-360">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-361">Ruft alle IoT Hubs in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="617c9-361">Get all the IoT hubs in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-362">Ruft alle IoT Hubs in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="617c9-362">Get all the IoT hubs in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-363">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-363">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="617c9-364">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="617c9-364">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="617c9-365">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="617c9-365">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-366">Ruft alle IoT Hubs in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="617c9-366">Get all the IoT hubs in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-367">Ruft alle IoT Hubs in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="617c9-367">Get all the IoT hubs in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscription">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt; ListBySubscription (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt; ListBySubscription(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListBySubscription(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListBySubscription (operations As IIotHubResourceOperations) As IPage(Of IotHubDescription)" />
      <MemberSignature Language="F#" Value="static member ListBySubscription : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListBySubscription operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-368">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-368">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-369">Ruft alle IoT Hubs in einem Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="617c9-369">Get all the IoT hubs in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-370">Ruft alle IoT Hubs in einem Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="617c9-370">Get all the IoT hubs in a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscriptionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt; ListBySubscriptionAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt; ListBySubscriptionAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListBySubscriptionAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListBySubscriptionAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListBySubscriptionAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;ListBySubscriptionAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-371">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-371">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="617c9-372">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="617c9-372">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-373">Ruft alle IoT Hubs in einem Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="617c9-373">Get all the IoT hubs in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-374">Ruft alle IoT Hubs in einem Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="617c9-374">Get all the IoT hubs in a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscriptionNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt; ListBySubscriptionNext (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt; ListBySubscriptionNext(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListBySubscriptionNext(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListBySubscriptionNext (operations As IIotHubResourceOperations, nextPageLink As String) As IPage(Of IotHubDescription)" />
      <MemberSignature Language="F#" Value="static member ListBySubscriptionNext : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListBySubscriptionNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-375">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-375">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="617c9-376">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="617c9-376">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-377">Ruft alle IoT Hubs in einem Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="617c9-377">Get all the IoT hubs in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-378">Ruft alle IoT Hubs in einem Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="617c9-378">Get all the IoT hubs in a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscriptionNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt; ListBySubscriptionNextAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt; ListBySubscriptionNextAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListBySubscriptionNextAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListBySubscriptionNextAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListBySubscriptionNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;ListBySubscriptionNextAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-379">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-379">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="617c9-380">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="617c9-380">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="617c9-381">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="617c9-381">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-382">Ruft alle IoT Hubs in einem Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="617c9-382">Get all the IoT hubs in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-383">Ruft alle IoT Hubs in einem Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="617c9-383">Get all the IoT hubs in a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListEventHubConsumerGroups">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;string&gt; ListEventHubConsumerGroups (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;string&gt; ListEventHubConsumerGroups(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListEventHubConsumerGroups(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListEventHubConsumerGroups (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String, eventHubEndpointName As String) As IPage(Of String)" />
      <MemberSignature Language="F#" Value="static member ListEventHubConsumerGroups : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;string&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListEventHubConsumerGroups (operations, resourceGroupName, resourceName, eventHubEndpointName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="eventHubEndpointName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-384">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-384">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-385">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-385">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-386">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-386">The name of the IoT hub.</span></span>
            </param>
        <param name="eventHubEndpointName">
            <span data-ttu-id="617c9-387">Der Name des Endpunkts Event Hub-kompatibel.</span><span class="sxs-lookup"><span data-stu-id="617c9-387">The name of the Event Hub-compatible endpoint.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-388">Abrufen einer Liste der consumergruppen im Event Hub-kompatibles Gerät-zu-Cloud-Endpunkt in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-388">Get a list of the consumer groups in the Event Hub-compatible device-to-cloud endpoint in an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-389">Abrufen einer Liste der consumergruppen im Event Hub-kompatibles Gerät-zu-Cloud-Endpunkt in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-389">Get a list of the consumer groups in the Event Hub-compatible device-to-cloud endpoint in an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListEventHubConsumerGroupsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt; ListEventHubConsumerGroupsAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;string&gt;&gt; ListEventHubConsumerGroupsAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListEventHubConsumerGroupsAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListEventHubConsumerGroupsAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListEventHubConsumerGroupsAsync (operations, resourceGroupName, resourceName, eventHubEndpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;ListEventHubConsumerGroupsAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="eventHubEndpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-390">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-390">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-391">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-391">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-392">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-392">The name of the IoT hub.</span></span>
            </param>
        <param name="eventHubEndpointName">
            <span data-ttu-id="617c9-393">Der Name des Endpunkts Event Hub-kompatibel.</span><span class="sxs-lookup"><span data-stu-id="617c9-393">The name of the Event Hub-compatible endpoint.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="617c9-394">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="617c9-394">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-395">Abrufen einer Liste der consumergruppen im Event Hub-kompatibles Gerät-zu-Cloud-Endpunkt in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-395">Get a list of the consumer groups in the Event Hub-compatible device-to-cloud endpoint in an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-396">Abrufen einer Liste der consumergruppen im Event Hub-kompatibles Gerät-zu-Cloud-Endpunkt in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-396">Get a list of the consumer groups in the Event Hub-compatible device-to-cloud endpoint in an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListEventHubConsumerGroupsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;string&gt; ListEventHubConsumerGroupsNext (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;string&gt; ListEventHubConsumerGroupsNext(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListEventHubConsumerGroupsNext(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListEventHubConsumerGroupsNext (operations As IIotHubResourceOperations, nextPageLink As String) As IPage(Of String)" />
      <MemberSignature Language="F#" Value="static member ListEventHubConsumerGroupsNext : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;string&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListEventHubConsumerGroupsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-397">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-397">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="617c9-398">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="617c9-398">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-399">Abrufen einer Liste der consumergruppen im Event Hub-kompatibles Gerät-zu-Cloud-Endpunkt in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-399">Get a list of the consumer groups in the Event Hub-compatible device-to-cloud endpoint in an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-400">Abrufen einer Liste der consumergruppen im Event Hub-kompatibles Gerät-zu-Cloud-Endpunkt in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-400">Get a list of the consumer groups in the Event Hub-compatible device-to-cloud endpoint in an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListEventHubConsumerGroupsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt; ListEventHubConsumerGroupsNextAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;string&gt;&gt; ListEventHubConsumerGroupsNextAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListEventHubConsumerGroupsNextAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListEventHubConsumerGroupsNextAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListEventHubConsumerGroupsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;ListEventHubConsumerGroupsNextAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-401">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-401">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="617c9-402">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="617c9-402">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="617c9-403">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="617c9-403">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-404">Abrufen einer Liste der consumergruppen im Event Hub-kompatibles Gerät-zu-Cloud-Endpunkt in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-404">Get a list of the consumer groups in the Event Hub-compatible device-to-cloud endpoint in an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-405">Abrufen einer Liste der consumergruppen im Event Hub-kompatibles Gerät-zu-Cloud-Endpunkt in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-405">Get a list of the consumer groups in the Event Hub-compatible device-to-cloud endpoint in an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListJobs">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt; ListJobs (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.JobResponse&gt; ListJobs(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListJobs(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListJobs (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String) As IPage(Of JobResponse)" />
      <MemberSignature Language="F#" Value="static member ListJobs : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListJobs (operations, resourceGroupName, resourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-406">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-406">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-407">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-407">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-408">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-408">The name of the IoT hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-409">Abrufen einer Liste aller Aufträge in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-409">Get a list of all the jobs in an IoT hub.</span></span> <span data-ttu-id="617c9-410">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span><span class="sxs-lookup"><span data-stu-id="617c9-410">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-411">Abrufen einer Liste aller Aufträge in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-411">Get a list of all the jobs in an IoT hub.</span></span> <span data-ttu-id="617c9-412">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span><span class="sxs-lookup"><span data-stu-id="617c9-412">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListJobsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt; ListJobsAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt; ListJobsAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListJobsAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListJobsAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListJobsAsync (operations, resourceGroupName, resourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;ListJobsAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-413">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-413">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-414">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-414">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-415">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-415">The name of the IoT hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="617c9-416">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="617c9-416">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-417">Abrufen einer Liste aller Aufträge in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-417">Get a list of all the jobs in an IoT hub.</span></span> <span data-ttu-id="617c9-418">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span><span class="sxs-lookup"><span data-stu-id="617c9-418">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-419">Abrufen einer Liste aller Aufträge in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-419">Get a list of all the jobs in an IoT hub.</span></span> <span data-ttu-id="617c9-420">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span><span class="sxs-lookup"><span data-stu-id="617c9-420">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListJobsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt; ListJobsNext (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.JobResponse&gt; ListJobsNext(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListJobsNext(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListJobsNext (operations As IIotHubResourceOperations, nextPageLink As String) As IPage(Of JobResponse)" />
      <MemberSignature Language="F#" Value="static member ListJobsNext : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListJobsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-421">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-421">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="617c9-422">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="617c9-422">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-423">Abrufen einer Liste aller Aufträge in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-423">Get a list of all the jobs in an IoT hub.</span></span> <span data-ttu-id="617c9-424">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span><span class="sxs-lookup"><span data-stu-id="617c9-424">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-425">Abrufen einer Liste aller Aufträge in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-425">Get a list of all the jobs in an IoT hub.</span></span> <span data-ttu-id="617c9-426">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span><span class="sxs-lookup"><span data-stu-id="617c9-426">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListJobsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt; ListJobsNextAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt; ListJobsNextAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListJobsNextAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListJobsNextAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListJobsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;ListJobsNextAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-427">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-427">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="617c9-428">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="617c9-428">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="617c9-429">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="617c9-429">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-430">Abrufen einer Liste aller Aufträge in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-430">Get a list of all the jobs in an IoT hub.</span></span> <span data-ttu-id="617c9-431">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span><span class="sxs-lookup"><span data-stu-id="617c9-431">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-432">Abrufen einer Liste aller Aufträge in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-432">Get a list of all the jobs in an IoT hub.</span></span> <span data-ttu-id="617c9-433">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span><span class="sxs-lookup"><span data-stu-id="617c9-433">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt; ListKeys (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt; ListKeys(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListKeys(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListKeys (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String) As IPage(Of SharedAccessSignatureAuthorizationRule)" />
      <MemberSignature Language="F#" Value="static member ListKeys : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListKeys (operations, resourceGroupName, resourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-434">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-434">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-435">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-435">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-436">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-436">The name of the IoT hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-437">Ruft die Sicherheits-Metadaten für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="617c9-437">Get the security metadata for an IoT hub.</span></span> <span data-ttu-id="617c9-438">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span><span class="sxs-lookup"><span data-stu-id="617c9-438">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-439">Ruft die Sicherheits-Metadaten für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="617c9-439">Get the security metadata for an IoT hub.</span></span> <span data-ttu-id="617c9-440">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span><span class="sxs-lookup"><span data-stu-id="617c9-440">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;&gt; ListKeysAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;&gt; ListKeysAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListKeysAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeysAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListKeysAsync (operations, resourceGroupName, resourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;ListKeysAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-441">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-441">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="617c9-442">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="617c9-442">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="617c9-443">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="617c9-443">The name of the IoT hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="617c9-444">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="617c9-444">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-445">Ruft die Sicherheits-Metadaten für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="617c9-445">Get the security metadata for an IoT hub.</span></span> <span data-ttu-id="617c9-446">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span><span class="sxs-lookup"><span data-stu-id="617c9-446">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-447">Ruft die Sicherheits-Metadaten für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="617c9-447">Get the security metadata for an IoT hub.</span></span> <span data-ttu-id="617c9-448">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span><span class="sxs-lookup"><span data-stu-id="617c9-448">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt; ListKeysNext (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt; ListKeysNext(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListKeysNext(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListKeysNext (operations As IIotHubResourceOperations, nextPageLink As String) As IPage(Of SharedAccessSignatureAuthorizationRule)" />
      <MemberSignature Language="F#" Value="static member ListKeysNext : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListKeysNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-449">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-449">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="617c9-450">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="617c9-450">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-451">Ruft die Sicherheits-Metadaten für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="617c9-451">Get the security metadata for an IoT hub.</span></span> <span data-ttu-id="617c9-452">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span><span class="sxs-lookup"><span data-stu-id="617c9-452">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-453">Ruft die Sicherheits-Metadaten für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="617c9-453">Get the security metadata for an IoT hub.</span></span> <span data-ttu-id="617c9-454">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span><span class="sxs-lookup"><span data-stu-id="617c9-454">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;&gt; ListKeysNextAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;&gt; ListKeysNextAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListKeysNextAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeysNextAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListKeysNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;ListKeysNextAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="617c9-455">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="617c9-455">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="617c9-456">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="617c9-456">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="617c9-457">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="617c9-457">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="617c9-458">Ruft die Sicherheits-Metadaten für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="617c9-458">Get the security metadata for an IoT hub.</span></span> <span data-ttu-id="617c9-459">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span><span class="sxs-lookup"><span data-stu-id="617c9-459">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="617c9-460">Ruft die Sicherheits-Metadaten für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="617c9-460">Get the security metadata for an IoT hub.</span></span> <span data-ttu-id="617c9-461">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span><span class="sxs-lookup"><span data-stu-id="617c9-461">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>