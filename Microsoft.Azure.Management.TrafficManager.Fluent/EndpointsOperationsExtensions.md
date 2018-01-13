<Type Name="EndpointsOperationsExtensions" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class EndpointsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit EndpointsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module EndpointsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type EndpointsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e6dbb-101">Erweiterungsmethoden für EndpointsOperations.</span><span class="sxs-lookup"><span data-stu-id="e6dbb-101">Extension methods for EndpointsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, class Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations * string * string * string * string * Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, profileName, endpointType, endpointName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e6dbb-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e6dbb-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e6dbb-103">Der Name der Ressourcengruppe, enthält die Traffic Manager-Endpunkt erstellt oder aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="e6dbb-103">The name of the resource group containing the Traffic Manager endpoint to be created or updated.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="e6dbb-104">Der Name des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="e6dbb-104">The name of the Traffic Manager profile.</span></span>
            </param>
        <param name="endpointType">
            <span data-ttu-id="e6dbb-105">Der Typ des Traffic Manager-Endpunkt erstellt oder aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="e6dbb-105">The type of the Traffic Manager endpoint to be created or updated.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="e6dbb-106">Der Name des Traffic Manager-Endpunkt erstellt oder aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="e6dbb-106">The name of the Traffic Manager endpoint to be created or updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e6dbb-107">Die Traffic Manager Endpunktparameter für den Vorgang CreateOrUpdate bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="e6dbb-107">The Traffic Manager endpoint parameters supplied to the CreateOrUpdate operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e6dbb-108">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e6dbb-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e6dbb-109">Erstellt oder aktualisiert einen Traffic Manager-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="e6dbb-109">Create or update a Traffic Manager endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.DeleteOperationResultInner&gt; DeleteAsync (this Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.DeleteOperationResultInner&gt; DeleteAsync(class Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.DeleteOperationResultInner&gt;" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions.DeleteAsync (operations, resourceGroupName, profileName, endpointType, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.DeleteOperationResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointType">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; GetAsync (this Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; GetAsync(class Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions.GetAsync(Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions.GetAsync (operations, resourceGroupName, profileName, endpointType, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e6dbb-110">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e6dbb-110">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e6dbb-111">Der Name der Ressourcengruppe, die die Traffic Manager-Endpunkt enthält.</span><span class="sxs-lookup"><span data-stu-id="e6dbb-111">The name of the resource group containing the Traffic Manager endpoint.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="e6dbb-112">Der Name des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="e6dbb-112">The name of the Traffic Manager profile.</span></span>
            </param>
        <param name="endpointType">
            <span data-ttu-id="e6dbb-113">Der Typ des Traffic Manager-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="e6dbb-113">The type of the Traffic Manager endpoint.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="e6dbb-114">Der Name des Traffic Manager-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="e6dbb-114">The name of the Traffic Manager endpoint.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e6dbb-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e6dbb-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e6dbb-116">Ruft eine Traffic Manager-Endpunkt ab.</span><span class="sxs-lookup"><span data-stu-id="e6dbb-116">Gets a Traffic Manager endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; UpdateAsync (this Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; UpdateAsync(class Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, class Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations * string * string * string * string * Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions.UpdateAsync (operations, resourceGroupName, profileName, endpointType, endpointName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions/&lt;UpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e6dbb-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e6dbb-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e6dbb-118">Der Name der Ressourcengruppe, die Traffic Manager-Dienstendpunkt enthält, aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="e6dbb-118">The name of the resource group containing the Traffic Manager endpoint to be updated.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="e6dbb-119">Der Name des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="e6dbb-119">The name of the Traffic Manager profile.</span></span>
            </param>
        <param name="endpointType">
            <span data-ttu-id="e6dbb-120">Der Typ des Endpunkts Traffic Manager aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="e6dbb-120">The type of the Traffic Manager endpoint to be updated.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="e6dbb-121">Der Name des Endpunkts Traffic Manager aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="e6dbb-121">The name of the Traffic Manager endpoint to be updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e6dbb-122">Die Traffic Manager Endpunktparameter auf den Updatevorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="e6dbb-122">The Traffic Manager endpoint parameters supplied to the Update operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e6dbb-123">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e6dbb-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e6dbb-124">Aktualisieren Sie einen Traffic Manager-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="e6dbb-124">Update a Traffic Manager endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>