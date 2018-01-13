<Type Name="BandwidthSettingsOperationsExtensions" FullName="Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BandwidthSettingsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BandwidthSettingsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BandwidthSettingsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BandwidthSettingsOperationsExtensions = class" />
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
            <span data-ttu-id="eebcb-101">Erweiterungsmethoden für BandwidthSettingsOperations.</span><span class="sxs-lookup"><span data-stu-id="eebcb-101">Extension methods for BandwidthSettingsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting BeginCreateOrUpdate (this Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations operations, string bandwidthSettingName, Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting BeginCreateOrUpdate(class Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations operations, string bandwidthSettingName, class Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IBandwidthSettingsOperations, bandwidthSettingName As String, parameters As BandwidthSetting, resourceGroupName As String, managerName As String) As BandwidthSetting" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting" Usage="Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions.BeginCreateOrUpdate (operations, bandwidthSettingName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations" RefType="this" />
        <Parameter Name="bandwidthSettingName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eebcb-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eebcb-102">The operations group for this extension method.</span></span>
            </param>
        <param name="bandwidthSettingName">
            <span data-ttu-id="eebcb-103">Der Name der Einstellung Bandbreite.</span><span class="sxs-lookup"><span data-stu-id="eebcb-103">The bandwidth setting name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="eebcb-104">Die bandbreiteneinstellung hinzugefügt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="eebcb-104">The bandwidth setting to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eebcb-105">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="eebcb-105">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="eebcb-106">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="eebcb-106">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="eebcb-107">Erstellt oder aktualisiert die Einstellung für die Bandbreite</span><span class="sxs-lookup"><span data-stu-id="eebcb-107">Creates or updates the bandwidth setting</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations operations, string bandwidthSettingName, Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations operations, string bandwidthSettingName, class Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions.BeginCreateOrUpdateAsync (operations, bandwidthSettingName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations" RefType="this" />
        <Parameter Name="bandwidthSettingName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eebcb-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eebcb-108">The operations group for this extension method.</span></span>
            </param>
        <param name="bandwidthSettingName">
            <span data-ttu-id="eebcb-109">Der Name der Einstellung Bandbreite.</span><span class="sxs-lookup"><span data-stu-id="eebcb-109">The bandwidth setting name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="eebcb-110">Die bandbreiteneinstellung hinzugefügt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="eebcb-110">The bandwidth setting to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eebcb-111">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="eebcb-111">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="eebcb-112">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="eebcb-112">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eebcb-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eebcb-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eebcb-114">Erstellt oder aktualisiert die Einstellung für die Bandbreite</span><span class="sxs-lookup"><span data-stu-id="eebcb-114">Creates or updates the bandwidth setting</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations operations, string bandwidthSettingName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations operations, string bandwidthSettingName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IBandwidthSettingsOperations, bandwidthSettingName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions.BeginDelete (operations, bandwidthSettingName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations" RefType="this" />
        <Parameter Name="bandwidthSettingName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eebcb-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eebcb-115">The operations group for this extension method.</span></span>
            </param>
        <param name="bandwidthSettingName">
            <span data-ttu-id="eebcb-116">Der Name der bandbreiteneinstellung für die.</span><span class="sxs-lookup"><span data-stu-id="eebcb-116">The name of the bandwidth setting.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eebcb-117">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="eebcb-117">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="eebcb-118">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="eebcb-118">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="eebcb-119">Löscht die Einstellung für die Bandbreite</span><span class="sxs-lookup"><span data-stu-id="eebcb-119">Deletes the bandwidth setting</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations operations, string bandwidthSettingName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations operations, string bandwidthSettingName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions.BeginDeleteAsync (operations, bandwidthSettingName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations" RefType="this" />
        <Parameter Name="bandwidthSettingName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eebcb-120">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eebcb-120">The operations group for this extension method.</span></span>
            </param>
        <param name="bandwidthSettingName">
            <span data-ttu-id="eebcb-121">Der Name der bandbreiteneinstellung für die.</span><span class="sxs-lookup"><span data-stu-id="eebcb-121">The name of the bandwidth setting.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eebcb-122">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="eebcb-122">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="eebcb-123">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="eebcb-123">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eebcb-124">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eebcb-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eebcb-125">Löscht die Einstellung für die Bandbreite</span><span class="sxs-lookup"><span data-stu-id="eebcb-125">Deletes the bandwidth setting</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting CreateOrUpdate (this Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations operations, string bandwidthSettingName, Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting CreateOrUpdate(class Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations operations, string bandwidthSettingName, class Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IBandwidthSettingsOperations, bandwidthSettingName As String, parameters As BandwidthSetting, resourceGroupName As String, managerName As String) As BandwidthSetting" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting" Usage="Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions.CreateOrUpdate (operations, bandwidthSettingName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations" RefType="this" />
        <Parameter Name="bandwidthSettingName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eebcb-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eebcb-126">The operations group for this extension method.</span></span>
            </param>
        <param name="bandwidthSettingName">
            <span data-ttu-id="eebcb-127">Der Name der Einstellung Bandbreite.</span><span class="sxs-lookup"><span data-stu-id="eebcb-127">The bandwidth setting name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="eebcb-128">Die bandbreiteneinstellung hinzugefügt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="eebcb-128">The bandwidth setting to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eebcb-129">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="eebcb-129">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="eebcb-130">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="eebcb-130">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="eebcb-131">Erstellt oder aktualisiert die Einstellung für die Bandbreite</span><span class="sxs-lookup"><span data-stu-id="eebcb-131">Creates or updates the bandwidth setting</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations operations, string bandwidthSettingName, Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations operations, string bandwidthSettingName, class Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions.CreateOrUpdateAsync (operations, bandwidthSettingName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations" RefType="this" />
        <Parameter Name="bandwidthSettingName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eebcb-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eebcb-132">The operations group for this extension method.</span></span>
            </param>
        <param name="bandwidthSettingName">
            <span data-ttu-id="eebcb-133">Der Name der Einstellung Bandbreite.</span><span class="sxs-lookup"><span data-stu-id="eebcb-133">The bandwidth setting name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="eebcb-134">Die bandbreiteneinstellung hinzugefügt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="eebcb-134">The bandwidth setting to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eebcb-135">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="eebcb-135">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="eebcb-136">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="eebcb-136">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eebcb-137">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eebcb-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eebcb-138">Erstellt oder aktualisiert die Einstellung für die Bandbreite</span><span class="sxs-lookup"><span data-stu-id="eebcb-138">Creates or updates the bandwidth setting</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations operations, string bandwidthSettingName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations operations, string bandwidthSettingName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions.Delete(Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IBandwidthSettingsOperations, bandwidthSettingName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions.Delete (operations, bandwidthSettingName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations" RefType="this" />
        <Parameter Name="bandwidthSettingName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eebcb-139">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eebcb-139">The operations group for this extension method.</span></span>
            </param>
        <param name="bandwidthSettingName">
            <span data-ttu-id="eebcb-140">Der Name der bandbreiteneinstellung für die.</span><span class="sxs-lookup"><span data-stu-id="eebcb-140">The name of the bandwidth setting.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eebcb-141">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="eebcb-141">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="eebcb-142">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="eebcb-142">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="eebcb-143">Löscht die Einstellung für die Bandbreite</span><span class="sxs-lookup"><span data-stu-id="eebcb-143">Deletes the bandwidth setting</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations operations, string bandwidthSettingName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations operations, string bandwidthSettingName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions.DeleteAsync (operations, bandwidthSettingName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations" RefType="this" />
        <Parameter Name="bandwidthSettingName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eebcb-144">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eebcb-144">The operations group for this extension method.</span></span>
            </param>
        <param name="bandwidthSettingName">
            <span data-ttu-id="eebcb-145">Der Name der bandbreiteneinstellung für die.</span><span class="sxs-lookup"><span data-stu-id="eebcb-145">The name of the bandwidth setting.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eebcb-146">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="eebcb-146">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="eebcb-147">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="eebcb-147">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eebcb-148">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eebcb-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eebcb-149">Löscht die Einstellung für die Bandbreite</span><span class="sxs-lookup"><span data-stu-id="eebcb-149">Deletes the bandwidth setting</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting Get (this Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations operations, string bandwidthSettingName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting Get(class Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations operations, string bandwidthSettingName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions.Get(Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IBandwidthSettingsOperations, bandwidthSettingName As String, resourceGroupName As String, managerName As String) As BandwidthSetting" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting" Usage="Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions.Get (operations, bandwidthSettingName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations" RefType="this" />
        <Parameter Name="bandwidthSettingName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eebcb-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eebcb-150">The operations group for this extension method.</span></span>
            </param>
        <param name="bandwidthSettingName">
            <span data-ttu-id="eebcb-151">Der Name der Einstellung für die Bandbreite abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="eebcb-151">The name of bandwidth setting to be fetched.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eebcb-152">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="eebcb-152">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="eebcb-153">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="eebcb-153">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="eebcb-154">Gibt die Eigenschaften der angegebenen Bandbreite Einstellungsname zurück.</span><span class="sxs-lookup"><span data-stu-id="eebcb-154">Returns the properties of the specified bandwidth setting name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting&gt; GetAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations operations, string bandwidthSettingName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting&gt; GetAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations operations, string bandwidthSettingName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions.GetAsync(Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions.GetAsync (operations, bandwidthSettingName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations" RefType="this" />
        <Parameter Name="bandwidthSettingName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eebcb-155">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eebcb-155">The operations group for this extension method.</span></span>
            </param>
        <param name="bandwidthSettingName">
            <span data-ttu-id="eebcb-156">Der Name der Einstellung für die Bandbreite abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="eebcb-156">The name of bandwidth setting to be fetched.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eebcb-157">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="eebcb-157">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="eebcb-158">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="eebcb-158">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eebcb-159">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eebcb-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eebcb-160">Gibt die Eigenschaften der angegebenen Bandbreite Einstellungsname zurück.</span><span class="sxs-lookup"><span data-stu-id="eebcb-160">Returns the properties of the specified bandwidth setting name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByManager">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting&gt; ListByManager (this Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations operations, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting&gt; ListByManager(class Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations operations, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions.ListByManager(Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByManager (operations As IBandwidthSettingsOperations, resourceGroupName As String, managerName As String) As IEnumerable(Of BandwidthSetting)" />
      <MemberSignature Language="F#" Value="static member ListByManager : Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions.ListByManager (operations, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eebcb-161">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eebcb-161">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eebcb-162">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="eebcb-162">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="eebcb-163">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="eebcb-163">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="eebcb-164">Ruft alle bandbreiteneinstellung in einem Manager ab.</span><span class="sxs-lookup"><span data-stu-id="eebcb-164">Retrieves all the bandwidth setting in a manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByManagerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting&gt;&gt; ListByManagerAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations operations, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting&gt;&gt; ListByManagerAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations operations, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions.ListByManagerAsync(Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByManagerAsync : Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions.ListByManagerAsync (operations, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BandwidthSettingsOperationsExtensions/&lt;ListByManagerAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBandwidthSettingsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eebcb-165">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eebcb-165">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eebcb-166">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="eebcb-166">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="eebcb-167">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="eebcb-167">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eebcb-168">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eebcb-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eebcb-169">Ruft alle bandbreiteneinstellung in einem Manager ab.</span><span class="sxs-lookup"><span data-stu-id="eebcb-169">Retrieves all the bandwidth setting in a manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>