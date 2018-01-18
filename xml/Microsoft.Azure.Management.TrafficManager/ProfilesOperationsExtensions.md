<Type Name="ProfilesOperationsExtensions" FullName="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ProfilesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ProfilesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ProfilesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ProfilesOperationsExtensions = class" />
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
            <span data-ttu-id="35146-101">Erweiterungsmethoden für ProfilesOperations.</span><span class="sxs-lookup"><span data-stu-id="35146-101">Extension methods for ProfilesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckTrafficManagerRelativeDnsNameAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability CheckTrafficManagerRelativeDnsNameAvailability (this Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, Microsoft.Azure.Management.TrafficManager.Models.CheckTrafficManagerRelativeDnsNameAvailabilityParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability CheckTrafficManagerRelativeDnsNameAvailability(class Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, class Microsoft.Azure.Management.TrafficManager.Models.CheckTrafficManagerRelativeDnsNameAvailabilityParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.CheckTrafficManagerRelativeDnsNameAvailability(Microsoft.Azure.Management.TrafficManager.IProfilesOperations,Microsoft.Azure.Management.TrafficManager.Models.CheckTrafficManagerRelativeDnsNameAvailabilityParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckTrafficManagerRelativeDnsNameAvailability (operations As IProfilesOperations, parameters As CheckTrafficManagerRelativeDnsNameAvailabilityParameters) As TrafficManagerNameAvailability" />
      <MemberSignature Language="F#" Value="static member CheckTrafficManagerRelativeDnsNameAvailability : Microsoft.Azure.Management.TrafficManager.IProfilesOperations * Microsoft.Azure.Management.TrafficManager.Models.CheckTrafficManagerRelativeDnsNameAvailabilityParameters -&gt; Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability" Usage="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.CheckTrafficManagerRelativeDnsNameAvailability (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IProfilesOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Models.CheckTrafficManagerRelativeDnsNameAvailabilityParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="35146-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="35146-102">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="35146-103">Die Traffic Manager-Name-Parameter für die CheckTrafficManagerNameAvailability zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="35146-103">The Traffic Manager name parameters supplied to the CheckTrafficManagerNameAvailability operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35146-104">Prüft die Verfügbarkeit eines relativen Traffic Manager-DNS-Namens.</span><span class="sxs-lookup"><span data-stu-id="35146-104">Checks the availability of a Traffic Manager Relative DNS name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckTrafficManagerRelativeDnsNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability&gt; CheckTrafficManagerRelativeDnsNameAvailabilityAsync (this Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, Microsoft.Azure.Management.TrafficManager.Models.CheckTrafficManagerRelativeDnsNameAvailabilityParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability&gt; CheckTrafficManagerRelativeDnsNameAvailabilityAsync(class Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, class Microsoft.Azure.Management.TrafficManager.Models.CheckTrafficManagerRelativeDnsNameAvailabilityParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.CheckTrafficManagerRelativeDnsNameAvailabilityAsync(Microsoft.Azure.Management.TrafficManager.IProfilesOperations,Microsoft.Azure.Management.TrafficManager.Models.CheckTrafficManagerRelativeDnsNameAvailabilityParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckTrafficManagerRelativeDnsNameAvailabilityAsync : Microsoft.Azure.Management.TrafficManager.IProfilesOperations * Microsoft.Azure.Management.TrafficManager.Models.CheckTrafficManagerRelativeDnsNameAvailabilityParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability&gt;" Usage="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.CheckTrafficManagerRelativeDnsNameAvailabilityAsync (operations, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions/&lt;CheckTrafficManagerRelativeDnsNameAvailabilityAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IProfilesOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Models.CheckTrafficManagerRelativeDnsNameAvailabilityParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="35146-105">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="35146-105">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="35146-106">Die Traffic Manager-Name-Parameter für die CheckTrafficManagerNameAvailability zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="35146-106">The Traffic Manager name parameters supplied to the CheckTrafficManagerNameAvailability operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="35146-107">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="35146-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35146-108">Prüft die Verfügbarkeit eines relativen Traffic Manager-DNS-Namens.</span><span class="sxs-lookup"><span data-stu-id="35146-108">Checks the availability of a Traffic Manager Relative DNS name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.TrafficManager.Models.Profile CreateOrUpdate (this Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName, Microsoft.Azure.Management.TrafficManager.Models.Profile parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.TrafficManager.Models.Profile CreateOrUpdate(class Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName, class Microsoft.Azure.Management.TrafficManager.Models.Profile parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.TrafficManager.IProfilesOperations,System.String,System.String,Microsoft.Azure.Management.TrafficManager.Models.Profile)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IProfilesOperations, resourceGroupName As String, profileName As String, parameters As Profile) As Profile" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.TrafficManager.IProfilesOperations * string * string * Microsoft.Azure.Management.TrafficManager.Models.Profile -&gt; Microsoft.Azure.Management.TrafficManager.Models.Profile" Usage="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, profileName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Models.Profile</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Models.Profile" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="35146-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="35146-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="35146-110">Der Name der Ressourcengruppe, die Traffic Manager-Profil enthält.</span><span class="sxs-lookup"><span data-stu-id="35146-110">The name of the resource group containing the Traffic Manager profile.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="35146-111">Der Name des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="35146-111">The name of the Traffic Manager profile.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="35146-112">Die Traffic Manager Profilparameter für den Vorgang CreateOrUpdate bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="35146-112">The Traffic Manager profile parameters supplied to the CreateOrUpdate operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35146-113">Erstellen oder Aktualisieren eines Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="35146-113">Create or update a Traffic Manager profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName, Microsoft.Azure.Management.TrafficManager.Models.Profile parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Profile&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName, class Microsoft.Azure.Management.TrafficManager.Models.Profile parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.TrafficManager.IProfilesOperations,System.String,System.String,Microsoft.Azure.Management.TrafficManager.Models.Profile,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.TrafficManager.IProfilesOperations * string * string * Microsoft.Azure.Management.TrafficManager.Models.Profile * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;" Usage="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, profileName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Models.Profile" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="35146-114">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="35146-114">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="35146-115">Der Name der Ressourcengruppe, die Traffic Manager-Profil enthält.</span><span class="sxs-lookup"><span data-stu-id="35146-115">The name of the resource group containing the Traffic Manager profile.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="35146-116">Der Name des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="35146-116">The name of the Traffic Manager profile.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="35146-117">Die Traffic Manager Profilparameter für den Vorgang CreateOrUpdate bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="35146-117">The Traffic Manager profile parameters supplied to the CreateOrUpdate operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="35146-118">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="35146-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35146-119">Erstellen oder Aktualisieren eines Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="35146-119">Create or update a Traffic Manager profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult Delete (this Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult Delete(class Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.Delete(Microsoft.Azure.Management.TrafficManager.IProfilesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IProfilesOperations, resourceGroupName As String, profileName As String) As DeleteOperationResult" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.TrafficManager.IProfilesOperations * string * string -&gt; Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult" Usage="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.Delete (operations, resourceGroupName, profileName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="35146-120">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="35146-120">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="35146-121">Der Name der Ressourcengruppe, enthält das Traffic Manager-Profil, gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="35146-121">The name of the resource group containing the Traffic Manager profile to be deleted.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="35146-122">Der Name des Traffic Manager-Profil, gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="35146-122">The name of the Traffic Manager profile to be deleted.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35146-123">Löscht ein Traffic Manager-Profil.</span><span class="sxs-lookup"><span data-stu-id="35146-123">Deletes a Traffic Manager profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult&gt; DeleteAsync (this Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult&gt; DeleteAsync(class Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.TrafficManager.IProfilesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.TrafficManager.IProfilesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult&gt;" Usage="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.DeleteAsync (operations, resourceGroupName, profileName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions/&lt;DeleteAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="35146-124">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="35146-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="35146-125">Der Name der Ressourcengruppe, enthält das Traffic Manager-Profil, gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="35146-125">The name of the resource group containing the Traffic Manager profile to be deleted.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="35146-126">Der Name des Traffic Manager-Profil, gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="35146-126">The name of the Traffic Manager profile to be deleted.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="35146-127">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="35146-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35146-128">Löscht ein Traffic Manager-Profil.</span><span class="sxs-lookup"><span data-stu-id="35146-128">Deletes a Traffic Manager profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.TrafficManager.Models.Profile Get (this Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.TrafficManager.Models.Profile Get(class Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.Get(Microsoft.Azure.Management.TrafficManager.IProfilesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IProfilesOperations, resourceGroupName As String, profileName As String) As Profile" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.TrafficManager.IProfilesOperations * string * string -&gt; Microsoft.Azure.Management.TrafficManager.Models.Profile" Usage="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.Get (operations, resourceGroupName, profileName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Models.Profile</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="35146-129">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="35146-129">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="35146-130">Der Name der Ressourcengruppe, die Traffic Manager-Profil enthält.</span><span class="sxs-lookup"><span data-stu-id="35146-130">The name of the resource group containing the Traffic Manager profile.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="35146-131">Der Name des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="35146-131">The name of the Traffic Manager profile.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35146-132">Ruft eine Traffic Manager-Profil ab.</span><span class="sxs-lookup"><span data-stu-id="35146-132">Gets a Traffic Manager profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt; GetAsync (this Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Profile&gt; GetAsync(class Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.GetAsync(Microsoft.Azure.Management.TrafficManager.IProfilesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.TrafficManager.IProfilesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;" Usage="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.GetAsync (operations, resourceGroupName, profileName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="35146-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="35146-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="35146-134">Der Name der Ressourcengruppe, die Traffic Manager-Profil enthält.</span><span class="sxs-lookup"><span data-stu-id="35146-134">The name of the resource group containing the Traffic Manager profile.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="35146-135">Der Name des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="35146-135">The name of the Traffic Manager profile.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="35146-136">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="35146-136">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35146-137">Ruft eine Traffic Manager-Profil ab.</span><span class="sxs-lookup"><span data-stu-id="35146-137">Gets a Traffic Manager profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAll">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt; ListAll (this Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Profile&gt; ListAll(class Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.ListAll(Microsoft.Azure.Management.TrafficManager.IProfilesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAll (operations As IProfilesOperations) As IEnumerable(Of Profile)" />
      <MemberSignature Language="F#" Value="static member ListAll : Microsoft.Azure.Management.TrafficManager.IProfilesOperations -&gt; seq&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;" Usage="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.ListAll operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IProfilesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="35146-138">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="35146-138">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35146-139">Listet alle Traffic Manager-Profile in einem Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="35146-139">Lists all Traffic Manager profiles within a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.TrafficManager.IProfilesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.TrafficManager.IProfilesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt;" Usage="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions/&lt;ListAllAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IProfilesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="35146-140">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="35146-140">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="35146-141">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="35146-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35146-142">Listet alle Traffic Manager-Profile in einem Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="35146-142">Lists all Traffic Manager profiles within a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllInResourceGroup">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt; ListAllInResourceGroup (this Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Profile&gt; ListAllInResourceGroup(class Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.ListAllInResourceGroup(Microsoft.Azure.Management.TrafficManager.IProfilesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAllInResourceGroup (operations As IProfilesOperations, resourceGroupName As String) As IEnumerable(Of Profile)" />
      <MemberSignature Language="F#" Value="static member ListAllInResourceGroup : Microsoft.Azure.Management.TrafficManager.IProfilesOperations * string -&gt; seq&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;" Usage="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.ListAllInResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="35146-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="35146-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="35146-144">Der Name der Ressourcengruppe, enthält die Traffic Manager-Profile aufgelistet werden.</span><span class="sxs-lookup"><span data-stu-id="35146-144">The name of the resource group containing the Traffic Manager profiles to be listed.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35146-145">Listet alle Traffic Manager-Profile innerhalb einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="35146-145">Lists all Traffic Manager profiles within a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllInResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt; ListAllInResourceGroupAsync (this Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt; ListAllInResourceGroupAsync(class Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.ListAllInResourceGroupAsync(Microsoft.Azure.Management.TrafficManager.IProfilesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllInResourceGroupAsync : Microsoft.Azure.Management.TrafficManager.IProfilesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt;" Usage="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.ListAllInResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions/&lt;ListAllInResourceGroupAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="35146-146">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="35146-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="35146-147">Der Name der Ressourcengruppe, enthält die Traffic Manager-Profile aufgelistet werden.</span><span class="sxs-lookup"><span data-stu-id="35146-147">The name of the resource group containing the Traffic Manager profiles to be listed.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="35146-148">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="35146-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35146-149">Listet alle Traffic Manager-Profile innerhalb einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="35146-149">Lists all Traffic Manager profiles within a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.TrafficManager.Models.Profile Update (this Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName, Microsoft.Azure.Management.TrafficManager.Models.Profile parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.TrafficManager.Models.Profile Update(class Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName, class Microsoft.Azure.Management.TrafficManager.Models.Profile parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.Update(Microsoft.Azure.Management.TrafficManager.IProfilesOperations,System.String,System.String,Microsoft.Azure.Management.TrafficManager.Models.Profile)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IProfilesOperations, resourceGroupName As String, profileName As String, parameters As Profile) As Profile" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.TrafficManager.IProfilesOperations * string * string * Microsoft.Azure.Management.TrafficManager.Models.Profile -&gt; Microsoft.Azure.Management.TrafficManager.Models.Profile" Usage="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.Update (operations, resourceGroupName, profileName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Models.Profile</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Models.Profile" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="35146-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="35146-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="35146-151">Der Name der Ressourcengruppe, die Traffic Manager-Profil enthält.</span><span class="sxs-lookup"><span data-stu-id="35146-151">The name of the resource group containing the Traffic Manager profile.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="35146-152">Der Name des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="35146-152">The name of the Traffic Manager profile.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="35146-153">Die Traffic Manager Profilparameter auf den Updatevorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="35146-153">The Traffic Manager profile parameters supplied to the Update operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35146-154">Aktualisieren Sie ein Traffic Manager-Profil ein.</span><span class="sxs-lookup"><span data-stu-id="35146-154">Update a Traffic Manager profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt; UpdateAsync (this Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName, Microsoft.Azure.Management.TrafficManager.Models.Profile parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Profile&gt; UpdateAsync(class Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName, class Microsoft.Azure.Management.TrafficManager.Models.Profile parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.TrafficManager.IProfilesOperations,System.String,System.String,Microsoft.Azure.Management.TrafficManager.Models.Profile,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.TrafficManager.IProfilesOperations * string * string * Microsoft.Azure.Management.TrafficManager.Models.Profile * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;" Usage="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.UpdateAsync (operations, resourceGroupName, profileName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions/&lt;UpdateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Models.Profile" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="35146-155">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="35146-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="35146-156">Der Name der Ressourcengruppe, die Traffic Manager-Profil enthält.</span><span class="sxs-lookup"><span data-stu-id="35146-156">The name of the resource group containing the Traffic Manager profile.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="35146-157">Der Name des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="35146-157">The name of the Traffic Manager profile.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="35146-158">Die Traffic Manager Profilparameter auf den Updatevorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="35146-158">The Traffic Manager profile parameters supplied to the Update operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="35146-159">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="35146-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35146-160">Aktualisieren Sie ein Traffic Manager-Profil ein.</span><span class="sxs-lookup"><span data-stu-id="35146-160">Update a Traffic Manager profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>