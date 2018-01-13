<Type Name="EndpointsOperationsExtensions" FullName="Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class EndpointsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit EndpointsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module EndpointsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type EndpointsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f8857-101">Erweiterungsmethoden für EndpointsOperations.</span><span class="sxs-lookup"><span data-stu-id="f8857-101">Extension methods for EndpointsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.TrafficManager.Models.Endpoint CreateOrUpdate (this Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, Microsoft.Azure.Management.TrafficManager.Models.Endpoint parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.TrafficManager.Models.Endpoint CreateOrUpdate(class Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, class Microsoft.Azure.Management.TrafficManager.Models.Endpoint parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.TrafficManager.IEndpointsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.TrafficManager.Models.Endpoint)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IEndpointsOperations, resourceGroupName As String, profileName As String, endpointType As String, endpointName As String, parameters As Endpoint) As Endpoint" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.TrafficManager.IEndpointsOperations * string * string * string * string * Microsoft.Azure.Management.TrafficManager.Models.Endpoint -&gt; Microsoft.Azure.Management.TrafficManager.Models.Endpoint" Usage="Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, profileName, endpointType, endpointName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Models.Endpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Models.Endpoint" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8857-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f8857-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f8857-103">Der Name der Ressourcengruppe, enthält die Traffic Manager-Endpunkt erstellt oder aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="f8857-103">The name of the resource group containing the Traffic Manager endpoint to be created or updated.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="f8857-104">Der Name des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="f8857-104">The name of the Traffic Manager profile.</span></span>
            </param>
        <param name="endpointType">
            <span data-ttu-id="f8857-105">Der Typ des Traffic Manager-Endpunkt erstellt oder aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="f8857-105">The type of the Traffic Manager endpoint to be created or updated.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="f8857-106">Der Name des Traffic Manager-Endpunkt erstellt oder aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="f8857-106">The name of the Traffic Manager endpoint to be created or updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f8857-107">Die Traffic Manager Endpunktparameter für den Vorgang CreateOrUpdate bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="f8857-107">The Traffic Manager endpoint parameters supplied to the CreateOrUpdate operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8857-108">Erstellt oder aktualisiert einen Traffic Manager-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="f8857-108">Create or update a Traffic Manager endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, Microsoft.Azure.Management.TrafficManager.Models.Endpoint parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, class Microsoft.Azure.Management.TrafficManager.Models.Endpoint parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.TrafficManager.IEndpointsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.TrafficManager.Models.Endpoint,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.TrafficManager.IEndpointsOperations * string * string * string * string * Microsoft.Azure.Management.TrafficManager.Models.Endpoint * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;" Usage="Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, profileName, endpointType, endpointName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Models.Endpoint" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8857-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f8857-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f8857-110">Der Name der Ressourcengruppe, enthält die Traffic Manager-Endpunkt erstellt oder aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="f8857-110">The name of the resource group containing the Traffic Manager endpoint to be created or updated.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="f8857-111">Der Name des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="f8857-111">The name of the Traffic Manager profile.</span></span>
            </param>
        <param name="endpointType">
            <span data-ttu-id="f8857-112">Der Typ des Traffic Manager-Endpunkt erstellt oder aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="f8857-112">The type of the Traffic Manager endpoint to be created or updated.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="f8857-113">Der Name des Traffic Manager-Endpunkt erstellt oder aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="f8857-113">The name of the Traffic Manager endpoint to be created or updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f8857-114">Die Traffic Manager Endpunktparameter für den Vorgang CreateOrUpdate bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="f8857-114">The Traffic Manager endpoint parameters supplied to the CreateOrUpdate operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f8857-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f8857-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8857-116">Erstellt oder aktualisiert einen Traffic Manager-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="f8857-116">Create or update a Traffic Manager endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult Delete (this Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult Delete(class Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.Delete(Microsoft.Azure.Management.TrafficManager.IEndpointsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IEndpointsOperations, resourceGroupName As String, profileName As String, endpointType As String, endpointName As String) As DeleteOperationResult" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.TrafficManager.IEndpointsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult" Usage="Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.Delete (operations, resourceGroupName, profileName, endpointType, endpointName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8857-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f8857-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f8857-118">Der Name der Ressourcengruppe, die Traffic Manager-Dienstendpunkt enthält, gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f8857-118">The name of the resource group containing the Traffic Manager endpoint to be deleted.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="f8857-119">Der Name des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="f8857-119">The name of the Traffic Manager profile.</span></span>
            </param>
        <param name="endpointType">
            <span data-ttu-id="f8857-120">Der Typ des Traffic Manager-Endpunkt gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f8857-120">The type of the Traffic Manager endpoint to be deleted.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="f8857-121">Der Name des Traffic Manager-Endpunkt gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f8857-121">The name of the Traffic Manager endpoint to be deleted.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8857-122">Löscht einen Traffic Manager-Endpunkt an.</span><span class="sxs-lookup"><span data-stu-id="f8857-122">Deletes a Traffic Manager endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult&gt; DeleteAsync (this Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult&gt; DeleteAsync(class Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.TrafficManager.IEndpointsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.TrafficManager.IEndpointsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult&gt;" Usage="Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.DeleteAsync (operations, resourceGroupName, profileName, endpointType, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8857-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f8857-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f8857-124">Der Name der Ressourcengruppe, die Traffic Manager-Dienstendpunkt enthält, gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f8857-124">The name of the resource group containing the Traffic Manager endpoint to be deleted.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="f8857-125">Der Name des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="f8857-125">The name of the Traffic Manager profile.</span></span>
            </param>
        <param name="endpointType">
            <span data-ttu-id="f8857-126">Der Typ des Traffic Manager-Endpunkt gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f8857-126">The type of the Traffic Manager endpoint to be deleted.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="f8857-127">Der Name des Traffic Manager-Endpunkt gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f8857-127">The name of the Traffic Manager endpoint to be deleted.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f8857-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f8857-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8857-129">Löscht einen Traffic Manager-Endpunkt an.</span><span class="sxs-lookup"><span data-stu-id="f8857-129">Deletes a Traffic Manager endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.TrafficManager.Models.Endpoint Get (this Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.TrafficManager.Models.Endpoint Get(class Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.Get(Microsoft.Azure.Management.TrafficManager.IEndpointsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IEndpointsOperations, resourceGroupName As String, profileName As String, endpointType As String, endpointName As String) As Endpoint" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.TrafficManager.IEndpointsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.TrafficManager.Models.Endpoint" Usage="Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.Get (operations, resourceGroupName, profileName, endpointType, endpointName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Models.Endpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8857-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f8857-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f8857-131">Der Name der Ressourcengruppe, die die Traffic Manager-Endpunkt enthält.</span><span class="sxs-lookup"><span data-stu-id="f8857-131">The name of the resource group containing the Traffic Manager endpoint.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="f8857-132">Der Name des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="f8857-132">The name of the Traffic Manager profile.</span></span>
            </param>
        <param name="endpointType">
            <span data-ttu-id="f8857-133">Der Typ des Traffic Manager-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="f8857-133">The type of the Traffic Manager endpoint.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="f8857-134">Der Name des Traffic Manager-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="f8857-134">The name of the Traffic Manager endpoint.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8857-135">Ruft eine Traffic Manager-Endpunkt ab.</span><span class="sxs-lookup"><span data-stu-id="f8857-135">Gets a Traffic Manager endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; GetAsync (this Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; GetAsync(class Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.GetAsync(Microsoft.Azure.Management.TrafficManager.IEndpointsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.TrafficManager.IEndpointsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;" Usage="Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.GetAsync (operations, resourceGroupName, profileName, endpointType, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8857-136">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f8857-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f8857-137">Der Name der Ressourcengruppe, die die Traffic Manager-Endpunkt enthält.</span><span class="sxs-lookup"><span data-stu-id="f8857-137">The name of the resource group containing the Traffic Manager endpoint.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="f8857-138">Der Name des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="f8857-138">The name of the Traffic Manager profile.</span></span>
            </param>
        <param name="endpointType">
            <span data-ttu-id="f8857-139">Der Typ des Traffic Manager-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="f8857-139">The type of the Traffic Manager endpoint.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="f8857-140">Der Name des Traffic Manager-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="f8857-140">The name of the Traffic Manager endpoint.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f8857-141">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f8857-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8857-142">Ruft eine Traffic Manager-Endpunkt ab.</span><span class="sxs-lookup"><span data-stu-id="f8857-142">Gets a Traffic Manager endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.TrafficManager.Models.Endpoint Update (this Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, Microsoft.Azure.Management.TrafficManager.Models.Endpoint parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.TrafficManager.Models.Endpoint Update(class Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, class Microsoft.Azure.Management.TrafficManager.Models.Endpoint parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.Update(Microsoft.Azure.Management.TrafficManager.IEndpointsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.TrafficManager.Models.Endpoint)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IEndpointsOperations, resourceGroupName As String, profileName As String, endpointType As String, endpointName As String, parameters As Endpoint) As Endpoint" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.TrafficManager.IEndpointsOperations * string * string * string * string * Microsoft.Azure.Management.TrafficManager.Models.Endpoint -&gt; Microsoft.Azure.Management.TrafficManager.Models.Endpoint" Usage="Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.Update (operations, resourceGroupName, profileName, endpointType, endpointName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Models.Endpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Models.Endpoint" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8857-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f8857-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f8857-144">Der Name der Ressourcengruppe, die Traffic Manager-Dienstendpunkt enthält, aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="f8857-144">The name of the resource group containing the Traffic Manager endpoint to be updated.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="f8857-145">Der Name des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="f8857-145">The name of the Traffic Manager profile.</span></span>
            </param>
        <param name="endpointType">
            <span data-ttu-id="f8857-146">Der Typ des Endpunkts Traffic Manager aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="f8857-146">The type of the Traffic Manager endpoint to be updated.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="f8857-147">Der Name des Endpunkts Traffic Manager aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="f8857-147">The name of the Traffic Manager endpoint to be updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f8857-148">Die Traffic Manager Endpunktparameter auf den Updatevorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="f8857-148">The Traffic Manager endpoint parameters supplied to the Update operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8857-149">Aktualisieren Sie einen Traffic Manager-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="f8857-149">Update a Traffic Manager endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; UpdateAsync (this Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, Microsoft.Azure.Management.TrafficManager.Models.Endpoint parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; UpdateAsync(class Microsoft.Azure.Management.TrafficManager.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, class Microsoft.Azure.Management.TrafficManager.Models.Endpoint parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.TrafficManager.IEndpointsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.TrafficManager.Models.Endpoint,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.TrafficManager.IEndpointsOperations * string * string * string * string * Microsoft.Azure.Management.TrafficManager.Models.Endpoint * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;" Usage="Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions.UpdateAsync (operations, resourceGroupName, profileName, endpointType, endpointName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.EndpointsOperationsExtensions/&lt;UpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Models.Endpoint" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8857-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f8857-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f8857-151">Der Name der Ressourcengruppe, die Traffic Manager-Dienstendpunkt enthält, aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="f8857-151">The name of the resource group containing the Traffic Manager endpoint to be updated.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="f8857-152">Der Name des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="f8857-152">The name of the Traffic Manager profile.</span></span>
            </param>
        <param name="endpointType">
            <span data-ttu-id="f8857-153">Der Typ des Endpunkts Traffic Manager aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="f8857-153">The type of the Traffic Manager endpoint to be updated.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="f8857-154">Der Name des Endpunkts Traffic Manager aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="f8857-154">The name of the Traffic Manager endpoint to be updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f8857-155">Die Traffic Manager Endpunktparameter auf den Updatevorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="f8857-155">The Traffic Manager endpoint parameters supplied to the Update operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f8857-156">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f8857-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8857-157">Aktualisieren Sie einen Traffic Manager-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="f8857-157">Update a Traffic Manager endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>